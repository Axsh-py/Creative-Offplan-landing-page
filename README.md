# Rabdan Avenue — Off-plan landing page

Client demo landing page for **Rabdan Avenue** (Rabdan Developments, Meydan · MBR City, Dubai), presented by **Savoir Privé Properties**.

A single static page, no build step:

- `index.html`: page, styles and scripts
- `frames-v2/`: scroll-driven building film (240 frames, desktop `hd` and mobile `sd`)
- `tour48/`: first-person apartment walkthrough (48 fps frames, desktop `hd` and mobile `sd`)

## Run locally

```
npx http-server . -p 5600
```

## Before going live

- The register form isn't connected. Set `FORM_ENDPOINT` in `index.html` to a form service or CRM endpoint.
- All images are artist's impressions.
