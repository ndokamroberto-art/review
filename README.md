# MIKE EPICBULYZ

This repository contains a static, single-page website in `index.html`.

## Deploy on Render

The included `render.yaml` configures the repository root as a Render Static Site. In Render, create a new Blueprint and connect this repository; Render will publish `index.html` from the repository root.

The reservation and contact form uses Web3Forms. Before deploying, replace `YOUR_WEB3FORMS_KEY_HERE` in `index.html` with your Web3Forms access key. The site itself can be deployed without this key, but form submissions will not work until it is configured.
