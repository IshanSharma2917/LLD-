# Interface Segregation Principle (ISP)

## Definition

Clients should not be forced to depend on methods they do not use.

## Simple Meaning

Don't create one big interface containing everything.
Split it into smaller, specific interfaces.

## Example

If a Worker interface contains:

- work()
- eat()
- sleep()

A Robot should not be forced to implement eat() and sleep()
because a robot doesn't need those methods.

## Better Approach

Split the large interface into smaller interfaces:

Workable
- work()

Eatable
- eat()

Sleepable
- sleep()

Now each class can implement only the interfaces it needs.

## Why do we need ISP?

- Smaller interfaces
- Less coupling
- Cleaner code
- Easier testing
- Easier maintenance
- Avoid unnecessary implementations

## How to identify ISP violation?

Ask:

"Is this class being forced to implement methods that it doesn't need?"

If yes, the interface may be too large.

## ISP vs SRP

SRP focuses on classes and their responsibilities.

ISP focuses on interfaces and preventing clients from depending
on methods they don't need.

## Interview Definition

The Interface Segregation Principle states that clients should not
be forced to depend on methods they do not use. Instead of having
large, general-purpose interfaces, we should create smaller,
focused interfaces.

## Key Point

Don't force unnecessary methods.

Keep interfaces small and specific.
