# WarData
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**warId** | **UUID** | Unique ID for the war. | [default to null]
**warNumber** | **Integer** | Current war number for the shard. | [default to null]
**winner** | [**Team**](Team.md) |  | [default to null]
**conquestStartTime** | **Integer** | UNIX timestamp for when conquest started, or &#x60;null&#x60; if it hasn&#39;t started yet. | [default to null]
**conquestEndTime** | **Integer** | UNIX timestamp for when conquest ended, or &#x60;null&#x60; if it hasn&#39;t ended yet. | [default to null]
**resistanceStartTime** | **Integer** | UNIX timestamp for when resistance phase started, or &#x60;null&#x60; if it hasn&#39;t started yet. | [default to null]
**requiredVictoryTowns** | **Integer** | Number of victory towns required to win the war. | [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

