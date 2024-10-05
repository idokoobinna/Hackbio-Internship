STAGE 3 PHASE 1 TASK

Contributors: Pranjal Paul, Natasha Murape, Oluchi Onyemeh,  Evans Boakye , Idoko obinna

PROTEIN INTERACTION WITH PHYTOCHEMICALS IN CANCER RESEARCH

Introduction 

The most frequent malignant tumor with high mortality is lung cancer. The global lung cancer mortality increased to 1.59 million deaths in 2012, responsible for 19.4% of cancer deaths (Ferlay et al., 2012).  Epidemic Studies have shown that tobacco, air pollution, radon exposure, occupational exposure, hereditary susceptibility, radiation and unbalanced diets are the risk factors for the incidence of lung cancer (Yousheng et al., 2016). The metastatic spread of cancer is the main cause for the mortality of cancer, which studies have shown to be a contributing factor for 90% of cancer mortality (Chaffer et al., 2011).

 The Rho-associated coiled-coil kinases (ROCK1 and ROCK2) and myotonic dystrophy-related CDC42 binding kinases (MRCKα and MRCKβ) that regulate actin-myosin cytoskeleton are directly associated to metastasis and tumor cell invasion (Olson, 2009). The myosin-actin cytoskeleton determines the shape of a cell by providing a structural framework and it also directly promotes biological activities including adhesion, cell migration and cell division which contribute to cancer (Olson, 2009). The Rho-associated coiled-coil kinases and myotonic dystrophy-related CDC42 binding kinases that enable distant metastasis also contribute to primary tumor growth (Waclaw et al., 2015); therefore, drugs that inhibit or restrict the processes that lead to cancer spread (eg cell division and invasion) have significant effects in minimizing or reducing tumor growth and progression. Studies have shown that the concerted inhibition of both ROCK and MRCK has greater effects than inhibiting either ROCK or MRCK. However, a study by Unbekandt et al., (2014) shows that blocking MRCK was sufficient enough to reduce the 3D invasion by squamous cell carcinoma (SCC) cells. 

Azadirachta indica commonly known as neem, is a local herb and also a fast-growing tropical evergreen tree with a highly branched and stout, solid stem and because of its tremendous therapeutic, domestic, agricultural and ethnomedicinal significance and its proximity with human culture and civilization, neem has been called “the wonder tree” and “nature’s drug store.” All parts of this tree, particularly the leaves, bark, seed-oil and their purified products are widely used for treatment of cancer (Asghari-Paskiabi et al., 2019; Paul, et al., 2011) such as lung cancer. The anticancer properties of Azadirachta indica have been studied largely in terms of its preventive, protective, tumor-suppressive, immunomodulatory and apoptotic effects against various types of cancer and their molecular mechanisms. Additionally, epidemiological studies suggest that the daily intake of certain phytochemicals can reduce the incidence of several types of cancers (Mohammad & Md 2013). A detailed metabolites/phytochemicals library of Azadirachta Indica:

https\://docs.google.com/document/d/1t1tW6Mj6MTWsh8V5nvI7iofKHVsOJ\_bq/edit?usp=sharing\&ouid=109918313132425774085\&rtpof=true\&sd=true

Docking-based virtual screening is a computational approach to identify leads from a database of molecules. Instead of screening entire libraries experimentally, virtual screening affords us a decrease in both time and resources. This research is focused on evaluating MRCK (PDB ID: 5OTE) as an anti-cancer drug target by screening it with reported bioactive compounds in Azadirachta Indica with anti-cancer activities.

Methodology 

Protein Selection

An advanced search for a prognostic lung cancer with unfavorable prognosis query was conducted by accessing the human proteome database (https\://www\.proteinatlas.org/ ). Using the ‘Fields’ function, a prognostic cancer was selected under ‘Field’ section, lung cancer was then selected under the cancer section and finally, unfavorable prognosis was selected under the prognosis option. All these queries were added and searched for. The CDC42 binding protein kinase beta (potential drug target) with gene name CDC42BP (KIAA1124, MRCKB) was selected. The structural information of the selected protein was accessed on Uniprot. The PDB structure of the protein with a PDB ID: 5OTE (Figure 1) and a resolution of 1.65 A was downloaded and further processed and docked with the secondary metabolites in Azadirachta Indica. 

Figure 1. Crystal structure of MRCKβ (PDB ID: 5OTE)

MRCKβ Binding site and residues

MRCKβ has a primary binding site for ATP located in its kinase domain. This interaction with ATP facilitates the phosphorylation of substrates including myosin II regulatory light chain (MLC). The residues that interact with ADP in the ATP binding site have been reported (Unbekandt et al., 2014). The side chains: Ile82, Val90, Ala103, Tyr155, Tyr156, Leu207 and Phe370, form a hydrophobic pocket which fits adenine, while also interacting with the hinge backbone through hydrogen bonding (Asp154 carbonyl and Tyr156 amine). Additionally, a water molecule in the binding pocket interacts with the residues Glu124, Thr137, Asp218 and Phe219 and form hydrogen bonds with the phosphates on the nucleotide. The diphosphate interacts directly and indirectly with the side chains of Asn205 via stabilizing Mg2+ ions or water molecules.

Moreover, Computed Atlas of Surface Topography of Proteins (CASTp) was used to predict the binding site on the three-dimensional structure of MRCKβ (PDB ID:5OTE). CASTp is an online tool that can generate protein visualizations of the protein surfaces showing potential binding sites for ligands. It quantified the area and volume of the potential binding pocket to be 573.842 Å2 and 546.664 Å3, respectively (Figure 2).

Figure 2. Binding site prediction of MRCKβ using CASTp (A). Structure of MRCKβ in complex with ADP (B), (Unbekandt et al., 2014). 

Docking Procedure in PyRx

Protein Preparation

Protein 50TE was downloaded from the Protein Data Bank (PDB) in .pdb format. Using PyRx, the protein was pre-processed to remove water molecules, ions, and other non-essential components, which may interfere with docking. Missing hydrogen atoms were added, and the structure was minimized to ensure stability.

Ligand Preparation

Ligands were prepared by converting their chemical structures to .mol2 or .sdf format and imported into PyRx. PyRx was used to convert the ligands to a suitable file format (typically .pdbqt) for the docking study. Ligands were optimized using the MMFF94 force field to ensure they were in the lowest energy conformation for docking.

Docking Protocol

PyRx employs Autodock Vina as the docking engine. The protein and ligands were imported, and the binding site was defined using a grid box that encompassed the active site of the protein. The docking was performed by setting the grid box to cover the catalytic domain, and multiple ligand conformations were generated. Vina scores were obtained for each ligand conformation, providing binding affinities for each pose.

Analysis of Docking Results

Binding affinity was analyzed for each ligand, and the pose with the lowest (most negative) binding affinity was selected as the best. RMSD (Root-Mean-Square Deviation) values were used to determine the similarity of different poses for a given ligand.

Results

A total of 49 ligands were tested across all CSV files. The best Binding Affinity achieved was -14.5 kcal/mol for Ligand 76311433,RMSD values varied between the upper bound (ub) and lower bound (lb) for each ligand, with values indicating variability in ligand binding poses. Ligand 76311433 exhibited the strongest binding affinity of -14.5 kcal/mol, indicating favorable interaction with protein 50TE. 

Visualization of the binding interaction in Discovery Studio revealed that the ligand formed key hydrogen bonds and hydrophobic interactions with the active site residues, which contributed significantly to its stability. The RMSD values indicated that ligand 76311433 had consistent binding poses (low RMSD), suggesting stable and reproducible binding. Ligands with higher RMSD values showed variability in binding poses, which could indicate fewer stable interactions. PyRx provided binding affinity values and RMSD information, allowing for a quantitative evaluation of ligand-protein interactions. Discovery Studio provided more detailed insights into specific molecular interactions, enhancing the qualitative understanding of the ligand binding mode.

Figure 3. MRCKβ Residues commonly interacting with the ligands from virtual screen in PyRx. 

Evaluation of pipeline reusability and potential applications  

The pipeline can be evaluated on the following key factors: Scalability, Reproducibility, cross platform reusability and Input & output management. Molecular docking was performed to screen a library of 50 metabolites found in Azadirachta indica. The procedure was repeated multiple times with the same input and we observed consistency in the docking results, demonstrating high reliability and reproducibility of the pipeline. The pipeline is also platform-independent in that it can be used on any operating system (Windows, Linux and macOS).

The pipeline is scalable and thus capable of processing large libraries of compounds. This is because the platform PyRx is able to handle a high computational load and multiple docking runs. AutoDock Vina is integrated into PyRx, and is known for its fast-docking speed making it suitable to screen large libraries ligands (Dallakyan and Olson, 2015). The platform PyRx does not automatically handle input file formats other than .pdbqt thus a ligand preparation step to convert the file formats is necessary. 

The molecular docking pipeline for the virtual screening of the Azadirachta indica compound library targeting MRCKβ has wide applications in cancer research and drug discovery.  There is an opportunity for high throughput virtual screening of plant compounds for the identification of novel lead compounds inhibiting MRCKβ that can be translated into therapeutic drugs. The pipeline can be exploited for personalized treatment strategies for instance, by screening compounds to inhibit a specific form of MRCKβ in particular patient populations. Furthermore, the pipeline is cost-effective and easy to use making it accessible for academic and industrial researchers in cancer and drug development. 

Conclusion

Strongest Ligand Interactions: Ligand 76311433 (PubChem ID 76311433) exhibited the best binding affinity, indicating its potential as a lead compound for further development. Visualizing the Binding Interaction: Discovery Studio revealed critical interactions, such as hydrogen bonds and hydrophobic contacts, between ligand 76311433 and protein 50TE, explaining the strong binding affinity observed. Next Steps: Ligand 76311433 should be further validated using molecular dynamics simulations to confirm its stability over time. Additionally, structure-activity relationship (SAR) studies may be conducted to modify the ligand for improved binding.

References 

CASTp 3.0: Computed Atlas of Surface Topography of proteins (uic.edu)

Asghari-Paskiabi F, Imani M, Rafi i-Tabar H, Razzaghi-Abyaneh M. Physicochemical properties, antifungal activity and cytotoxicity of selenium sulfi de nanoparticles green synthesized by saccharomyces cerevisiae. Biochem Biophys Res Commun. 2019 Sep 3;516(4):1078-1084. doi: 10.1016/j.bbrc.2019.07.007. Epub 2019 Jul 4. PMID: 31280861.

Mohammad Mijanur and Md. Asaduzzaman, Anti-cancer potential of South Asian plants, Nat prod bio prospect, 2013; 3(3): 74-88.

Paul, R., Prasad, M., & Sah, N. K. (2011). Anticancer biology of Azadirachta indica L (neem): a mini review. Cancer biology & therapy, 12(6), 467-476.

Ferlay J, Soerjomataram I, Ervik M, et al. GLOBOCAN 2012 v1.0, Cancer incidence and mortality Worldwide: IARC CancerBase No. 11 \[Internet]. Lyon (France): International Agency for Research on Cancer; 2013.

Chaffer CL, Weinberg RA. A perspective on cancer cell metastasis. Science 2011;331:1559–64.

Olson MF, Sahai E. The actin cytoskeleton in cancer cell motility. Clin Exp Metastasis 2009;26:273–87.

Olson MF, Sahai E. The actin cytoskeleton in cancer cell motility. all A. The cytoskeleton and cancer. Cancer Metastasis Rev 2009;28:5–14.Clin Exp Metastasis 2009;26:273–87.

Waclaw B, Bozic I, Pittman ME, Hruban RH, Vogelstein B, Nowak MA. A spatial model predicts that dispersal and cell turnover limit intratumour heterogeneity. Nature 2015;525:261–4.

Dallakyan, S., Olson, A.J. (2015). Small-Molecule Library Screening by Docking with PyRx. In: Hempel, J., Williams, C., Hong, C. (eds) Chemical Biology. Methods in Molecular Biology, vol 1263. Humana Press, New York, NY. https\://doi.org/10.1007/978-1-4939-2269-7\_19

Unbekandt M, Croft DR, Crighton D, Mezna M, McArthur D, McConnell P, et al. A novel small-molecule MRCK inhibitor blocks cancer cell invasion. Cell Commun Signal 2014;12:54.

Ruscetta VM, Seaton TJ, Shakeel A, Vasconcelos SNS, Viirre RD, Adler MJ, Olson MF. Opportunities and Challenges for the Development of MRCK Kinases Inhibitors as Potential Cancer Chemotherapeutics. Cells. 2023 Feb 7;12(4):534. Doi: 10.3390/cells12040534.
