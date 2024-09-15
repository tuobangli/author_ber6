Infer metabolic velocities from moment differences of molecular weight distributions

submit to PNAS


Metabolic pathways are fundamental maps in biochemistry that detail how molecules are transformed through various reactions. The complexity of metabolic network, where a single compound can play a part in multiple pathways, poses a challenge in inferring metabolic balance changes over time or after different treatments. Isotopic labeling experiment is the standard method to infer metabolic flux, which is currently defined as the flow of a metabolite through a given pathway over time. However, there is still no way to accurately infer the metabolic balance changes after different treatments in an experiment. This study introduces a different concept: molecular weight distribution, which is the empirical distribution of the molecular weights of all metabolites of interest. By estimating the differences of the location and scale estimates of these distributions, it becomes possible to infer the metabolic direction changes with magnitudes even without requiring knowledge of the exact chemical structures of these compounds and their related pathways. This research article provides a mathematical framing for a classic biological concept.

Metabolic pathways consist of enzyme-mediated biochemical reactions that are commonly categorized into two main processes within a living organism: biosynthesis (known as anabolism) and breakdown (known as catabolism) of molecules. Since the discovery of zymase by Buchner and Rapp in 1897 \cite{Eduard} and urea cycle by Krebs and Henseleit in 1932 \cite{Krebs_Henseleit_1932}, a vast body of metabolic pathway knowledge has grown over the last centuries, especially aided by the development of analytical techniques such as chromatography, NMR and mass spectrometry. It is common to compare the concentration changes of compounds in the same metabolic pathway in two groups of samples, i.e., up or down-regulation of a certain pathway. The definitions of these up-regulation and down-regulation are actually completely copied from the principle of chemical equilibrium shift, in which the equilibrium moves from left to right. For example, the overall equation of the urea cycle can be simplified as $2 \textbf{NH}_3 + \textbf{CO}_2 + 3 \textbf{ATP} + 3 \textbf{H}_2\textbf{O} \rightarrow \textbf{urea} + 2 \textbf{ADP}  + 4 \textbf{Pi} + \textbf{AMP}$. Traditionally, if the concentration of urea or ADP or Pi or AMP of samples of experimental group is higher than that of samples in the control group, and the concentration of ammonia or carbon dioxide or ATP is lower than that of samples of the control group, biochemists would say that the urea cycle is up-regulated. This definition is from the irreversible nature of this cycle and analogous to the equilibrium shift in chemistry. Since the urea cycle is a synthetic reaction, it is sometimes said that the anabolic process is dominant. On the contrary, if it is down-regulated and the catabolic process is dominant. 

However, this definition is flawed. Even the comparison is within the same individuals over time, as one compound can be part of several pathways, the change in the amount of certain compounds cannot conclusively determine the metabolic direction of a specific pathway. For example, although urea is a product of the urea cycle, it can also be a product of other metabolic pathways, e.g., arginine, as a nitrogen-containing amino acid, can be converted into L-ornithine and urea under the catalysis of L-arginine amidinohydrolase. In addition, urea is also the starting material for many metabolic pathways. For example, it can be directly eliminated from the body, converted into carbon dioxide, and can also be synthesized into allophanic acid. This means that if the urea concentration of the experimental group increases, there are several possibilities, maybe the metabolic pathway from arginine to ornithine is actually up-regulated, or maybe these downstream reactions are blocked for some reason in the experimental group of samples. 

In practice, it is usually necessary to manually compare the concentration changes of multiple compounds before drawing a conclusion about the changes of metabolic direction, but such a conclusion is still unclear. 
