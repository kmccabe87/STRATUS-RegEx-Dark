# STRATUS RegEx Dark

A Notepad++ user-defined language (UDL) for GTP STRATUS data, with regex-based word styling and an optional auto-complete dictionary.

## Contents

| File | Purpose |
| --- | --- |
| `STRATUS_RegEx_Dark.xml` | Main user-defined language (UDL) definition |
| `AutoComplete/STRATUS_RegEx_Dark.xml` | Auto-complete dictionary for the language |
| `AutoComplete/Install.txt` | Auto-complete installation instructions |

## Requirements

- [Notepad++](https://notepad-plus-plus.org/) (latest stable)
- Optional: the [JetBrains Mono](https://www.jetbrains.com/mono/) font for the look the language was designed around (grab the latest from the [JetBrains Mono releases](https://github.com/JetBrains/JetBrainsMono/releases))

## Installation

### 1. Install the language

1. In Notepad++, go to **Language → Import → Import from file…**.
2. Select `STRATUS_RegEx_Dark.xml` from this repository.
3. The STRATUS language now appears in the **Language** menu. Select it on a document to apply the syntax highlighting.

### 2. Install auto-complete (optional)

> The auto-complete XML needs to have the **same name as the UDL** to work.

1. Copy `AutoComplete/STRATUS_RegEx_Dark.xml` into the `autoComplete` folder located in the Notepad++ programs folder.
2. Restart Notepad++ (or open a new document) and type inside a STRATUS file to trigger auto-complete.

### 3. Font (optional)

To match the intended look, install the [JetBrains Mono font](https://github.com/JetBrains/JetBrainsMono/releases), then in Notepad++ go to **Settings → Style Configurator → Font** and select it.

## Notes

- The root `STRATUS_RegEx_Dark.xml` is the current UDL. The copy in `AutoComplete/` is the matching auto-complete dictionary — install them as a pair.

## License

Distributed under the [GPL-3.0](LICENSE) license.
