# Developer Getting Started

## Local Setup

Recommended tools:

- PHP 8.0+
- WordPress 6.4+
- LocalWP, DDEV, Docker or similar
- Git
- VS Code or PhpStorm

## Repositories

Clone:

```bash
git clone https://github.com/revpip/bx-platform.git
git clone https://github.com/revpip/bx-theme.git
git clone https://github.com/revpip/Business-X-Ray-Bible.git
git clone https://github.com/revpip/bx-design-system.git
git clone https://github.com/revpip/bx-ai.git
git clone https://github.com/revpip/bx-docs.git
```

## WordPress Paths

Symlink or copy:

```text
bx-platform → wp-content/plugins/business-xray-platform
bx-theme → wp-content/themes/business-xray-framework
```

## Development Rules

- Read the Bible before building.
- Check the design system before styling.
- Document new shortcodes in `bx-docs`.
- Keep AI prompts in `bx-ai`.
- Keep product rules in `Business-X-Ray-Bible`.

## First Engineering Priority

The immediate priority after foundation is the production assessment submission flow.
