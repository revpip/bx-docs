# Shortcode Reference

This document records planned and existing Business X-Ray shortcodes.

## Implemented Production Shortcodes

These are implemented in the production `bx-platform` repository.

### `[business_xray_landing_page]`

Displays the primary Business X-Ray landing journey with headline, explanation, action buttons and three proof cards.

### `[business_xray_assessment]`

Displays the working free assessment form.

Current behaviour:

- validates a nonce
- collects business/contact details
- asks scored diagnostic questions
- calculates an overall score
- assigns a score band
- saves or updates an organisation
- saves an assessment record
- creates a follow-up task
- logs activity
- emails the configured lead address
- displays an immediate result to the user

### `[business_xray_pricing]`

Displays the founding pilot / pricing structure block.

## Planned Core Shortcodes

### `[business_xray_website_scan]`

Displays the 60 Second X-Ray website scan form.

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
