# WarReportApi

All URIs are relative to *https://war-service-live.foxholeservices.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getMapWarReport**](WarReportApi.md#getMapWarReport) | **GET** /worldconquest/warReport/{mapName} | 


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

