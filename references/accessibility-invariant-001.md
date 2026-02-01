# ACCESSIBILITY-INV-001: All interactive elements must be reachable and operable via keyboard

**Category**: Accessibility

Every interactive element must be focusable and fully operable with a keyboard alone.

## Invariant

All interactive elements (links, buttons, inputs, toggles, menus, dialogs, custom controls) must be reachable via a logical keyboard focus order and be fully operable using standard keyboard interactions without requiring a pointer.

**Example**: A custom dropdown opens with Enter/Space, navigates options with Arrow keys, and confirms with Enter.

## Applies When

Any time a user can take an action or change state in the UI, including custom components, modals, overlays, and in-context controls.

**Example**: A table row action menu, a date picker, and a drag-and-drop alternative action.

## Why This Exists

Keyboard access is essential for users who cannot use a mouse, supports assistive technologies, and is a baseline accessibility requirement for compliance and usability.

**Example**: Users navigating via switch control rely on predictable keyboard focus and activation.

## AVOID: Common Violations

Controls that are not focusable, not visible in the tab order, or require mouse-only interactions to complete.

**Example**:

- Click-only icons or div-based buttons without keyboard handlers
- Custom dropdowns that trap focus or cannot be opened with Enter/Space
- Drag-and-drop flows with no keyboard alternative
