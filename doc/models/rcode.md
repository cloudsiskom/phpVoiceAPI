
# Rcode

## Structure

`Rcode`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `transactionId` | `string` | Required | - | getTransactionId(): string | setTransactionId(string transactionId): void |
| `callbackKey` | `string` | Required | - | getCallbackKey(): string | setCallbackKey(string callbackKey): void |
| `destination` | `string` | Required | - | getDestination(): string | setDestination(string destination): void |
| `textToSpeech` | `string` | Required | - | getTextToSpeech(): string | setTextToSpeech(string textToSpeech): void |
| `language` | `string` | Required | - | getLanguage(): string | setLanguage(string language): void |
| `gender` | `string` | Required | - | getGender(): string | setGender(string gender): void |
| `voiceRepeat` | `string` | Required | - | getVoiceRepeat(): string | setVoiceRepeat(string voiceRepeat): void |
| `externalId` | `string` | Required | - | getExternalId(): string | setExternalId(string externalId): void |
| `callbackUrl` | `string` | Required | - | getCallbackUrl(): string | setCallbackUrl(string callbackUrl): void |

## Example (as JSON)

```json
{
  "transaction_id": "489EF4175D9E35DDAEFD74839DB9558D",
  "callback_key": "25c1e6ec24db6cf8bcff665761e1c985",
  "destination": "62127867676",
  "text_to_speech": "Hai.... Selamat datang saudara-saudaraku, anda adalah pelanggan utama hari ini, selamat yaaa gaeees!",
  "language": "id-ID",
  "gender": "FEMALE",
  "VoiceRepeat": "2",
  "external_id": "93894893483984938",
  "callback_url": "http"
}
```

