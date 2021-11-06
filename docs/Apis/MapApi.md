# MapApi

All URIs are relative to *https://war-service-live.foxholeservices.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getDynamicPublicMapData**](MapApi.md#getDynamicPublicMapData) | **GET** /worldconquest/maps/{mapName}/dynamic/public | 
[**getMapWarReport**](MapApi.md#getMapWarReport) | **GET** /worldconquest/warReport/{mapName} | 
[**getStaticMapData**](MapApi.md#getStaticMapData) | **GET** /worldconquest/maps/{mapName}/static | 
[**listMapNames**](MapApi.md#listMapNames) | **GET** /worldconquest/maps | 


<a name="getDynamicPublicMapData"></a>
# **getDynamicPublicMapData**
> MapData getDynamicPublicMapData(mapName)



    Dynamic map data includes map icons that could change over the lifecycle of a map. This includes static bases and static base build sites.

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **mapName** | **String**| Map name. | [default to null]

### Return type

[**MapData**](../Models/MapData.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getMapWarReport"></a>
# **getMapWarReport**
> WarReport getMapWarReport(mapName)



    Returns the number of enlistments, casualties, and other map specific information

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **mapName** | **String**| Map name. | [default to null]

### Return type

[**WarReport**](../Models/WarReport.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getStaticMapData"></a>
# **getStaticMapData**
> MapData getStaticMapData(mapName)



    Static map data includes things that never change over the lifecycle of a map. This includes map text labels, resource nodes, and world structures. You only need to request this once per map between World Conquests.

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **mapName** | **String**| Map name. | [default to null]

### Return type

[**MapData**](../Models/MapData.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="listMapNames"></a>
# **listMapNames**
> List listMapNames()



    List map names.

### Parameters
This endpoint does not need any parameter.

### Return type

**List**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

