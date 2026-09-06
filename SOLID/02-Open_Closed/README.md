# Open/Closed Principle (OCP)

## Definition

Software entities should be open for extension but closed for modification.

## Simple Meaning

We should be able to add new behavior without changing existing,
working code.

## Open for Extension

We should be able to add new functionality or behavior.

## Closed for Modification

Existing, tested code should not need to be modified whenever
we add a new feature.

## Why do we need OCP?

- Avoid breaking existing code
- Reduce bugs
- Easier to extend
- Better maintainability
- Reduce large if-else/switch blocks

## How to identify OCP violation?

If adding every new type or behavior requires repeatedly modifying
the same existing class, the design may be violating OCP.

## Interview Definition

The Open/Closed Principle states that software entities should be
open for extension but closed for modification.

## Key Point

Open for Extension → Add new behavior

Closed for Modification → Don't keep changing existing code
