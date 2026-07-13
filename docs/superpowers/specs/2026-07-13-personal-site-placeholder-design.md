# Personal Site Placeholder — Design Spec

**Date:** 2026-07-13  
**Status:** Approved

## Overview

A single-page placeholder site for danieldavey.co.uk. The page displays the domain name in full caps at the top with nothing else — a clean, intentional holding page.

## Visual Style

- **Background:** white (`#fff`)
- **Font:** `'Helvetica Neue', Helvetica, Arial, sans-serif`
- **Name:** `DANIELDAVEY.CO.UK` — bold, 12px, letter-spacing 5px, color `#111`
- **Rule:** 1px solid `#111` border-bottom beneath the name
- **Padding:** 40px top, 48px left — positioned top-left
- **Body:** otherwise completely empty white space

## Architecture

- **One file:** `index.html` at the repo root
- No external CSS file, no JavaScript, no frameworks
- All styles inline in a `<style>` block in `<head>`

## Deliverable

`index.html` — valid HTML5, renders correctly in all modern browsers, no external dependencies.
