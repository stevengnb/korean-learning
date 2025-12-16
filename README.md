# Korean Learning Guide

A comprehensive Korean language curriculum from absolute beginner to advanced level, built with MkDocs.

## Overview

This guide covers five proficiency levels aligned with the TOPIK framework:

| Level | TOPIK | Topics |
|-------|-------|--------|
| 1. Beginner | - | Hangul, basic grammar, numbers, essential phrases |
| 2. Elementary | TOPIK I (1-2) | Connectors, verb forms, speech levels |
| 3. Intermediate | TOPIK II (3-4) | Complex grammar, honorifics, reported speech |
| 4. Upper-Intermediate | TOPIK II (4-5) | Nuanced expressions, written/colloquial Korean |
| 5. Advanced | TOPIK II (5-6) | Literary forms, Hanja, specialized Korean |

## Local Development

### Prerequisites

- Python 3.8+
- pip

### Setup

```bash
# Install MkDocs and dependencies
pip install mkdocs mkdocs-material

# Serve locally
mkdocs serve
```

The site will be available at `http://127.0.0.1:8000`.

### Build

```bash
mkdocs build
```

Static files are generated in the `site/` directory.

## Project Structure

```
.
├── docs/
│   ├── 01-beginner/       # Hangul, basic grammar, numbers
│   ├── 02-elementary/     # Connectors, verb forms, particles
│   ├── 03-intermediate/   # Complex grammar, honorifics
│   ├── 04-upper-intermediate/  # Nuanced expressions, idioms
│   ├── 05-advanced/       # Literary forms, Hanja
│   ├── appendix/          # Reference materials
│   └── stylesheets/       # Custom CSS
├── mkdocs.yml             # MkDocs configuration
└── README.md
```

## Features

- Dark/light mode toggle
- Full-text search
- Hangul-only approach (no romanization)
- Practice exercises with reveal-able answers
- Quick reference boxes for spaced repetition

## License

All rights reserved.
