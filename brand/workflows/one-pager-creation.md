# ConnectSmart One-Pager Creation Workflow

## Overview
This workflow ensures consistent, error-free one-pager production using ConnectSmart brand guidelines.

---

## Critical Rules

1. **NEVER embed text directly in AI-generated images**
   - AI tools (DALL·E, Stable Diffusion, Midjourney) distort and misspell text
   - Results in incorrect spelling, spacing, and grammar

2. **Always use the official master copy**
   - Located at: `brand/assets/master-copy/connectsmart-one-pager.txt`
   - This text is approved and error-free

---

## Production Workflow

### Step 1: Prepare Text
- Use the exact text from the master copy file
- Do not modify or paraphrase
- Verify all contact information is current

### Step 2: Generate Background Layout
- Create visual mockup WITHOUT any text
- Follow brand color guidelines
- Leave clean space for text placement

**Background Style Options:**

| Option | Description | Use Case |
|--------|-------------|----------|
| A | Dark navy background (#0B1D2C) | Sales, marketing, executive presentations |
| B | Light background (#F7F9FA) | Training docs, internal materials |
| C | Hybrid (dark header, light body) | Executive slides, balanced layouts |

### Step 3: Compose Final Design
- Use professional design tool:
  - Canva
  - PowerPoint
  - Adobe Illustrator
  - Figma
- Place master copy text over background
- Apply brand typography (Inter for headings, Lato for body)

---

## Layout Requirements

### Header Section
- Dark navy background
- White text
- Bright green accent bar/underline

### Body Sections
- Clear visual hierarchy
- Section headers in teal (#1FA6A0)
- Body text in appropriate contrast color

### Footer
- NetCarrier logo: bottom-right corner
- Minimum 16px clearspace around logo
- Contact info: left-aligned

---

## Checklist Before Export

- [ ] All text matches master copy exactly
- [ ] Brand colors are correct
- [ ] Typography follows guidelines (Inter/Lato)
- [ ] Logo has proper clearspace (16px minimum)
- [ ] WCAG AA contrast requirements met
- [ ] Pattern usage under 25% of layout surface

---

## File Locations

- **Master Copy:** `brand/assets/master-copy/connectsmart-one-pager.txt`
- **Brand Config:** `brand/brand.json`
- **CSS Variables:** `brand/styles/variables.css`
