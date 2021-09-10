---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research is funded by the [Department of Energy Office of Science](https://www.energy.gov/science/office-science), the [National Science Foundation](https://nsf.gov) and the [Purdue Research Foundation](http://prf.org).

# Current:

- **Search for new heavy neutral vector bosons, contact interactions and extra dimensions using dilepton events:**
: New heavy neutral gauge bosons (Z<sup>'</sup>) are predicted in extensions of the Standard Model. There are many options for this extra gauge symmetry including Grand Unified Theory (GUTs), Randall-Sundrum graviton models and Kaluza-Klein excitation of extra dimensions. Since the very beginning I have been involved in the search for high-mass resonances in the dimuon channel (Z<sup>'</sup>&rarr;&mu;&mu;). Together with my students and postdocs I have been working on many important aspects of the search for high-mass resonances in the dimuon channel and published the most precise determination of the dimuon mass spectrum up to the highest masses ever achieved. This result has provided the most sensitive limits on new high-mass particles.  This search has been one of the flagship analyses of the LHC physics program. In addition to the search for high-mass resonances in we have been working on searches for a non-resonant dilepton excess in the context of contact interactions and large extra dimensions.  Furthermore, my group has been working on additional interpretations of the limits set for a high mass dilepton resonance in the context of dark matter mediators and pioneered a new analysis searching for leptophobic Z<sup>'</sup> bosons decaying into four-lepton final states. This baryonic gauge boson is well motivated in a supersymmetry framework.

- **Search for lepton flavor universality (LFU) violation:**
: One of the fundamental predictions of the Standard Model is Lepton Flavour Universality (LFU). Any deviation from this prediction would indicate the existence of physics beyond the Standard Model.
Hints for LFU violation in several measurements of rare B-meson decays recently reported by the LHCb Collaboration have sparked interest in models for physics beyond the SM that could explain these effects, such as heavy neutral gauge bosons or leptoquarks. Some of these models would result in a significant deviation from unity of the ratio of the dimuon to dielectron differential cross section as a function of dilepton mass. To search for signs of LFU violation at high dilepton mass we spearheaded a new analysis, where the ratio of the differential dilepton production cross sections in the muon and electron channels is measured as a function of dilepton mass. This is the first measurement of this kind at the LHC and the results have been recently published.

- **Search for new heavy physics using dimuon + b jet events:**
: We recently started a new search that can improve the sensitivity to new physics in dimuon + b jet events.  We study the impact of contact interactions involving two leptons (electrons or muons) and two b-quarks on the high-mass dilepton region at the LHC. The idea is based on [1](https://arxiv.org/abs/1805.11402), 
[2](https://arxiv.org/abs/1912.00425), 
[3](https://arxiv.org/pdf/2005.06457.pdf) and 
[4](https://arxiv.org/pdf/2106.15647.pdf).

- **Measurement of the Higgs boson properties (coupling to the second-generation fermions); H &rarr; &mu;&mu;:**
: Since 2016 my group has been working on the Higgs to two muon decay analysis to measure the coupling of the Higgs boson to the second-generation fermions. After the discovery of the Higgs boson in 2012, the measurement of its properties is of paramount importance. Since so far only couplings to the third-generation fermions have been observed it is important to show that the Higgs boson also couples to second-generation fermions. The H→μμ channel has a clean final-state signature and it is the only channel where the Higgs coupling to second-generation fermions can be measured at the LHC. The challenge is to search for a narrow mass peak on a smooth background that is dominated by the irreducible Drell-Yan tail above the Z boson resonance. Since the kinematic properties of the signal and the main background are very similar in this analysis, advanced machine-learning techniques are needed, and we developed new deep learning techniques to optimize the signal extraction. In September 2020, the CMS Collaboration published a paper reporting the first evidence of a Higgs boson decaying to a pair of oppositely charged muons. An excess of events over the expected background was reported, with a statistical significance of 3σ, and the measured signal strength has been found to be in agreement with the Standard Model predictions. This result is an important milestone in Higgs physics, as it provides the first statistically significant measurement of the Higgs boson coupling to second generation fermions. Our  group significantly contributed to this result, specifically in the gluon-gluon fusion (ggH) and the vector boson fusion (VBF) production channels where new ways to optimally take the dimuon mass resolution into account were explored and the input features and hyperparameters of MVA discriminants that are used to improve the separation between signal and background events were optimization. The H→μμ analysis will remain one of our main analysis goals during Run 3 of the LHC that is scheduled to start in 2022.

- **Design and development of High-Level Trigger algorithms for Run 3 and the HL-LHC:**
: For Run 2 we developed a new Level-3 muon trigger that is be able to better cope with the high-energy and high-luminosity conditions. An evolution of this trigger will be deployed for Run 3 and HL-LHC.

- **Track Selection using Machine Learning techniques:**
: We develop a new track selection based on Machine Learning techniques. Currently we use a DNN (deep neural network) to maximize the track selection effiency and minimize the fake rate. 

- **Heterogeneous computing:**
: With the introduction of a track trigger at L1 in the Phase-2 tracker, the upgraded detector will allow for significant further improvements of the muon HLT. The new high-momentum track stub information provided by the L1 track trigger can be used to seed muon track reconstruction. Possibilities at the HLT will vary depending on the tracking available, but if reconstruction is sufficiently fast CMS’s sensitivity to displaced muons will significantly increase and even more exciting options become available.
We are currently working on implementing the online muon reconstruction algorithms on GPUs.

- **Columnar interactive analysis:**
: We are working on the development of an analysis framework based on the columnar analysis approach implemented
using the tools of the [coffea](https://arxiv.org/abs/2008.12712) package which is based on [awkward-array](https://doi.org/10.5281/zenodo.3952674) and [uproot](https://zenodo.org/record/4193917#.YTJtvC1h2iA).
The framework implements all analysis steps of the H→μμ analysis and therefore can serve 
as an example of a typical HEP analysis for benchmarking various processing methods and
workflows.
In the framework development, we pursue two main objectives. Firstly, to implement data
processing in a way that accelerates both development and performance by using a columnar
approach (via coffea, awkward-array). Secondly, to distribute the computations across a
local Analysis Facility using custom Dask workflows in a way that efficiently utilizes available
computing resources.  
The Analysis Facility (AF) at the Tier-2 center at Purdue is implemented on top of the existing CMS computing infrastructure and
in1cludes a dedicated Storage Element based on HDFS; a dedicated Compute Element, as well as
opportunistic access to all Community Clusters, including one dedicated to GPU workloads;
and centralized disk- and tape-storage systems. After its currently undergoing expansion, the
AF will also allow bursting into the public cloud providers.
In its final design the Analysis Facility will leverage the Service for Web-based ANalysis (SWAN)
project at CERN and the [Geddes Composable Platform](https://doi.org/10.1109/SuperCompCloud51944.2020.00011) - a Kubernetes-based “Community Cloud” resource at 
Purdue - to provide a platform for flexible, elastic, and customizable cloud and container computing with bursting capabilities to the Community Clusters at Purdue
due, Open Science Grid, and the public clouds.


- **Principal investigator of the US CMS Tier-2 analysis center at Purdue:**
: In collaboration with the [Information Technology at Purdue (ITaP) research computing](https://www.rcac.purdue.edu/about) I operating the [CMS Tier-2 analysis center](http://www.physics.purdue.edu/Tier2/), which enables and supports important physics analyses.

- **Operations and maintenance of the Forward Pixel detector:**
: My group has been taking active part in the commissioning, operations and data quality monitoring of the forward pixel detector (FPIX).



# Past:
## Proton-Proton Annihilation at the LHC (CMS):
* Measurement of the differential and double-differential Drell–Yan cross section
* Measurement of the W and Z cross section
* Same-sign dilepton search for Supersymmetric particles
* Search for exotic four-lepton resonances
* Level-1 muon trigger design and simulation
* Measurement of the charge ratio of atmospheric muons
* Physics commissioning of the CMS detector with cosmic rays
* Design and implementation of novel muon reconstruction and identification algorithms
* Online event selection (High-Level Trigger)
* Large-scale distributed data analysis (Grid computing)
* Development of a Web portal for grid job submission
* B physics studies (CP violation, b-Baryons)

## Electron-Positron Annihilation at LEP (DELPHI):
* Search for supersymmetric (SUSY) particles (three-body decays of scalar top quarks)
* Reconstruction of colour-suppressed B decays
* Inclusive J/&psi; analysis

## Proton-Antiproton Annihilation at SPS (UA1):
* Intermittency studies
* Analysis of Bose-Einstein correlations

{% include base_path %}

<img src="/images/DOE_Logo.jpg" width="400"> <img src="/images/NSF_Logo.png" width="140" style="margin-left: 2em">  <img src="/images/PRF_Logo.png" width="200" style="margin-left: 2em">
