
# Data 1

## Structure

`Data1`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `extension` | `string` | Required | - | getExtension(): string | setExtension(string extension): void |
| `host` | `string` | Required | - | getHost(): string | setHost(string host): void |
| `deviceType` | `string` | Required | - | getDeviceType(): string | setDeviceType(string deviceType): void |
| `deviceOwner` | `string` | Required | - | getDeviceOwner(): string | setDeviceOwner(string deviceOwner): void |
| `secret` | `string` | Required | - | getSecret(): string | setSecret(string secret): void |
| `isOnline` | `int` | Required | - | getIsOnline(): int | setIsOnline(int isOnline): void |
| `deviceState` | `?string` | Required | - | getDeviceState(): ?string | setDeviceState(?string deviceState): void |

## Example (as JSON)

```json
{
  "extension": "968976567",
  "host": "dynamic",
  "device_type": "EXTEN",
  "device_owner": "sahabat",
  "secret": "sahabat",
  "isOnline": 0,
  "device_state": "UNAVAILABLE"
}
```

