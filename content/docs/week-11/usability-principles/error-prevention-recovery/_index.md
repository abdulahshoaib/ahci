---
title: Error Prevention and Recovery
weight: 3
---

# Error Prevention and Recovery

Error prevention and recovery are fundamental usability principles that help users avoid mistakes and recover from them when they occur.

Good interface design assumes that users will make errors. Instead of blaming users, systems should be designed to minimize errors and provide effective recovery mechanisms.

## Error Prevention

Error prevention focuses on stopping mistakes before they happen.

Designers should identify situations where users commonly make errors and modify the interface to reduce the likelihood of those errors.

### Techniques for Error Prevention

| Technique | Purpose | Example |
|------------|---------|---------|
| Input Validation | Prevent invalid data entry | Reject letters in a phone number field |
| Constraints | Restrict invalid actions | Disabled Submit button until required fields are completed |
| Confirmation Dialogs | Prevent accidental actions | "Are you sure you want to delete this file?" |
| Clear Instructions | Reduce misunderstanding | Password requirements shown before entry |
| Default Values | Guide correct actions | Pre-selecting common options |
| Limited Choices | Reduce decision errors | Dropdown menus instead of free-text input |

### Norman's Principle: Exploit the Power of Constraints

Constraints prevent users from performing incorrect actions.

#### Physical Constraints

Prevent actions physically.

**Example:**

- Disabled buttons
- Read-only fields

#### Logical Constraints

Allow only valid choices.

**Example:**

- Invalid dates cannot be selected
- Unavailable seats cannot be booked

Good constraints reduce user errors before they occur.

### Shneiderman's Golden Rule

**Offer Error Prevention and Simple Error Handling**

Interfaces should prevent errors whenever possible and provide understandable guidance when errors occur.

---

## Error Recovery

Error recovery focuses on helping users correct mistakes after they have been recognized.

A system should allow users to recover with minimal effort and without losing important work.

### Recoverability

Recoverability is the ability of users to take corrective action once an error has been recognized.

Two forms of recovery are commonly used.

| Type | Description |
|--------|-------------|
| Forward Recovery | Continue from the error and move toward completion |
| Backward Recovery | Return to a previous safe state |

### Forward Recovery

The user fixes the problem and continues.

**Examples:**

- Correcting an invalid password
- Updating missing form fields
- Re-uploading a failed file

### Backward Recovery

The user returns to an earlier state.

**Examples:**

- Undo command
- Recycle Bin
- Restore previous version
- Cancel operation

### Norman's Principle: Design for Error

Design should assume mistakes will occur.

Interfaces should support:

- Error detection
- Error explanation
- Error correction
- Error recovery

### Examples

| Error | Recovery Mechanism |
|---------|------------------|
| Accidental deletion | Undo or Recycle Bin |
| Wrong text entered | Edit and resubmit |
| Application crash | Auto-save and recovery |
| Incorrect form submission | Error message with correction guidance |

---

## Characteristics of Good Error Messages

Good error messages should:

- Clearly explain the problem
- Identify what caused the error
- Suggest a solution
- Avoid technical jargon
- Be polite and constructive

### Poor Example

> Error 0x5047A2

### Better Example

> Password must contain at least 8 characters and one number.

---

## Benefits of Error Prevention and Recovery

- Reduces user frustration
- Improves usability
- Increases user confidence
- Reduces task failure
- Improves efficiency
- Supports exploration without fear of mistakes

## Summary Table

| Concept | Goal | Examples |
|----------|------|---------|
| Error Prevention | Stop errors before they occur | Constraints, validation, confirmations, defaults |
| Error Recovery | Help users fix mistakes after they occur | Undo, Recycle Bin, auto-save, version history |
| Forward Recovery | Continue after correcting an error | Fix invalid input and proceed |
| Backward Recovery | Return to a previous safe state | Undo, restore, cancel |
| Recoverability | Enable corrective action after errors | Error correction tools and recovery options |
| Design for Error | Assume mistakes will occur and support recovery | Undo, confirmations, recovery dialogs |
