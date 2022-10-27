
# Incoming Route

## Structure

`IncomingRoute`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `id` | `int` | Required | - | getId(): int | setId(int id): void |
| `transactionId` | `?string` | Required | - | getTransactionId(): ?string | setTransactionId(?string transactionId): void |
| `customerCode` | `string` | Required | - | getCustomerCode(): string | setCustomerCode(string customerCode): void |
| `did` | `string` | Required | - | getDid(): string | setDid(string did): void |
| `destination` | `string` | Required | - | getDestination(): string | setDestination(string destination): void |
| `destinationDetail` | `?string` | Required | - | getDestinationDetail(): ?string | setDestinationDetail(?string destinationDetail): void |
| `createDate` | `string` | Required | - | getCreateDate(): string | setCreateDate(string createDate): void |
| `isActive` | `int` | Required | - | getIsActive(): int | setIsActive(int isActive): void |

## Example (as JSON)

```json
{
  "id": 57,
  "transaction_id": null,
  "customer_code": "GOJEK",
  "did": "6285757920462",
  "destination": "DTMFTEST",
  "destination_detail": null,
  "create_date": "2022-08-23T22:57:32.000Z",
  "isActive": 1
}
```

