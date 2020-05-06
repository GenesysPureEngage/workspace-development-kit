# WWE Service Client API

Service Client API can be use to customize how your web application or website integrates with Workspace Web Edition. This JavaScript API is based on window.postMessage and provides methods your application can use to communicate cross domain with Workspace Web Edition while maintaining secured isolation.

You can use the Service Client API to perform the following actions:

- Controlling call recording from a third-party application
- Embedding multiple third-party applications in Agent Desktop
- Updating attached data from a third-party application
- Enabling click-to-dial from a third-party application
- Enabling Service Client API to invoke toast in Agent Desktop
- Controlling Case Selection from a Third Party Application

## Code

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

- [sample.html](./index.html) (custom webpage)
- [wwe-service-client-api.js](./wwe-service-client-api.js) (SCAPI JavaScript client)
