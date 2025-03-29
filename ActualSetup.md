# Setup Copilot Authentication
## Step 1. In Copilot Studio under Settings > Security > Authentication.  Setup up manual Authentication NOT Microsoft Entra ID auth or No Auth.
Redirect URL: https://token.botframework.com/.auth/web/redirect
siteURL : "https://churchofjesuschrist.sharepoint.com/sites/CloudPOrtal"
botURL: https://9a9f9f69e439e04d92caaf38f65f27.00.environment.api.powerplatform.com/powervirtualagents/botsbyschema/crc2c_lydia/directline/token?api-version=2022-03-01-preview
botName : "Lydia"
ClientID : "eb09ea59-15a9-435d-a2ce-74f2617f7aec"
custom scope - Token Exchange URL : api://eb09ea59-15a9-435d-a2ce-74f2617f7aec/Sites.Read.All
Authority : "https://login.microsoftonline.com/churchofjesuschrist.onmicrosoft.com" OR Authority : "https://login.microsoftonline.com/common" (for multi-tenant applications)
buttonLabel : "Ask Lydia"
greet : $true




Lydia 2 POC - old delete
customScope : "api://a7f0fc7f-3c80-4960-ad8b-18d928fb9ff9/Sites.Read.All"
botUrl : "https://9a9f9f69e439e04d92caaf38f65f27.00.environment.api.powerplatform.com/powervirtualagents/botsbyschema/crc2c_lydia2/directline/token?api-version=2022-03-01-preview"



