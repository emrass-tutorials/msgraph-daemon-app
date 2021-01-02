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
