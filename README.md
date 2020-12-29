# MS Graph Daemon App - Example

## Daemon

Based on https://github.com/microsoftgraph/msgraph-training-nodeexpressapp

- Create the app: `npx express-generator --hbs daemon`

## Client

Next.js application that serves the interactive homepage. Uses OIDC to
authenticate users using Microsoft Azure AD and communicates with the
Daemon application to retrieve data.
