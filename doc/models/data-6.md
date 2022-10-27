
# Data 6

## Structure

`Data6`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `queueId` | `int` | Required | - | getQueueId(): int | setQueueId(int queueId): void |
| `queueName` | `string` | Required | - | getQueueName(): string | setQueueName(string queueName): void |
| `musiclass` | `string` | Required | - | getMusiclass(): string | setMusiclass(string musiclass): void |
| `strategy` | `string` | Required | - | getStrategy(): string | setStrategy(string strategy): void |
| `members` | [`Member[]`](../../doc/models/member.md) | Required | - | getMembers(): array | setMembers(array members): void |

## Example (as JSON)

```json
{
  "queue_id": 35,
  "queue_name": "96789665",
  "musiclass": "default",
  "strategy": "ringall",
  "members": [
    {
      "member": "SIP/968976567"
    }
  ]
}
```

