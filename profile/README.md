<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/zephyrus-framework/.github/main/profile/assets/zephyrus-logo-dark.png">
    <img src="https://raw.githubusercontent.com/zephyrus-framework/.github/main/profile/assets/zephyrus-logo-light.png" alt="Zephyrus" width="325" height="55">
  </picture>
</p>

<p align="center">
  A cohesive PHP 8.4+ framework, MIT licensed.<br>
  Attribute routing, immutable HTTP, typed configuration and security middleware out of the box.<br>
  And Leaf, the static site generator built on it: Markdown to a finished site.
</p>

<p align="center"><strong>
  <a href="https://zephyrus.ophelios.com">Documentation</a> &nbsp;·&nbsp; <a href="https://leaf.ophelios.com">Leaf</a> &nbsp;·&nbsp; <a href="https://packagist.org/packages/zephyrus-framework/">Packagist</a>
</strong></p>

## Get started

Create an application from the starter template:

```bash
composer create-project zephyrus-framework/project my-app
```

Or add the framework to an existing project:

```bash
composer require zephyrus-framework/core
```

## The framework

- **[core](https://github.com/zephyrus-framework/core)**: the framework itself, with routing, HTTP, configuration, security, sessions, views and data access.
- **[project](https://github.com/zephyrus-framework/project)**: the starter application template, for `composer create-project`.
- **[php](https://github.com/zephyrus-framework/php)**: the base Docker image, PHP 8.4 and 8.6 on Apache, with slim production and dev tags.

## Leaf

- **[leaf](https://github.com/zephyrus-framework/leaf)**: the project template, to write in Markdown, preview with live reload and build to static HTML.
- **[leaf-core](https://github.com/zephyrus-framework/leaf-core)**: the library behind Leaf, with the build pipeline, Markdown content, SEO and multi-locale output.
- **[leaf-cli](https://github.com/zephyrus-framework/leaf-cli)**: Leaf as a single binary, with no Composer project to set up.
- **[leaf-site](https://github.com/zephyrus-framework/leaf-site)**: the source of [leaf.ophelios.com](https://leaf.ophelios.com), the Leaf documentation, built with Leaf.

## The website

- **[site](https://github.com/zephyrus-framework/site)**: the source of [zephyrus.ophelios.com](https://zephyrus.ophelios.com), the showcase and documentation, built with Leaf.
