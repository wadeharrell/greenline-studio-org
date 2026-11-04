# greenline-studio-org

Source for **https://greenline-studio.org**, the Greenline Studio docs site, served by GitHub Pages from `main` (root).

Right now it is a one-page placeholder. Later, a GitHub Action will pull the core and plugin markdown, build the docs and deploy them here.

- `CNAME`: the custom domain (greenline-studio.org). greenlinestudio.org forwards to it from Squarespace.
- `.nojekyll`: serve the files as they are, without a Jekyll build.
- Icons and the social image come from the Greenline Studio brand kit.
- `fonts/`: Manrope (500, 800) and IBM Plex Mono (500), Latin subset, served from this site so pages make no request to any other server. Both are under the SIL Open Font License 1.1; the licences are beside them.
