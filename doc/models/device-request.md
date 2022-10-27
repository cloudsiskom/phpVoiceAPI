
# Device Request

## Structure

`DeviceRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `deviceType` | `string` | Required | - | getDeviceType(): string | setDeviceType(string deviceType): void |
| `deviceOwner` | `string` | Required | - | getDeviceOwner(): string | setDeviceOwner(string deviceOwner): void |
| `extension` | `string` | Required | - | getExtension(): string | setExtension(string extension): void |
| `secret` | `string` | Required | - | getSecret(): string | setSecret(string secret): void |
| `ipAddress` | `string` | Required | - | getIpAddress(): string | setIpAddress(string ipAddress): void |

## Example (as JSON)

```json
{
  "device_type": "[DEVICE_TYPE]",
  "device_owner": "[DEVICE_OWNER]",
  "extension": "[DEVICE_NAME / EXTENSION]",
  "secret": "[DEVICE_SECRET]",
  "ip_address": "[DEVICE_IP_ADDRESS]"
}
```

