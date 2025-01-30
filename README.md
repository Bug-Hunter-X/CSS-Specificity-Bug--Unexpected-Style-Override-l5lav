# CSS Specificity Bug: Unexpected Style Override

This repository demonstrates a subtle bug related to CSS selector specificity. The bug arises from the interaction of different selectors (class, ID, element) and their order of appearance in a stylesheet.  Understanding CSS specificity is crucial for avoiding such unexpected behavior.

## Bug Description

The bug involves an unexpected style override due to the high specificity of a selector.  While the expectation is that one selector should take precedence, a more specific selector overrides it unexpectedly.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` to see the problematic code.
3. Open `bugSolution.css` to see the solution. 
4. Inspect the behavior in a browser's developer tools to observe how the styles are applied.

## Solution

The solution lies in understanding and correctly using CSS selector specificity. The solution demonstrates a way to correctly manage specificity to avoid such errors.
