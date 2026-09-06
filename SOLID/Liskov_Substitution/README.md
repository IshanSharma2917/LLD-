# Liskov Substitution Principle (LSP)

## Definition

Objects of a child class should be able to replace objects of the
parent class without breaking the behavior of the program.

## Simple Meaning

If B is a subtype of A, we should be able to use B wherever A is
expected without changing the correctness of the program.

## Example

If Bird has a fly() method, Penguin should not extend Bird if Penguin
cannot fulfill the behavior expected from Bird.

## Key Concept

A parent class defines a contract or expected behavior.
Child classes should respect that contract.

## How to identify LSP violation?

Ask:

"Can I replace the parent object with its child object without
breaking the program?"

If the answer is no, the inheritance relationship may violate LSP.

## Common Warning Signs

- Child throws UnsupportedOperationException for parent behavior
- Client code requires instanceof checks for specific subclasses
- Child changes the expected behavior of the parent
- Subclass cannot fulfill the parent's contract

## Interview Definition

The Liskov Substitution Principle states that objects of a subclass
should be replaceable for objects of the superclass without affecting
the correctness of the program.

## Key Point

Child should behave like a proper Parent.
