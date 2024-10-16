# CancelDeploymentGitSource4

## Example Usage

```typescript
import { CancelDeploymentGitSource4 } from "@vercel/sdk/models/operations/canceldeployment.js";

let value: CancelDeploymentGitSource4 = {
  type: "bitbucket",
  repoUuid: "<id>",
};
```

## Fields

| Field                                                                                                                                            | Type                                                                                                                                             | Required                                                                                                                                         | Description                                                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| `type`                                                                                                                                           | [operations.CancelDeploymentGitSourceDeploymentsResponse200Type](../../models/operations/canceldeploymentgitsourcedeploymentsresponse200type.md) | :heavy_check_mark:                                                                                                                               | N/A                                                                                                                                              |
| `workspaceUuid`                                                                                                                                  | *string*                                                                                                                                         | :heavy_minus_sign:                                                                                                                               | N/A                                                                                                                                              |
| `repoUuid`                                                                                                                                       | *string*                                                                                                                                         | :heavy_check_mark:                                                                                                                               | N/A                                                                                                                                              |
| `ref`                                                                                                                                            | *string*                                                                                                                                         | :heavy_minus_sign:                                                                                                                               | N/A                                                                                                                                              |
| `sha`                                                                                                                                            | *string*                                                                                                                                         | :heavy_minus_sign:                                                                                                                               | N/A                                                                                                                                              |
| `prId`                                                                                                                                           | *number*                                                                                                                                         | :heavy_minus_sign:                                                                                                                               | N/A                                                                                                                                              |