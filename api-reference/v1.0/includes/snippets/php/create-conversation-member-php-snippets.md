---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestBody = new AadUserConversationMember();
$requestBody->setOdataType('#microsoft.graph.aadUserConversationMember');

$requestBody->setRoles([	]);

$additionalData = [
		'user@odata.bind' => 'https://graph.microsoft.com/v1.0/users/8b081ef6-4792-4def-b2c9-c363a1bf41d5', 
];
$requestBody->setAdditionalData($additionalData);




$result = $graphServiceClient->teams()->byTeamId('team-id')->channels()->byChannelId('channel-id')->members()->post($requestBody);


```