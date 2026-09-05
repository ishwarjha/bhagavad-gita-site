# Bhagavad Gita GitHub Pages Site

Upload the contents of this directory to the root of the `main` branch in the
public `bhagavad-gita-site` GitHub repository.

In repository Settings > Pages, select:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/(root)`
- Custom domain: `bg.ishwarjha.com`

At the DNS provider, create this record:

- Type: `CNAME`
- Name: `bg`
- Value: `ishwarjha.github.io`

After DNS validation completes, enable Enforce HTTPS. The privacy policy will
be available at `https://bg.ishwarjha.com/privacy/`.
