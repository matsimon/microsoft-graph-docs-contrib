---
description: "Automatically generated file. DO NOT MODIFY"
---

```go


import (
	  "context"
	  msgraphsdk "github.com/microsoftgraph/msgraph-sdk-go"
	  //other-imports
)

graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)



getRecentNotebooks(includePersonalNotebooks={includePersonalNotebooks}), err := graphClient.Me().Onenote().Notebooks().GetRecentNotebooks(includePersonalNotebooks={includePersonalNotebooks})().Get(context.Background(), nil)


```