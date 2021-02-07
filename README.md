# My vscode-snippets

Here are my VSCode-Snippets

## Installation

Follow [this instructions](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_create-your-own-snippets) and add the desired Snippets from the 'snippets.code-snippets' file of this Repo.

## The Snippets

### CSS

#### font-definitions

This will give you all the important CSS attributes for font definition. Perfect start for typography nerds.

```css
/* ----------------------------------- */
/* -------- Font Definitionen -------- */
font-family: ; /* Schriftart */
font-size: ; /* Schriftgröße, Schriftgrad */
font-weight: ; /* Schriftstärke */
font-style: ; /* Schriftschnitt */
/* line-height: ; */ /* Zeilenabstand */
/* font-variant: ; */ /* Versalien, Kapitälchen usw. */
/* text-decoration: ; */
/* text-shadow: ; */
/* paint-order: ; */ /* für SVGs, wichig bei z.B. Schriftkonturen */

/* ------------------------------------------------------ */
/* -------- Verhalten des Textes im Blockelement -------- */
text-align: ;
/* text-justify: ; */ /* Darstellung bei Blocksatz (text-align: justify;) */
/* overflow-wrap: ; */
/* text-overflow: ;*/ /* Textfluss-Verhalten am Zeilenende */
/* white-space$: ;*/ /* Umbruchverhalten von Leerzeichen */
/* word-break: ;*/ /* Umbruchverhalten ohne Trennstriche */
/* text-align-last: ; */
/* -- Worttrennungen mit Trennstrichen -- */
/* -ms-hyphens: ; */ /* Edge, Internetexplorer */
/* -webkit-hyphens: ; */ /* Safari */
/* hyphens: ; */

/* ----------------------------------------------- */
/* -------- Fortgeschrittene Definitionen -------- */
/* letter-spacing: ; */ /* Spationierung */
/* text-indent: ; */ /* Einzug */
/* font-kerning: ; */ /* Kerning */
/* word-spacing: ; */ /* Ausschluss, Wortzwischenraum */
/* text-transform: ; */ /* Diverses. Großbuchstaben, Kleinbuchstaben, Laufweite, usw. */
/* font-stretch:; */ /* Skalierung der Glyphen */
/* text-size-adjust: ;*/ /* Schriftgrößenkorrekur auf Devices */

/* -------------------------------------- */
/* -------- Weitere Definitionen -------- */
/* font-feature-settings: ; */
/* font-language-override: ; */
/* font-optical-sizing: ; */
/* font-size-adjust: ; */
/* font-smooth: ; */ /* anti-aliasing KEIN STANDARD */
/* font-synthesis: ; */ /* steuert z.B. Bold-Simulation von Browsern  */
/* font-variant-alternates: ; */
/* font-variant-caps: ; */
/* font-variant-east-asian: ; */
/* font-variant-ligatures: ; */
/* font-variant-numeric: ; */
/* font-variant-position: ; */
/* font-variation-settings: ; */
/* line-height-step: ; */ /* Rundet die Line-height auf. Erzeugt Grundlinienraster (???) */
/* line-break: ; */ /* Umbruchverhalten im Chinesischen, Japanischen und Koreanischen */
/* tab-size: ; */
```

### Javascript

#### export-funct

```javascript
export const exportname = () => {
  // [...] Code

  return elements;
};
```

#### anonymous function

```javascript
() => {
  // [...] code
};
```

#### document-getElementById

```javascript
document.getElementById("elementId");
```

#### getElementsByClassName

```javascript
document.getElementsByClassName("className");
```

#### console.log

```javascript
console.log("Stuff");
```
