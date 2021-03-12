> How much do we know about the brain?
> What are the key labs?
> Which companies work on this?
> What software is being used?

Here you may find good entrypoints to answer these questions

### Basics

* brain is not a _randomly_ connected mesh, there is a lot of high and low level structure.
* _grey matter_ — surface layer, cortex, mostly neurons, ~6 layers of neurons; _white matter_ — insides, connections between neurons, moslty axons.
* _current representation_ — vector at layer in network, what is being processed now; _abeyant representation_ — stored knowledge, weights at layer of network.
* _local coding_ — concept of "grandmother" is handled by a single neuron; _distributed coding_ — it is distributed on many neurons, vector coding.
* _connectomics_ — given brain is a graph, what are its properties, how does it differ in animals, how it comes into being, how it changes with time. Status of mapping: C elegans worm, Drosophilia fruit fly — fully mapped; pigeon, cat, monkey, human — good, but not full. A lot of structure of connectome is encoded in genes.
* _plasticity_ — how neurons change their connection weights: structural plasticity — changing what is connected; functional plasticity — changing strength of connection.
* _time_ is important, as a lot of processing is oscilating potentiation; many recurrent loops; different types of neurons; neurons are either inhibitory or excitatory.

### Books

* [The Computational Brain](https://www.goodreads.com/book/show/32078490-the-computational-brain),  Patricia S. Churchland,
Terrence J. Sejnowski, MIT Press
* [Changing Connectomes](https://www.goodreads.com/book/show/51456624-changing-connectomes), Marcus Kaiser, MIT Press
* [Dynamic Patterns: The Self-Organization of Brain and Behavior](https://mitpress.mit.edu/books/dynamic-patterns), MIT Press
* [Principles of Neural Science](https://www.goodreads.com/book/show/826396.Principles_of_Neural_Science), Kandel
* [Fundamental Neuroscience](https://www.goodreads.com/book/show/13658691-fundamental-neuroscience), Squire, Academic Press
* [Neuroscience of Mathematical Cognitive Development](https://www.goodreads.com/book/show/38250564-neuroscience-of-mathematical-cognitive-development), Rhonda Douglas Brown, Springer
* [Chasing Men on Fire](https://www.goodreads.com/book/show/36722581-chasing-men-on-fire), Stephen G Waxman, MIT Press
* [The Ego Tunnel](https://www.goodreads.com/book/show/5895503-the-ego-tunnel), Thomas Metzinger

[Strüngmann Forum Reports](https://mitpress.mit.edu/books/series/strungmann-forum-reports), yearly meeting of leading researchers regarding current status of selected topic:

* [The Neocortex](https://mitpress.mit.edu/books/neocortex), MIT Press, 2019
* [Emergent Brain Dynamics: Prebirth to Adolescence](https://mitpress.mit.edu/books/emergent-brain-dynamics), MIT Press, 2018
* [Translational Neuroscience: Toward New Therapies](https://mitpress.mit.edu/books/translational-neuroscience), MIT Press, 2015

### Courses

* [Neuromatch Academy](https://github.com/NeuromatchAcademy)
* [List of MIT Brain and Cognitive Sciences courses](https://ocw.mit.edu/courses/brain-and-cognitive-sciences/)

### Software

* [NITRC](https://www.nitrc.org/projects) - large list of neuroimaging tools
* [LEAD-DBS](https://www.lead-dbs.org/) - model of deep brain stimulation as population level
* [VERTEX](http://vertexsimulator.org/) - model of electrical stimulation at neuronal level
* [SpikeInterface](https://github.com/SpikeInterface) - a unified framework for spike sorting
* [MICrONS](https://www.iarpa.gov/index.php/research-programs/microns) - machine intelligence from cortical networks, IARPA
* [SpikeGLX](http://billkarsh.github.io/SpikeGLX/) - used in neuropixels, Allen Institute
* [SMART](https://github.com/mjin1812/SMART) - spatial registration tool, BICCN
* [HistoloZee](http://picsl.upenn.edu/software/histolozee/) - spatial registration tool, MRI visualization, histology, BICCN
* [cnpkg](https://github.com/srinituraga/cnpkg) - cortical network simulator, optimized with CUDA, Seung Lab, MIT
* ... many more software is available in labs and organizations links

### Hardware

* 🇺🇸 [Neuropixels](https://www.neuropixels.org/), Allan Institute
* 🇺🇸 [Auto-Surgery](http://www.autosurgery.org/), Allan Institute, MIT

### Labs

* 🇩🇪 Ernst Strüngmann Institute for Neuroscience: [Singer Lab](https://www.esi-frankfurt.de/research/singer-lab/)
* 🇺🇸 University of Pennsylvania: [Kording Lab](kordinglab.com) [:octocat:](https://github.com/KordingLab) | [Penn Image Computing & Science](picsl.upenn.edu) [:keyboard:](http://picsl.upenn.edu/software/)
* 🇺🇸 MIT, Princeton: [Seung Lab](https://seunglab.org/) [:keyboard:](https://seunglab.org/software/) [:octocat:](https://github.com/seung-lab)
* 🇺🇸 MIT: [brain + cognitive sciences department](https://bcs.mit.edu/)
* 🇺🇸 Stanford: [Cognitive & Systems Neuroscience](https://med.stanford.edu/scsnl/about1.html) [:octocat:](https://github.com/scsnl) | [Brain Dynamics](https://web.stanford.edu/group/bdl/) [:octocat:](https://github.com/braindynamicslab) | [Lee Lab](https://llab.stanford.edu/index.html)
* 🇺🇸 Carnegie Mellon: [Cognitive Neuroscience](https://www.cmu.edu/ni/research/cognitive-neuroscience.html) | [Computational Neuroscience](https://www.cmu.edu/ni/research/computational-neuroscience.html) | [Neuro Tech & Engineering](https://www.cmu.edu/ni/research/neuro-tech-and-engineering.html) | [Systems Neuroscience](https://www.cmu.edu/ni/research/systems-neuroscience.html)
* 🇯🇵 OIST: [Neural Coding and Brain Computing](https://groups.oist.jp/ncbc) [:octocat:](https://github.com/oist-ncbc)
* 🇸🇬 Duke-NUS: [Neuroscience and Behavioural Disorders](https://www.duke-nus.edu.sg/nbd)
* 🇰🇷 KAIST: [Cognitive Neuroscience and Neuroimaging](http://ibrain.kaist.ac.kr/) | [Brain Dynamics](http://raphe.kaist.ac.kr/index.htm) | [Behavioral Genetics](https://sites.google.com/site/bglabkorea/) | [Synaptic Brain Dysfunction](http://molneuro.kaist.ac.kr/contents/) | [Neural Interoception](https://www.suhlab-neuralinteroception.kaist.ac.kr/) | [Sensory processing](https://sites.google.com/site/leelab2013/) | [Systems neuroscience](https://sites.google.com/site/systemsneurolaboratory/)

### Companies

* 🇺🇸 [Neuralink](https://neuralink.com) [:octocat:](https://github.com/neuralinkcorp)
* 🇺🇸🇰🇷 [LVIS](http://lviscorp.com/) — Lee Lab, Stanford, visualization
* 🇺🇸 [Imaging Biometrics](https://www.imagingbiometrics.com)
* 🇺🇸 [Numenta](https://numenta.com) [:octocat:](https://github.com/numenta)
* 🇺🇸🇯🇵 [INSIGHTEC](https://www.insightec.com/) — neurosurgery, lesion with no incisions, ultrasound

### Organizations

* 🌏 [INCF](http://www.incf.org) International Neuroinformatics Coordinating Facility [:octocat:](https://github.com/INCF)
* 🇺🇸 [The BRAIN Initiative](https://www.braininitiative.org/) [:keyboard:](https://www.braininitiative.org/toolmakers-resources/)
* 🇺🇸 [IEEE Brain](https://brain.ieee.org/)
* 🇺🇸 [Allen Institute of Brain Science](https://alleninstitute.org/what-we-do/brain-science/) [:octocat:](http://alleninstitute.github.io/)
* 🇺🇸 [BICCN](https://biccn.org/) BRAIN Initiative Cell Census Network, Allen Institute of Brain Science [:octocat:](https://github.com/BICCN) [:keyboard:](https://biccn.org/tools)
* 🇺🇸 [NWB](https://www.nwb.org/) Neuroscience without borders [:keyboard:](https://www.nwb.org/source-codes/)
* 🇺🇸 [IARPA](https://www.iarpa.gov) Intelligence Advanced Research Projects Activity
* 🇸🇬 [SFN Sigapore](https://www.sfn.sg/) Society for Neuroscience Singapore chapter
* 🇰🇷 [KSBNS](https://www.ksbns.org/Default.asp) Korean Society for Brain and Neural Sciences
* 🇰🇷 [AKNeuro](https://akneuro.org/) Assosiation of Korean Neuroscientists
* 🇰🇷 [KBRI](https://www.kbri.re.kr/new/pages_eng/main/) Korea Brain Research Institute
* 🇯🇵 [JNSS](https://www.jnss.org/en/) Japan Neuroscience Society
