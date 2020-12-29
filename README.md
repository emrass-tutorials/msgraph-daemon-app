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

## Daemon

Based on https://github.com/microsoftgraph/msgraph-training-nodeexpressapp

- Create the app: `npx express-generator --hbs daemon`

## Client

Next.js application that serves the interactive homepage. Uses OIDC to
authenticate users using Microsoft Azure AD and communicates with the
Daemon application to retrieve data.
