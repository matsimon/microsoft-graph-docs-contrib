---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);


$result = $graphServiceClient->identityProtection()->riskyUsers()->byRiskyUserId('riskyUser-id')->history()->byRiskyUserHistoryItemId('riskyUserHistoryItem-id')->get();


```