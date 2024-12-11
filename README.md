# CSS filter: blur() Cross-Browser Incompatibility

This repository demonstrates a common issue with the CSS `filter: blur()` property and provides a solution for ensuring consistent rendering across various browsers, particularly older versions of Internet Explorer.

The `blur-bug.css` file showcases the inconsistent behavior of the blur filter across different browser versions.  The `blur-solution.css` file offers a solution using alternative techniques to achieve a similar effect across all browsers.

## Problem

The `filter: blur()` property is not consistently supported across older browsers.  This can result in blurry effects appearing differently or not at all in older browsers. This can break the design and user experience of a website.

## Solution

The solution involves using a combination of box-shadow for a drop shadow effect, and potentially JavaScript to implement a sophisticated blur effect if needed.  This ensures cross-browser compatibility and maintain a consistent visual presentation across different browsers.