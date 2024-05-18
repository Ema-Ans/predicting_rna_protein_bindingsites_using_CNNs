# predicting_rna_protein_bindingsites_using_CNNs

CMU-Q; eansar@andrew.cmu.edu 5
CMU-Q; szewil@andrew.cmu.edu 6

# Abstract: 
RNA-binding proteins (RBPs) play a crucial role in a range of cellular processes, includ- 7
ing RNA splicing, stabilization, and localization, by binding to specific RNA sequences or struc- 8
tures. The identification of RNA-protein binding sites is key to understanding gene expression 9
regulation and has traditionally relied on labor-intensive experimental methods. Given the scala- 10
bility challenges of such methods, computational models, notably deep learning techniques, have 11
emerged as promising alternatives. However, so far these techniques have only used global se- 12
quences of RNAs. Local sequences are also known to have a great biological significance in the 13
RNA-protein interactions, as they are integral in determining the specificity of binding sites, thus 14
enriching our understanding of protein-RNA affinities. Our work propels the integration of both 15
local and global convolutional neural networks (CNNs) to discern structural attributes of RNA, 16
facilitating a comprehensive analysis of RNA-protein interactions. Utilizing the CLIP-seq 17
(Cross-linking and Immunoprecipitation) dataset RBP-24, which focuses on subsequence-level 18
RNA-protein interactions, wherein proteins selectively interact with distinct regions or sequences 19
embedded within extensive RNA molecules. This approach aims to enhance the accuracy of RNA 20
binding sites predictions by integrating local and global RNA sequences. The potential outcomes of 21
this research span from novel insights into disease mechanisms and drug discovery to a better 22
understanding of gene regulation, ultimately contributing to the advancement of molecular biol- 23
ogy and its applications in health and disease treatment. From our results, we see that our ap- 24
proach does enhance predictive when compared with using just the global or local CNNs on their 25
own. 

# References:
1. Maticzka, D. et al. (2014) ‘GraphProt: Modeling binding preferences of RNA-binding proteins’, Genome Biology, 15(1). 204
doi:10.1186/gb-2014-15-1-r17. Author 1, A.; Author 2, B. Title of the chapter. In Book Title, 2nd ed.; Editor 1, A., Editor 2, B., Eds.; 205
Publisher: Publisher Location, Country, 2007; Volume 3, pp. 154–196. 206
2. Alipanahi, B. et al. (2015) ‘Predicting the sequence specificities of DNA- and RNA-binding proteins by deep learning’, Nature 207
Biotechnology, 33(8), pp. 831–838. doi:10.1038/nbt.3300. Author 1, A.B.; Author 2, C. Title of Unpublished Work. Abbreviated 208
Journal Name year, phrase indicating stage of publication (submitted; accepted; in press). 209
3. Pan, X. and Shen, H.-B. (2018) ‘Predicting RNA–protein binding sites and motifs through combining local and global deep 210
convolutional Neural Networks’, Bioinformatics, 34(20), pp. 3427–3436. doi:10.1093/bioinformatics/bty364. 211
4. GraphProt - modeling binding preferences of RNA-binding proteins (no date) Bioinformatics Group Freiburg - GraphProt - 212
modeling binding preferences of RNA-binding proteins. Available at: http://www.bioinf.uni-freiburg.de/Software/GraphProt 213
5. Quang, D. and Xie, X. (2016) ‘DanQ: A hybrid convolutional and recurrent deep neural network for quantifying the function of 214
DNA sequences’, Nucleic Acids Research, 44(11). doi:10.1093/nar/gkw226. 215
6. Zhou, J. and Troyanskaya, O.G. (2015) ‘Predicting effects of noncoding variants with deep learning–based sequence model’, 216
Nature Methods, 12(10), pp. 931–934. doi:10.1038/nmeth.3547. Disclaimer/Publisher’s Note: The statements, opinions and 217
data contained in all publications are solely those of the individual author(s) and contributor(s) and not of MDPI and/or the 218
editor(s). MDPI and/or the editor(s) disclaim responsibility for any injury to people or property resulting from any ideas, 219
methods, instructions or products referred to in the content.
