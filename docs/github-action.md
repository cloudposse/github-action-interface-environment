<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| application | Application name | N/A | false |
| attributes | Comma separated attributes | N/A | false |
| environment | Environment name | N/A | true |
| implementation\_github\_pat | GitHub PAT allow fetch environment action implementation | N/A | true |
| implementation\_path | Repository path with Environment action implementation |  | true |
| implementation\_ref | Ref of environment action implementation | main | true |
| implementation\_repository | Repository with Environment action implementation | N/A | true |
| namespace | Namespace name | N/A | true |
| repository | Repository name | N/A | false |


## Outputs

| Name | Description |
|------|-------------|
| cluster | Environments that need to be destroyed |
| name | Environment name |
| namespace | Namespace |
| region | JSON formatted {label}: {environment} map |
| role | Environments that need to be deployed |
| ssm-path | Path to ssm secrets |
<!-- markdownlint-restore -->
