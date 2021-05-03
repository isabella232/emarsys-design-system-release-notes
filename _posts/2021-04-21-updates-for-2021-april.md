---
layout: post
title: "Design System Updates for 2021 April"
date: 2021-04-21 08:55:00
---

Enhancements:
- `e-widget` now can be implemented without shadow.
- Improved error message handling for `e-datetime` component.
- The emoji picker has been updated with new emojis.
- In destructive dialogs, the destructive button can now be disabled.
- `e-datagrid` action icons can now open a new tab.

Changes:
- Unified the look of `e-multiselect` and `e-select`.
- Icon usage in “error state” and “warning state” are now consistent across components.
- Improved copywriting in `e-datetime` error state.
- Unified hover and select style in `e-multiselect`, `e-select`, and `e-dropdown`.
- The "close button" in `e-dialog` now use the `e-button` component, instead of an `e-icon`.
- Added border around tabbed page layout to make it consistent with other layouts.
- “Danger” state has been renamed to “error” state to distance it from “warning” state.

Fixes:
- Fixed button labels and caret position in Editor toolbar.
- Fixed header in form layout.

Icon updates:
- We’ve replaced most of our “fill-style” icons with “outline-style” icons for a consistent visual look.
- Added `e-logo-sap`, `ac-doi`, `ac-contacts-delete`, and `e-error` icons.
- Updated `warning`, `exclamation`, `exclamation-circle` icons.
- Fixed color problems with some icons.

Deprecation:
- Old date formatter has been deprecated. Pages that use the deprecated date formatter will get a warning in the console. Use new “date utils” instead.
- We’ve officially removed the old 2015 design from the current code. It's been a long journey!
