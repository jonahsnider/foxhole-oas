# Documentation for Foxhole

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *https://war-service-live.foxholeservices.com/api*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*MapApi* | [**getDynamicPublicMapData**](Apis/MapApi.md#getdynamicpublicmapdata) | **GET** /worldconquest/maps/{mapName}/dynamic/public | Dynamic map data includes map icons that could change over the lifecycle of a map. This includes static bases and static base build sites.
*MapApi* | [**getMapWarReport**](Apis/MapApi.md#getmapwarreport) | **GET** /worldconquest/warReport/{mapName} | Returns the number of enlistments, casualties, and other map specific information
*MapApi* | [**getStaticMapData**](Apis/MapApi.md#getstaticmapdata) | **GET** /worldconquest/maps/{mapName}/static | Static map data includes things that never change over the lifecycle of a map. This includes map text labels, resource nodes, and world structures. You only need to request this once per map between World Conquests.
*MapApi* | [**listMapNames**](Apis/MapApi.md#listmapnames) | **GET** /worldconquest/maps | List map names.
*WarApi* | [**getWarState**](Apis/WarApi.md#getwarstate) | **GET** /worldconquest/war | Returns data about the current state of the war.


<a name="documentation-for-models"></a>
## Documentation for Models

 - [MapData](./Models/MapData.md)
 - [MapItem](./Models/MapItem.md)
 - [MapTextItem](./Models/MapTextItem.md)
 - [Team](./Models/Team.md)
 - [WarData](./Models/WarData.md)
 - [WarReport](./Models/WarReport.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

All endpoints do not require authorization.
