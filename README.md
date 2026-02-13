All styling decisions are driven by centralized CSS variables defined in `:root` inside `base.css`.
```bash
git clone https://github.com/De-jola/FLAMES.git
```

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
