
# IVR New Request

## Structure

`IVRNewRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `action` | `string` | Required | - | getAction(): string | setAction(string action): void |
| `ivrName` | `string` | Required | - | getIvrName(): string | setIvrName(string ivrName): void |
| `ivrTitle` | `string` | Required | - | getIvrTitle(): string | setIvrTitle(string ivrTitle): void |
| `lang` | `string` | Required | - | getLang(): string | setLang(string lang): void |
| `gender` | `string` | Required | - | getGender(): string | setGender(string gender): void |
| `annauncementText` | `string` | Required | - | getAnnauncementText(): string | setAnnauncementText(string annauncementText): void |
| `maxTrying` | `string` | Required | - | getMaxTrying(): string | setMaxTrying(string maxTrying): void |
| `exitKey` | `string` | Required | - | getExitKey(): string | setExitKey(string exitKey): void |
| `backMenu` | `string` | Required | - | getBackMenu(): string | setBackMenu(string backMenu): void |
| `mainMenu` | `string` | Required | - | getMainMenu(): string | setMainMenu(string mainMenu): void |
| `keyPressed` | `string` | Required | - | getKeyPressed(): string | setKeyPressed(string keyPressed): void |
| `ivrParent` | `string` | Required | - | getIvrParent(): string | setIvrParent(string ivrParent): void |
| `ivrAction` | `string` | Required | - | getIvrAction(): string | setIvrAction(string ivrAction): void |

## Example (as JSON)

```json
{
  "action": "[ACTION]",
  "ivr_name": "[IVR_NAME]",
  "ivr_title": "[IVR_TTITLE]",
  "lang": "[LANG]",
  "gender": "[GENDER]",
  "annauncement_text": "[TEXT_TO_SPEECH]",
  "max_trying": "[MAX_TRYING]",
  "exit_key": "[EXIT_KEY]",
  "back_menu": "[BACK_MENU]",
  "main_menu": "0",
  "key_pressed": "[KEY_PRESSED]",
  "ivr_parent": "[PARENT_IVR_ID]",
  "ivr_action": "NONE"
}
```

