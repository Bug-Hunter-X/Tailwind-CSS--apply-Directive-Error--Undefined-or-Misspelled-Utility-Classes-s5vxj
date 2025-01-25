# Tailwind CSS @apply Directive Error: Undefined or Misspelled Utility Classes

This repository demonstrates a common yet often overlooked error when using Tailwind CSS's `@apply` directive: applying undefined or misspelled utility classes.

## The Problem

The `@apply` directive is powerful, but it's crucial to ensure that the classes you apply are correctly defined in your Tailwind configuration.  Using a class that doesn't exist or has a typo leads to unexpected behavior: no styling changes at all.  This can be difficult to debug because it doesn't produce a clear error message in many cases.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in your browser. You'll see that the div element has no red background, despite the attempt to apply the `bg-red-500` class.

## The Solution

1. Open `bugSolution.html`.
2. Notice that the `bg-red-500` class is now correctly applied (or remove any erroneous classes).

## Key Takeaway

Always double-check that all classes used with `@apply` are correctly spelled and defined within your Tailwind configuration.  Thoroughly review your Tailwind configuration and your CSS to pinpoint the root of the issue. Using your browser's developer tools to inspect elements and check for missing or incorrect classes can also be very helpful.