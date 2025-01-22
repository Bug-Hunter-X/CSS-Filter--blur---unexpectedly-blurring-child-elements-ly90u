# CSS filter: blur() issue

This repository demonstrates a bug encountered when using the CSS `filter: blur()` property.  The issue arises when applying the blur to a parent element; the blur effect unintentionally extends to its child elements. This can lead to undesirable visual results and layout problems. The `blurBug.css` file showcases the problem, while `blurFix.css` provides a solution.

## Problem

The `blurBug.css` file shows how the blur applied to the parent element affects the child elements, obscuring their styling and layout.

## Solution

The `blurFix.css` file solves this issue by employing techniques that isolate the blur to only the parent element, leaving the child elements unaffected.