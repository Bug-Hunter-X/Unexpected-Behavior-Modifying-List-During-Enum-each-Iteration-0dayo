# Elixir List Modification During Enum.each Iteration

This example demonstrates an issue related to modifying a list while iterating over it using `Enum.each` in Elixir.  Directly modifying the list within the `Enum.each` loop will not produce the expected result.

The `bug.exs` file shows the attempt to remove the element `3` from the list.  The `bugSolution.exs` file provides a corrected approach to achieve the desired list modification.

This repository showcases a common pitfall in Elixir list manipulation and illustrates a safe and efficient alternative.