# namida-site

Landing page for [namida](https://github.com/namidaco/namida), served at **https://namida.app**.

Plain static HTML, no build step. Edit `index.html` and push to `main` — the
[deploy workflow](.github/workflows/deploy.yml) publishes the repository to GitHub Pages as-is.

The documentation lives in a separate repository,
[namida-docs](https://github.com/namidaco/namida-docs), served at **https://docs.namida.app**.

## Preview locally

```bash
npx serve .
```

## Custom domain

`CNAME` pins the apex domain. The matching DNS records and the Pages setting are described in the
repository settings under Settings → Pages.
