
# Queue Remove Agent Exception

## Structure

`QueueRemoveAgentException`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `response` | `bool` | Required | - | getResponse(): bool | setResponse(bool response): void |
| `errorCode` | `int` | Required | - | getErrorCode(): int | setErrorCode(int errorCode): void |
| `reason` | `string` | Required | - | getReason(): string | setReason(string reason): void |

## Example (as JSON)

```json
{
  "response": false,
  "error_code": 1405,
  "reason": "Queue name doesn't  exist"
}
```

