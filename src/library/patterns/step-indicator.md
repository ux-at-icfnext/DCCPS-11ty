---
layout: layouts/right
title: Step Indicator
tags: patterns
summary:

---

## Design 
{% include 'patterns/step-indicator/step-indicator.html' %}

## Theme Settings
- $theme-footer-font-family - Font family of the footer.
- $theme-footer-max-width - Maximum width of footer container.

For this library we've set the `$theme-footer-max-width` to "widescreen", to fit with our [Grid](/library/styles/grid) strategy.

All other aspects to brand the footer will have to be overwritten using CSS.

## Nex+ Library prototyping notes
The library and prototype use the same footer which is set in the `_layouts/default.html` file. At default it's using the regular jekyll partial footer, this can be updated to use the extended header by changing `footer.md` or `footer-small` or `footer-ext.md`.

The navigation for the library is in `_data/lib-nav.yml` and for the prototype in `_data/nav.yml`. Settings for the logo and site name are in the `_data/settings.yml` file.