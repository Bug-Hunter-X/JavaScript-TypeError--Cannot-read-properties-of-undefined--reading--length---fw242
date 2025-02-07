# JavaScript TypeError Bug

This repository demonstrates a common JavaScript error: a TypeError caused by attempting to access the 'length' property of an undefined variable.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a corrected version.

## Bug Description

The function `foo` attempts to access the `length` property of the input `a`. If `a` is `undefined` (not just `null`), this will throw a `TypeError`. The original code only checks for `null`.

## Solution

The solution explicitly checks for both `null` and `undefined` before accessing the `length` property.