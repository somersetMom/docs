---
title: Salesforce (Sandbox) API
name: Salesforce (sandbox)
thirdParty: true
image: //auth0.com/lib/saas-collection/img/salesforce.png
lodash: true
tags:
  - quickstart
---
<% configuration.thirdParty = 'Salesforce (Sandbox)' %>
@@includes.thirdpartyapi@@

### Additional information

Auth0 supports both the __production__ connection to Salesforce and the __Sandbox__, the only difference being the endpoints hosted by Salesforce: `https://login.salesforce.com` and `https://test.salesforce.com` respectively.

> Under the hood, Auth0 uses [OAuth 2.0 JWT Bearer Token Flow](https://help.salesforce.com/HTViewHelpDoc?id=remoteaccess_oauth_jwt_flow.htm&language=en_US) to obtain an `access_token`. All details of construction of the right JWT are taken care of by Auth0.

![](https://docs.google.com/drawings/d/1aTHLCUPT4fCOXgX6fvUpxJdzd_rH_VzayBkLwLkwOBk/pub?w=784&amp;h=437)
