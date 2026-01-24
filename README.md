# CRE APT Workshop — AI och Elevhälsa
> Åstorps kommun, januari 2026

## 📋 Projektinfo

| Fält | Värde |
|------|-------|
| **Status** | ✅ Genomförd 2026-01-24 |
| **Målgrupp** | Elevhälsoteam, Åstorps kommun |
| **Format** | 90 min interaktiv workshop |
| **Webbadress** | https://hktcr.github.io/CRE_APT_jan2026/shell.html |

## 🎯 Syfte

Ge elevhälsopersonal förståelse för:
- Hur AI-chatbotar fungerar (tokens, mönstermaskning)
- Risker med ungdomars AI-användning (parasociala relationer, integritet, normalisering)
- Praktiska verktyg för att upptäcka och samtala om AI-användning
- Möjligheter att använda AI i eget arbete (dokumentation, översättning, samtalsförberedelse)

## 📁 Filstruktur

```
CRE_APT_jan2026/
├── shell.html          # Huvudpresentation (all logik + styling)
├── slides.json         # Slide-innehåll (redigera för att ändra text/bilder)
├── assets/             # Bilder och ikoner
│   ├── presenter_avatar.png
│   ├── hinton_portrait.png
│   ├── icon_*.png      # Possibilities-ikoner
│   └── risk_*.png      # Risk-ikoner
└── README.md           # Denna fil
```

## 🔧 Återanvändning

### Enkla ändringar (slides.json)
- **Ändra texter**: Redigera `text`, `title`, `label` etc. i JSON
- **Lägg till slides**: Kopiera en befintlig slide-block och ändra `id`
- **Ta bort slides**: Radera slide-blocket från arrayen

### Tema-ändringar (shell.html)
Ändra CSS-variabler i `:root`:
```css
--bg: #000000;           /* Bakgrundsfärg */
--card-bg: #2a2a2a;      /* Kortfärg */
--accent: #f97316;       /* Accentfärg (orange) */
```

### Slide-typer

| Typ | Användning |
|-----|------------|
| `title` | Titelsida |
| `presenter` | Presentatörssida med avatar |
| `quote` | Citat med typewriter-effekt |
| `stat` | Stor siffra med källa |
| `grid` | 2x2 informationskort |
| `modal-cards` | Klickbara kort med förstorbar modal |
| `quad-flip` | Vändbara kort (fram/bak) |
| `traffic-light` | Grön/gul/röd kategorisering |
| `incidents` | Fallstudier med modal |
| `step-slide` | Stegvis genomgång |
| `token-demo` | Interaktiv ordprediktion |

## 📚 Källor

Alla använda källor finns dokumenterade i `slides.json` med `sources`-array per slide.

Huvudkällor:
- RAND Corporation (2025) — AI-användning bland unga
- SVT/Aftonbladet — Sewell-fallet
- NYT — Geoffrey Hinton-varning
- EU AI Act — Reglering

## 🏷️ Taggar

#workshop #ai #elevhälsa #presentation #åstorp #2026
