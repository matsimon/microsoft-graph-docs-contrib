---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestConfiguration = new BookingBusinessesRequestBuilderGetRequestConfiguration();
$queryParameters = BookingBusinessesRequestBuilderGetRequestConfiguration::createQueryParameters();
$queryParameters->query = "Adventure";
$requestConfiguration->queryParameters = $queryParameters;


$result = $graphServiceClient->solutions()->bookingBusinesses()->get($requestConfiguration);


```