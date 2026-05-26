---
layout: post
title: "HTML Defaults and Browser Inconsistencies"
description: "Browser defaults are helpful, but small differences can create visual and usability issues when a project grows."
author: Brandon Himpfen
---

HTML is designed to be readable even without a custom stylesheet. That is one of the strengths of the web. But browser defaults were never meant to be a complete design foundation for modern projects.

Small differences in spacing, form controls, typography, and rendering can become noticeable as a site grows. A project may look polished in one browser and slightly uneven in another.

## The hidden cost of untreated defaults

Untreated defaults usually do not fail dramatically. They create small differences that accumulate. A button may inherit unexpected styles. A table may need more consistent spacing. A heading scale may feel uneven beside custom components.

These issues are easy to miss at the start of a project and harder to correct once many pages depend on them.

## Standardization as maintenance

A base stylesheet is a maintenance tool. It establishes common assumptions so that later CSS can focus on layout, branding, and interaction instead of repeatedly correcting the same defaults.

That makes the project easier to reason about, especially when more than one person edits the front end.
