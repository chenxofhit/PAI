Pairwise Asymmetric Interference 
===

See LICENSE.txt for license information.

This code performs the convergent-cross mapping (CCM) and pairwise asymmetric interference (PAI) calculations in the following paper:

    "Convergent Cross-Mapping and Pairwise Asymmetric Inference"
    James M. McCracken and Robert S. Weigel
    doi: [TBD]
    arxiv: [TBD]

The code calculates CCM correlations slightly differently than Sugihara et al., who originally introduced the techniques in "Detecting Causality in Complex Ecosystems" [http://www.sciencemag.org/content/338/6106/496.figures-only].  See the above paper for details on the algorithms used in the code.  The plots from the paper were generated with the initial commit version of this code.  

This code requires C++11.  Running makePAI.sh should compile the code, which should be run as 

    PAI -? 
    
to see the currently available command line options and requirements.  All of the input and output files are currently plain text with the specific formats indicated by PAI -?.
