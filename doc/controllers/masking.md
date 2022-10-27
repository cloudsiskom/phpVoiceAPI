# Masking

masking api lets you to use your original phone number as callerid at our SIP trunk

```php
$maskingController = $client->getMaskingController();
```

## Class Name

`MaskingController`

## Methods

* [Request](../../doc/controllers/masking.md#request)
* [Delete](../../doc/controllers/masking.md#delete)
* [List](../../doc/controllers/masking.md#list)


# Request

```php
function request(Requestrequest $body): Request
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`Requestrequest`](../../doc/models/requestrequest.md) | Body, Required | - |

## Response Type

[`Request`](../../doc/models/request.md)

## Example Usage

```php
$body_callerId = '[CALLER_ID]';
$body = new Models\Requestrequest(
    $body_callerId
);

$result = $maskingController->request($body);
```

## Example Response *(as JSON)*

```json
{
  "response": true,
  "caller_id": "628198788686",
  "isActive": 0
}
```


# Delete

```php
function delete(Deleterequest $body): Delete
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`Deleterequest`](../../doc/models/deleterequest.md) | Body, Required | - |

## Response Type

[`Delete`](../../doc/models/delete.md)

## Example Usage

```php
$body_callerId = '[CALLER_ID]';
$body = new Models\Deleterequest(
    $body_callerId
);

$result = $maskingController->delete($body);
```

## Example Response *(as JSON)*

```json
{
  "response": true,
  "caller_id": "628198788686",
  "action": "delete"
}
```


# List

```php
function mList(): MList
```

## Response Type

[`MList`](../../doc/models/m-list.md)

## Example Usage

```php
$result = $maskingController->mList();
```

## Example Response *(as JSON)*

```json
{
  "response": true,
  "data": []
}
```

