# 0002-ADR-invitation-code-length-and-type

## Status

Accepted

## Context

When user wants to invite someone to join a house, user needs to generate an invitation code.
The invitation code was designed to be sent by LINE or other messaging apps.
In future, we may also want to show the QR code in our app.

The invitation code needs to be unique and easy to remember.

## Decision Drivers

We decided to use a random string with a length of 6 characters including numbers and letters.
This length is enough to be unique and easy to remember.
Although the length of 6 characters is not enough to be unique, we can restrict the invitation code to expire after a certain period of time.
So it only needs to be unique within a certain period of time.

## Alternatives Considered

1. **Random string with a length of more characters**: It may be hard to remember for users if they need to type it by themselves.
2. **Random string with a length of less characters**: It may not be unique enough.

## Consequences

The invitation code may still be too long for some users.
