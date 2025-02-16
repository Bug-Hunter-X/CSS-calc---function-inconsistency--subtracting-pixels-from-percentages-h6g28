# CSS calc() Function Inconsistency

This repository demonstrates a subtle bug related to the CSS `calc()` function when subtracting pixels from a percentage value. The issue isn't consistently reproducible across all browsers but highlights a potential area for unexpected behavior.

## The Bug

The `bug.css` file contains a simple CSS rule attempting to set the width of a `div` element to 50% of its parent's width, minus 10 pixels.  In certain contexts, the calculation within `calc()` might produce unexpected results, deviating from the expected width.

## The Solution

The `bugSolution.css` file provides a potential workaround, illustrating different ways to achieve the intended layout behavior more reliably. This might involve using alternative approaches to achieve the same visual outcome without relying on the potentially problematic `calc()` calculation.