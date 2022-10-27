
# Translation Setup

## Structure

`TranslationSetup`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `respose` | `bool` | Required | - | getRespose(): bool | setRespose(bool respose): void |
| `action` | `string` | Required | - | getAction(): string | setAction(string action): void |
| `transactionId` | `string` | Required | - | getTransactionId(): string | setTransactionId(string transactionId): void |
| `externalId` | `string` | Required | - | getExternalId(): string | setExternalId(string externalId): void |
| `fromNumber` | `string` | Required | - | getFromNumber(): string | setFromNumber(string fromNumber): void |
| `destinationNumber` | `string` | Required | - | getDestinationNumber(): string | setDestinationNumber(string destinationNumber): void |
| `callerDidgateway` | `string` | Required | - | getCallerDidgateway(): string | setCallerDidgateway(string callerDidgateway): void |
| `calledDidgateway` | `string` | Required | - | getCalledDidgateway(): string | setCalledDidgateway(string calledDidgateway): void |

## Example (as JSON)

```json
{
  "respose": true,
  "action": "setup",
  "transaction_id": "cf54bfa60c738515574809998f71bd62",
  "external_id": "1000",
  "from_number": "62811949736",
  "destination_number": "6285161422932",
  "caller_didgateway": "6285757920463",
  "called_didgateway": "6285757920463"
}
```

