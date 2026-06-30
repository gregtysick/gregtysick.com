# Deployment Notes

## Public Surface

- Public deployable files live in `site/`.

## Current Hosting Plan

- Current site source is being staged from the Reputation workspace.
- Target hosting provider: Namecheap.
- Public GitHub repo: `https://github.com/gregtysick/gregtysick-website`
- Namecheap document root: `/home/beaufgfv/gregtysick.com`

## Deploy Flow

Use cPanel Git Version Control to deploy `main`. The `.cpanel.yml` file copies everything in `site/` to the production document root.

## Migration Notes

- Keep the WHC backup intact until the transfer is verified.
- Back up the WordPress site before moving DNS or changing hosting.
- Do not publish repository docs to the public web root.
