## Styling Guide

**CSS Architecture**

The project uses a modular CSS structure:

• `base.css` → Design tokens, global resets, utility classes

• `components.css` → Section-level component styling

• `style.css` → Imports and bundles styles

This separation ensures:

• Scalability

• Clear responsibility boundaries

• Easier collaboration in a team setting

**Design Tokens (CSS Variables)**

All styling decisions are driven by centralized CSS variables defined in `:root` inside `base.css`.

**Color System**

The color system uses semantic tokens mapped to brand tokens:
```css
  --color-blush-red: #e94b6a;
  --color-cotton-candy-pink: #f7a8b8;
  --color-creamy-white: #fff5ec;
  --color-wine-red: #5a0f2e;
  --color-soft-peach: #ffe3dc;
```
These are mapped to semantic variables:
```css
  --action-primary
  --action-secondary
  --text-main
  --bg-body
  --bg-nav
```

**Why This Approach?**

• Prevents hard-coded colors

• Makes theme updates easy

• Improves consistency

• Encourages scalable design

## Links to the Case Study and Design Documents

- [Case Study Document](https://docs.google.com/document/d/10sSPaC7eT5ar5xGpL0Z7Zjgmv5B9D0x_rr76d7eJwi8/edit?usp=sharing)
- [Design Document](https://docs.google.com/document/d/1vC-gI-Z0wWPh3IMVYmDQaIPncc59SCCFuK3dXT18Fjw/edit?usp=sharing)

---

## Link to the Contribution Sheet
