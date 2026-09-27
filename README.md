# Borozdov Brief

A theme from the Borozdov collection. Two faces — light **Docket**, an editorial law journal
on warm white, and dark **Chambers**, the same journal in a panelled room. A whisper serif,
black ink, square 2px corners and pale verdigris and slate washes instead of colour.

![Borozdov Brief in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/brief/main/screenshots/light.png)

![Borozdov Brief in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/brief/main/screenshots/dark.png)

## Principles

- **Authority through type, not colour.** STIX Two Text for the title, the two largest
  headings and pull quotes, at display size with tight tracking and leading; the
  platform's own sans for the column text.
- **Near-monochrome.** Ivory and ink carry the page. The only tints are two pale washes:
  verdigris for what is selected or open, slate mist for highlights, the plain note and a
  link under the pointer.
- **Eyebrows.** Callout titles, table headers, tags and property names are small tracked
  capitals, the way a journal labels its sections.
- **Square corners.** Buttons, fields and tags keep 2px corners; cards 8px. The main
  button is solid black with ivory text, plain buttons are ghosts with an ink rule.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as pale washes of their type's colour with an eyebrow label
- Pull quotes in the serif, two sizes up, behind a hairline ink rule
- Tags as eyebrow chips behind a pewter rule
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory:** Settings → Appearance → Themes → Manage, search for
**Borozdov Brief**, then **Install and use**.

**By hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/brief/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Brief/`, then choose Borozdov Brief under
Settings → Appearance → Themes.

## Font

STIX Two Text (© 2001–2021 The STIX Fonts Project Authors) is embedded in `theme.css` as
base64 WOFF2 under the SIL Open Font License 1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt).
One weight, Latin and Cyrillic, for the title, the two largest headings and pull quotes
only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Реестр» — редакционный
юридический журнал на тёплом белом, и тёмный «Кабинет» — тот же журнал в комнате с
панелями. Шепчущая антиква (STIX Two), чёрные чернила, прямые углы 2px и бледные заливки
ярь-медянки и грифеля вместо цвета. Устанавливается из каталога: Настройки → Оформление →
Темы → Настроить → Borozdov Brief → Установить и применить.
