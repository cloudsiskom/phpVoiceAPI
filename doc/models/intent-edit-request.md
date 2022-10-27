
# Intent Edit Request

## Structure

`IntentEditRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `aiName` | `string` | Required | - | getAiName(): string | setAiName(string aiName): void |
| `displayName` | `string` | Required | - | getDisplayName(): string | setDisplayName(string displayName): void |
| `trainingPhrases` | `string` | Required | - | getTrainingPhrases(): string | setTrainingPhrases(string trainingPhrases): void |
| `messageTexts` | `string` | Required | - | getMessageTexts(): string | setMessageTexts(string messageTexts): void |

## Example (as JSON)

```json
{
  "ai_name": "[AI_NAME]",
  "display_name": "[DISPLAY_NAME]",
  "training_phrases": "[TRAINING_PHRASE,SPARATED BY ;]",
  "message_texts": "[RESPONSE_TEXT SPARATED BY ;]"
}
```

