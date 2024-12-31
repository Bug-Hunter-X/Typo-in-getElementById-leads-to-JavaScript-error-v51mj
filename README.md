# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle but common error in JavaScript when interacting with HTML elements. The bug arises from a simple typo in the `getElementById` function.

## Bug Description
The provided HTML file attempts to change the content of a div element. However, due to a typo (`getElementByIdx` instead of `getElementById`), the JavaScript code fails to locate the element, resulting in an error and no change to the HTML content.

## Solution
The solution file corrects the typo, allowing the JavaScript code to function correctly.