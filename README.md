# Radius

[![Radius Website](https://github.com/radius-project/website/actions/workflows/publish.yaml/badge.svg)](https://github.com/radius-project/website/actions/workflows/publish.yaml)
[![License](https://img.shields.io/github/license/radius-project/website)](https://github.com/radius-project/website/blob/main/LICENSE)

This repository contains the source code for the Radius website, available at <https://radapp.io>.

## Contributing

1. Install dependencies
   - [Node.js](https://nodejs.org/) (see [`.node-version`](./.node-version) for the expected version)

1. Clone the repository

   ```bash
   git clone https://github.com/radius-project/website.git
   cd website
   ```

1. Install npm packages (this also installs the pinned Hugo extended binary)

   ```bash
   npm ci
   ```

1. Run the development server

   ```bash
   npm run start
   ```

   To include draft and future-dated content, use `npm run start:drafts` instead.
1. Open a browser to <http://localhost:1313>

The Hugo project lives at the repository root, with configuration under
[`config/_default/`](./config/_default/). Run `npm run build` from the root to
generate the static site in `public/`. Do not commit generated output.

## Publishing

The [Radius Website workflow](./.github/workflows/publish.yaml) builds once and
deploys the `public/` artifact to GitHub Pages on pushes to `main` or manual runs
from `main`. The Pages publishing source is **GitHub Actions**, not a branch.
With no custom domain configured, deployments are served at
<https://radius-project.github.io/website/> without changing `radapp.io`.
After [configuring the custom domain and DNS](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site),
rerun the workflow from `main` so Hugo builds with the new base URL.

Pull requests build downloadable `preview-*` artifacts, including drafts and
future-dated content, without deploying them. Extract the artifact and run this
command from the extracted directory, then open <http://localhost:8000/>.

```bash
python -m http.server 8000 --bind 127.0.0.1
```

## Code of Conduct

Please refer to our [Radius Community Code of Conduct](https://github.com/radius-project/community/blob/main/CODE-OF-CONDUCT.md)
