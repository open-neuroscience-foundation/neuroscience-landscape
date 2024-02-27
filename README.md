# Neuroscience Landscape

This is community-driven landscape of resources on neuroscience.
The primary goal is to make bird-eye view of academic and commercial neuroscience
with dimensions of educational materials, research groups, software, hardware, and more.

## How to add new entry

1. get logo in SVG
   1. (optional) convert PNG to SVG ([png2svg.com](https://png2svg.com/#google_vignette))
   2. (optional) edit SVG ([editor.method.ac](https://editor.method.ac))
2. add your entry to `data.yaml`
3. add links
   1. `repo_url` has to be repository, not organization
4. submit Pull Request

## Appendix: Build

This project utilizes https://github.com/cncf/landscape2.

build
```bash
landscape2 build \                    
  --data-file data.yml \
  --settings-file settings.yml \
  --guide-file guide.yml \
  --logos-path logos \
  --output-dir build
```

serve
```bash
landscape2 serve --landscape-dir build
```

## Appendix: Work in Progress

Laboratories
- [ ] citations plugin
- [ ] leader tab (similar to organization)
- [ ] funding
- [ ] industry affiliations

Main
- [ ] images
- [ ] PNG
- [ ] feature item by custom enums (to allow more academic books)

Books
- [ ] dedicated Amazon URL icon

### Labs
🇨🇭 EPFL: [BlueBrain](https://www.epfl.ch/research/domains/bluebrain/) [:octocat:](https://github.com/BlueBrain)  
🇺🇸 Utah: [Normann Lab](https://neuroscience.med.utah.edu/faculty/normann.php)[BCI Utah Array creator]  
🇺🇸 [Braingate](https://www.braingate.org): Brown, MGH, Stanford, USA gov, USA hospitals  
🇩🇪 Ernst Strüngmann Institute for Neuroscience: [Singer Lab](https://www.esi-frankfurt.de/research/singer-lab/)  
🇩🇪 TUM: [Portugues Lab](http://www.portugueslab.com) [:octocat:](https://github.com/portugueslab)  
🇺🇸 University of Pennsylvania: [Kording Lab](www.kordinglab.com) [:octocat:](https://github.com/KordingLab) | [Penn Image Computing & Science](www.picsl.upenn.edu) [:keyboard:](http://picsl.upenn.edu/software/)  
🇺🇸 MIT, Princeton: [Seung Lab](https://seunglab.org/) [:keyboard:](https://seunglab.org/software/) [:octocat:](https://github.com/seung-lab)  
🇺🇸 MIT: [brain + cognitive sciences department](https://bcs.mit.edu/)  
🇺🇸 Stanford: [Cognitive & Systems Neuroscience](https://med.stanford.edu/scsnl/about1.html) [:octocat:](https://github.com/scsnl) | [Brain Dynamics](https://web.stanford.edu/group/bdl/) [:octocat:](https://github.com/braindynamicslab) | [Lee Lab](https://llab.stanford.edu/index.html)  
🇺🇸 Carnegie Mellon: [Cognitive Neuroscience](https://www.cmu.edu/ni/research/cognitive-neuroscience.html) | [Computational Neuroscience](https://www.cmu.edu/ni/research/computational-neuroscience.html) | [Neuro Tech & Engineering](https://www.cmu.edu/ni/research/neuro-tech-and-engineering.html) | [Systems Neuroscience](https://www.cmu.edu/ni/research/systems-neuroscience.html)  
🇺🇸 Berkeley: [Compuatation and Language](http://colala.berkeley.edu/) [:octocat:](https://github.com/piantado) | [Perceptual Reality](http://www.emilyacooper.org/index.html) [:octocat:](https://github.com/eacooper) | [Gallant Lab](https://www.gallantlab.org) [:octocat:](https://github.com/gallantlab) | [Theunissen Lab](http://theunissen.berkeley.edu) [:octocat:](https://github.com/theunissenlab) | [Bouchard Lab](https://bouchardlab.lbl.gov/) [:octocat:](https://github.com/BouchardLab)  
🇺🇸 CU: [Kandel Lab](https://www.biochem.cuimc.columbia.edu/research-labs/kandel-lab)  
🇯🇵 OIST: [Neural Coding and Brain Computing](https://groups.oist.jp/ncbc) [:octocat:](https://github.com/oist-ncbc)  
🇸🇬 Duke-NUS: [Neuroscience and Behavioural Disorders](https://www.duke-nus.edu.sg/nbd)  
🇰🇷 KAIST: [Cognitive Neuroscience and Neuroimaging](http://ibrain.kaist.ac.kr/) | [Brain Dynamics](http://raphe.kaist.ac.kr/index.htm) | [Behavioral Genetics](https://sites.google.com/site/bglabkorea/) | [Synaptic Brain Dysfunction](http://molneuro.kaist.ac.kr/contents/) | [Neural Interoception](https://www.suhlab-neuralinteroception.kaist.ac.kr/) | [Sensory processing](https://sites.google.com/site/leelab2013/) | [Systems neuroscience](https://sites.google.com/site/systemsneurolaboratory/)  

### Organizations
🌏 [INCF](http://www.incf.org) International Neuroinformatics Coordinating Facility [:octocat:](https://github.com/INCF)  
🌎 [NITRC](https://www.nitrc.org) Neuroimaging Informatics Tools and Resources Clearinghouse  
🇺🇸 [BRAIN Initiative](https://www.braininitiative.org/) [:keyboard:](https://www.braininitiative.org/toolmakers-resources/)  
🇺🇸 [IEEE Brain](https://brain.ieee.org/)  
🇺🇸 [Allen Institute of Brain Science](https://alleninstitute.org/what-we-do/brain-science/) [:octocat:](http://alleninstitute.github.io/)  
🇺🇸 [BICCN](https://biccn.org/) BRAIN Initiative Cell Census Network, Allen Institute of Brain Science [:octocat:](https://github.com/BICCN) [:keyboard:](https://biccn.org/tools)  
🇺🇸 [NWB](https://www.nwb.org/) Neuroscience without borders [:keyboard:](https://www.nwb.org/source-codes/)  
🇺🇸 [IARPA](https://www.iarpa.gov) Intelligence Advanced Research Projects Activity  
🇺🇸 [OCNS](https://www.cnsorg.org) Organization for Computational Neuroscience  
🇸🇬 [SFN Sigapore](https://www.sfn.sg/) Society for Neuroscience Singapore chapter  
🇰🇷 [KSBNS](https://www.ksbns.org/Default.asp) Korean Society for Brain and Neural Sciences  
🇰🇷 [AKNeuro](https://akneuro.org/) Assosiation of Korean Neuroscientists  
🇰🇷 [KBRI](https://www.kbri.re.kr/new/pages_eng/main/) Korea Brain Research Institute  
🇯🇵 [JNSS](https://www.jnss.org/en/) Japan Neuroscience Society  

### Software

Labs
* [OSB](https://www.opensourcebrain.org/projects#technology)(Open Source Brain) — collection of open source neuroscience tools
* [NITRC](https://www.nitrc.org) - large list of neuroimaging tools
* [LEAD-DBS](https://www.lead-dbs.org/) - model of deep brain stimulation as population level
* [VERTEX](http://vertexsimulator.org/) - model of electrical stimulation at neuronal level
* [SpikeInterface](https://github.com/SpikeInterface) - a unified framework for spike sorting
* [MICrONS](https://www.iarpa.gov/index.php/research-programs/microns) - machine intelligence from cortical networks, IARPA
* [SpikeGLX](http://billkarsh.github.io/SpikeGLX/) - used in neuropixels, Allen Institute
* [SMART](https://github.com/mjin1812/SMART) - spatial registration tool, BICCN
* [HistoloZee](http://picsl.upenn.edu/software/histolozee/) - spatial registration tool, MRI visualization, histology, BICCN
* [cnpkg](https://github.com/srinituraga/cnpkg) - cortical network simulator, optimized with CUDA, Seung Lab, MIT
* [fimpy](https://github.com/portugueslab/fimpy) - parallelizable processing of fluorescent imaging data, HDF5
* [Connectome Workbench](https://github.com/Washington-University/workbench) — visualization of connectome, UW
* [Connectome Viewer](https://github.com/LTS5/connectomeviewer) 🏚️ — visualization of connectome
* [Open Worm](https://openworm.org) — tools for simulation full neural system of C'Elegans
* [Sibernetic](https://github.com/openworm/sibernetic) — simulator of biomechanical matter (membrances, potentials, liquids, solids)
* [OCNS](https://www.cnsorg.org/model-database)🏚️  — list of models for compuational neruoseicnes
* [google/neuroglancer](http://github.com/google/neuroglancer) — interactive visualization of volumetric neural data (cross sections, slices)
* [pyrates](https://github.com/pyrates-neuroscience/PyRates) — toolkit for dynamical system simualation (ref. "From Neuoron to Cognition via Computational Neuroscience")
* ... many more software is available in labs and organizations links

Enterprise
* [Siemense](https://www.siemens-healthineers.com/en-sg/magnetic-resonance-imaging/options-and-upgrades/clinical-applications)

### Hardware
🇺🇸 [Neuropixels](https://www.neuropixels.org/), Allan Institute  
🇺🇸 [Auto-Surgery](http://www.autosurgery.org/), Allan Institute, MIT  
🇩🇪 Siemens [fMRI](https://www.siemens-healthineers.com/en-sg/magnetic-resonance-imaging)  
🇺🇸 [Braingate](https://www.braingate.org), BCI   
🇺🇸 [Neurolutions](https://www.neurolutions.com), BCI  

### Data

* [ConnectomeDB](https://db.humanconnectome.org) — humman connectome 
* [1000 Functional Connectomes](https://fcon_1000.projects.nitrc.org/) — human functional connetomes, NITRC, INDI 
* [Virtual Brain](http://thevirtualbrain.org) — human brain simulator, 11 labs, Berlin Institute of Health, Simon Fraser University, Univeristy of Toronto, INSERM
* [NiMARE](https://github.com/neurostuff/NiMARE):octocat: — automatic meta analysis of published fMRI to generate visualizations
* [Neurosynth](https://neurosynth.org)[:octocat:](https://github.com/neurosynth/neurosynth)🏚️ — automatic meta analysis of published fMRI to generate visualizations

