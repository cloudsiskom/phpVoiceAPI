
# Device Edit Request

## Structure

`DeviceEditRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `extension` | `string` | Required | - | getExtension(): string | setExtension(string extension): void |
| `deviceOwner` | `string` | Required | - | getDeviceOwner(): string | setDeviceOwner(string deviceOwner): void |
| `secret` | `string` | Required | - | getSecret(): string | setSecret(string secret): void |

## Example (as JSON)

```json
{
  "extension": "[DEVICE_EXTENSION]",
  "device_owner": "[DEVICE_OWNER]",
  "secret": "[DEVICE_SECRET]"
}
```

