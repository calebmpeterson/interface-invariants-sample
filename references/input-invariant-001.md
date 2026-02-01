# INPUT-INV-001: Use appropriate input type for the data expected from the user

**Category**: Input

Input controls must match the data type being collected so the browser, OS, and assistive tech can help the user enter it correctly.

## Invariant

Use the most specific, semantically correct input type (and related attributes) for the data expected, instead of a generic text field.

**Example**: Use `type="email"` for email, `type="tel"` for phone numbers, and `type="number"` with min/max/step for numeric values in browser-based apps.

## Applies When

Any form or flow that collects structured data with known formats or constraints.

**Example**: Signup, checkout, profile settings, billing, or scheduling fields.

## Why This Exists

Correct input types unlock native keyboards, validation, autofill, and accessibility semantics, reducing errors and friction.

**Example**: Email keyboards expose `@`, numeric keyboards reduce typos, and screen readers announce expected input.

## AVOID: Common Violations

Using generic text inputs when a specific type or control exists.

**Example**:

- `type="text"` for email, phone, or number fields
- Freeform text for dates instead of a date input or picker
- Numeric inputs without min/max/step or units, leading to ambiguous values
