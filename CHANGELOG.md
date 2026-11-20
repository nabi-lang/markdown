# Changelog

All notable changes to this package. Versions follow semver, independent of the Nabi toolchain.

## 0.1.0 (unreleased)

First release.

- `render` converts Markdown to HTML: the main parts of CommonMark plus
  GitHub tables, strikethrough, callouts, footnotes and heading anchors.
- `render_untrusted` for Markdown of unknown origin.
- `Doc`: the HTML, the title and the headings of a page.
- `Options`: map link and image destinations, highlight fenced code through
  a function of your own (no highlighter dependency).
- Helpers `esc`, `strip_tags` and `slug`.
- Needs Nabi 0.1 or later.
