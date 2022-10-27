
# Blastrequest

## Structure

`Blastrequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `callerid` | `string` | Required | - | getCallerid(): string | setCallerid(string callerid): void |
| `destination` | `string` | Required | - | getDestination(): string | setDestination(string destination): void |
| `textToSpeech` | `string` | Required | - | getTextToSpeech(): string | setTextToSpeech(string textToSpeech): void |
| `language` | `string` | Required | - | getLanguage(): string | setLanguage(string language): void |
| `gender` | `string` | Required | - | getGender(): string | setGender(string gender): void |
| `repeat` | `int` | Required | - | getRepeat(): int | setRepeat(int repeat): void |
| `externalId` | `string` | Required | - | getExternalId(): string | setExternalId(string externalId): void |
| `callbackUrl` | `string` | Required | - | getCallbackUrl(): string | setCallbackUrl(string callbackUrl): void |

## Example (as JSON)

```json
{
  "callerid": "6285757920463",
  "destination": "6285772337980",
  "text_to_speech": "Halo mas machri apa kabar? halo mas machri apa",
  "language": "id_ID",
  "gender": "FEMALE",
  "repeat": 10,
  "external_id": "[EXTERNAL_ID]",
  "callback_url": "https://eov2zjk1xwqtjan.m.pipedream.net"
}
```

