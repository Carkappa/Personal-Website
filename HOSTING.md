# Hosting This Website (GitHub Pages)

This project is ready to deploy with GitHub Pages using GitHub Actions.

## 1) Push this folder to a GitHub repository

- Create a new repository on GitHub.
- Push your files to the `main` branch.

## 2) Enable GitHub Pages

- Open your repository on GitHub.
- Go to **Settings** > **Pages**.
- Under **Build and deployment**, set **Source** to **GitHub Actions**.

## 3) Deploy automatically

- Every push to `main` triggers the workflow in `.github/workflows/deploy-pages.yml`.
- GitHub will publish your site and show the live URL in:
  - **Actions** tab (latest successful run)
  - **Settings** > **Pages**

## Notes

- Your PDF and HTML files are deployed as-is.
- If your default branch is not `main`, update the workflow branch value.
- If you use a custom domain later, add it in **Settings** > **Pages**.
