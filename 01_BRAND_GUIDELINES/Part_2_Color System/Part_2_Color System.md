# 02_Brand_Guidelines.md — Part 2
# Color System

---

# Overview

Color is one of the strongest identity elements of FANNAN.

The color system is inspired by Palestinian heritage while maintaining a modern digital product aesthetic.

Every color has a semantic purpose.

Avoid using colors arbitrarily.

The interface should feel:

- Calm
- Elegant
- Warm
- Premium
- Human
- Cultural

Artwork must always remain the visual focus.

---

# Color Philosophy

The FANNAN color palette is built around six foundational colors.

Each represents an aspect of Palestinian identity.

| Color | Meaning |
|---------|---------|
| Fannan Blue | Trust • Technology • Professionalism |
| Heritage Green | Heritage • Olive Trees • Authenticity |
| Creative Orange | Creativity • Action • Energy |
| Sandy Beige | Warmth • Handmade Paper • Stone |
| Embroidery Crimson | Palestinian Embroidery • Culture |
| Fresh Mint | Freshness • Balance • Soft Accent |

---

# Primary Brand Colors

## FANNAN Blue

Primary Brand Color

Purpose

- Navigation
- Headers
- Logos
- Primary Text
- Brand Identity

HEX

```text
#0F3D5E
```

RGB

```text
15 61 94
```

HSL

```text
204° 72% 21%
```

Usage

70% of branding.

Never use as page background.

Always maintain high contrast.

---

## Heritage Green

Secondary Brand Color

Purpose

- Heritage labels
- Category indicators
- Verified Artist Badge
- Decorative accents

HEX

```text
#6B8E23
```

RGB

```text
107 142 35
```

HSL

```text
80° 60% 35%
```

Usage

Accent only.

Avoid large green surfaces.

---

## Creative Orange

CTA Color

Purpose

- Primary Buttons
- Buy Now
- Explore
- Checkout
- Add to Cart

HEX

```text
#E67E22
```

RGB

```text
230 126 34
```

HSL

```text
30° 80% 52%
```

Usage

Maximum visual attention.

Reserved for important actions.

Never overuse.

---

## Sandy Beige

Primary Background

Purpose

- App Background
- Website Background
- Cards Background Alternative
- Empty States

HEX

```text
#F5EFE4
```

RGB

```text
245 239 228
```

HSL

```text
39° 46% 93%
```

Usage

Default application background.

Provides warmth.

Reduces eye fatigue.

---

## Embroidery Crimson

Cultural Accent

Purpose

- Borders
- Decorative Patterns
- Traditional Categories
- Hover Decorations

HEX

```text
#8C1D40
```

RGB

```text
140 29 64
```

HSL

```text
341° 66% 33%
```

Usage

Use sparingly.

Never replace primary brand colors.

---

## Fresh Mint

Supporting Accent

Purpose

- Success Highlights
- Secondary Decorations
- Empty States
- Educational Sections

HEX

```text
#BDE5C8
```

RGB

```text
189 229 200
```

HSL

```text
136° 42% 82%
```

---

# Neutral Palette

## Gray 50

```text
#FAFAFA
```

---

## Gray 100

```text
#F5F5F5
```

---

## Gray 200

```text
#EEEEEE
```

---

## Gray 300

```text
#DDDDDD
```

---

## Gray 400

```text
#BBBBBB
```

---

## Gray 500

```text
#888888
```

---

## Gray 600

```text
#666666
```

---

## Gray 700

```text
#444444
```

---

## Gray 800

```text
#2A2A2A
```

---

## Gray 900

```text
#111111
```

---

# Semantic Colors

## Success

```text
#2E7D32
```

Purpose

- Successful payments
- Completed orders
- Success alerts

---

## Warning

```text
#F9A825
```

Purpose

- Low inventory
- Pending verification
- Draft content

---

## Error

```text
#D32F2F
```

Purpose

- Validation errors
- Failed payment
- Critical alerts

---

## Information

```text
#1976D2
```

Purpose

- System information
- Tooltips
- Help messages

---

# Surface Colors

Primary Surface

```text
#FFFFFF
```

Secondary Surface

```text
#F9F7F3
```

Elevated Surface

```text
#FFFFFF
```

Disabled Surface

```text
#F1F1F1
```

---

# Text Colors

Primary

```text
#1B1B1B
```

Secondary

```text
#5C5C5C
```

Muted

```text
#7C7C7C
```

Placeholder

```text
#A5A5A5
```

Inverse

```text
#FFFFFF
```

Link

```text
#0F3D5E
```

---

# Border Colors

Light

```text
#EAEAEA
```

Medium

```text
#D6D6D6
```

Strong

```text
#BBBBBB
```

Focus Border

```text
#0F3D5E
```

Error Border

```text
#D32F2F
```

---

# Color Usage Rules

## Blue

Use for:

- Navigation
- Links
- Titles
- Authentication
- Brand Identity

Never use blue for warning states.

---

## Orange

Use only for:

- Primary CTA
- Checkout
- Purchase
- Add To Cart

Do not use orange as body text.

---

## Green

Use for:

- Verified Artist
- Heritage Categories
- Success

Never use green for destructive actions.

---

## Crimson

Use as:

- Decorative divider
- Embroidery motifs
- Premium highlights

Avoid large crimson backgrounds.

---

## Beige

Default page background.

Large sections.

Cards grouping.

Landing pages.

---

# Color Hierarchy

Visual Priority

1.

Orange

↓

2.

Blue

↓

3.

Green

↓

4.

Crimson

↓

5.

Mint

↓

6.

Neutral Gray

---

# Accessibility

All text combinations must meet WCAG AA.

Minimum contrast ratio

Body Text

4.5:1

Large Text

3:1

Interactive Components

4.5:1

Icons

3:1

---

# Design Tokens

```json
{
  "brand.primary": "#0F3D5E",
  "brand.secondary": "#6B8E23",
  "brand.accent": "#E67E22",
  "background.primary": "#F5EFE4",
  "accent.cultural": "#8C1D40",
  "accent.soft": "#BDE5C8",
  "text.primary": "#1B1B1B",
  "text.secondary": "#5C5C5C",
  "surface.primary": "#FFFFFF",
  "border.default": "#EAEAEA"
}
```

---

# CSS Variables

```css
:root{

--color-primary:#0F3D5E;
--color-secondary:#6B8E23;
--color-accent:#E67E22;
--color-background:#F5EFE4;
--color-crimson:#8C1D40;
--color-mint:#BDE5C8;

--text-primary:#1B1B1B;
--text-secondary:#5C5C5C;

--surface:#FFFFFF;
--border:#EAEAEA;

--success:#2E7D32;
--warning:#F9A825;
--error:#D32F2F;
--info:#1976D2;

}
```

---

# Tailwind Theme

```ts
colors:{

primary:"#0F3D5E",

secondary:"#6B8E23",

accent:"#E67E22",

background:"#F5EFE4",

crimson:"#8C1D40",

mint:"#BDE5C8",

success:"#2E7D32",

warning:"#F9A825",

error:"#D32F2F",

info:"#1976D2"

}
```

---

# Future Dark Mode

Dark mode is planned but not included in MVP.

Guidelines

- Never invert artwork.
- Preserve original artwork colors.
- Use dark neutral surfaces.
- Maintain brand blue.
- Reduce saturated orange brightness by approximately 10–15%.
- Keep contrast compliant with WCAG AA.

---

# Color Do's

✅ Use beige as the default page background.

✅ Use orange only for primary actions.

✅ Let artwork remain the most colorful element on screen.

✅ Keep generous whitespace.

✅ Prefer neutral UI around vibrant artwork.

---

# Color Don'ts

❌ Don't use all brand colors in one component.

❌ Don't use orange for headings.

❌ Don't place colorful gradients behind artwork.

❌ Don't use saturated backgrounds behind product images.

❌ Don't compete visually with artists' work.

---

# Guiding Principle

The interface should never steal attention from the artwork.

Color exists to support the artist—not to compete with them.

---

# Next Section

**02_Brand_Guidelines.md — Part 3**

Typography

Grid System

Spacing

Sizing

Elevation

Border Radius

Responsive Breakpoints

Layout Principles
