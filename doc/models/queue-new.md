
# Queue New

## Structure

`QueueNew`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `response` | `bool` | Required | - | getResponse(): bool | setResponse(bool response): void |
| `data` | [`Data5`](../../doc/models/data-5.md) | Required | - | getData(): Data5 | setData(Data5 data): void |

## Example (as JSON)

```json
{
  "response": true,
  "data": {
    "queue_name": "queue-151-3",
    "ring_strategy": "ringall"
  }
}
```

