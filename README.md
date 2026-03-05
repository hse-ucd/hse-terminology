# HSE Terminology

A controlled vocabulary for the Health Service Executive public health terminology including code schemes for data catalogues and health indicators.

## Overview

This repository contains the HSE Terminology specification, providing standardized terms and classifications for health data management, supporting interoperability and consistent data cataloguing across the Irish health system.

## Files

- **HSE Terminology.html** - Main A-Z terminology listing with metadata and professional documentation
- **visualize.htm** - Interactive hierarchical tree visualization using D3.js
- **HSE Terminology_files/** - JavaScript and CSS dependencies for the main page
- **visualize_files/** - JavaScript and CSS dependencies for the visualization

## Features

- **A-Z Listing**: Complete alphabetical listing of all terminology concepts
- **Hierarchical Tree View**: Interactive D3.js visualization showing parent-child relationships
- **Metadata**: Full documentation including namespaces, contributors, and licensing
- **Abbreviations**: Clear explanation of SKOS relationships (DEF, BT, NT, TT)

## Viewing the Terminology

### Online (GitHub Pages)

Visit the live deployment: **https://hse-ucd.github.io/hse-terminology/**

The site is automatically deployed via GitHub Actions whenever changes are pushed to the main branch.

### Local Viewing

Open `index.html` or `HSE Terminology.html` in a web browser to view:
- Abstract and introduction
- Full metadata section
- A-Z terminology listing
- Navigation to tree visualization

Click the "Tree View" button or open `visualize.htm` directly to see the interactive hierarchical tree.

## Deployment

The site is automatically deployed to GitHub Pages using GitHub Actions. The workflow is defined in `.github/workflows/deploy.yml` and triggers on every push to the main branch.

## Version Information

- **Version**: 1.0.0
- **Date Released**: March 2026
- **Preferred Namespace Prefix**: phpt
- **Preferred Namespace URI**: https://hse.ie/terminology/phpt#
- **License**: Creative Commons Attribution 4.0 International (CC BY 4.0)

## Contributors

- Health Service Executive
- ADAPT Centre
- University College Dublin

## Source

Generated using [SKOS Play](https://skos-play.sparna.fr/)

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
