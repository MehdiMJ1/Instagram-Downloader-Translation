<a href="//t.me/IGLoaderRobot"><img src="logo.png" width="100%"/></a>
#### Help translate [@IGLoaderRobot](//t.me/IGLoaderRobot) — a Instagram downloader for Telegram Messenger
_Stay tuned for news and updates on our [Telegram Channel](//t.me/iCode11)_

---

YTAudioBot is currently available in the following languages:

Language | Contributors | (%)
:-- | :-- | :--
:us: **English** ([en_US](locales/en_US.json)) | [𝐇𝐀𝐂𝐇𝐄](//github.com/MehdiMJ1) | 100%
:ir: **Arabic** ([ar_IQ](locales/ar_IQ.json)) | [𝐇𝐀𝐂𝐇𝐄](//github.com/MehdiMJ1) | 100%

> Add yourself here once you submit your translations

All translations, except English (en_US), are made by volunteers who decided to help.
More translations and improved translations in any language are gratefully accepted!

You don't need to know how to program to create or improve translations.
All you need is a text editor, knowledge of the English language and of course knowledge of your own language.

## Localization guidelines
- Source/fallback is in English (en_US), updated simultaneously with Araic (ar_IQ).
- Locale files are stored under `locales` in JSON format: `{"key": "value"}`.
- You only need to modify the `value` of the strings; do not translate the `key`.
- Keep symbols like `**bold**`, `__italic__`, `` `code` ``, `\n`, `[` , `]` unaltered.
- Do not translate format fields such as `{username}` and `{seconds}`.
- Do not add or omit any text, also try to keep the same string length.

## How to improve or create a new localization
The process is slightly different depending upon whether you are improving an existing localization or creating a new one.

### Improving an existing localization
* [Look](locales) for the language file you want to review and compare it with [English (en_US)](locales/en_US.json).
* Edit the translated strings you want to improve or translate the missing ones (`null`) by following the [localization guidelines](#localization-guidelines).
* Send a pull request with your changes.

### Creating a new localization
To avoid different people working on the same language at the same time, first check whether your language is not already taken by someone else. So, if it's not listed under [Open Issues](//github.com/MehdiMJ1/Instagram-Downloader-Translation/issues):

- Open a [New Issue](//github.com/MehdiMJ1/Instagram-Downloader-Translation/issues/new) to let other people know you are working on a new translation. 
    - Put language name and code in the title, e.g. `Deutsch (de_DE)`.

Then, you can start.

* Copy `en_US.json` and rename the file to your [language code](LANGUAGES.md), e.g. `de_DE.json`.
* Edit the file to change the English strings to your language strings by following the [localization guidelines](#localization-guidelines). 
* Send a pull request with your changes.

If you don't know exactly how to translate a specific string you can set the entire value to `null`, e.g. `"ConfirmRevoke": null`.
This way, it will be replaced with the corresponding string in English (en_US) as a fallback until the translated string is available.

---

If you happen to find something to improve (without completely change the meaning), feel free to make changes.

## Contacts
- Telegram: [@haskell](//t.me/BotsDevsChat).
