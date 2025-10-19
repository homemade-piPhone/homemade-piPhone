# Website for homemade piPhone project

## How does the project website work?

Website is deployed using [GitHub Pages](https://docs.github.com/en/pages) with [Jekyll](https://jekyllrb.com/).

Code from the `main` branch, folder `docs` is compiled and served on https://homemade-piphone.github.io.

GitHub Pages settings can be updated [here](https://github.com/homemade-piPhone/homemade-piPhone/settings/pages).

Pages builds and deployments can be monitored in the [Actions tab](https://github.com/homemade-piPhone/homemade-piPhone/actions).

For more details on this Continuous Integration / Continuous Deployment (CI/CD), see [GitHub Actions docs](https://docs.github.com/en/actions)

## How do I update the project website?

To update the project website, modify the files in the `docs` folder.

We suggest using [GitHub codespace](https://github.com/homemade-piPhone/homemade-piPhone/codespaces) to edit the files.

### Adding new pages

The website now supports Markdown files thanks to Jekyll integration:

1. Create a new `.md` file in the `docs` folder
2. Add front matter at the top of the file:
   ```yaml
   ---
   layout: default
   title: Your Page Title
   ---
   ```
3. Write your content in Markdown format
4. The page will be automatically converted to HTML and published at `https://homemade-piphone.github.io/your-filename.html`

### File structure

- `index.html` - Homepage with logo and links
- `research.md` - Example markdown page with research documentation
- `_config.yml` - Jekyll configuration
- `_layouts/default.html` - Default layout template for markdown pages
- `images/` - Image assets
