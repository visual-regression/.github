<p align="center">
  <a href="https://visual-regression.dev">
    <img src="https://raw.githubusercontent.com/visual-regression/visual-regression/main/apps/site/public/brand/mark.svg" alt="visual-regression.dev" width="96" height="96">
  </a>
</p>

<h1 align="center">visual-regression</h1>

<p align="center">Bringing visual regression tools together.</p>

## Mission

Every visual regression tool captures, compares, and reports screenshots in its own format, so a run from one tool can't be read by another. We want the tools to share their results.

We run [visual-regression.dev](https://visual-regression.dev), a vendor-neutral site for learning visual regression testing and comparing the tools. We also maintain a shared run manifest format and two packages built on it:

- [`visual-regression-manifest`](https://github.com/visual-regression/visual-regression/tree/main/packages/visual-regression-manifest) holds the manifest format (JSON Schema, TypeScript types, reader, writer, and merger) and converters from other tools' output.
- [`visual-regression-viewer`](https://github.com/visual-regression/visual-regression/tree/main/packages/visual-regression-viewer) reads the manifests of a run, then serves a review page for it or writes the page to a folder.

## How to help

Everything lives in the [visual-regression repository](https://github.com/visual-regression/visual-regression). [CONTRIBUTING.md](https://github.com/visual-regression/visual-regression/blob/main/CONTRIBUTING.md) explains how to get started.

- Help with development. Fix a bug, improve the docs, or pick up an open [issue](https://github.com/visual-regression/visual-regression/issues).
- Propose integrations. If you maintain a visual regression tool, add a converter from its output to a manifest. If your tool is missing from the comparison, open an issue.
- Propose changes to the manifest standard. If the format can't express something your tool produces, start a [discussion](https://github.com/visual-regression/visual-regression/discussions) or send a pull request.

## Support us financially

The packages and the site are open source. You can fund the work through [FRSOURCE](https://github.com/FRSOURCE):

- [GitHub Sponsors](https://github.com/sponsors/FRSOURCE)
- [Patreon](https://www.patreon.com/frsource)
- [Buy Me a Coffee](https://www.buymeacoffee.com/FRSOURCE)
