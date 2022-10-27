
# Queue New Request

## Structure

`QueueNewRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `queueName` | `string` | Required | - | getQueueName(): string | setQueueName(string queueName): void |
| `ringStrategy` | `string` | Required | - | getRingStrategy(): string | setRingStrategy(string ringStrategy): void |

## Example (as JSON)

```json
{
  "queue_name": "[QUEUE_NAME]",
  "ring_strategy": "[RING_STRATEGY]"
}
```

