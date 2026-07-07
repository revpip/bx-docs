# Staging Checklist

Use this checklist before installing or updating Business X-Ray on a live site.

## Before Upload

- Confirm WordPress version.
- Confirm PHP version is 8.0 or higher.
- Take a full file backup.
- Take a full database backup.
- Confirm admin login works.
- Confirm FTP/file manager access works.

## Plugin Checks

- Activate plugin.
- Confirm no fatal errors.
- Confirm database tables are created.
- Open Business X-Ray dashboard.
- Open settings page.
- Save settings.
- Check PHP error log.

## Theme Checks

- Activate theme on staging only.
- Check homepage.
- Check mobile layout.
- Check header and footer.
- Check navigation.
- Check accessibility basics.

## Browser Checks

Test in:

- Chrome
- Safari
- Edge
- Mobile Safari
- Android Chrome where possible

## Go/No-Go

Do not deploy to production if:

- fatal errors appear
- admin is locked
- forms fail
- layouts break badly on mobile
- server logs show repeated warnings
