# Neuroscience Landscape

This is community driven landscape of resources on neuroscience.
The primary goal is to make bird eye view of academic and commercial neuroscience
with dimensions such as companies, research groups, software, hardware, datasets, educational materials, and more.

## How to add new entry?

Add your entry to `data.yaml`. Build and run locally, confirm that it looks correctly and no errors reported.

Helpful links:
* convert PNG to SVG ([png2svg.com](https://png2svg.com/#google_vignette))
* edit SVG ([editor.method.ac](https://editor.method.ac))

## Build

This project utilizes https://github.com/cncf/landscape2.

```bash
landscape2 build --data-file data.yml --settings-file settings.yml --guide-file guide.yml --logos-path logos --output-dir build
```

```bash
landscape2 serve --landscape-dir build
```

## Work in Progress

Laboratories
- [ ] citations metric
- [ ] number of papers metric
- [ ] head description
- [ ] hindex of head

Main
- [ ] manual location
- [ ] search by everything
- [ ] filter by tags
- [ ] filter by location
- [ ] image in summary
- [ ] feature by hindex
- [ ] feature manually
- [ ] BibTeX citation in footer
- [ ] git organization url instead of repository url

Books
- [ ] dedicated Amazon URL icon

## Notes

- `2024-02-29`, not using crunchbase, since it requires expensive Enterprise level subscription

### Labs

🇺🇸 CU: [Kandel Lab](https://www.biochem.cuimc.columbia.edu/research-labs/kandel-lab)  
🇯🇵 OIST: [Neural Coding and Brain Computing](https://groups.oist.jp/ncbc) [:octocat:](https://github.com/oist-ncbc)  
🇸🇬 Duke-NUS: [Neuroscience and Behavioural Disorders](https://www.duke-nus.edu.sg/nbd)  
🇰🇷 KAIST: [Cognitive Neuroscience and Neuroimaging](http://ibrain.kaist.ac.kr/) | [Brain Dynamics](http://raphe.kaist.ac.kr/index.htm) | [Behavioral Genetics](https://sites.google.com/site/bglabkorea/) | [Synaptic Brain Dysfunction](http://molneuro.kaist.ac.kr/contents/) | [Neural Interoception](https://www.suhlab-neuralinteroception.kaist.ac.kr/) | [Sensory processing](https://sites.google.com/site/leelab2013/) | [Systems neuroscience](https://sites.google.com/site/systemsneurolaboratory/)  
