# Groovy NullPointerException in Arithmetic Operations

This example demonstrates a potential issue in Groovy related to null values and arithmetic operations.  Groovy's flexible type system allows for implicit type coercion, which can lead to unexpected behavior and NullPointerExceptions if not carefully managed, especially when dealing with null values.

The `bug.groovy` file showcases a function that attempts to gracefully handle null inputs. The `bugSolution.groovy` file provides a more robust solution. 

## How to reproduce

1. Clone this repository.
2. Run the `bug.groovy` script using a Groovy interpreter (e.g., `groovy bug.groovy`).
3. Observe the output and note the implicit handling of `null` values.

## Solution

The improved solution is in `bugSolution.groovy` file.