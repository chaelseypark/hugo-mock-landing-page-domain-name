# hugo-mock-landing-page

This repository contains an automatically deployed Hugo-based static website using GitHub Actions and GitHub Pages. The workflow ensures that any changes pushed to the main branch trigger a build and deployment process. The deployment process is fully automated and utilizes continuous integration (CI) and continuous deployment (CD) principles to update the website whenever new changes are pushed to the main branch.

Workflow File: .github/workflows/gh-pages-deployment.yaml


I have configured a custom domain for the site using GitHub Pages and Namecheap as the domain registrar (https://chaelseypark.online/). I updated the config.toml file with my domain, modified the GitHub Actions workflow to include the CNAME, and adjusted the repository settings to enable GitHub Pages with HTTPS.

I also updated DNS settings in Namecheap by adding A records pointing to GitHub Pages IPs and a CNAME record linking www to my GitHub username’s GitHub Pages URL. After verifying the deployment, the website is now accessible via my custom domain.
