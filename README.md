# [Neuroscience Landscape](http://neuroscience-landscape.com/)

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fopen-neuroscience-foundation%2Fneuroscience-landscape&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/open-neuroscience-foundation/neuroscience-landscape/badge)](https://securityscorecards.dev/viewer/?uri=github.com/open-neuroscience-foundation/neuroscience-landscape)

This is community driven landscape of resources on neuroscience.
The primary goal is to make bird eye view of academic and commercial neuroscience
with dimensions such as companies, research groups, software, hardware, datasets, educational materials, and more.

<img width="1842" alt="neuroscience-landscape" src="https://github.com/open-neuroscience-foundation/neuroscience-landscape/assets/2933061/960f4f11-4ee2-44ea-adf3-c8352687d0b2">

## How to add new entry?

- Add your entry to `data.yaml`
- Add logo in svg to `/logos`
- (optional) if you added `crunchbase`, then manually add entry to `crunchbase.json`
- (optional) build and run locally, confirm that it looks correctly and no errors reported
- (optional) if you added `github_org_url` (`repo_url` does not require this), copy and replace `github_org.json` based on local cache after you build it, you can find your local cache path at log statment during build containing `cache: Cache { cache_dir:`
- Raise a PR

Helpful links:
* convert PNG to SVG ([png2svg.com](https://png2svg.com/#google_vignette))
* edit SVG ([editor.method.ac](https://editor.method.ac))
* create SVG or PNG ([canva](http://canva.com))

## Build

This project utilizes http://github.com/open-neuroscience-foundation/landscape2-academic.

```bash
CRUNCHBASE_CACHE_TTL=0 CRUNCHBASE_API_KEY=test GITHUB_TOKENS=<your token here> landscape2-academic build --data-file data.yml --settings-file settings.yml --guide-file guide.yml --logos-path logos --output-dir build && landscape2-academic serve --landscape-dir build
```

You may also need to copy `crunchbase.json` into `landscape2-academic` cache location. Refer to debug logs.
