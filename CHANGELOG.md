# Change Log

## [0.3.0]

#### Code Snippets

Added code snippets support for `.hytrans`.
added `%1.0`, `&encoding=utf-8`, `&indent=1`, `&non-content=ignore` snippets.

Added code snippets support for `.hylangs`.
Currently, there's some language family template.

> The weight of each language in Language Family Template currently is set based on the population of the language's main country area.

#### Syntax Highights changes

- Added `.hytrans` empty line (starts with spaces/tabs) support.
  - Will trade this line as a comment line.
- Fix `.hytrans` support for non-break-line (starts with `\`) in content section.

## [0.2.1]

- Better suppport for `.hytrans`.
- Added `.aiin` as *HyTrans* file extensions.
- Normalize syntax names/colors (maybe).
  - and language-configuration now basicly set.

- Add support for *Hyper Language List `.hylangs`*.
  - supported syntax highlighting for each language define line with its weight

## [0.0.1-dev1]

Add basic support.
