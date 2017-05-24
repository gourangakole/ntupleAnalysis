# Analysis

### Download and compile the package  ###
* cmsrel CMSSW_8_0_26
* cd CMSSW_8_0_26/src
* cmsenv
* git clone https://github.com/hplusTocsbar/ntupleAnalysis.git 
* cd Analysis/src
* make clean
* make
* cd ..

### Compile and run, in one go ###
* root -l 'runMe.C("hplusAnalyzer")'

### Submit condor batch jobs  ###

* voms-proxy-init -voms cms
* cd condor
* ./hplusRunCond.sh