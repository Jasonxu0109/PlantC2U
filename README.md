# News - PlantC2U

Exploring the cellular landscape of RNA editing from scRNA-seq data in plants. 2024-03-18

#### Xu C<sup>1,2</sup>, Li J<sup>1,2</sup>, Song L-Y<sup>1,2</sup>, Guo Z-J<sup>1</sup>, Song S-W<sup>1</sup>, Zhang L-D<sup>1</sup>, Zheng H-L<sup>1,*</sup>. PlantC2U: Deep learning of cross-species sequence landscapes predict plastid C-to-U RNA editing in plants. (*Journal of Experimental Botany*; Impact Factor 6.9; accepted ) 2024-01-04

In this study, we developed PlantC2U by utilizing a convolutional neural network (CNN) for genome sequence-dependent identification of plastid C-to-U RNA editing sites in plants. PlantC2U achieves over 95% sensitivity and 99% specificity, which outperforms random forest (RF) and support vector machine (SVM). PlantC2U not only further checks RNA editing sites from transcriptome data to reduce the possible false positives, but also assesses the effect of different mutations on C-to-U RNA editing status based on the flanking sequences.

## Requirements


## Dependencies 
* R version >= 4.0.0.
* R packages: keras, tensorflow

The R codes have been tested successfully on Operating systems: 
* Windows 10

RNAeditDB website is online. The web server address is https://jasonxu.shinyapps.io/RNAeditDB/. 2023-04-11

The RNAeditDB coming soon: 2023-4-8

## [Welcome to RNAeditDB](https://jasonxu.shinyapps.io/RNAeditDB/)

RNAeditDB is a database for identification of C-to-U RNA editing sites in the chloroplast of mangrove species

![图片](https://user-images.githubusercontent.com/11934986/230062862-b33636c7-bab6-44d8-8ca3-4c8e5d432339.png)


# Schematic diagram of PlantC2U model construction

![图片](https://user-images.githubusercontent.com/11934986/202233185-023ceb03-5643-4b63-afa4-7d3e949aea9d.png)


![图片](https://user-images.githubusercontent.com/11934986/200177071-788c4956-5d49-4083-a866-f01b25b62f27.png)

# Cite
Please cite the following paper if you used PlantC2U and RNAeditDB in your research.  

Xu C, Li J, Song L-Y, Guo Z-J, Song S-W, Zhang L-D, Zheng H-L. 2024. PlantC2U: Deep learning of cross-species sequence landscapes predict plastid C-to-U RNA editing in plants. Journal of Experimental Botany, erae007.
