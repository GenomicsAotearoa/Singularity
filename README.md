# Singularity

A set of [singularity](https://sylabs.io/docs/) recipes for creating the software containers used in the Genomics Aotearoa [projects](https://www.genomics-aotearoa.org.nz/projects).

Containers are organised by project.

## Environmental metagenomics (env_metagenomics)

#### David Waite, Kim Handley, Carmen Astudillo-Garcia, Hwee Sze Tee

*Maintained by David Waite*

This workflow is currently under development, as we migrate our software stack on NeSI into generic singularity containers. The containers currently available are:

1. MetaBAT v2.13-30 ([Kang et al., 2019](https://doi.org/10.7717/peerj.7359))
1. MaxBin v2.2.7 ([Wu et al., 2014](https://doi.org/10.1093/bioinformatics/btv638))
1. CONCOCT v1.1.0 ([Alneberg et al., 2014](https://doi.org/10.1038/nmeth.3103))
1. VAMB v2.0.1 ([Nissen et al., 2018](https://www.biorxiv.org/content/10.1101/490078v2))
1. DAS_Tool v1.1.1 ([Sieber et al., 2018](https://doi.org/10.1038/s41564-018-0171-1))
1. CheckM v1.0.18 (including 2015/01/16 database) ([Parks et al., 2015](http://www.genome.org/cgi/doi/10.1101/gr.186072.114))
1. dRep v2.3.2 ([Olm et al., 2017](https://doi.org/10.1038/ismej.2017.126))
1. GTDB-TK v0.3.2 ([Parks et al., 2018](https://doi.org/10.1038/nbt.4229))
1. MinPath v1.4 ([Ye & Doak, 2009](https://doi.org/10.1371/journal.pcbi.1000465))
1. Shasta v0.1.0 ([Shafin et al., *preprint*](https://www.biorxiv.org/content/10.1101/715722v1))
1. Miniasm v0.3-r179 ([Li, 2016](https://www.ncbi.nlm.nih.gov/pubmed/27153593))

---

## Handy tool collections

*Maintained by David Waite*

This section is simply small images containing useful bundles of software for preprocessing or small workflows.

1. ONT_Correction
   - [FMLRC](https://github.com/holtjma/fmlrc)
   - [ropebwt2](https://github.com/lh3/ropebwt2)
