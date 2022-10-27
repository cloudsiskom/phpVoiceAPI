
# Delete

## Structure

`Delete`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `response` | `bool` | Required | - | getResponse(): bool | setResponse(bool response): void |
| `callerId` | `string` | Required | - | getCallerId(): string | setCallerId(string callerId): void |
| `action` | `string` | Required | - | getAction(): string | setAction(string action): void |

## Example (as JSON)

```json
{
  "response": true,
  "caller_id": "628198788686",
  "action": "delete"
}
```

