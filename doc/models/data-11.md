
# Data 11

## Structure

`Data11`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `did` | `string` | Required | - | getDid(): string | setDid(string did): void |
| `activationCost` | `int` | Required | - | getActivationCost(): int | setActivationCost(int activationCost): void |
| `monthlyCost` | `int` | Required | - | getMonthlyCost(): int | setMonthlyCost(int monthlyCost): void |
| `didType` | `string` | Required | - | getDidType(): string | setDidType(string didType): void |
| `active` | `int` | Required | - | getActive(): int | setActive(int active): void |

## Example (as JSON)

```json
{
  "did": "6285873935693",
  "activation_cost": 100000,
  "monthly_cost": 100000,
  "did_type": "MVN",
  "active": 1
}
```

