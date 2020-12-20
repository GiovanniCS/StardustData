# StardustData
In this repository are collected all the datasets discussed in "Stardust: improving spatial tranScripTomics data analysis through space awARe modularity optimization baseD clUSTering."  
The datasets are: Lymph Node, Human Brest Cancer 1, Human Brest Cancer 2, Mouse Kidney and Human Heart.  
For each dataset is included:
* Image of the tissue used in the 10X Visium protocol,
* 2D coordinates of each spot,
* a compressed version of the expression matrix (uncompression is required in order to let Stardust work properly)

Moreover, under directory "Results" is collected all the data used in the method validation (Wilcoxon rank sum statistical test over 100 positional shufllings per dataset). Results subdirectories have been cleaned from unnecessary files.