
# IVR Lang

## Structure

`IVRLang`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `response` | `bool` | Required | - | getResponse(): bool | setResponse(bool response): void |
| `data` | [`Data7[]`](../../doc/models/data-7.md) | Required | - | getData(): array | setData(array data): void |

## Example (as JSON)

```json
{
  "response": true,
  "data": [
    {
      "code": "fil-PH",
      "name": "fil-PH-Wavenet-B",
      "language": "Filipino (Philippines)",
      "gender": "FEMALE"
    },
    {
      "code": "fil-PH",
      "name": "fil-PH-Wavenet-C",
      "language": "Filipino (Philippines)",
      "gender": "MALE"
    },
    {
      "code": "fil-PH",
      "name": "fil-PH-Wavenet-D",
      "language": "Filipino (Philippines)",
      "gender": "MALE"
    },
    {
      "code": "fi-FI",
      "name": "fi-FI-Standard-A",
      "language": "Finnish (Finland)",
      "gender": "FEMALE"
    },
    {
      "code": "fi-FI",
      "name": "fi-FI-Wavenet-A",
      "language": "Finnish (Finland)",
      "gender": "FEMALE"
    },
    {
      "code": "fr-CA",
      "name": "fr-CA-Standard-A",
      "language": "French (Canada)",
      "gender": "FEMALE"
    },
    {
      "code": "fr-CA",
      "name": "fr-CA-Standard-B",
      "language": "French (Canada)",
      "gender": "MALE"
    },
    {
      "code": "fr-CA",
      "name": "fr-CA-Standard-C",
      "language": "French (Canada)",
      "gender": "FEMALE"
    },
    {
      "code": "fr-CA",
      "name": "fr-CA-Standard-D",
      "language": "French (Canada)",
      "gender": "MALE"
    },
    {
      "code": "fr-CA",
      "name": "fr-CA-Wavenet-A",
      "language": "French (Canada)",
      "gender": "FEMALE"
    },
    {
      "code": "fr-CA",
      "name": "fr-CA-Wavenet-B",
      "language": "French (Canada)",
      "gender": "MALE"
    },
    {
      "code": "fr-CA",
      "name": "fr-CA-Wavenet-C",
      "language": "French (Canada)",
      "gender": "FEMALE"
    },
    {
      "code": "sv-SE",
      "name": "sv-SE-Wavenet-A",
      "language": "Swedish (Sweden)",
      "gender": "FEMALE"
    },
    {
      "code": "af-ZA",
      "name": "af-ZA-Standard-A",
      "language": "Afrikaans (South Africa)",
      "gender": "FEMALE"
    },
    {
      "code": "fr-CA",
      "name": "fr-CA-Wavenet-D",
      "language": "French (Canada)",
      "gender": "MALE"
    },
    {
      "code": "sv-SE",
      "name": "sv-SE-Wavenet-B",
      "language": "Swedish (Sweden)",
      "gender": "FEMALE"
    },
    {
      "code": "fr-FR",
      "name": "fr-FR-Standard-A",
      "language": "French (France)",
      "gender": "FEMALE"
    },
    {
      "code": "ar-XA",
      "name": "ar-XA-Standard-A",
      "language": "Arabic",
      "gender": "FEMALE"
    },
    {
      "code": "fr-FR",
      "name": "fr-FR-Standard-B",
      "language": "French (France)",
      "gender": "MALE"
    },
    {
      "code": "sv-SE",
      "name": "sv-SE-Wavenet-C",
      "language": "Swedish (Sweden)",
      "gender": "MALE"
    },
    {
      "code": "ar-XA",
      "name": "ar-XA-Standard-B",
      "language": "Arabic",
      "gender": "MALE"
    },
    {
      "code": "fr-FR",
      "name": "fr-FR-Standard-C",
      "language": "French (France)",
      "gender": "FEMALE"
    },
    {
      "code": "sv-SE",
      "name": "sv-SE-Wavenet-D",
      "language": "Swedish (Sweden)",
      "gender": "FEMALE"
    },
    {
      "code": "fr-FR",
      "name": "fr-FR-Standard-D",
      "language": "French (France)",
      "gender": "MALE"
    },
    {
      "code": "ar-XA",
      "name": "ar-XA-Standard-C",
      "language": "Arabic",
      "gender": "MALE"
    },
    {
      "code": "fr-FR",
      "name": "fr-FR-Standard-E",
      "language": "French (France)",
      "gender": "FEMALE"
    },
    {
      "code": "sv-SE",
      "name": "sv-SE-Wavenet-E",
      "language": "Swedish (Sweden)",
      "gender": "MALE"
    },
    {
      "code": "ar-XA",
      "name": "ar-XA-Standard-D",
      "language": "Arabic",
      "gender": "FEMALE"
    },
    {
      "code": "fr-FR",
      "name": "fr-FR-Wavenet-A",
      "language": "French (France)",
      "gender": "FEMALE"
    },
    {
      "code": "ar-XA",
      "name": "ar-XA-Wavenet-A",
      "language": "Arabic",
      "gender": "FEMALE"
    },
    {
      "code": "fr-FR",
      "name": "fr-FR-Wavenet-B",
      "language": "French (France)",
      "gender": "MALE"
    },
    {
      "code": "ar-XA",
      "name": "ar-XA-Wavenet-B",
      "language": "Arabic",
      "gender": "MALE"
    },
    {
      "code": "ar-XA",
      "name": "ar-XA-Wavenet-C",
      "language": "Arabic",
      "gender": "MALE"
    },
    {
      "code": "ta-IN",
      "name": "ta-IN-Standard-A",
      "language": "Tamil (India)",
      "gender": "FEMALE"
    },
    {
      "code": "ar-XA",
      "name": "ar-XA-Wavenet-D",
      "language": "Arabic",
      "gender": "FEMALE"
    },
    {
      "code": "ta-IN",
      "name": "ta-IN-Standard-B",
      "language": "Tamil (India)",
      "gender": "MALE"
    },
    {
      "code": "bn-IN",
      "name": "bn-IN-Standard-A",
      "language": "Bengali (India)",
      "gender": "FEMALE"
    },
    {
      "code": "ta-IN",
      "name": "ta-IN-Wavenet-A",
      "language": "Tamil (India)",
      "gender": "FEMALE"
    },
    {
      "code": "bn-IN",
      "name": "bn-IN-Standard-B",
      "language": "Bengali (India)",
      "gender": "MALE"
    },
    {
      "code": "fr-FR",
      "name": "fr-FR-Wavenet-C",
      "language": "French (France)",
      "gender": "FEMALE"
    },
    {
      "code": "ta-IN",
      "name": "ta-IN-Wavenet-B",
      "language": "Tamil (India)",
      "gender": "MALE"
    },
    {
      "code": "bn-IN",
      "name": "bn-IN-Wavenet-A",
      "language": "Bengali (India)",
      "gender": "FEMALE"
    },
    {
      "code": "te-IN",
      "name": "te-IN-Standard-A",
      "language": "Telugu (India)",
      "gender": "FEMALE"
    },
    {
      "code": "fr-FR",
      "name": "fr-FR-Wavenet-D",
      "language": "French (France)",
      "gender": "MALE"
    },
    {
      "code": "te-IN",
      "name": "te-IN-Standard-B",
      "language": "Telugu (India)",
      "gender": "MALE"
    },
    {
      "code": "bn-IN",
      "name": "bn-IN-Wavenet-B",
      "language": "Bengali (India)",
      "gender": "MALE"
    },
    {
      "code": "fr-FR",
      "name": "fr-FR-Wavenet-E",
      "language": "French (France)",
      "gender": "FEMALE"
    },
    {
      "code": "th-TH",
      "name": "th-TH-Standard-A",
      "language": "Thai (Thailand)",
      "gender": "FEMALE"
    },
    {
      "code": "bg-BG",
      "name": "bg-bg-Standard-A",
      "language": "Bulgarian (Bulgaria)",
      "gender": "FEMALE"
    },
    {
      "code": "de-DE",
      "name": "de-DE-Standard-A",
      "language": "German (Germany)",
      "gender": "FEMALE"
    },
    {
      "code": "tr-TR",
      "name": "tr-TR-Standard-A",
      "language": "Turkish (Turkey)",
      "gender": "FEMALE"
    },
    {
      "code": "ca-ES",
      "name": "ca-es-Standard-A",
      "language": "Catalan (Spain)",
      "gender": "FEMALE"
    },
    {
      "code": "de-DE",
      "name": "de-DE-Standard-B",
      "language": "German (Germany)",
      "gender": "MALE"
    },
    {
      "code": "yue-HK",
      "name": "yue-HK-Standard-A",
      "language": "Chinese (Hong Kong)",
      "gender": "FEMALE"
    },
    {
      "code": "de-DE",
      "name": "de-DE-Standard-C",
      "language": "German (Germany)",
      "gender": "FEMALE"
    },
    {
      "code": "yue-HK",
      "name": "yue-HK-Standard-B",
      "language": "Chinese (Hong Kong)",
      "gender": "MALE"
    },
    {
      "code": "de-DE",
      "name": "de-DE-Standard-D",
      "language": "German (Germany)",
      "gender": "MALE"
    },
    {
      "code": "yue-HK",
      "name": "yue-HK-Standard-C",
      "language": "Chinese (Hong Kong)",
      "gender": "FEMALE"
    },
    {
      "code": "de-DE",
      "name": "de-DE-Standard-E",
      "language": "German (Germany)",
      "gender": "MALE"
    },
    {
      "code": "tr-TR",
      "name": "tr-TR-Standard-B",
      "language": "Turkish (Turkey)",
      "gender": "MALE"
    },
    {
      "code": "de-DE",
      "name": "de-DE-Standard-F",
      "language": "German (Germany)",
      "gender": "FEMALE"
    },
    {
      "code": "tr-TR",
      "name": "tr-TR-Standard-C",
      "language": "Turkish (Turkey)",
      "gender": "FEMALE"
    },
    {
      "code": "tr-TR",
      "name": "tr-TR-Standard-D",
      "language": "Turkish (Turkey)",
      "gender": "FEMALE"
    },
    {
      "code": "yue-HK",
      "name": "yue-HK-Standard-D",
      "language": "Chinese (Hong Kong)",
      "gender": "MALE"
    },
    {
      "code": "de-DE",
      "name": "de-DE-Wavenet-A",
      "language": "German (Germany)",
      "gender": "FEMALE"
    },
    {
      "code": "tr-TR",
      "name": "tr-TR-Standard-E",
      "language": "Turkish (Turkey)",
      "gender": "MALE"
    },
    {
      "code": "cs-CZ",
      "name": "cs-CZ-Standard-A",
      "language": "Czech (Czech Republic)",
      "gender": "FEMALE"
    },
    {
      "code": "de-DE",
      "name": "de-DE-Wavenet-B",
      "language": "German (Germany)",
      "gender": "MALE"
    },
    {
      "code": "tr-TR",
      "name": "tr-TR-Wavenet-A",
      "language": "Turkish (Turkey)",
      "gender": "FEMALE"
    },
    {
      "code": "de-DE",
      "name": "de-DE-Wavenet-C",
      "language": "German (Germany)",
      "gender": "FEMALE"
    },
    {
      "code": "tr-TR",
      "name": "tr-TR-Wavenet-B",
      "language": "Turkish (Turkey)",
      "gender": "MALE"
    },
    {
      "code": "cs-CZ",
      "name": "cs-CZ-Wavenet-A",
      "language": "Czech (Czech Republic)",
      "gender": "FEMALE"
    },
    {
      "code": "de-DE",
      "name": "de-DE-Wavenet-D",
      "language": "German (Germany)",
      "gender": "MALE"
    },
    {
      "code": "da-DK",
      "name": "da-DK-Standard-A",
      "language": "Danish (Denmark)",
      "gender": "FEMALE"
    },
    {
      "code": "de-DE",
      "name": "de-DE-Wavenet-E",
      "language": "German (Germany)",
      "gender": "MALE"
    },
    {
      "code": "da-DK",
      "name": "da-DK-Standard-C",
      "language": "Danish (Denmark)",
      "gender": "MALE"
    },
    {
      "code": "de-DE",
      "name": "de-DE-Wavenet-F",
      "language": "German (Germany)",
      "gender": "FEMALE"
    },
    {
      "code": "da-DK",
      "name": "da-DK-Standard-D",
      "language": "Danish (Denmark)",
      "gender": "FEMALE"
    },
    {
      "code": "el-GR",
      "name": "el-GR-Standard-A",
      "language": "Greek (Greece)",
      "gender": "FEMALE"
    },
    {
      "code": "el-GR",
      "name": "el-GR-Wavenet-A",
      "language": "Greek (Greece)",
      "gender": "FEMALE"
    },
    {
      "code": "tr-TR",
      "name": "tr-TR-Wavenet-C",
      "language": "Turkish (Turkey)",
      "gender": "FEMALE"
    },
    {
      "code": "gu-IN",
      "name": "gu-IN-Standard-A",
      "language": "Gujarati (India)",
      "gender": "FEMALE"
    },
    {
      "code": "tr-TR",
      "name": "tr-TR-Wavenet-D",
      "language": "Turkish (Turkey)",
      "gender": "FEMALE"
    },
    {
      "code": "gu-IN",
      "name": "gu-IN-Standard-B",
      "language": "Gujarati (India)",
      "gender": "MALE"
    },
    {
      "code": "gu-IN",
      "name": "gu-IN-Wavenet-A",
      "language": "Gujarati (India)",
      "gender": "FEMALE"
    },
    {
      "code": "tr-TR",
      "name": "tr-TR-Wavenet-E",
      "language": "Turkish (Turkey)",
      "gender": "MALE"
    },
    {
      "code": "gu-IN",
      "name": "gu-IN-Wavenet-B",
      "language": "Gujarati (India)",
      "gender": "MALE"
    },
    {
      "code": "uk-UA",
      "name": "uk-UA-Standard-A",
      "language": "Ukrainian (Ukraine)",
      "gender": "FEMALE"
    },
    {
      "code": "hi-IN",
      "name": "hi-IN-Standard-A",
      "language": "Hindi (India)",
      "gender": "FEMALE"
    },
    {
      "code": "uk-UA",
      "name": "uk-UA-Wavenet-A",
      "language": "Ukrainian (Ukraine)",
      "gender": "FEMALE"
    },
    {
      "code": "hi-IN",
      "name": "hi-IN-Standard-B",
      "language": "Hindi (India)",
      "gender": "MALE"
    },
    {
      "code": "vi-VN",
      "name": "vi-VN-Standard-A",
      "language": "Vietnamese (Vietnam)",
      "gender": "FEMALE"
    },
    {
      "code": "vi-VN",
      "name": "vi-VN-Standard-B",
      "language": "Vietnamese (Vietnam)",
      "gender": "MALE"
    },
    {
      "code": "hi-IN",
      "name": "hi-IN-Standard-C",
      "language": "Hindi (India)",
      "gender": "MALE"
    },
    {
      "code": "vi-VN",
      "name": "vi-VN-Standard-C",
      "language": "Vietnamese (Vietnam)",
      "gender": "FEMALE"
    },
    {
      "code": "hi-IN",
      "name": "hi-IN-Standard-D",
      "language": "Hindi (India)",
      "gender": "FEMALE"
    },
    {
      "code": "da-DK",
      "name": "da-DK-Standard-E",
      "language": "Danish (Denmark)",
      "gender": "FEMALE"
    },
    {
      "code": "hi-IN",
      "name": "hi-IN-Wavenet-A",
      "language": "Hindi (India)",
      "gender": "FEMALE"
    },
    {
      "code": "da-DK",
      "name": "da-DK-Wavenet-A",
      "language": "Danish (Denmark)",
      "gender": "FEMALE"
    },
    {
      "code": "hi-IN",
      "name": "hi-IN-Wavenet-B",
      "language": "Hindi (India)",
      "gender": "MALE"
    },
    {
      "code": "da-DK",
      "name": "da-DK-Wavenet-C",
      "language": "Danish (Denmark)",
      "gender": "MALE"
    },
    {
      "code": "hi-IN",
      "name": "hi-IN-Wavenet-C",
      "language": "Hindi (India)",
      "gender": "MALE"
    },
    {
      "code": "da-DK",
      "name": "da-DK-Wavenet-D",
      "language": "Danish (Denmark)",
      "gender": "FEMALE"
    },
    {
      "code": "hi-IN",
      "name": "hi-IN-Wavenet-D",
      "language": "Hindi (India)",
      "gender": "FEMALE"
    },
    {
      "code": "da-DK",
      "name": "da-DK-Wavenet-E",
      "language": "Danish (Denmark)",
      "gender": "FEMALE"
    },
    {
      "code": "hu-HU",
      "name": "hu-HU-Standard-A",
      "language": "Hungarian (Hungary)",
      "gender": "FEMALE"
    },
    {
      "code": "nl-BE",
      "name": "nl-BE-Standard-A",
      "language": "Dutch (Belgium)",
      "gender": "FEMALE"
    },
    {
      "code": "hu-HU",
      "name": "hu-HU-Wavenet-A",
      "language": "Hungarian (Hungary)",
      "gender": "FEMALE"
    },
    {
      "code": "vi-VN",
      "name": "vi-VN-Standard-D",
      "language": "Vietnamese (Vietnam)",
      "gender": "MALE"
    },
    {
      "code": "nl-BE",
      "name": "nl-BE-Standard-B",
      "language": "Dutch (Belgium)",
      "gender": "MALE"
    },
    {
      "code": "is-IS",
      "name": "is-is-Standard-A",
      "language": "Icelandic (Iceland)",
      "gender": "FEMALE"
    },
    {
      "code": "vi-VN",
      "name": "vi-VN-Wavenet-A",
      "language": "Vietnamese (Vietnam)",
      "gender": "FEMALE"
    },
    {
      "code": "nl-BE",
      "name": "nl-BE-Wavenet-A",
      "language": "Dutch (Belgium)",
      "gender": "FEMALE"
    },
    {
      "code": "id-ID",
      "name": "id-ID-Standard-A",
      "language": "Indonesian (Indonesia)",
      "gender": "FEMALE"
    },
    {
      "code": "vi-VN",
      "name": "vi-VN-Wavenet-B",
      "language": "Vietnamese (Vietnam)",
      "gender": "MALE"
    },
    {
      "code": "nl-BE",
      "name": "nl-BE-Wavenet-B",
      "language": "Dutch (Belgium)",
      "gender": "MALE"
    },
    {
      "code": "id-ID",
      "name": "id-ID-Standard-B",
      "language": "Indonesian (Indonesia)",
      "gender": "MALE"
    },
    {
      "code": "nl-NL",
      "name": "nl-NL-Standard-A",
      "language": "Dutch (Netherlands)",
      "gender": "FEMALE"
    },
    {
      "code": "vi-VN",
      "name": "vi-VN-Wavenet-C",
      "language": "Vietnamese (Vietnam)",
      "gender": "FEMALE"
    },
    {
      "code": "id-ID",
      "name": "id-ID-Standard-C",
      "language": "Indonesian (Indonesia)",
      "gender": "MALE"
    },
    {
      "code": "nl-NL",
      "name": "nl-NL-Standard-B",
      "language": "Dutch (Netherlands)",
      "gender": "MALE"
    },
    {
      "code": "id-ID",
      "name": "id-ID-Standard-D",
      "language": "Indonesian (Indonesia)",
      "gender": "FEMALE"
    },
    {
      "code": "nl-NL",
      "name": "nl-NL-Standard-C",
      "language": "Dutch (Netherlands)",
      "gender": "MALE"
    },
    {
      "code": "id-ID",
      "name": "id-ID-Wavenet-A",
      "language": "Indonesian (Indonesia)",
      "gender": "FEMALE"
    },
    {
      "code": "nl-NL",
      "name": "nl-NL-Standard-D",
      "language": "Dutch (Netherlands)",
      "gender": "FEMALE"
    },
    {
      "code": "id-ID",
      "name": "id-ID-Wavenet-B",
      "language": "Indonesian (Indonesia)",
      "gender": "MALE"
    },
    {
      "code": "nl-NL",
      "name": "nl-NL-Standard-E",
      "language": "Dutch (Netherlands)",
      "gender": "FEMALE"
    },
    {
      "code": "nl-NL",
      "name": "nl-NL-Wavenet-A",
      "language": "Dutch (Netherlands)",
      "gender": "FEMALE"
    },
    {
      "code": "id-ID",
      "name": "id-ID-Wavenet-C",
      "language": "Indonesian (Indonesia)",
      "gender": "MALE"
    },
    {
      "code": "vi-VN",
      "name": "vi-VN-Wavenet-D",
      "language": "Vietnamese (Vietnam)",
      "gender": "MALE"
    },
    {
      "code": "nl-NL",
      "name": "nl-NL-Wavenet-B",
      "language": "Dutch (Netherlands)",
      "gender": "MALE"
    },
    {
      "code": "id-ID",
      "name": "id-ID-Wavenet-D",
      "language": "Indonesian (Indonesia)",
      "gender": "FEMALE"
    },
    {
      "code": "nl-NL",
      "name": "nl-NL-Wavenet-C",
      "language": "Dutch (Netherlands)",
      "gender": "MALE"
    },
    {
      "code": "it-IT",
      "name": "it-IT-Standard-A",
      "language": "Italian (Italy)",
      "gender": "FEMALE"
    },
    {
      "code": "nl-NL",
      "name": "nl-NL-Wavenet-D",
      "language": "Dutch (Netherlands)",
      "gender": "FEMALE"
    },
    {
      "code": "it-IT",
      "name": "it-IT-Standard-B",
      "language": "Italian (Italy)",
      "gender": "FEMALE"
    },
    {
      "code": "nl-NL",
      "name": "nl-NL-Wavenet-E",
      "language": "Dutch (Netherlands)",
      "gender": "FEMALE"
    },
    {
      "code": "it-IT",
      "name": "it-IT-Standard-C",
      "language": "Italian (Italy)",
      "gender": "MALE"
    },
    {
      "code": "en-AU",
      "name": "en-AU-Standard-A",
      "language": "English (Australia)",
      "gender": "FEMALE"
    },
    {
      "code": "it-IT",
      "name": "it-IT-Standard-D",
      "language": "Italian (Italy)",
      "gender": "MALE"
    },
    {
      "code": "en-AU",
      "name": "en-AU-Standard-B",
      "language": "English (Australia)",
      "gender": "MALE"
    },
    {
      "code": "it-IT",
      "name": "it-IT-Wavenet-A",
      "language": "Italian (Italy)",
      "gender": "FEMALE"
    },
    {
      "code": "en-AU",
      "name": "en-AU-Standard-C",
      "language": "English (Australia)",
      "gender": "FEMALE"
    },
    {
      "code": "en-AU",
      "name": "en-AU-Standard-D",
      "language": "English (Australia)",
      "gender": "MALE"
    },
    {
      "code": "it-IT",
      "name": "it-IT-Wavenet-B",
      "language": "Italian (Italy)",
      "gender": "FEMALE"
    },
    {
      "code": "en-AU",
      "name": "en-AU-Wavenet-A",
      "language": "English (Australia)",
      "gender": "FEMALE"
    },
    {
      "code": "it-IT",
      "name": "it-IT-Wavenet-C",
      "language": "Italian (Italy)",
      "gender": "MALE"
    },
    {
      "code": "en-AU",
      "name": "en-AU-Wavenet-B",
      "language": "English (Australia)",
      "gender": "MALE"
    },
    {
      "code": "it-IT",
      "name": "it-IT-Wavenet-D",
      "language": "Italian (Italy)",
      "gender": "MALE"
    },
    {
      "code": "en-AU",
      "name": "en-AU-Wavenet-C",
      "language": "English (Australia)",
      "gender": "FEMALE"
    },
    {
      "code": "ja-JP",
      "name": "ja-JP-Standard-A",
      "language": "Japanese (Japan)",
      "gender": "FEMALE"
    },
    {
      "code": "en-AU",
      "name": "en-AU-Wavenet-D",
      "language": "English (Australia)",
      "gender": "MALE"
    },
    {
      "code": "ja-JP",
      "name": "ja-JP-Standard-B",
      "language": "Japanese (Japan)",
      "gender": "FEMALE"
    },
    {
      "code": "en-IN",
      "name": "en-IN-Standard-A",
      "language": "English (India)",
      "gender": "FEMALE"
    },
    {
      "code": "ja-JP",
      "name": "ja-JP-Standard-C",
      "language": "Japanese (Japan)",
      "gender": "MALE"
    },
    {
      "code": "en-IN",
      "name": "en-IN-Standard-B",
      "language": "English (India)",
      "gender": "MALE"
    },
    {
      "code": "ja-JP",
      "name": "ja-JP-Standard-D",
      "language": "Japanese (Japan)",
      "gender": "MALE"
    },
    {
      "code": "en-IN",
      "name": "en-IN-Standard-C",
      "language": "English (India)",
      "gender": "MALE"
    },
    {
      "code": "ja-JP",
      "name": "ja-JP-Wavenet-A",
      "language": "Japanese (Japan)",
      "gender": "FEMALE"
    },
    {
      "code": "en-IN",
      "name": "en-IN-Standard-D",
      "language": "English (India)",
      "gender": "FEMALE"
    },
    {
      "code": "ja-JP",
      "name": "ja-JP-Wavenet-B",
      "language": "Japanese (Japan)",
      "gender": "FEMALE"
    },
    {
      "code": "en-IN",
      "name": "en-IN-Wavenet-A",
      "language": "English (India)",
      "gender": "FEMALE"
    },
    {
      "code": "ja-JP",
      "name": "ja-JP-Wavenet-C",
      "language": "Japanese (Japan)",
      "gender": "MALE"
    },
    {
      "code": "en-IN",
      "name": "en-IN-Wavenet-B",
      "language": "English (India)",
      "gender": "MALE"
    },
    {
      "code": "ja-JP",
      "name": "ja-JP-Wavenet-D",
      "language": "Japanese (Japan)",
      "gender": "MALE"
    },
    {
      "code": "en-IN",
      "name": "en-IN-Wavenet-C",
      "language": "English (India)",
      "gender": "MALE"
    },
    {
      "code": "kn-IN",
      "name": "kn-IN-Standard-A",
      "language": "Kannada (India)",
      "gender": "FEMALE"
    },
    {
      "code": "en-IN",
      "name": "en-IN-Wavenet-D",
      "language": "English (India)",
      "gender": "FEMALE"
    },
    {
      "code": "kn-IN",
      "name": "kn-IN-Standard-B",
      "language": "Kannada (India)",
      "gender": "MALE"
    },
    {
      "code": "en-GB",
      "name": "en-GB-Standard-A",
      "language": "English (UK)",
      "gender": "FEMALE"
    },
    {
      "code": "kn-IN",
      "name": "kn-IN-Wavenet-A",
      "language": "Kannada (India)",
      "gender": "FEMALE"
    },
    {
      "code": "en-GB",
      "name": "en-GB-Standard-B",
      "language": "English (UK)",
      "gender": "MALE"
    },
    {
      "code": "kn-IN",
      "name": "kn-IN-Wavenet-B",
      "language": "Kannada (India)",
      "gender": "MALE"
    },
    {
      "code": "en-GB",
      "name": "en-GB-Standard-C",
      "language": "English (UK)",
      "gender": "FEMALE"
    },
    {
      "code": "ko-KR",
      "name": "ko-KR-Standard-A",
      "language": "Korean (South Korea)",
      "gender": "FEMALE"
    },
    {
      "code": "en-GB",
      "name": "en-GB-Standard-D",
      "language": "English (UK)",
      "gender": "MALE"
    },
    {
      "code": "ko-KR",
      "name": "ko-KR-Standard-B",
      "language": "Korean (South Korea)",
      "gender": "FEMALE"
    },
    {
      "code": "en-GB",
      "name": "en-GB-Standard-F",
      "language": "English (UK)",
      "gender": "FEMALE"
    },
    {
      "code": "ko-KR",
      "name": "ko-KR-Standard-C",
      "language": "Korean (South Korea)",
      "gender": "MALE"
    },
    {
      "code": "ko-KR",
      "name": "ko-KR-Standard-D",
      "language": "Korean (South Korea)",
      "gender": "MALE"
    },
    {
      "code": "ko-KR",
      "name": "ko-KR-Wavenet-A",
      "language": "Korean (South Korea)",
      "gender": "FEMALE"
    },
    {
      "code": "en-GB",
      "name": "en-GB-Wavenet-A",
      "language": "English (UK)",
      "gender": "FEMALE"
    },
    {
      "code": "ko-KR",
      "name": "ko-KR-Wavenet-B",
      "language": "Korean (South Korea)",
      "gender": "FEMALE"
    },
    {
      "code": "en-GB",
      "name": "en-GB-Wavenet-B",
      "language": "English (UK)",
      "gender": "MALE"
    },
    {
      "code": "en-GB",
      "name": "en-GB-Wavenet-C",
      "language": "English (UK)",
      "gender": "FEMALE"
    },
    {
      "code": "ko-KR",
      "name": "ko-KR-Wavenet-C",
      "language": "Korean (South Korea)",
      "gender": "MALE"
    },
    {
      "code": "en-GB",
      "name": "en-GB-Wavenet-D",
      "language": "English (UK)",
      "gender": "MALE"
    },
    {
      "code": "en-GB",
      "name": "en-GB-Wavenet-F",
      "language": "English (UK)",
      "gender": "FEMALE"
    },
    {
      "code": "ko-KR",
      "name": "ko-KR-Wavenet-D",
      "language": "Korean (South Korea)",
      "gender": "MALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Standard-A",
      "language": "English (US)",
      "gender": "MALE"
    },
    {
      "code": "lv-LV",
      "name": "lv-lv-Standard-A",
      "language": "Latvian (Latvia)",
      "gender": "MALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Standard-B",
      "language": "English (US)",
      "gender": "MALE"
    },
    {
      "code": "ms-MY",
      "name": "ms-MY-Standard-A",
      "language": "Malay (Malaysia)",
      "gender": "FEMALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Standard-C",
      "language": "English (US)",
      "gender": "FEMALE"
    },
    {
      "code": "ms-MY",
      "name": "ms-MY-Standard-B",
      "language": "Malay (Malaysia)",
      "gender": "MALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Standard-D",
      "language": "English (US)",
      "gender": "MALE"
    },
    {
      "code": "ms-MY",
      "name": "ms-MY-Standard-C",
      "language": "Malay (Malaysia)",
      "gender": "FEMALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Standard-E",
      "language": "English (US)",
      "gender": "FEMALE"
    },
    {
      "code": "ms-MY",
      "name": "ms-MY-Standard-D",
      "language": "Malay (Malaysia)",
      "gender": "MALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Standard-F",
      "language": "English (US)",
      "gender": "FEMALE"
    },
    {
      "code": "ms-MY",
      "name": "ms-MY-Wavenet-A",
      "language": "Malay (Malaysia)",
      "gender": "FEMALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Standard-G",
      "language": "English (US)",
      "gender": "FEMALE"
    },
    {
      "code": "ms-MY",
      "name": "ms-MY-Wavenet-B",
      "language": "Malay (Malaysia)",
      "gender": "MALE"
    },
    {
      "code": "ms-MY",
      "name": "ms-MY-Wavenet-C",
      "language": "Malay (Malaysia)",
      "gender": "FEMALE"
    },
    {
      "code": "ms-MY",
      "name": "ms-MY-Wavenet-D",
      "language": "Malay (Malaysia)",
      "gender": "MALE"
    },
    {
      "code": "ml-IN",
      "name": "ml-IN-Standard-A",
      "language": "Malayalam (India)",
      "gender": "FEMALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Standard-H",
      "language": "English (US)",
      "gender": "FEMALE"
    },
    {
      "code": "ml-IN",
      "name": "ml-IN-Standard-B",
      "language": "Malayalam (India)",
      "gender": "MALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Standard-I",
      "language": "English (US)",
      "gender": "MALE"
    },
    {
      "code": "ml-IN",
      "name": "ml-IN-Wavenet-A",
      "language": "Malayalam (India)",
      "gender": "FEMALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Standard-J",
      "language": "English (US)",
      "gender": "MALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Wavenet-A",
      "language": "English (US)",
      "gender": "MALE"
    },
    {
      "code": "ml-IN",
      "name": "ml-IN-Wavenet-B",
      "language": "Malayalam (India)",
      "gender": "MALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Wavenet-B",
      "language": "English (US)",
      "gender": "MALE"
    },
    {
      "code": "cmn-CN",
      "name": "cmn-CN-Standard-A",
      "language": "Mandarin Chinese",
      "gender": "FEMALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Wavenet-C",
      "language": "English (US)",
      "gender": "FEMALE"
    },
    {
      "code": "cmn-CN",
      "name": "cmn-CN-Standard-B",
      "language": "Mandarin Chinese",
      "gender": "MALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Wavenet-D",
      "language": "English (US)",
      "gender": "MALE"
    },
    {
      "code": "cmn-CN",
      "name": "cmn-CN-Standard-C",
      "language": "Mandarin Chinese",
      "gender": "MALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Wavenet-E",
      "language": "English (US)",
      "gender": "FEMALE"
    },
    {
      "code": "cmn-CN",
      "name": "cmn-CN-Standard-D",
      "language": "Mandarin Chinese",
      "gender": "FEMALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Wavenet-F",
      "language": "English (US)",
      "gender": "FEMALE"
    },
    {
      "code": "cmn-CN",
      "name": "cmn-CN-Wavenet-A",
      "language": "Mandarin Chinese",
      "gender": "FEMALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Wavenet-G",
      "language": "English (US)",
      "gender": "FEMALE"
    },
    {
      "code": "cmn-CN",
      "name": "cmn-CN-Wavenet-B",
      "language": "Mandarin Chinese",
      "gender": "MALE"
    },
    {
      "code": "cmn-CN",
      "name": "cmn-CN-Wavenet-C",
      "language": "Mandarin Chinese",
      "gender": "MALE"
    },
    {
      "code": "cmn-CN",
      "name": "cmn-CN-Wavenet-D",
      "language": "Mandarin Chinese",
      "gender": "FEMALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Wavenet-H",
      "language": "English (US)",
      "gender": "FEMALE"
    },
    {
      "code": "cmn-TW",
      "name": "cmn-TW-Standard-A",
      "language": "Mandarin Chinese",
      "gender": "FEMALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Wavenet-I",
      "language": "English (US)",
      "gender": "MALE"
    },
    {
      "code": "cmn-TW",
      "name": "cmn-TW-Standard-B",
      "language": "Mandarin Chinese",
      "gender": "MALE"
    },
    {
      "code": "en-US",
      "name": "en-US-Wavenet-J",
      "language": "English (US)",
      "gender": "MALE"
    },
    {
      "code": "cmn-TW",
      "name": "cmn-TW-Standard-C",
      "language": "Mandarin Chinese",
      "gender": "MALE"
    },
    {
      "code": "cmn-TW",
      "name": "cmn-TW-Wavenet-A",
      "language": "Mandarin Chinese",
      "gender": "FEMALE"
    },
    {
      "code": "fil-PH",
      "name": "fil-PH-Standard-A",
      "language": "Filipino (Philippines)",
      "gender": "FEMALE"
    },
    {
      "code": "cmn-TW",
      "name": "cmn-TW-Wavenet-B",
      "language": "Mandarin Chinese",
      "gender": "MALE"
    },
    {
      "code": "fil-PH",
      "name": "fil-PH-Standard-B",
      "language": "Filipino (Philippines)",
      "gender": "FEMALE"
    },
    {
      "code": "cmn-TW",
      "name": "cmn-TW-Wavenet-C",
      "language": "Mandarin Chinese",
      "gender": "MALE"
    },
    {
      "code": "fil-PH",
      "name": "fil-PH-Standard-C",
      "language": "Filipino (Philippines)",
      "gender": "MALE"
    },
    {
      "code": "nb-NO",
      "name": "nb-NO-Standard-A",
      "language": "Norwegian (Norway)",
      "gender": "FEMALE"
    },
    {
      "code": "fil-PH",
      "name": "fil-PH-Standard-D",
      "language": "Filipino (Philippines)",
      "gender": "MALE"
    },
    {
      "code": "fil-PH",
      "name": "fil-PH-Wavenet-A",
      "language": "Filipino (Philippines)",
      "gender": "FEMALE"
    },
    {
      "code": "nb-NO",
      "name": "nb-NO-Standard-B",
      "language": "Norwegian (Norway)",
      "gender": "MALE"
    },
    {
      "code": "nb-NO",
      "name": "nb-NO-Standard-C",
      "language": "Norwegian (Norway)",
      "gender": "FEMALE"
    },
    {
      "code": "nb-NO",
      "name": "nb-NO-Standard-D",
      "language": "Norwegian (Norway)",
      "gender": "MALE"
    },
    {
      "code": "nb-NO",
      "name": "nb-NO-Wavenet-A",
      "language": "Norwegian (Norway)",
      "gender": "FEMALE"
    },
    {
      "code": "nb-NO",
      "name": "nb-NO-Wavenet-B",
      "language": "Norwegian (Norway)",
      "gender": "MALE"
    },
    {
      "code": "nb-NO",
      "name": "nb-NO-Wavenet-C",
      "language": "Norwegian (Norway)",
      "gender": "FEMALE"
    },
    {
      "code": "nb-NO",
      "name": "nb-NO-Wavenet-D",
      "language": "Norwegian (Norway)",
      "gender": "MALE"
    },
    {
      "code": "nb-NO",
      "name": "nb-no-Standard-E",
      "language": "Norwegian (Norway)",
      "gender": "FEMALE"
    },
    {
      "code": "nb-NO",
      "name": "nb-no-Standard-E",
      "language": "Norwegian (Norway)",
      "gender": "FEMALE"
    },
    {
      "code": "nb-NO",
      "name": "nb-no-Wavenet-E",
      "language": "Norwegian (Norway)",
      "gender": "FEMALE"
    },
    {
      "code": "pl-PL",
      "name": "pl-PL-Standard-A",
      "language": "Polish (Poland)",
      "gender": "FEMALE"
    },
    {
      "code": "pl-PL",
      "name": "pl-PL-Standard-B",
      "language": "Polish (Poland)",
      "gender": "MALE"
    },
    {
      "code": "pl-PL",
      "name": "pl-PL-Standard-C",
      "language": "Polish (Poland)",
      "gender": "MALE"
    },
    {
      "code": "pl-PL",
      "name": "pl-PL-Standard-D",
      "language": "Polish (Poland)",
      "gender": "FEMALE"
    },
    {
      "code": "pl-PL",
      "name": "pl-PL-Standard-E",
      "language": "Polish (Poland)",
      "gender": "FEMALE"
    },
    {
      "code": "pl-PL",
      "name": "pl-PL-Wavenet-A",
      "language": "Polish (Poland)",
      "gender": "FEMALE"
    },
    {
      "code": "pl-PL",
      "name": "pl-PL-Wavenet-B",
      "language": "Polish (Poland)",
      "gender": "MALE"
    },
    {
      "code": "pl-PL",
      "name": "pl-PL-Wavenet-C",
      "language": "Polish (Poland)",
      "gender": "MALE"
    },
    {
      "code": "pl-PL",
      "name": "pl-PL-Wavenet-D",
      "language": "Polish (Poland)",
      "gender": "FEMALE"
    },
    {
      "code": "pl-PL",
      "name": "pl-PL-Wavenet-E",
      "language": "Polish (Poland)",
      "gender": "FEMALE"
    },
    {
      "code": "pt-BR",
      "name": "pt-BR-Standard-A",
      "language": "Portuguese (Brazil)",
      "gender": "FEMALE"
    },
    {
      "code": "pt-BR",
      "name": "pt-BR-Standard-B",
      "language": "Portuguese (Brazil)",
      "gender": "MALE"
    },
    {
      "code": "pt-BR",
      "name": "pt-BR-Wavenet-A",
      "language": "Portuguese (Brazil)",
      "gender": "FEMALE"
    },
    {
      "code": "pt-BR",
      "name": "pt-BR-Wavenet-B",
      "language": "Portuguese (Brazil)",
      "gender": "MALE"
    },
    {
      "code": "pt-PT",
      "name": "pt-PT-Standard-A",
      "language": "Portuguese (Portugal)",
      "gender": "FEMALE"
    },
    {
      "code": "pt-PT",
      "name": "pt-PT-Standard-B",
      "language": "Portuguese (Portugal)",
      "gender": "MALE"
    },
    {
      "code": "pt-PT",
      "name": "pt-PT-Standard-C",
      "language": "Portuguese (Portugal)",
      "gender": "MALE"
    },
    {
      "code": "pt-PT",
      "name": "pt-PT-Standard-D",
      "language": "Portuguese (Portugal)",
      "gender": "FEMALE"
    },
    {
      "code": "pt-PT",
      "name": "pt-PT-Wavenet-A",
      "language": "Portuguese (Portugal)",
      "gender": "FEMALE"
    },
    {
      "code": "pt-PT",
      "name": "pt-PT-Wavenet-B",
      "language": "Portuguese (Portugal)",
      "gender": "MALE"
    },
    {
      "code": "pt-PT",
      "name": "pt-PT-Wavenet-C",
      "language": "Portuguese (Portugal)",
      "gender": "MALE"
    },
    {
      "code": "pt-PT",
      "name": "pt-PT-Wavenet-D",
      "language": "Portuguese (Portugal)",
      "gender": "FEMALE"
    },
    {
      "code": "pa-IN",
      "name": "pa-IN-Standard-A",
      "language": "Punjabi (India)",
      "gender": "FEMALE"
    },
    {
      "code": "pa-IN",
      "name": "pa-IN-Standard-B",
      "language": "Punjabi (India)",
      "gender": "MALE"
    },
    {
      "code": "pa-IN",
      "name": "pa-IN-Standard-C",
      "language": "Punjabi (India)",
      "gender": "FEMALE"
    },
    {
      "code": "pa-IN",
      "name": "pa-IN-Standard-D",
      "language": "Punjabi (India)",
      "gender": "MALE"
    },
    {
      "code": "pa-IN",
      "name": "pa-IN-Wavenet-A",
      "language": "Punjabi (India)",
      "gender": "FEMALE"
    },
    {
      "code": "pa-IN",
      "name": "pa-IN-Wavenet-B",
      "language": "Punjabi (India)",
      "gender": "MALE"
    },
    {
      "code": "pa-IN",
      "name": "pa-IN-Wavenet-C",
      "language": "Punjabi (India)",
      "gender": "FEMALE"
    },
    {
      "code": "pa-IN",
      "name": "pa-IN-Wavenet-D",
      "language": "Punjabi (India)",
      "gender": "MALE"
    },
    {
      "code": "ro-RO",
      "name": "ro-RO-Standard-A",
      "language": "Romanian (Romania)",
      "gender": "FEMALE"
    },
    {
      "code": "ro-RO",
      "name": "ro-RO-Wavenet-A",
      "language": "Romanian (Romania)",
      "gender": "FEMALE"
    },
    {
      "code": "ru-RU",
      "name": "ru-RU-Standard-A",
      "language": "Russian (Russia)",
      "gender": "FEMALE"
    },
    {
      "code": "ru-RU",
      "name": "ru-RU-Standard-B",
      "language": "Russian (Russia)",
      "gender": "MALE"
    },
    {
      "code": "ru-RU",
      "name": "ru-RU-Standard-C",
      "language": "Russian (Russia)",
      "gender": "FEMALE"
    },
    {
      "code": "ru-RU",
      "name": "ru-RU-Standard-D",
      "language": "Russian (Russia)",
      "gender": "MALE"
    },
    {
      "code": "ru-RU",
      "name": "ru-RU-Standard-E",
      "language": "Russian (Russia)",
      "gender": "FEMALE"
    },
    {
      "code": "ru-RU",
      "name": "ru-RU-Wavenet-A",
      "language": "Russian (Russia)",
      "gender": "FEMALE"
    },
    {
      "code": "ru-RU",
      "name": "ru-RU-Wavenet-B",
      "language": "Russian (Russia)",
      "gender": "MALE"
    },
    {
      "code": "ru-RU",
      "name": "ru-RU-Wavenet-C",
      "language": "Russian (Russia)",
      "gender": "FEMALE"
    },
    {
      "code": "ru-RU",
      "name": "ru-RU-Wavenet-D",
      "language": "Russian (Russia)",
      "gender": "MALE"
    },
    {
      "code": "ru-RU",
      "name": "ru-RU-Wavenet-E",
      "language": "Russian (Russia)",
      "gender": "FEMALE"
    },
    {
      "code": "sr-RS",
      "name": "sr-rs-Standard-A",
      "language": "Serbian (Cyrillic)",
      "gender": "FEMALE"
    },
    {
      "code": "sk-SK",
      "name": "sk-SK-Standard-A",
      "language": "Slovak (Slovakia)",
      "gender": "FEMALE"
    },
    {
      "code": "sk-SK",
      "name": "sk-SK-Wavenet-A",
      "language": "Slovak (Slovakia)",
      "gender": "FEMALE"
    },
    {
      "code": "es-ES",
      "name": "es-ES-Standard-A",
      "language": "Spanish (Spain)",
      "gender": "FEMALE"
    },
    {
      "code": "es-ES",
      "name": "es-ES-Standard-B",
      "language": "Spanish (Spain)",
      "gender": "MALE"
    },
    {
      "code": "es-ES",
      "name": "es-ES-Standard-C",
      "language": "Spanish (Spain)",
      "gender": "FEMALE"
    },
    {
      "code": "es-ES",
      "name": "es-ES-Standard-D",
      "language": "Spanish (Spain)",
      "gender": "FEMALE"
    },
    {
      "code": "es-ES",
      "name": "es-ES-Wavenet-B",
      "language": "Spanish (Spain)",
      "gender": "MALE"
    },
    {
      "code": "es-ES",
      "name": "es-ES-Wavenet-C",
      "language": "Spanish (Spain)",
      "gender": "FEMALE"
    },
    {
      "code": "es-ES",
      "name": "es-ES-Wavenet-D",
      "language": "Spanish (Spain)",
      "gender": "FEMALE"
    },
    {
      "code": "es-US",
      "name": "es-US-Standard-A",
      "language": "Spanish (US)",
      "gender": "FEMALE"
    },
    {
      "code": "es-US",
      "name": "es-US-Standard-B",
      "language": "Spanish (US)",
      "gender": "MALE"
    },
    {
      "code": "es-US",
      "name": "es-US-Standard-C",
      "language": "Spanish (US)",
      "gender": "MALE"
    },
    {
      "code": "es-US",
      "name": "es-US-Wavenet-A",
      "language": "Spanish (US)",
      "gender": "FEMALE"
    },
    {
      "code": "es-US",
      "name": "es-US-Wavenet-B",
      "language": "Spanish (US)",
      "gender": "MALE"
    },
    {
      "code": "es-US",
      "name": "es-US-Wavenet-C",
      "language": "Spanish (US)",
      "gender": "MALE"
    },
    {
      "code": "sv-SE",
      "name": "sv-SE-Standard-A",
      "language": "Swedish (Sweden)",
      "gender": "FEMALE"
    },
    {
      "code": "sv-SE",
      "name": "sv-SE-Standard-B",
      "language": "Swedish (Sweden)",
      "gender": "FEMALE"
    },
    {
      "code": "sv-SE",
      "name": "sv-SE-Standard-C",
      "language": "Swedish (Sweden)",
      "gender": "FEMALE"
    },
    {
      "code": "sv-SE",
      "name": "sv-SE-Standard-D",
      "language": "Swedish (Sweden)",
      "gender": "MALE"
    },
    {
      "code": "sv-SE",
      "name": "sv-SE-Standard-E",
      "language": "Swedish (Sweden)",
      "gender": "MALE"
    }
  ]
}
```

