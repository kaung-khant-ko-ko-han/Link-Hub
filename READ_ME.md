# Link-Hub
# Kaung Khant Ko Ko Han — Hugo Website

A personal profile website built with Hugo and deployed through GitHub Actions.

This repository contains the source files used to generate the website. You can edit Markdown content directly on GitHub without installing Hugo on your local device.

## Features

- Hugo static site generation
- Markdown content with YAML Front Matter
- Automated build and deployment using GitHub Actions
- Responsive personal profile and link-in-bio website
- Version-controlled configuration and website source files

## Technology Stack

- [Hugo](https://gohugo.io/) — Static site generator
- [GitHub Actions](https://docs.github.com/en/actions) — Automated build and deployment
- Markdown — Website content format
- HTML, CSS, and JavaScript — Website presentation and behavior

## Getting Started

### 1. Edit Website Content

Open the relevant Markdown file in the `content/` directory.

For example:

```text
content/
└── _index.md
```

Edit the file directly on GitHub and preserve the Front Matter format expected by the site's layouts.

Example:

```yaml
---
title: "Kaung Khant Ko Ko Han"
description: "Control System Engineer"
---
```

The actual fields supported by the website depend on its Hugo templates and configuration.

### 2. Commit Your Changes

Commit the updated Markdown file to the branch configured for deployment.

### 3. Automatic Build and Deployment

GitHub Actions runs the configured Hugo build workflow. If the workflow and GitHub Pages settings are configured correctly, the generated website is deployed automatically.

You do not need to install Hugo locally to edit and publish content.

## Project Structure

```text
.
├── .github/
│   └── workflows/
├── archetypes/
├── content/
├── layouts/
├── static/
├── hugo.toml
├── LICENSE
└── README.md
```

The exact directory structure may vary depending on the version of the project.

## License and Copyright

This repository contains materials that may be subject to different licenses and copyright restrictions.

### 1. Original Source Code

Original source code authored by Kaung Khant Ko Ko Han for this project is licensed under the MIT License, subject to the scope and exclusions stated in the root `LICENSE` file.

You may use, copy, modify, and redistribute the covered code in accordance with the MIT License terms.

When redistributing covered code, retain the applicable copyright notice and license text.

### 2. Personal Content and Branding

Unless a separate license or written permission expressly states otherwise, the following materials are excluded from the MIT License:

- Personal biographies, profile text, and original written content
- Personal photographs and other original images
- Personal logos, brand assets, and visual identity
- Names, trademarks, and branding elements
- Other materials explicitly identified as excluded or separately licensed

All applicable rights in these materials are reserved by their respective rights holders.

The availability of these materials in a public GitHub repository does not, by itself, grant permission to reproduce, redistribute, or use them commercially.

### 3. Third-Party Components and Theme

This project may include or derive from third-party themes, libraries, fonts, icons, images, or other resources.

Those materials are governed by their own applicable licenses and notices. The MIT License in this repository does not replace or override third-party license requirements.

Review the original theme's license and preserve the required copyright notices and license files before redistributing the project.

### 4. Generated Website

The generated website may contain a mixture of MIT-licensed source code, third-party assets, and excluded personal content.

The MIT License for source code does not automatically grant permission to reuse every asset or piece of content appearing in the generated website.

### 5. Permissions and Questions

For permission to reuse excluded personal content, photographs, logos, or branding, contact the relevant rights holder and obtain permission before use.

## Disclaimer

This repository is provided for informational and development purposes. No additional rights are granted beyond those expressly provided by the applicable licenses or the relevant rights holders.

---

© 2026 Kaung Khant Ko Ko Han. Rights reserved for excluded personal content and branding.
