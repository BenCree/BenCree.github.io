---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---



I am undertaking a PhD in Computational (Medicinal) Chemistry in the Daniel Cole group at Newcastle University, and my project is focused on developing automated workflows for computer-aided drug design (CADD) by utilising and integrating molecular dynamics and structural biology software, for fragment hit-to-lead optimisation. This sort of automation will utilise Python and be validated using specific targets (CDK9, SARS-CoV-2 - NSP13). The new workflow will allow non-specialists to access CADD more readily, and for specialists, automate laborious preparatory work.

I hold a MChem degree in Chemistry, specialising in computational chemistry, from St. Chad's College at Durham University. My thesis was on simulation models of bent-core liquid crystals. I am currently a PhD student at Newcastle University with Molecular Science for Medicine (MoSMed), 

I also have a strong interest in the philosophy of science.



# About Me
## Optional Author Name <benstuartcree@gmail.com>
Optional version, optional date

## Revision: AlternativeWayToSetOptional version

Alright? I'm a computational scientist, I'm quite into linguistics and etymologies, [DnB](https://www.youtube.com/watch?v=6XQc_FGNS98), comedy & spending far too much time trying to make money from crypto with various machine learning strategies.

## PhD
[Me](#me)

I'm currently finishing my PhD in Computational (Medicinal) Chemistry in the Daniel Cole group at Newcastle University, and my project is focused on developing automated workflows for computer-aided drug design (CADD) for fragment hit-to-lead optimisation. validated using specific targets (CDK9, SARS-CoV-2 - NSP13). In practice this means I spend lots of my time on but not limited to: open-source development (have a look at our free energy de novo design tool : [https://github.com/cole-group/FEgrow](https://github.com/cole-group/FEgrow)), OpenMM (FEP calculations), messing around with RDKit, some Machine Learning and data analysis.
I am also a part of the Molecular Science for Medicine (MoSMed) CDT.

### Education
I hold a MChem degree in Chemistry, specialising in computational chemistry, from St. Chad's College at Durham University.

My [thesis](https://github.com/BenCree/Thesis/blob/master/report_template(8).pdf) was on simulation models of bent-core liquid crystals.

## Research
### FEgrow

{% include image.html url="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs42004-022-00754-9/MediaObjects/42004_2022_754_Fig1_HTML.png?as=webp" alt="FEgrow workflow" width="600" height="300" float="right" %}

**Celebrating 5 years of Communications Chemistry - _Most highly downloaded paper_**

_An interactive workflow for building user-defined congeneric series of ligands in protein binding pockets for input to free energy calculations._

FEgrow integrates medicinal chemistry expertise in the design workflow, with state-of-the-art methods for pose prediction, scoring and free energy calculation. By building ligands from the constrained core of a known hit, we maximize the use of input from structural biology, and reduce reliance on docking algorithms. We have benchmarked FEgrow by building and scoring binding poses for ten congeneric series of ligands bound to targets from a standard, high quality dataset of protein-ligand complexes, as well as a series of inhibitors of the SARS-CoV-2 main protease, but this would be the first prospective use of FEgrow in hit identification.

We are currently working on an active learning and generative model augmented version.

[https://doi.org/10.1038/s42004-022-00754-9](https://doi.org/10.1038/s42004-022-00754-9)

#### Further Information

Please see [https://www.cole-group.github.io/fegrow](https://www.cole-group.github.io/fegrow) for full installation instructions, documentation and acknowledgements.

To get started see the online tutorial for which the IPython Notebook is available [here](https://cole-group.github.io/FEgrow/tutorial/tutorial/).

_Bieniek, Mateusz K., Ben Cree, Rachael Pirie, Joshua T. Horton, Natalie J. Tatum, and Daniel J. Cole. "An open-source molecular builder and free energy preparation workflow." Communications Chemistry 5, no. 1 (2022): 136._

### AFF4:Cyclin T hit-to-lead campaign

The super-elongation complex (SEC) functions during gene transcription to control release from promoter-proximal pausing and the induction of rapid gene transcription.
*AFF4* acts as a scaffold for the *CDK9-Cyclin T* complex (P-TEFb) to facilitate the phosphorylation of the RNA Polymerase II CTD through a direct interaction of the AFF4 N- terminus with cyclin T.
SEC disruption is a potential method to target MYC-driven cancers and diffuse midline gliomas, which show a dependency on the AFF4:P-TEFb SEC, as well as leukemias with MLL-AF4 fusions.

We have been providing computational assistance via FEP/docking to the hit-to-lead optimisation campaign from the fragment screening of cyclin T1/T2.

### CACHE#2 Challenge

The [CACHE#2](https://cache-challenge.org/challenges/finding-ligands-targeting-the-conserved-rna-binding-site-of-sars-cov-2-nsp13) challenge is the second CACHE Challenge target is the NSP13 helicase of SARS-CoV-2.

Participants were asked to find hits for the RNA-binding site of NSP13, and we have employed our [workflow](https://cache-challenge.org/challenges/app/630f530533e41) to discover a 9 µm inhibitor compound, which progressed to the next round.

