# Device

```php
$deviceController = $client->getDeviceController();
```

## Class Name

`DeviceController`

## Methods

* [Device](../../doc/controllers/device.md#device)
* [Devcie List](../../doc/controllers/device.md#devcie-list)
* [Device Edit](../../doc/controllers/device.md#device-edit)
* [Device Delete](../../doc/controllers/device.md#device-delete)


# Device

DEVICE_TYPE :

\*   TRUNK (This will be sip trunk with dedicated IP Address)
\*   EXTEN (Extension)

```php
function device(DeviceRequest $body): Device
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`DeviceRequest`](../../doc/models/device-request.md) | Body, Required | - |

## Response Type

[`Device`](../../doc/models/device.md)

## Example Usage

```php
$body_deviceType = '[DEVICE_TYPE]';
$body_deviceOwner = '[DEVICE_OWNER]';
$body_extension = '[DEVICE_NAME / EXTENSION]';
$body_secret = '[DEVICE_SECRET]';
$body_ipAddress = '[DEVICE_IP_ADDRESS]';
$body = new Models\DeviceRequest(
    $body_deviceType,
    $body_deviceOwner,
    $body_extension,
    $body_secret,
    $body_ipAddress
);

$result = $deviceController->device($body);
```

## Example Response *(as JSON)*

```json
{
  "response": true,
  "data": {
    "extension": "961424500000013",
    "secret": "padamunegeri",
    "device_owner": "kiki"
  }
}
```

## Errors

| HTTP Status Code | Error Description | Exception Class |
|  --- | --- | --- |
| 403 | Forbidden | [`Device1Exception`](../../doc/models/device-1-exception.md) |


# Devcie List

```php
function devcieList(): DevcieList
```

## Response Type

[`DevcieList`](../../doc/models/devcie-list.md)

## Example Usage

```php
$result = $deviceController->devcieList();
```

## Example Response *(as JSON)*

```json
{
  "response": true,
  "data": [
    {
      "extension": "968976567",
      "host": "dynamic",
      "device_type": "EXTEN",
      "device_owner": "sahabat",
      "secret": "sahabat",
      "isOnline": 0,
      "device_state": "UNAVAILABLE"
    },
    {
      "extension": "961424500000013",
      "host": "192.168.1.1",
      "device_type": "TRUNK",
      "device_owner": "kiki",
      "secret": "padamunegeri",
      "isOnline": 0,
      "device_state": null
    }
  ]
}
```


# Device Edit

```php
function deviceEdit(DeviceEditRequest $body): void
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`DeviceEditRequest`](../../doc/models/device-edit-request.md) | Body, Required | - |

## Response Type

`void`

## Example Usage

```php
$body_extension = '[DEVICE_EXTENSION]';
$body_deviceOwner = '[DEVICE_OWNER]';
$body_secret = '[DEVICE_SECRET]';
$body = new Models\DeviceEditRequest(
    $body_extension,
    $body_deviceOwner,
    $body_secret
);

$deviceController->deviceEdit($body);
```

## Errors

| HTTP Status Code | Error Description | Exception Class |
|  --- | --- | --- |
| 403 | Forbidden | [`DeviceEditException`](../../doc/models/device-edit-exception.md) |


# Device Delete

```php
function deviceDelete(DeviceDeleteRequest $body): void
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`DeviceDeleteRequest`](../../doc/models/device-delete-request.md) | Body, Required | - |

## Response Type

`void`

## Example Usage

```php
$body_extension = '[DEVICE_EXTENSION / NAME]';
$body = new Models\DeviceDeleteRequest(
    $body_extension
);

$deviceController->deviceDelete($body);
```

## Errors

| HTTP Status Code | Error Description | Exception Class |
|  --- | --- | --- |
| 404 | Not Found | [`DeviceDeleteException`](../../doc/models/device-delete-exception.md) |

