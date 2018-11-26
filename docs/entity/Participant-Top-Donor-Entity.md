### Get Participant Top Donor
`/api/participants/{participantID}/donors/top`
#### Supported Query Parameters
|Query Parameter|Description|
|---|---|
|`callback`|The value provided will wrap the payload as a JSONP-formatted response.|
|`version`|The version of the API desired. If no version parameter is provided, the API will default to the oldest supported version.|
#### Path Parameters
|Field|Description|
|---|---|
|`participantID`| The unique ID of the participant |
#### Response format
On a successful HTTP Call, `200` OK will be returned with an object whose body will contain a participants top donor.
#### Participant Top Donor Object
|Field|Type|Description|
|---|---|---|
|`avatarImageURL` (string)|The URL for the avatar image associated with the Participant|
|`displayName` (string)|The donor's name|
|`numDonations` |integer|The number of donations this Participant has received|
|`sumAmount` |float|The total sum of donations this Participant has received|
