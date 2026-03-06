# Land Far Away — Brand Kit

> Studio: Land Far Away  
> App: Peek A Boo  
> Audience: Ages 0–5 and their faraway loved ones  
> Last updated: 2026-03-05

---

## Color Palette

| Swatch | Name | Hex | Usage |
|---|---|---|---|
| 🟦 | **Brand Teal** | `#6DCEC5` | Primary — mascot body, UI accents, borders |
| 🟧 | **Brand Orange** | `#E85A2B` | Secondary — CTAs, icon backgrounds, emphasis |
| 🟨 | **Sunshine Gold** | `#F5C442` | Highlights, "morning" theme, step numbers |
| 🔵 | **Night Blue** | `#5A9DD8` | "Night" theme, secondary accents |
| 🟩 | **Lime Green** | `#B8C82E` | Tertiary accent, energy, nature moments |
| 🟫 | **Charcoal** | `#3A3632` | Primary text, dark backgrounds |
| 🫙 | **Cream** | `#F5F0E1` | Page background, card fills |
| ⬜ | **White** | `#FFFFFF` | Content sections, contrast backgrounds |

### CSS Tokens

```css
:root {
  --teal:       #6DCEC5;
  --teal-dark:  #3EB5AD;
  --orange:     #E85A2B;
  --orange-dark:#C44A20;
  --gold:       #F5C442;
  --lime:       #B8C82E;
  --night-blue: #5A9DD8;
  --cream:      #F5F0E1;
  --charcoal:   #3A3632;
  --muted:      #7A7062;
}
```

### Accessibility
- **Teal on White:** Contrast ratio ~3.1:1 (large text / decorative only)
- **Orange on White:** Contrast ratio ~3.5:1 (use with bold/large text)
- **Charcoal on Cream:** Contrast ratio ~10:1 ✅ WCAG AAA for body text
- **White on Charcoal:** Contrast ratio ~10:1 ✅ WCAG AAA
- **White on Orange:** Contrast ratio ~3.5:1 (buttons — bold text passes AA)

---

## Typography

| Role | Font | Weight | Notes |
|---|---|---|---|
| Display / Headings | **Baloo 2** | 700, 800 | Rounded, playful — matches mascot energy |
| Body / UI | **Nunito** | 400, 600, 700 | Clean, friendly, highly readable |

Google Fonts import:
```html
<link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@600;700;800&family=Nunito:wght@400;600;700&display=swap" rel="stylesheet" />
```

---

## Brand Assets

All assets live in `assets/brand/`.

### Core Brand

| File | Description | Usage |
|---|---|---|
| `app-icon.png` | 1024×1024 mascot bust on orange circle | App Store / Play Store icon, nav logo, favicon source |
| `lockup.png` | Icon + "PEEK A BOO" wordmark + tagline | Marketing collateral, splash screen, press kit, OG image |
| `mascot.png` | Full-body mascot, transparent background | Hero sections, onboarding, CTA sections, animations |

### Feature Icons

| File | Feature | Description |
|---|---|---|
| `icon-peekaboo.png` | Peek-a-Boo | Mascot peeking — cropped compositional variant of app icon |
| `icon-gmgn.png` | Good Morning / Good Night | Split warm/cool half-and-half icon |
| `icon-drawwithme.png` | Draw With Me | Mascot with paintbrush + colorful splatters, watercolor style |

### Screenshots (`assets/screenshots/`)

| File | Content |
|---|---|
| `screen-01.png` | Color palette reference sheet |
| `screen-02.png` | Brand overview / style sheet |
| `screen-03.png` | Logo lockup — large |
| `screen-04.png` | Logo lockup — compact |
| `screen-05.png` | Early UX wireframes + expanded color palette |
| `screen-06.png` | In-app hallway (brown doors) |
| `screen-07.png` | In-app hallway (colored doors) |
| `screen-08.png` | "My Videos" UI screen |
| `screen-09.png` | Illustrated hallway environment / prop sheet |

---

## Mascot — Usage Guidelines

**The mascot is the brand's heart.** It should appear prominently on:
- App icon (always the orange circle crop)
- Hero sections (full body, with animation)
- Onboarding screens
- Empty states and delight moments
- Merchandise and marketing

**Do:**
- Keep it on light or white backgrounds for maximum impact
- Use the transparent PNG for compositing
- Drop-shadow is welcome: `filter: drop-shadow(0 12px 28px rgba(0,0,0,.15))`
- Animate it with gentle floating/bobbing (see CSS `@keyframes bob`)

**Don't:**
- Stretch or distort the proportions
- Place on busy photographic backgrounds without a colored circle
- Recolor the character (teal is the canonical body color)

---

## Art Style

- **Primary:** Flat vector illustration, minimal shading, clean edges, geometric shapes
- **Character style:** Kawaii-influenced Western (Toca Boca / Sago Mini aesthetic)
- **Accent style:** The "Draw With Me" icon uses watercolor/painted style — intentional to signal "creative mode"
- **Mood:** Warm, gender-neutral, safe, playful
- **Target age:** 0–5

---

## AI & SEO Optimization

The marketing site includes:
- Semantic HTML5 landmarks (`<nav>`, `<section>`, `<footer>` with `aria-labelledby`)
- JSON-LD structured data (`MobileApplication` schema)
- `<meta>` description, keywords, Open Graph, Twitter Card tags
- Descriptive `alt` text on all meaningful images
- Decorative images marked `aria-hidden="true"`
- Focus-visible styles for keyboard navigation

---

## Ownership

All brand assets are original and owned by Land Far Away / Emily Yang.  
Public GitHub hosting is approved. For questions: see `TOOLS.md` for contact info.
