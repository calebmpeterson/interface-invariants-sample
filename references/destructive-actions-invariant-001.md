# DESTRUCTIVE-ACTIONS-INV-001: Destructive Actions Require Explicit Confirmation

**Category**: Destructive Actions

Irreversible actions must require an explicit confirmation step.

## Invariant

Irreversible actions must require an explicit confirmation step.

**Example**: Deleting an account requires a confirmation dialog with clear consequences.

## Applies When

An action permanently deletes or irreversibly alters user data.

**Example**: Removing a workspace, deleting a project, or revoking access cannot be undone.

## Why This Exists

Users make accidental clicks under stress. Irreversible loss breaks trust.

**Example**: A single misclick should not erase data, so we require explicit confirmation.

## AVOID: Common Violations

Single-click destructive actions with no confirmation step.

**Example**:

- Single-click delete buttons
- Confirmation via toast only
