# Shuchao Gao — Academic Homepage

Source for [scophield.github.io](https://scophield.github.io/), built with Jekyll using the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) template.

## Editing

- Main content and publications: `_pages/about.md`
- Profile and site settings: `_config.yml`
- Navigation: `_data/navigation.yml`

Keep publication years tied to their original venue; a later arXiv upload does not create a new publication. Only list verified public work and link to available papers or code.

## Local preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Open http://127.0.0.1:4000. GitHub Pages publishes the configured source after approved changes are pushed to the publishing branch; verify the repository Pages settings before deployment.

## Attribution

The site retains the AcadHomepage layout and assets. See [LICENSE](LICENSE) and the [upstream documentation](https://github.com/RayeRen/acad-homepage.github.io) for template credits and setup details.
