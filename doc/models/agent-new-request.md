
# Agent New Request

## Structure

`AgentNewRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `action` | `string` | Required | - | getAction(): string | setAction(string action): void |
| `agentCode` | `string` | Required | - | getAgentCode(): string | setAgentCode(string agentCode): void |
| `agentName` | `string` | Required | - | getAgentName(): string | setAgentName(string agentName): void |
| `agentPassword` | `string` | Required | - | getAgentPassword(): string | setAgentPassword(string agentPassword): void |

## Example (as JSON)

```json
{
  "action": "[ACTION]",
  "agent_code": "[AGENT_CODE]",
  "agent_name": "[AGENT_NAME]",
  "agent_password": "[AGENT_PASSWORD]"
}
```

