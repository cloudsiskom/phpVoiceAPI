
# Intent List

## Structure

`IntentList`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `response` | `bool` | Required | - | getResponse(): bool | setResponse(bool response): void |
| `data` | [`Data8[]`](../../doc/models/data-8.md) | Required | - | getData(): array | setData(array data): void |

## Example (as JSON)

```json
{
  "response": true,
  "data": [
    {
      "id": 14,
      "ai_name": "BANK_BKKN",
      "display_name": "sahabat",
      "training_phrases": "sahabatmu siapa",
      "message_texts": "nggak punya deh",
      "create_date": "2022-08-22T19:59:06.000Z"
    },
    {
      "id": 15,
      "ai_name": "BANK_BKKN",
      "display_name": "terima kasih",
      "training_phrases": "terima kasih",
      "message_texts": "pulang saja kamu sana!",
      "create_date": "2022-08-23T14:45:39.000Z"
    },
    {
      "id": 16,
      "ai_name": "BANK_BKKN",
      "display_name": "teman",
      "training_phrases": "temanmu siapa",
      "message_texts": "nggak punya juga",
      "create_date": "2022-08-24T02:11:58.000Z"
    },
    {
      "id": 17,
      "ai_name": "BANK_BKKN",
      "display_name": "kamu siapa yang buat",
      "training_phrases": "kamu siapa yang buat;siapa yang buat;programmermu siapa",
      "message_texts": "Aku lahir dari batu !",
      "create_date": "2022-08-25T18:53:35.000Z"
    },
    {
      "id": 19,
      "ai_name": "BANK_BKKN",
      "display_name": "Hidayat",
      "training_phrases": "hidayat",
      "message_texts": "jelek banget",
      "create_date": "2022-09-01T17:02:54.000Z"
    }
  ]
}
```

