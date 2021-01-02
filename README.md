# MS Graph Daemon App - Example

Usage:

```
# starts daemon and SPA client concurrently
yarn start
# starts the daemon only
yarn daemon
# starts the SPA client only
yarn client
```

Note: currently only the daemon app exists, so only `yarn daemon` will work. In the future, I'll add a
Single Page Application (SPA) for delegated access, whereas application requests will remain in the daemon.

## Setup

1. Register the application in the Azure Portal
2. Copy `.env.sample` to `.env` and update app id and client secret

## Credits

Combines the tutorials / samples:

1. Microsoft Graph Training Module - Build Node.js Express apps with Microsoft Graph ([Tutorial](https://docs.microsoft.com/en-us/graph/tutorials/node) / [Source Code](https://github.com/microsoftgraph/msgraph-training-nodeexpressapp))
2. ASP.NET multi-tenant daemon ([Tutorial](https://docs.microsoft.com/en-in/azure/active-directory/develop/tutorial-v2-aspnet-daemon-web-app) / [Source Code](https://github.com/Azure-Samples/ms-identity-aspnet-daemon-webapp))
3. MSAL Node Standalone Sample: Client Credentials ([Source Code](https://github.com/AzureAD/microsoft-authentication-library-for-js/tree/dev/samples/msal-node-samples/standalone-samples/client-credentials))
4. MSAL Node Standalone Sample: Auth Code ([Source Code](https://github.com/AzureAD/microsoft-authentication-library-for-js/tree/dev/samples/msal-node-samples/standalone-samples/auth-code))
