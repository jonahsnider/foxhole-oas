# MapApi

All URIs are relative to *https://war-service-live.foxholeservices.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**worldconquestMapsGet**](MapApi.md#worldconquestMapsGet) | **GET** /worldconquest/maps | 
[**worldconquestMapsMapNameDynamicPublicGet**](MapApi.md#worldconquestMapsMapNameDynamicPublicGet) | **GET** /worldconquest/maps/{mapName}/dynamic/public | 
[**worldconquestMapsMapNameStaticGet**](MapApi.md#worldconquestMapsMapNameStaticGet) | **GET** /worldconquest/maps/{mapName}/static | 
[**worldconquestWarReportMapNameGet**](MapApi.md#worldconquestWarReportMapNameGet) | **GET** /worldconquest/warReport/{mapName} | 


<a name="worldconquestMapsGet"></a>
# **worldconquestMapsGet**
> List worldconquestMapsGet()



    List map names.

### Parameters
This endpoint does not need any parameter.

### Return type

[**List**](../Models/string.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="worldconquestMapsMapNameDynamicPublicGet"></a>
# **worldconquestMapsMapNameDynamicPublicGet**
> inline_response_200_3 worldconquestMapsMapNameDynamicPublicGet(mapName)



    Dynamic map data includes map icons that could change over the lifecycle of a map. This includes static bases and static base build sites.

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **mapName** | **String**| Map name. | [default to null]

### Return type

[**inline_response_200_3**](../Models/inline_response_200_3.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="worldconquestMapsMapNameStaticGet"></a>
# **worldconquestMapsMapNameStaticGet**
> inline_response_200_2 worldconquestMapsMapNameStaticGet(mapName)



    Static map data includes things that never change over the lifecycle of a map. This includes map text labels, resource nodes, and world structures. You only need to request this once per map between World Conquests.

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **mapName** | **String**| Map name. | [default to null]

### Return type

[**inline_response_200_2**](../Models/inline_response_200_2.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="worldconquestWarReportMapNameGet"></a>
# **worldconquestWarReportMapNameGet**
> inline_response_200_1 worldconquestWarReportMapNameGet(mapName)



    Returns the number of enlistments, casualties, and other map specific information

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **mapName** | **String**| Map name. | [default to null]

### Return type

[**inline_response_200_1**](../Models/inline_response_200_1.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

