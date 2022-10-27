
# Device

## Structure

`Device`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `response` | `bool` | Required | - | getResponse(): bool | setResponse(bool response): void |
| `data` | [`Data`](../../doc/models/data.md) | Required | - | getData(): Data | setData(Data data): void |

## Example (as JSON)

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

