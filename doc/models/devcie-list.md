
# Devcie List

## Structure

`DevcieList`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `response` | `bool` | Required | - | getResponse(): bool | setResponse(bool response): void |
| `data` | [`Data1[]`](../../doc/models/data-1.md) | Required | - | getData(): array | setData(array data): void |

## Example (as JSON)

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

