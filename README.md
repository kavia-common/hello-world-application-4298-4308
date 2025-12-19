# hello-world-application-4298-4422

This project includes a reusable button component for Django templates.

- Template tag: `{% load ui_buttons %}` then `{% button "Click me" %}`.
- Supports variants: `primary`, `secondary`, `success`, `outline`, `ghost`, `link`.
- Supports sizes: `sm`, `md`, `lg`.
- Icons: pass class names via `icon_left` and/or `icon_right`.
- States: `disabled=True`, `loading=True` (adds spinner and aria-busy).
- As a link: pass `href="#"`. Disabled link uses `aria-disabled="true"` and prevents click.

Styles are in `api/static/css/components/button.css`.
Examples in `api/templates/home.html`.
