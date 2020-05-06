# WWE Service Client API - API Overview

This sample shows the use of the Workspace Service Client API based on window.postMessage.

The security option "service-client-api.accepted-web-content-origins" must be configured for this sample to work.

The web page "sample.html" could be hosted by a third party web server.
It is referenced by the Workspace Web Edition (see: [https://docs.genesys.com/Documentation/PSAAS/latest/Administrator/ServiceClientAPI](https://docs.genesys.com/Documentation/PSAAS/latest/Administrator/ServiceClientAPI)) through the following options:

```
[interaction-workspace]
workspace.web-content=MyCustomAPISample
service-client-api.accepted-web-content-origins=http://my-web-server

[MyCustomAPISample]
label=My Sample
url=http://my-web-server/path/sample.html
```

Click on the following assets :

- [sample.html](./sample.html) (custom webpage)
- [wwe-service-client-api.js](./wwe-service-client-api.js) (SCAPI JavaScript client)
