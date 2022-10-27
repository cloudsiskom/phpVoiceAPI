
# Queue Remove Agent Request

## Structure

`QueueRemoveAgentRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `queueName` | `string` | Required | - | getQueueName(): string | setQueueName(string queueName): void |
| `agents` | `string` | Required | - | getAgents(): string | setAgents(string agents): void |
| `agentType` | `string` | Required | - | getAgentType(): string | setAgentType(string agentType): void |

## Example (as JSON)

```json
{
  "queue_name": "[QUEUE_NAME]",
  "agents": "[agent]",
  "agent_type": "[AGENT_TYPE]"
}
```

