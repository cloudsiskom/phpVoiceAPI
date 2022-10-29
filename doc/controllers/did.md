# DID

```php
$dIDController = $client->getDIDController();
```

## Class Name

`DIDController`

## Methods

* [DID List](../../doc/controllers/did.md#did-list)
* [DID Buy](../../doc/controllers/did.md#did-buy)
* [DID List All](../../doc/controllers/did.md#did-list-all)


# DID List

```php
function dIDList(): DIDList
```

## Response Type

[`DIDList`](../../doc/models/did-list.md)

## Example Usage

```php
$result = $dIDController->dIDList();
```


# DID Buy

```php
function dIDBuy(DIDBuyRequest $body): void
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`DIDBuyRequest`](../../doc/models/did-buy-request.md) | Body, Required | - |

## Response Type

`void`

## Example Usage

```php
$body_did = '12345678';
$body = new Models\DIDBuyRequest(
    $body_did
);

$dIDController->dIDBuy($body);
```

## Errors

| HTTP Status Code | Error Description | Exception Class |
|  --- | --- | --- |
| 404 | Not Found | [`DIDBuyException`](../../doc/models/did-buy-exception.md) |


# DID List All

```php
function dIDListAll(): DIDListAll
```

## Response Type

[`DIDListAll`](../../doc/models/did-list-all.md)

## Example Usage

```php
$result = $dIDController->dIDListAll();
```

## Example Response *(as JSON)*

```json
{
  "response": true,
  "total": 1,
  "data": [
    {
      "did": "6285873935693",
      "activation_cost": 100000,
      "monthly_cost": 100000,
      "did_type": "MVN",
      "active": 1
    }
  ]
}
```

