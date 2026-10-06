# Petrified Fence website

Marketing site for Petrified Fence (wood-grain concrete fencing). Static site,
deployed to Netlify via continuous deploy from this repository.

## Structure

- `index.html` - the whole site. Single page with hash-based routing
  (`#/`, `#/solutions`, `#/gallery`, `#/about`, `#/faq`, `#/contact`, `#/distributor`).
- `assets/` - images, logo, and other static files.
- `netlify.toml` - tells Netlify to publish the repo root with no build step.

## Deploying

Pushing to `main` triggers a Netlify deploy automatically. There is no build
step; Netlify serves the files as they are in the repo.

## Notes

- The contact and partner forms are front-end only for now. Wiring them to
  HubSpot is pending the client's Portal ID and Form GUIDs.
- Brand accent is green (#5DAC46) on a neutral-gray dark theme.
