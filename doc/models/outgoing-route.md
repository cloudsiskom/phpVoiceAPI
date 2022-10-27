
# Outgoing Route

## Structure

`OutgoingRoute`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `id` | `int` | Required | - | getId(): int | setId(int id): void |
| `customerCode` | `string` | Required | - | getCustomerCode(): string | setCustomerCode(string customerCode): void |
| `extension` | `string` | Required | - | getExtension(): string | setExtension(string extension): void |
| `routeTo` | `string` | Required | - | getRouteTo(): string | setRouteTo(string routeTo): void |
| `routeDetail` | `string` | Required | - | getRouteDetail(): string | setRouteDetail(string routeDetail): void |
| `techPrefix` | `string` | Required | - | getTechPrefix(): string | setTechPrefix(string techPrefix): void |
| `createDate` | `string` | Required | - | getCreateDate(): string | setCreateDate(string createDate): void |
| `isActive` | `int` | Required | - | getIsActive(): int | setIsActive(int isActive): void |

## Example (as JSON)

```json
{
  "id": 582,
  "customer_code": "GOJEK",
  "extension": "ALL",
  "route_to": "PROVIDER",
  "route_detail": "6285592055236",
  "tech_prefix": "",
  "create_date": "2022-09-14T19:40:24.000Z",
  "isActive": 1
}
```

