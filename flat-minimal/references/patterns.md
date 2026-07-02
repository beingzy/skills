# Flat Minimal Patterns

Use this reference when implementing layout, spacing, and visual polish.

## Enclave Recipe

```css
:root {
  --page: #fafafa;
  --wash: #f3f2ef;
  --surface-soft: color-mix(in srgb, var(--wash) 82%, #fff);
  --ink: #21201c;
  --text: #66645e;
  --radius: 14px;
  --read: 600px;
  --wide: 1040px;
}

.section {
  padding-bottom: clamp(96px, 10vw, 132px);
}

.section-header {
  width: min(var(--read), 100%);
  margin-bottom: clamp(30px, 4vw, 42px);
}

.breakout-grid {
  width: min(var(--wide), calc(100vw - 40px));
  margin-left: 50%;
  transform: translateX(-50%);
  display: grid;
  gap: clamp(24px, 3.5vw, 44px);
}

.enclave {
  border: 0;
  border-radius: var(--radius);
  background: var(--surface-soft);
  padding: clamp(30px, 3.5vw, 42px);
}
```

## When To Break Width

Break wider for:

- naming do and do-not cards
- usage rules
- logo and asset grids
- download package cards
- visual misuse examples
- public-facing implementation rules

Stay narrow for:

- section headings
- explanatory intros
- legal or policy copy
- prose that needs sustained reading

## Density Targets

The desired density is "chill but useful."

Too tight:

- body copy wraps every few words
- three cards feel like narrow columns
- examples touch labels or captions
- sections feel like stacked UI controls

Too loose:

- card padding dominates the content
- scroll distance increases without added clarity
- pale surfaces disappear into empty canvas
- group relationships become unclear

Balanced:

- cards are wide enough for natural lines
- labels are obvious but not loud
- pale surfaces read without outlines
- section scan order is immediate

## Common Fixes

- If text columns feel squeezed, widen the grid before shrinking type.
- If soft cards disappear, increase surface contrast slightly before adding borders.
- If a page feels noisy, remove outlines before reducing content.
- If a region feels unstructured, add an enclave before adding dividers.
- If a hero or intro feels heavy, keep it narrow and let the following content breathe wider.
