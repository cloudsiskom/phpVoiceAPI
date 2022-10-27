
# Blast

## Structure

`Blast`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `response` | `bool` | Required | - | getResponse(): bool | setResponse(bool response): void |
| `rcode` | [`Rcode`](../../doc/models/rcode.md) | Required | - | getRcode(): Rcode | setRcode(Rcode rcode): void |

## Example (as JSON)

```json
{
  "response": true,
  "rcode": {
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
}
```

