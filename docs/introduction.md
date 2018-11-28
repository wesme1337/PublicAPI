### DonorDrive Public API

The DonorDrive Public API makes it easy to build lightweight integrations using public event, participant, and team data. The Public API is RESTful and read-only. Data is retrieved via GET requests and successful responses are returned in JSON format. The API is completely open to integrations using the interface in a responsible manner.

Please limit requests to one every 15 seconds. Please don't abuse the API, or we may be forced to rate-limit requests. A reasonable example of the interval is as follows: when updating a streaming overlay, polling the participant endpoint every 15 seconds and checking for a change in participant donations. If a change is detected, using the participantID to get the donation amount from the donations endpoint and display the combined information on the streaming overlay.

For general inquiries and requests for larger volume integrations, please email support@donordrive.com for assistance.
