# Conversation AI

```php
$conversationAIController = $client->getConversationAIController();
```

## Class Name

`ConversationAIController`

## Methods

* [Create Intent](../../doc/controllers/conversation-ai.md#create-intent)
* [Intent Query](../../doc/controllers/conversation-ai.md#intent-query)
* [Intent List](../../doc/controllers/conversation-ai.md#intent-list)
* [Intent Edit](../../doc/controllers/conversation-ai.md#intent-edit)
* [AI Name](../../doc/controllers/conversation-ai.md#ai-name)
* [Intent Delete](../../doc/controllers/conversation-ai.md#intent-delete)


# Create Intent

```php
function createIntent(CreateIntentRequest $body): void
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`CreateIntentRequest`](../../doc/models/create-intent-request.md) | Body, Required | - |

## Response Type

`void`

## Example Usage

```php
$body_aiName = '[AI_NAME]';
$body_displayName = '[DISPLAY_NAME';
$body_trainingPhrases = '[TRAINING_PHRASE,SPARATED BY ;]';
$body_messageTexts = '[RESPONSE_TEXT SPARATED BY ;]';
$body = new Models\CreateIntentRequest(
    $body_aiName,
    $body_displayName,
    $body_trainingPhrases,
    $body_messageTexts
);

$conversationAIController->createIntent($body);
```

## Errors

| HTTP Status Code | Error Description | Exception Class |
|  --- | --- | --- |
| 403 | Forbidden | [`CreateIntentException`](../../doc/models/create-intent-exception.md) |


# Intent Query

```php
function intentQuery(IntentQueryRequest $body): IntentQuery
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`IntentQueryRequest`](../../doc/models/intent-query-request.md) | Body, Required | - |

## Response Type

[`IntentQuery`](../../doc/models/intent-query.md)

## Example Usage

```php
$body_aiName = '[AI_NAME]';
$body_trainingPhrases = '[TRAINING_PHRASE]';
$body = new Models\IntentQueryRequest(
    $body_aiName,
    $body_trainingPhrases
);

$result = $conversationAIController->intentQuery($body);
```

## Example Response *(as JSON)*

```json
{
  "response": true,
  "message_texts": "Saya tidak dengar Anda bilang apa. Bisa ulangi lagi?"
}
```


# Intent List

```php
function intentList(): IntentList
```

## Response Type

[`IntentList`](../../doc/models/intent-list.md)

## Example Usage

```php
$result = $conversationAIController->intentList();
```

## Example Response *(as JSON)*

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


# Intent Edit

```php
function intentEdit(IntentEditRequest $body): IntentEdit
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`IntentEditRequest`](../../doc/models/intent-edit-request.md) | Body, Required | - |

## Response Type

[`IntentEdit`](../../doc/models/intent-edit.md)

## Example Usage

```php
$body_aiName = '[AI_NAME]';
$body_displayName = '[DISPLAY_NAME]';
$body_trainingPhrases = '[TRAINING_PHRASE,SPARATED BY ;]';
$body_messageTexts = '[RESPONSE_TEXT SPARATED BY ;]';
$body = new Models\IntentEditRequest(
    $body_aiName,
    $body_displayName,
    $body_trainingPhrases,
    $body_messageTexts
);

$result = $conversationAIController->intentEdit($body);
```

## Example Response *(as JSON)*

```json
{
  "response": true,
  "message": "Update intent success"
}
```


# AI Name

```php
function aIName(): AIName
```

## Response Type

[`AIName`](../../doc/models/ai-name.md)

## Example Usage

```php
$result = $conversationAIController->aIName();
```

## Example Response *(as JSON)*

```json
{
  "response": true,
  "data": [
    {
      "id": 1,
      "ai_name": "BANK_BKKN",
      "create_date": "2022-08-15T17:13:43.000Z"
    }
  ]
}
```


# Intent Delete

```php
function intentDelete(IntentDeleteRequest $body): IntentDelete
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`IntentDeleteRequest`](../../doc/models/intent-delete-request.md) | Body, Required | - |

## Response Type

[`IntentDelete`](../../doc/models/intent-delete.md)

## Example Usage

```php
$body_aiName = '[AI_NAME]';
$body_displayName = '[DISPLAY_NAME]';
$body = new Models\IntentDeleteRequest(
    $body_aiName,
    $body_displayName
);

$result = $conversationAIController->intentDelete($body);
```

## Example Response *(as JSON)*

```json
{
  "response": true,
  "message": "Delete intent success"
}
```

