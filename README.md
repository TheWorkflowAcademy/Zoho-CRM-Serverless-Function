# Zoho-CRM-Serverless-Function
Call a Serverless Function (function call via API) in Zoho CRM. This is extremely powerful for multiple reasons:
- Promotes reusing current code base and avoiding duplicate code.
- Breaking up large scripts into digestable, testable functions.
- Invoking a Zoho CRM Function from another Zoho App (Books, Desk, etc).

## Configuration
The only configuration is setting up the function you would like to call.
1. From Zoho CRM, click Setup, then under Developer Space, click Functions
2. Select + New Function to create the function.
3. Give your function a name and a display name.
4. In Category, select "standalone" and click Next.
5. Write your function and save it. Note: Be sure to return the string value you want to consume in another function.
6. Find your new function under My Functions and select the elipses icon and click REST API.
7. Turn on API KEY, copy the link, and click save. You will need this link in your custom function.

