# Shortcode Reference

This document records planned and existing Business X-Ray shortcodes.

## Current Production Status

The GitHub production repositories are being rebuilt from foundation level. Some shortcodes existed in earlier prototype ZIPs but are not yet implemented in the production `bx-platform` repo.

## Planned Core Shortcodes

### `[business_xray_landing_page]`

Displays the primary Business X-Ray landing journey.

### `[business_xray_assessment]`

Displays the free assessment form.

### `[business_xray_website_scan]`

Displays the 60 Second X-Ray website scan form.

### `[business_xray_pricing]`

Displays pricing or founding pilot offer.

### `[business_xray_report_preview]`

Displays a public report preview block.

### `[business_xray_portal]`

Displays the client portal entry point.

## Shortcode Standards

Every shortcode should:

- escape output
- sanitise input
- use nonces for submissions
- degrade gracefully if required data is missing
- avoid hard-coded URLs where settings exist
- use shared templates where possible
