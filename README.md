# ServiceNow-LinkedIn-Outbound-Integration-
ServiceNow LinkedIn Outbound Integration
Steps:
1. Created an app in LinkedIn Developer site
2. Purchased products Share on linkedIn & Sign-in with LinkedIn using OpenID Connect
3. Provided the redirect URL to servicenow authentication. Noted the client id and client secret.
4. On ServiceNow, created a System Oauth registry for LinkedIn giving the client id, secret, Access url, authorization url , redirect url and entity scopes (got from app created in LinkedIn)
5. Created the App in Studio, got the userinfo using GET outbound REST message and using the ID from the GET outbound message, created a POST outbound REST message and tested it. Generation of Oauth token is mandate in this step.
6. Table created for Post, an UI action button is developed to post the content in ServiceNow.

For other users:
CLient ID and secret will be different for the app you are making and naturally the id will be different. 

