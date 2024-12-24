# Tailwind CSS Directive Application Issue with CSS Preprocessors

This repository demonstrates an uncommon bug encountered when using Tailwind CSS with a CSS preprocessor like Sass or Less. The problem is that Tailwind directives, despite being correctly written, fail to be applied.

## Bug Description

The issue arises when Tailwind directives are not correctly processed by the CSS preprocessor before being applied to the project's CSS.  This can happen due to various reasons, including:

* **Incorrect configuration**: Misconfigured Tailwind setup in the preprocessor's context.
* **Unexpected behavior**: Unusual interaction between the preprocessor and Tailwind's build process.
* **Missing dependencies**: The necessary packages or modules might be missing. 

## Bug Reproduction

The `bug.js` file contains sample code that demonstrates the problem.  The  `bugSolution.js` provides the corrected implementation.

## Solution

The solution typically involves verifying and fixing the Tailwind CSS configuration within your preprocessor's workflow.