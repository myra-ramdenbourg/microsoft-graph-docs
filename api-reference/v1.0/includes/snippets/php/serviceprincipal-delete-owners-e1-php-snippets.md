---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);

$requestBody = new $refDeleteRequestBody();
$additionalData = [
		'@odata.id' => 'https://graph.microsoft.com/v1.0/directoryObjects/{id}', 
];
$requestBody->setAdditionalData($additionalData);




$graphServiceClient->servicePrincipalsById('servicePrincipal-id')->ownersById('directoryObject-id')->ref()->delete($requestBody);


```