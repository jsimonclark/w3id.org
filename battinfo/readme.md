# BattINFO Ontology PURLs

This repository contains the .htaccess file to set up Persistent Uniform Resource Locators (PURLs) for the Battery Interface Ontology (BattINFO), developed through the Horizon 2020 research project **BIG-MAP** (BATTERY INTERFACE GENOME - MATERIALS ACCELERATION PLATFORM).

## Project Information

- Project Title: Battery Interface Ontology (BattINFO)
- Grant Agreement No.: 957189
- Websites: [BattINFO documentation](https://big-map.github.io/battinfo/index.html), [BIG-MAP Project](https://www.big-map.eu/)

## Purpose

The .htaccess file provided in this repository is intended to be used with the w3id.org Persistent URL (PURL) service. It redirects general requests to the index of the documentation and specific IRIs to corresponding pages on the project website.

## Redirect Rules

The .htaccess file implements the following redirect rules:

1. Redirects the base <https://w3id.org/battinfo> to the **index** page <https://big-map.github.io/battinfo/index.html>.
2. Redirects URIs for specific resources at <https://w3id.org/battinfo#{ID}> to their respective pages on the project resource documentation <https://big-map.github.io/battinfo/battinfo.html#{ID}>.

For detailed information about each redirect rule, please refer to the comments within the .htaccess file.

---

For any questions or issues, please contact [BattINFO Project Team](mailto:simon.clark@sintef.no).

BattINFO W3ID Maintainer: [@jsimonclark](https://github.com/jsimonclark)
