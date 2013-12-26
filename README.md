lead-api-php
============

Sample code demonstrating usage of LeadSquared API in php

Before you try the code:

1. All LeadSquared APIs need an access key and secret key for authentication. Get your API access key and secret key. (How? http://help.leadsquared.com/how-do-i-obtain-api-access-keys-in-leadsquared/)

2. To know LeadSquared schema or the lead fields which API would understand, this is the API method you need:
GET  https://api.leadsquared.com/v2/LeadManagement.svc/LeadsMetaData.Get?accessKey=<youraccesskey>&secretKey=<yoursecretkey>

3. Please note that the DateTime format for all date fields would be “yyyy-mm-dd hh:mm:ss”.   The time is in 24 hour format, and there is a space between date and time.  Most importantly, this date should in GMT time-zone. So you will have to convert the DateTime in your time-zone to GMT/UTC. 