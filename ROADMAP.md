{\rtf1\ansi\ansicpg1252\cocoartf2870
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww30040\viewh18980\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # VisualPhysiologyDB Roadmap\
\
## Long-term vision\
\
VisualPhysiologyDB is an open-source ecosystem for connecting light-sensitive genes, physiological phenotypes, ecological context, and predictive models of light sensitivity. Our long-term goal is to make visual and light-interaction phenotypes accessible, computable, and reusable across scales: from individual amino-acid substitutions to ecological communities and environmental sequence datasets.\
\
The project began with the Visual Physiology Opsin Database (VPOD), which organizes opsin genotype\'96phenotype data for spectral sensitivity, and OPTICS, which uses VPOD-trained models to predict opsin spectral sensitivity from sequence. Future development will broaden this ecosystem into a more general visual physiology resource that can support additional phenotypes, richer ecological metadata, community-scale inference, and interoperable workflows for sensory ecology, molecular evolution, biodiversity science, and AI-enabled genotype\'96phenotype prediction.\
\
## Current core projects\
\
### VPOD: Visual Physiology Opsin Database\
\
VPOD curates opsin sequences, phenotypic measurements, metadata, and training datasets for machine-learning analyses of opsin function.\
\
### OPTICS: Opsin Phenotype Tool for Inference of Color Sensitivity\
\
OPTICS predicts opsin spectral sensitivity from amino-acid sequences using models trained on VPOD and related datasets. It provides accessible interfaces for researchers who may not have machine-learning or bioinformatics expertise.\
\
### Related prior work\
\
The VisualPhysiologyDB ecosystem builds on prior Oakley Lab tools and workflows, including PIA/LIT-PIA, a phylogenetically informed annotation workflow for identifying opsins and other light-interaction genes in transcriptomic data.\
\
## Near-term priorities\
\
1. Improve VPOD data structure, documentation, validation, and versioning.\
2. Improve OPTICS usability, batch prediction, uncertainty reporting, and quality control.\
3. Develop OPTICS-Community workflows for predicting light-sensitivity landscapes from species lists, ecological community matrices, transcriptomes, metatranscriptomes, metagenomes, and assembled protein datasets.\
4. Add clearer interfaces between gene discovery, opsin classification, phenotype prediction, and downstream ecological analysis.\
5. Provide benchmark workflows, tutorials, example datasets, and standardized outputs for reproducible research.\
\
## Longer-term priorities\
\
1. Expand beyond \uc0\u955 max to additional opsin and light-interaction phenotypes, such as kinetics, chromophore effects, G-protein coupling, expression context, and assay metadata.\
2. Incorporate ecological and environmental metadata, including habitat, depth, light environment, diel activity, and community composition.\
3. Support community-level and ecosystem-level summaries of predicted light sensitivity.\
4. Improve interoperability with biodiversity databases, sequence repositories, workflow managers, Galaxy, and downstream modeling tools.\
5. Build governance and contributor pathways that allow external users to submit data, report issues, request features, and contribute workflows.\
\
## Guiding principles\
\
VisualPhysiologyDB development will prioritize open licensing, reproducibility, transparent provenance, uncertainty reporting, biological interpretabil}