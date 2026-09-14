# Tata 1mg Labs — Redesign concept

A cleaner, search-first redesign of [1mg.com/labs](https://www.1mg.com/labs), built as static HTML with the original copy and images.

## Pages

| Page | Description |
| --- | --- |
| `redesign/index.html` | Clean redesign (light theme, 64px gutters, FAQ-style about section, full 1mg footer) |
| `redesign/showcase.html` | Award-style showcase variant with choreographed motion |
| `UX Audit/1mg-lab-tests-ux-audit.html` | UX audit of the original page |

## Editing

`redesign/template.html` and `redesign/showcase-template.html` are the editable sources. They use `{{img:name}}` placeholders that map to files in `redesign/images/`. The built pages embed those images as data URIs, so each page is a single self-contained file.

Prices and search results in the pages are illustrative sample data, not live 1mg prices.
