# Translation

```php
$translationController = $client->getTranslationController();
```

## Class Name

`TranslationController`

## Methods

* [Translation Delete](../../doc/controllers/translation.md#translation-delete)
* [Translation Setup](../../doc/controllers/translation.md#translation-setup)


# Translation Delete

```php
function translationDelete(TranslationDeleteRequest $body): void
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`TranslationDeleteRequest`](../../doc/models/translation-delete-request.md) | Body, Required | - |

## Response Type

`void`

## Example Usage

```php
$body_transactionId = '[TRANSACTION_ID]';
$body = new Models\TranslationDeleteRequest(
    $body_transactionId
);

$translationController->translationDelete($body);
```

## Errors

| HTTP Status Code | Error Description | Exception Class |
|  --- | --- | --- |
| 404 | Not Found | [`TranslationDeleteException`](../../doc/models/translation-delete-exception.md) |


# Translation Setup

```php
function translationSetup(TranslationSetupRequest $body): TranslationSetup
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`TranslationSetupRequest`](../../doc/models/translation-setup-request.md) | Body, Required | - |

## Response Type

[`TranslationSetup`](../../doc/models/translation-setup.md)

## Example Usage

```php
$body_fromNumber = '[FROM_NUMBER]';
$body_callerDidgateway = '[DID_GATEWAY]';
$body_calledDidgateway = '[DID_GATEWAY]';
$body_destinationNumber = '[DESTINATION]';
$body_externalId = '[EXTERNAL_ID]';
$body = new Models\TranslationSetupRequest(
    $body_fromNumber,
    $body_callerDidgateway,
    $body_calledDidgateway,
    $body_destinationNumber,
    $body_externalId
);

$result = $translationController->translationSetup($body);
```

## Example Response *(as JSON)*

```json
{
  "respose": true,
  "action": "setup",
  "transaction_id": "cf54bfa60c738515574809998f71bd62",
  "external_id": "1000",
  "from_number": "62811949736",
  "destination_number": "6285161422932",
  "caller_didgateway": "6285757920463",
  "called_didgateway": "6285757920463"
}
```

