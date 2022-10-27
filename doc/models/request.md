
# Request

## Structure

`Request`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `response` | `bool` | Required | - | getResponse(): bool | setResponse(bool response): void |
| `callerId` | `string` | Required | - | getCallerId(): string | setCallerId(string callerId): void |
| `isActive` | `int` | Required | - | getIsActive(): int | setIsActive(int isActive): void |

## Example (as JSON)

```json
{
  "response": true,
  "caller_id": "628198788686",
  "isActive": 0
}
```

