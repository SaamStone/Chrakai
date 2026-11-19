# Aveline Floss Replica

A local copy of the Aveline Floss template replica. Its images and Geist font files are bundled, so the site does not need the Framer or Google Fonts servers to render.

## Run locally

1. Install [Node.js](https://nodejs.org/) if it is not already installed.
2. From this folder, run:

   ```powershell
   npm run dev
   ```

3. Open [http://localhost:4173](http://localhost:4173).

The server uses Node's built-in HTTP module; there are no packages to install. To use another port, set `PORT` before starting it.

## Update bundled assets

The original remote image references and selected image variants are recorded in `outputs/assets/asset-manifest.json`. Run `npm run assets` to restore any missing bundled images or Geist font files.
