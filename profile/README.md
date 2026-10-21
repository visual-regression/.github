<p align="center">
  <a href="https://visual-regression.dev">
    <img src="https://raw.githubusercontent.com/visual-regression/visual-regression/main/apps/site/public/brand/mark.svg" alt="visual-regression.dev" width="96" height="96">
  </a>
</p>

<h1 align="center">visual-regression</h1>

<p align="center">Bringing visual regression tools together.</p>

## Our mission

Visual regression testing is split across many tools: each one captures, compares and reports screenshots in its own way, and none of them can read another's results. We want to change that.

We maintain [visual-regression.dev](https://visual-regression.dev), a vendor-neutral place to learn visual regression testing and compare the tools, and a shared run manifest format so that the tools can exchange their results:

- [`visual-regression-manifest`](https://github.com/visual-regression/visual-regression/tree/main/packages/visual-regression-manifest): the manifest format (JSON Schema, TypeScript types, reader, writer, merger) and converters from other tools' output.
- [`visual-regression-viewer`](https://github.com/visual-regression/visual-regression/tree/main/packages/visual-regression-viewer): a command that reads the manifests of a run and serves a review page for it, or writes it to a folder.

## How to help

- **Help with development.** Pick an issue, fix a bug or improve the docs in the [visual-regression repository](https://github.com/visual-regression/visual-regression). See [CONTRIBUTING.md](https://github.com/visual-regression/visual-regression/blob/main/CONTRIBUTING.md) to get started.
- **Propose integrations.** Maintain a visual regression tool, or use one that is missing? Add a converter from its output to a manifest, or open an issue and tell us what you need.
- **Shape the manifest standard.** The manifest format is only useful if it fits every tool. Propose changes, point out what your tool cannot express, or open a discussion about where the format should go.

## Support us financially

Our work is open source and maintained in our free time. If it saves you time, you can support it through [FRSOURCE](https://github.com/FRSOURCE):

- [GitHub Sponsors](https://github.com/sponsors/FRSOURCE)
- [Patreon](https://www.patreon.com/frsource)
- [Buy Me a Coffee](https://www.buymeacoffee.com/FRSOURCE)
