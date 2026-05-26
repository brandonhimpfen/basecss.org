---
layout: post
title: "Where base.css Fits in a Modern Front-End Stack"
description: "base.css works as a small foundation layer beneath frameworks, custom themes, utility classes, and project-specific components."
author: Brandon Himpfen
---

Modern front-end stacks can include frameworks, utility systems, component libraries, build tools, and design tokens. In that context, a small base stylesheet may seem simple, but that simplicity is the point.

base.css belongs near the beginning of the styling stack. It provides a foundation for HTML elements before more specific design decisions are applied.

## Not a framework

A framework gives you patterns for layout and components. A base stylesheet gives you a cleaner starting point for native elements. These are different jobs.

Using a base stylesheet does not prevent a project from using Bootstrap, Tailwind, custom Sass, design tokens, or hand-written CSS. It simply helps normalize the baseline that those systems build on.

## Useful for documentation and small sites

Base styles are especially useful for documentation, project sites, open source pages, and static websites where plain HTML content appears often. Posts, tables, lists, code samples, forms, and headings all benefit from a consistent baseline.

For small projects, that can be enough. For larger projects, it becomes the first layer in a broader design system.
