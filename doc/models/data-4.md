
# Data 4

## Structure

`Data4`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `id` | `int` | Required | - | getId(): int | setId(int id): void |
| `customerCode` | `string` | Required | - | getCustomerCode(): string | setCustomerCode(string customerCode): void |
| `agentCode` | `int` | Required | - | getAgentCode(): int | setAgentCode(int agentCode): void |
| `agentName` | `string` | Required | - | getAgentName(): string | setAgentName(string agentName): void |
| `requirePassword` | `int` | Required | - | getRequirePassword(): int | setRequirePassword(int requirePassword): void |
| `agentPassword` | `int` | Required | - | getAgentPassword(): int | setAgentPassword(int agentPassword): void |
| `lastlogin` | `int` | Required | - | getLastlogin(): int | setLastlogin(int lastlogin): void |
| `isActive` | `int` | Required | - | getIsActive(): int | setIsActive(int isActive): void |
| `isLogin` | `int` | Required | - | getIsLogin(): int | setIsLogin(int isLogin): void |
| `loginChannel` | `?string` | Required | - | getLoginChannel(): ?string | setLoginChannel(?string loginChannel): void |
| `loginExtension` | `?string` | Required | - | getLoginExtension(): ?string | setLoginExtension(?string loginExtension): void |
| `loginUniqueid` | `?string` | Required | - | getLoginUniqueid(): ?string | setLoginUniqueid(?string loginUniqueid): void |

## Example (as JSON)

```json
{
  "id": 34,
  "customer_code": "GOJEK",
  "agent_code": 9610002,
  "agent_name": "queue-152",
  "require_password": 1,
  "agent_password": 4321,
  "lastlogin": 0,
  "isActive": 1,
  "isLogin": 0,
  "login_channel": null,
  "login_extension": null,
  "login_uniqueid": null
}
```

