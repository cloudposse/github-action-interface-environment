<!-- markdownlint-disable -->
## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| environment | Environment name | N/A | true |
| implementation\_github\_pat | GitHub PAT allow fetch environment action implementation | N/A | true |
| implementation\_path | Repository path with Environment action implementation |  | true |
| implementation\_ref | Ref of environment action implementation | main | true |
| implementation\_repository | Repository with Environment action implementation | N/A | true |
| namespace | Namespace name | N/A | true |

## Outputs

| Name | Description |
|------|-------------|
| cluster | Environments that need to be destroyed |
| cluster-role | Environments that need to be destroyed |
| name | Environment name |
| namespace | Namespace |
| region | JSON formatted {label}: {environment} map |
| role | Environments that need to be deployed |
<!-- markdownlint-restore -->
