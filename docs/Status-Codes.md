### Status Codes
A 200 Status Code will return for successful API calls. Meaningful codes + messaging will be furnished in the event of an error. Here are some other responses you may encounter.

|Status Code|Description|
|---|---|
|204|No Content - The pagination offset is out of range.|
|304|Not Modified - If `If-None-Match` was furnished, and the response is unmodified, a 304 will be returned instead of a payload.|
|400|Bad Request - The request could not be interpreted.|
|404|Not Found - The request could not be found for the ID or URL provided.|
|412|Precondition Failed - The version furnished is unsupported.|
|500|Internal Server Error - Technical support has been notified.|
|503|Service Unavailable - The API is unavailable or undergoing maintenance. Please try again later.|
