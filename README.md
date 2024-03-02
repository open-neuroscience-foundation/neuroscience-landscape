# [Neuroscience Landscape](http://neuroscience-landscape.com/)

This is community driven landscape of resources on neuroscience.
The primary goal is to make bird eye view of academic and commercial neuroscience
with dimensions such as companies, research groups, software, hardware, datasets, educational materials, and more.

<img width="1842" alt="neuroscience-landscape" src="https://github.com/open-neuroscience-foundation/neuroscience-landscape/assets/2933061/960f4f11-4ee2-44ea-adf3-c8352687d0b2">

## How to add new entry?

Add your entry to `data.yaml`. Build and run locally, confirm that it looks correctly and no errors reported. Then raise a PR.

Helpful links:
* convert PNG to SVG ([png2svg.com](https://png2svg.com/#google_vignette))
* edit SVG ([editor.method.ac](https://editor.method.ac))

## Build

This project utilizes http://github.com/open-neuroscience-foundation/landscape2-academic.

```bash
GITHUB_TOKENS=... landscape2-academic build --data-file data.yml --settings-file settings.yml --guide-file guide.yml --logos-path logos --output-dir build && landscape2-academic serve --landscape-dir build
```
