# CSS Specificity Issue with :hover Pseudo-class

This repository demonstrates a common yet subtle issue in CSS related to specificity and the `:hover` pseudo-class. The problem arises when nested elements have conflicting hover styles, resulting in unexpected behavior.

## Problem

The provided CSS has a container with an inner element. Each has a `:hover` effect defined. However, due to specificity rules, the expected hover effect on the inner element doesn't work as intended.

## Solution

The solution involves understanding CSS specificity and adjusting selectors to achieve the desired effect. By increasing the specificity of the inner element's selector, we can override the parent's hover style, ensuring that the inner element's hover effect is correctly applied.