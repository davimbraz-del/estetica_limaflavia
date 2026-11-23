---
name: Flávia Lima · Estética e Massoterapia
description: A calm pastel spa care card; white and lilac, fine-line botanicals, a hand that welcomes.
colors:
  branco: "#FFFFFF"
  nuvem: "#FBF8FD"
  lilas: "#E9DDF7"
  lilas-2: "#D9C6F0"
  lavanda: "#B79CE0"
  roxo-claro: "#805EBA"
  roxo: "#6E4BA8"
  roxo-escuro: "#5A3B8F"
  cha: "#F6E4EC"
  tinta: "#3D3550"
  tinta-2: "#5E5470"
typography:
  signature:
    fontFamily: "Pinyon Script, cursive"
    fontSize: "clamp(2.4rem, 1.8rem + 2vw, 3.4rem)"
    fontWeight: 400
    lineHeight: 1
  display:
    fontFamily: "Gilda Display, Times New Roman, serif"
    fontSize: "clamp(2.75rem, 1.9rem + 4.2vw, 5.1rem)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "Gilda Display, Times New Roman, serif"
    fontSize: "clamp(2rem, 1.4rem + 2.6vw, 3.1rem)"
    fontWeight: 400
    lineHeight: 1.12
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Gilda Display, Times New Roman, serif"
    fontSize: "clamp(1.4rem, 1.2rem + 0.8vw, 1.75rem)"
    fontWeight: 400
    lineHeight: 1.2
  body:
    fontFamily: "Nunito, Segoe UI, system-ui, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "Nunito, Segoe UI, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 700
    lineHeight: 1.3
rounded:
  pill: "999px"
  card: "28px"
  card-lg: "44px"
  arch: "999px 999px 44px 44px"
spacing:
  gutter: "clamp(1.25rem, 5vw, 3rem)"
  section: "clamp(3.5rem, 8vw, 6.5rem)"
  container: "1160px"
components:
  button-primary:
    backgroundColor: "{colors.roxo}"
    textColor: "{colors.branco}"
    rounded: "{rounded.pill}"
    padding: "0.9rem 1.75rem"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.roxo-escuro}"
    textColor: "{colors.branco}"
  chip:
    backgroundColor: "{colors.nuvem}"
    textColor: "{colors.tinta}"
    rounded: "{rounded.pill}"
    height: "46px"
  chip-selected:
    backgroundColor: "{colors.lilas}"
    textColor: "{colors.roxo-escuro}"
  card:
    backgroundColor: "{colors.branco}"
    textColor: "{colors.tinta}"
    rounded: "{rounded.card-lg}"
    padding: "2rem 1.6rem"
---

# Design System: Flávia Lima · Estética e Massoterapia

## Overview

**Creative North Star: "The Care Card"**

The system is a spa's printed care card brought to the screen: a white and off-white ground, pastel lilac fields that own whole sections, and lavender fine-line leaves drawn as if by hand. Everything is soft-edged and unhurried. It should feel like a welcoming hand, never a clinic brochure and never a sales page.

Density is low and the rhythm is generous. Large serif headlines carry the voice, and a rounded sans keeps body copy easy to read for an audience up to 60+. Colour is always pastel. The one deep lilac belongs to actions and short emphasis only.

**Key Characteristics:**
- Pastel lilac and rose-tea fields alternate with white, joined by soft waves.
- Fine-line lavender botanicals (leaf, flower, drop, hand, crystal, calendar, house) are the only icon family.
- Pills and large rounded cards. The organic arch frames portraits.
- Diffuse, lilac-tinted, offset shadows. Never hard.
- The script face appears only on the name "Flávia Lima".

## Colors

A white-and-lilac palette, always pastel, with one deep lilac reserved for action.

### Primary
- **Orchid Ink** (`roxo`): fills every primary button and the floating WhatsApp button, and colours links. White text on it is 6.5:1.
- **Deep Orchid** (`roxo-escuro`): hover state for buttons, plus selected-state text on chips and toggles.
- **Soft Orchid** (`roxo-claro`): large display emphasis (the "sem dor." of the headline), titles in the objection cards and timeline dots. It is the brand's #8E6CC4 darkened to pass AA.

### Secondary
- **Lilac Mist** (`lilas`): section fields, the message bubble, selected chips and toggles, step badges, the footer.
- **Lilac Veil** (`lilas-2`): borders of chips and toggles, dotted leaders, scrollbar thumb and selection.
- **Lavender Line** (`lavanda`): every fine-line drawing and bullet dot.

### Tertiary
- **Rose Tea** (`cha`): one quiet second field (the proof section) and the highlight behind pending placeholders.

### Neutral
- **White** (`branco`) and **Cloud** (`nuvem`): grounds, cards and the hero wash.
- **Plum Ink** (`tinta`): all primary text. Never pure black.
- **Soft Plum** (`tinta-2`): secondary text. It holds 4.5:1 on every field in the palette.

### Named Rules
**The Pastel Field Rule.** Colour arrives as whole-section fields of Lilac Mist, Cloud or Rose Tea, never as scattered accents on a grey template.
**The One Ink Rule.** Orchid Ink is for actions and short emphasis only, never for large surfaces or long text.
**The No Red Rule.** No red, no alarm hues, anywhere.

## Typography

**Display Font:** Gilda Display (with Times New Roman)
**Body Font:** Nunito (with Segoe UI, system-ui)
**Signature Font:** Pinyon Script, used only for the name

**Character:** A slender, high-contrast serif speaks gently and with elegance. The rounded sans underneath keeps everything warm and legible.

### Hierarchy
- **Signature** (400, clamp 2.4–3.4rem, 1): "Flávia Lima" above the hero headline. Nowhere else.
- **Display** (400, clamp 2.75–5.1rem, 1.02): the single hero headline.
- **Headline** (400, clamp 2–3.1rem, 1.12): section titles, balanced wrap.
- **Title** (400, clamp 1.4–1.75rem): card and group titles in the serif.
- **Body** (400, 1.125rem, 1.65): paragraphs at 62ch maximum.
- **Label** (700–800, 0.95–1.06rem): buttons, chips, legends, timeline headings.

### Named Rules
**The Name-Only Script Rule.** The script face is reserved for "Flávia Lima". Headings never use it.
**The No Kicker Rule.** No eyebrow labels above headings. The serif heading speaks alone.

## Layout

Mobile-first single column. The container is 1160px wide with a fluid gutter of clamp(1.25rem, 5vw, 3rem). Sections pad clamp(3.5rem, 8vw, 6.5rem) top and less at the bottom when a wave follows. From 900–980px up, content splits into two columns (text and card, list and aside). The hero splits into a headline column and a 560px card column, with the care card overlapping the arch portrait. Waves (40–90px tall SVG, full bleed) separate every change of field.

## Elevation & Depth

Depth is ambient and soft: cards float slightly above pastel fields using lilac-tinted shadows with a vertical offset and a wide blur. Surfaces never use hard edges or zero-blur shadows.

### Shadow Vocabulary
- **Float** (`box-shadow: 0 18px 40px -18px rgba(94,64,150,.28), 0 4px 12px -6px rgba(94,64,150,.14)`): hero care card, arch portrait, slider, pricing card.
- **Rest** (`box-shadow: 0 10px 26px -14px rgba(94,64,150,.26)`): list cards, menu groups, objection cards, selected toggle.
- **Press** (`box-shadow: 0 14px 28px -14px rgba(90,59,143,.7)`): primary buttons, deepening on hover.

## Shapes

Everything is rounded. Pills (999px) for buttons, chips, toggles and tags; 28px for small cards; 44px for large cards and the slider; the arch (999px top, 44px bottom) for portraits. Waves are the only horizontal dividers between sections. Inside cards, 1px Lilac Mist rules and 2px dotted Lilac Veil leaders separate menu items.

## Components

### Buttons
- **Shape:** full pill (999px), at least 56px tall (48px in the header).
- **Primary:** Orchid Ink fill, white 800-weight Nunito, WhatsApp glyph at 22px.
- **Hover / Focus:** Deep Orchid fill, 2px lift, deeper Press shadow over 0.5s on an exponential ease-out; 3px Orchid Ink focus ring offset by 3px.

### Chips
- **Style:** Cloud fill, 1.5px Lilac Veil border, 600-weight text, 46px tall.
- **State:** when selected, the fill turns Lilac Mist, the border Soft Orchid and the text Deep Orchid, and a check icon slides in.

### Segmented toggle
- **Style:** white pill track with a Lilac Veil border and two 46px segments.
- **State:** the selected segment gets a Lilac Mist fill, a 2px Orchid Ink inset ring and a check icon.

### Cards / Containers
- **Corner Style:** 44px (large) or 28px (small).
- **Background:** White on pastel fields; Cloud for the quiet aside.
- **Shadow Strategy:** Float or Rest (see Elevation).
- **Border:** none, except a 1px Lilac Mist edge on the hero care card and a dashed Lavender Line on pending placeholders.
- **Internal Padding:** 1.5–2.25rem.

### Navigation
- Header: leaf mark, serif name and a pill CTA. Text links (Nunito 600) appear from 900px up and turn Orchid Ink on hover. A floating WhatsApp pill stays fixed at the bottom right and recedes while the care card is on screen.

### Care Card (signature)
A white 44px card that writes the WhatsApp message live. Chips say what to care for, the toggle picks the studio or home, a Lilac Mist bubble shows the composed message, and a full-width primary pill sends it.

### Care Menu (signature)
Grouped service lists, like a spa's printed menu: the service name, a dotted leader, then "Quero saber mais →" in Orchid Ink.

## Do's and Don'ts

### Do:
- **Do** keep every field pastel (Lilac Mist, Cloud, Rose Tea) and join fields with soft waves.
- **Do** draw icons as fine-line lavender botanicals with a 1.5px non-scaling stroke and round caps.
- **Do** keep body text at 1.125rem or larger, with touch targets of at least 44–48px.
- **Do** mark every placeholder visibly ("em breve", "exemplo ilustrativo", Rose Tea `[INSERIR]` highlights).

### Don't:
- **Don't** use red, countdowns, pop-ups or urgency badges.
- **Don't** use pure black text, or Orchid Ink for long text or large fills.
- **Don't** use the script face for anything but "Flávia Lima".
- **Don't** use emoji or unicode glyphs as icons. 💜 belongs to copy, sparingly.
- **Don't** use hard offset shadows or gradient text.
