---
sidebar_label: 'Button'
sidebar_position: 0
---

# Button

A simple, accessible Button component used across the site. Use this component for primary actions, secondary actions, and general clickable controls.

## Usage

```jsx
<Button variant="primary" onClick={() => alert('Clicked!')}>Click me</Button>
```

## Props

- `variant` (string) — "primary" | "secondary". Controls the visual style. Default: "primary".
- `disabled` (boolean) — When true, the button is disabled and not interactive.
- `onClick` (function) — Click handler for the button.
- `size` (string) — "sm" | "md" | "lg". Controls the button size. Default: "md".

## Accessibility

- Ensure the `onClick` handler is keyboard-friendly (use button element or role/button with key handlers).
- Provide meaningful button text that describes the action.

## Do

- Do prefer descriptive text: "Save changes" instead of "Click".
- Do use `disabled` for unavailable actions.
- Do keep button labels short and action-oriented.

