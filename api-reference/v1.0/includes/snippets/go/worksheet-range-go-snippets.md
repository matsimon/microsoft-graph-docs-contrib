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



range(address='{address}'), err := graphClient.Drives().ByDriveId("drive-id").Items().ByDriveItemId("driveItem-id").Workbook().Worksheets().ByWorkbookWorksheetId("workbookWorksheet-id").Range(address='{address}')().Get(context.Background(), nil)


```