# BITE
## BITE: BioInformatics Tools for Everyone


Nowadays, molecular data analyses for biodiversity studies often require advanced bioinformatics skills, preventing many life scientists from analysing their own data autonomously. BITE R package provides complete and user-friendly functions to handle SNP data and third-party software results (i.e. Admixture, TreeMix), facilitating their visualization, interpretation and use. Furthermore, BITE implements additional useful procedures, such as representative sampling and bootstrap for TreeMix, filling the gap in existing biodiversity data analysis tools. 

Examples of BITE function outputs from human trial datasets. 
A) Membership coefficients estimated with Admixture software at K= 2, 3, 4, 7 and plotted in curcular fasihion with the membercoef.circos function of BITE;
B) Gene flow analysis using TreeMix. Nodes robustness was estimated with 100 bootstrap replicates and plotted using the treemix.bootstrap function of BITE.
![Fig1_20190924](https://user-images.githubusercontent.com/13908985/65525052-463f7c00-dec5-11e9-88f7-309640394a1d.jpg)


**The BITE manuscript is available at bioxriv.org.** Link to [paper](http://www.biorxiv.org/content/early/2017/08/29/181610) & [doi](https://doi.org/10.1101/181610 )



### Instructions
The package could be installed from source in R. 
The necessary dependencies are below reported. 

**Faster method (using devtools)**
```{r, results='hide'}
# install devtools
install.packages("devtools")

# install BiocManager (if necessary)
if (!require("BiocManager", quietly = TRUE))
  install.packages("BiocManager")

# install SNPRelate using BiocManager
BiocManager::install("SNPRelate")

# load devtools
library(devtools)

# install BITE V2 from source
devtools::install_local("BITEV2_2.1.2.tar.gz")
```

#### Dependencies
* SNPRelate >= 1.32.2 
* ggplot2 >= 3.4.2
* gridExtra >= 2.3
* stringr >= 1.5.0
* shiny >= 1.7.4.1
* dplyr >= 1.1.2
* plotly >= 4.10.2
* ggrepel >= 0.9.3
* data.table >= 1.14.8
* RCircos >= 1.2.2
* OptM >= 0.1.6
* poolfstat >= 2.1.2
* RColorBrewer >= 1.1-3

### How to cite
Milanesi M., Litta P., Vajana E., Somenzi E., Bomba L., Pietrucci D., Ajmone-Marsan P., Chillemi G., Capomaccio S., Colli L., 2017. BITE: an R package for biodiversity analyses. bioRxiv 181610. doi:10.1101/181610

### Maintainers contacts
* Marco Milanesi <marco.milanesi.mm@gmail.com>
* Paolo Litta <paolo.litta.pl@gmail.com>
* Stefano Capomaccio <capemaster@gmail.com>
* Elia Vajana <vajana.elia@gmail.com>
* Lorenzo Bomba <lory.bomb@gmail.com>

