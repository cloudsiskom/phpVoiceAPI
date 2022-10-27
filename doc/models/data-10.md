
# Data 10

## Structure

`Data10`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `customerCode` | `string` | Required | - | getCustomerCode(): string | setCustomerCode(string customerCode): void |
| `id` | `int` | Required | - | getId(): int | setId(int id): void |
| `active` | `int` | Required | - | getActive(): int | setActive(int active): void |
| `did` | `string` | Required | - | getDid(): string | setDid(string did): void |
| `didType` | `string` | Required | - | getDidType(): string | setDidType(string didType): void |
| `activationCost` | `int` | Required | - | getActivationCost(): int | setActivationCost(int activationCost): void |
| `incoming` | `?string` | Required | - | getIncoming(): ?string | setIncoming(?string incoming): void |
| `destinationDetail` | `?string` | Required | - | getDestinationDetail(): ?string | setDestinationDetail(?string destinationDetail): void |
| `isActive` | `?array` | Required | - | getIsActive(): ?array | setIsActive(?array isActive): void |

## Example (as JSON)

```json
{
  "customer_code": "GOJEK",
  "id": 2,
  "active": 1,
  "did": "6285757920463",
  "did_type": "MVN",
  "activation_cost": 100000,
  "incoming": "TRUNK",
  "destination_detail": "CVAI",
  "isActive": 1
}
```

