# Hassi Berkane RH

This project is configured for deployment to GitHub Pages.

## Deployment Instructions

1.  **Push to GitHub**: Ensure your code is pushed to a GitHub repository.
2.  **Install Dependencies**: Run `npm install`.
3.  **Deploy**: Run `npm run deploy`.
    This command will build the project and push the `dist` folder to the `gh-pages` branch.
4.  **Configure GitHub Pages**:
    -   Go to your repository settings on GitHub.
    -   Navigate to "Pages".
    -   Select the `gh-pages` branch as the source.
    -   Save.

Your site will be available at `https://<username>.github.io/<repo-name>/`.

## Configuration

-   **Base Path**: The `vite.config.ts` file has been updated with `base: './'` to support relative paths.
-   **Homepage**: Update the `homepage` field in `package.json` with your actual GitHub Pages URL.
