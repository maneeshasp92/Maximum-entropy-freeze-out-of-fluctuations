Code accompanying:

Quantifying fluctuation signatures of the QCD critical point using maximum entropy
freeze-out - https://arxiv.org/pdf/2508.19237

Author: Maneesha Sushama Pradeep

Instructions:

Before running the notebook, download the files 
https://github.com/jordissm/PDG2021Plus/blob/main/hadron-lists/PDG2016Plus/for_Thermal-FIST/PDG2016Plus_ThFIST.dat
and https://github.com/jordissm/PDG2021Plus/blob/main/hadron-lists/PDG2016Plus/for_Thermal-FIST/decays_PDG2016Plus_ThFIST.dat 
which provide the list of hadrons in the PDGList along with their decay properties, that are required for running the file.

In the first subsection of the mathematica notebook, "Preparations" , set the Directory to where you have the downloaded PDG data files saved. Following that you can 
vary the mapping parameters between QCD and Ising Model in the mapping parameters to be input Section.

In the last Section of the mathematica notebook, Analysis and Tables, the \Delta T which parametrizes the freeze-out curve that is used for calculating the Table
can be changed.
One can also change the chemical potential values along the freeze-out curve where the observables are calculated by varying the UList.

Run the notebook to produce the data for second, third and fourth factorial cumulant of proton multiplicty
along a freeze-out curve parameterized using \Delta T (as in the paper) and and Ising like EoS parameterized by (\mu_c, \alpha_2, \rho ,w). 
The data is saved in the Table named as Tab1.


Dependencies:
Mathematica 13+
