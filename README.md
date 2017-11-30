# Brown Delphes Analysis

=======================

From https://cp3.irmp.ucl.ac.be/projects/delphes

```
    A framework for fast simulation of a generic collider experiment

    Delphes is a C++ framework, performing a fast multipurpose detector response simulation. 
    The simulation includes a tracking system, embedded into a magnetic field, calorimeters and a muon system. 
    The framework is interfaced to standard file formats (e.g. Les Houches Event File or HepMC) and outputs observables such as isolated leptons, missing transverse energy and collection of jets which can be used for dedicated analyses. 
    The simulation of the detector response takes into account the effect of magnetic field, the granularity of the calorimeters and sub-detector resolutions. 
    Visualisation of the final state particles is also built-in using the corresponding ROOT library.
 ```
 
 This packages takes event samples simulated with Delphes and applies standard selection critera and corrections for a ttbar analysis to each event and constructs histograms of kinematic and geometric variables.
 
 =======================
 

Setup Area (LPC):
```
    cmsrel CMSSW_8_0_4
    cd CMSSW_8_0_4/src/
    cmsenv
```

Checkout Repository: 
```
git clone https://github.com/agarabed/Delphes_Analysis.git Delphes_Analysis
```
