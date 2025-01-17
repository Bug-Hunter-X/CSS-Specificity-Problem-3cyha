# CSS Specificity Bug

This repository demonstrates a common CSS bug related to specificity. The goal is to style a paragraph element within a div, but due to specificity issues, the expected styling isn't applied.

## Bug Description

The paragraph element within the div doesn't inherit the expected text color because of CSS specificity rules.

## Solution

The solution involves adjusting the specificity of the paragraph selector to override the div's specificity. This is usually achieved by adding more specific selectors (i.e. using a class or ID).