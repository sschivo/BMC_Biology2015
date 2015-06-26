The .cys files are the Cytoscape session files with the models from the paper. You can open it in Cytoscape with File --> Open. In particular:
 - Model_Drosophila_Circadian_Clock.cys contains the model of the Drosophila Melanogaster circadian clock (Fig. S4 in the Additional Materials)
 - Model_TNF_EGF_no_hypotheses.cys contains the initial model of the TNF-alpha and EGF pathways (Fig. 4A in the main text)
 - Model_TNF_EGF.cys contains the improved model of the TNF-alpha and EGF pathways (Fig. 5A in the main text)
 - Small_TNF_model.cys contains the small model used as example in the Methods section (Fig. 7C in the main text)
 
The .csv files contain the normalized series for some of the experimental data taken from [1] and [2]. You can add them to a simulation graph with the graph right-click menu "Add data from CSV" (see ANIMO's User Manual available at http://fmt.cs.utwente.nl/tools/animo/content/Manual.pdf).
Initial activity levels and interaction parameters can be changed by the right-clicking on the corresponding nodes and edges and choosing "ANIMO" --> "Edit reactant/reaction...".
Pressing the "Analyze network" button makes ANIMO automatically perform the analysis and show the results in graphical form.
Right-clicking on a graph gives access to additional options. For example, to change between line and heat-map graphs, enable or disable the last menu item "Heat-map graph". A slider under the graph allows to see the activiy levels of  the nodes at each point in time reflected in the Network panel.
For more details about these and other features of ANIMO, please consult ANIMO's User Manual.

[1] Fathallah-Shaykh, H.M., Bona, J.L., Kadener, S.: Mathematical model of the drosophila circadian clock: Loop
regulation and transcriptional integration. Biophysical Journal 97(9), 2399–2408 (2009)
[2] S. Gaudet, K. A. Janes, J. G. Albeck, E. A. Pace, D. A. Lauffenburger, P. K. Sorger, A compendium of signals and responses triggered by prodeath and prosurvival cytokines.  Mol. Cell Proteomics 4, 1569-1590 (2005)
