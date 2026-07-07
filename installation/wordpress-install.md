# WordPress Installation Guide

## Repositories Required

For a standard WordPress installation you need:

1. `bx-platform` — plugin
2. `bx-theme` — theme

## Install Plugin

1. Download or package the `bx-platform` repository as a plugin folder.
2. Upload to:

```text
wp-content/plugins/business-xray-platform/
```

3. In WordPress Admin, go to **Plugins**.
4. Activate **Business X-Ray Platform**.
5. Confirm the **Business X-Ray** admin menu appears.

## Install Theme

1. Download or package the `bx-theme` repository as a theme folder.
2. Upload to:

```text
wp-content/themes/business-xray-framework/
```

3. In WordPress Admin, go to **Appearance → Themes**.
4. Activate **Business X-Ray Framework** if the site should use the Business X-Ray design.

## First Checks

After activation:

- Visit **Business X-Ray → Dashboard**.
- Visit **Business X-Ray → Settings**.
- Save settings once.
- Confirm no PHP fatal errors in server logs.
- Confirm the front page renders if the theme is active.

## Safety

Always test on staging before production.
