---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestConfiguration = new EdiscoveryNoncustodialDataSourceRequestBuilderGetRequestConfiguration();
$queryParameters = EdiscoveryNoncustodialDataSourceRequestBuilderGetRequestConfiguration::createQueryParameters();
$queryParameters->expand = ["dataSource"];
$requestConfiguration->queryParameters = $queryParameters;


$result = $graphServiceClient->security()->cases()->ediscoveryCases()->byEdiscoveryCaseId('ediscoveryCase-id')->noncustodialDataSources()->byEdiscoveryNoncustodialDataSourceId('ediscoveryNoncustodialDataSource-id')->get($requestConfiguration);


```