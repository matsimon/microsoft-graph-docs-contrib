---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestBody = new WorkPosition();
$requestBody->setIsCurrent(true);



$result = $graphServiceClient->me()->profile()->positions()->byWorkPositionId('workPosition-id')->patch($requestBody);


```