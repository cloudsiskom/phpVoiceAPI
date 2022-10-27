
# Translation Setup Request

## Structure

`TranslationSetupRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `fromNumber` | `string` | Required | - | getFromNumber(): string | setFromNumber(string fromNumber): void |
| `callerDidgateway` | `string` | Required | - | getCallerDidgateway(): string | setCallerDidgateway(string callerDidgateway): void |
| `calledDidgateway` | `string` | Required | - | getCalledDidgateway(): string | setCalledDidgateway(string calledDidgateway): void |
| `destinationNumber` | `string` | Required | - | getDestinationNumber(): string | setDestinationNumber(string destinationNumber): void |
| `externalId` | `string` | Required | - | getExternalId(): string | setExternalId(string externalId): void |

## Example (as JSON)

```json
{
  "from_number": "[FROM_NUMBER]",
  "caller_didgateway": "[DID_GATEWAY]",
  "called_didgateway": "[DID_GATEWAY]",
  "destination_number": "[DESTINATION]",
  "external_id": "[EXTERNAL_ID]"
}
```

