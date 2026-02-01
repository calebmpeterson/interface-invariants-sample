# FEEDBACK-INV-001: Direct the user's attention to the first invalid input when they attempt to submit data

**Category**: Feedback

When submission fails validation, the interface must guide the user to the first invalid field immediately.

## Invariant

On submit attempts, the first invalid input is clearly highlighted and brought into focus so the user can correct it without hunting.

**Example**: After clicking Submit, focus moves to the first invalid field and its error is visible.

## Applies When

Any form or data entry flow where a submit/save/continue action can be blocked by validation errors.

**Example**: A checkout form, signup flow, or settings save can fail due to validation errors.

## Why This Exists

Users should never have to guess why a submit failed. Guiding them to the first error reduces confusion, speeds recovery, and prevents abandonment.

**Example**: Users lose confidence when a submit fails without guidance, so we lead them to the first fix.

## AVOID: Common Violations

The submission fails but the user is left to find errors manually.

**Example**:

- Error messages only appear at the top of the page with no field focus
- Inline errors are shown, but focus stays on the submit button
- Multiple fields fail, but nothing indicates which one is first
