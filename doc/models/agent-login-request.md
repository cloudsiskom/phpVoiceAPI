
# Agent Login Request

## Structure

`AgentLoginRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `actionType` | `string` | Required | - | getActionType(): string | setActionType(string actionType): void |
| `agentCode` | `string` | Required | - | getAgentCode(): string | setAgentCode(string agentCode): void |
| `extension` | `string` | Required | - | getExtension(): string | setExtension(string extension): void |
| `agentPassword` | `string` | Required | - | getAgentPassword(): string | setAgentPassword(string agentPassword): void |

## Example (as JSON)

```json
{
  "action_type": "[ACTION]",
  "agent_code": "[AGENT_CODE]",
  "extension": "[EXTENSION TO LOGIN]",
  "agent_password": "[AGENT_PASSWORD]"
}
```

