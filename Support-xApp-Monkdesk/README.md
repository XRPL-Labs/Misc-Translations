# Xumm Support xApp

Translation files (`langcode.json`, langcode lower case) are used in the Xumm Support xApp

## [https://xumm.app/detect/xapp:xumm.support-md](https://xumm.app/detect/xapp:xumm.support-md)

When merged, if the JSON is valid, updates will be published every two hours.

# Credits

- Thank you @rsteimen for German 🇩🇪 @ [#4](https://github.com/XRPL-Labs/Misc-Translations/pull/4)
- Thank you @ihomp for Russian 🇷🇺 @ [#3](https://github.com/XRPL-Labs/Misc-Translations/pull/3)
- Thank you @silkjaer for Danish 🇩🇰 @ [#2](https://github.com/XRPL-Labs/Misc-Translations/pull/2)
- Thank you @ekiserrepe for Spanish 🇪🇸 @ [#1](https://github.com/XRPL-Labs/Misc-Translations/pull/1)

## Base translation(s)

Base Translations are in English (`en.json`). If labels are missing in other languages, they automatically fall back to English.

The language used to render the xApp:

1. Try Xumm Language (if present)
2. Try OS Browser language (if presenrt)
3. Fall back to default (English)

## Warnings

Please note:

- Some translations contain minor HTML (tags). This is OK. They should be left in place around whatever emphasis is added to.
- Variables are named and look like this: `{{ version }}`. Variables should stay present, but can be moved around.

# Contributing

1. Create/edit the language file (`langcode.json`), e.g. `jp.json`
2. If you are creating, please copy the contents of `en.json`
3. If you are editing, please check if new keys have been added to `en.json`, potentially missing from your language of choice
4. Make your changes.
5. Copy the entire file contents, and use an [online JSON validator](https://jsonlint.com/) to check if it's still valid JSON
6. Submit a Pull Request
