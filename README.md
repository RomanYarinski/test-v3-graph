### Subgraph Endpoint

Synced at: https://api.thegraph.com/subgraphs/name/wewayio/weway-subgraph

Pending Changes at same URL

## Deployment APY VISION

```
nvm use 10.16.3
```

To generate the mapping ts files, please do:

```
yarn codegen
```

To deploy, please use:

```
yarn codegen && graph build

```

```
graph auth --product hosted-service <ACCESS_TOKEN>

```

```
graph deploy --product hosted-service wewayio/weway-subgraph

```
