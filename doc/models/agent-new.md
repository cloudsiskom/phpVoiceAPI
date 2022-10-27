
# Agent New

## Structure

`AgentNew`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `response` | `bool` | Required | - | getResponse(): bool | setResponse(bool response): void |
| `data` | [`Data2`](../../doc/models/data-2.md) | Required | - | getData(): Data2 | setData(Data2 data): void |

## Example (as JSON)

```json
{
  "response": true,
  "data": {
    "action": "new",
    "agent_code": "10002",
    "agent_name": "queue-152",
    "agent_password": "4321"
  }
}
```

