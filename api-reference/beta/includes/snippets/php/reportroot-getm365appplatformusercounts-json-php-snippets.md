---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestConfiguration = new GetM365AppPlatformUserCountsWithPeriodRequestBuilderGetRequestConfiguration();
$queryParameters = GetM365AppPlatformUserCountsWithPeriodRequestBuilderGetRequestConfiguration::createQueryParameters();
$queryParameters->format = "application/json";
$requestConfiguration->queryParameters = $queryParameters;


$graphServiceClient->reports()->getM365AppPlatformUserCountsWithPeriod('{period}', )->get($requestConfiguration);


```