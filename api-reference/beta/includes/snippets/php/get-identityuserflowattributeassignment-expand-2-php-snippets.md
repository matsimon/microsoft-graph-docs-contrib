---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestConfiguration = new UserAttributeAssignmentsRequestBuilderGetRequestConfiguration();
$queryParameters = UserAttributeAssignmentsRequestBuilderGetRequestConfiguration::createQueryParameters();
$queryParameters->expand = ["userAttribute"];
$requestConfiguration->queryParameters = $queryParameters;


$result = $graphServiceClient->identity()->b2xUserFlows()->byB2xIdentityUserFlowId('b2xIdentityUserFlow-id')->userAttributeAssignments()->get($requestConfiguration);


```