# BITE
## BITE: BioInformatics Tools for Everyone


Nowadays, molecular data analyses for biodiversity studies often require advanced bioinformatics skills, preventing many life scientists from analysing their own data autonomously. BITE R package provides complete and user-friendly functions to handle SNP data and third-party software results (i.e. Admixture, TreeMix), facilitating their visualization, interpretation and use. Furthermore, BITE implements additional useful procedures, such as representative sampling and bootstrap for TreeMix, filling the gap in existing biodiversity data analysis tools. 

Examples of BITE function outputs from human trial datasets. 
A) Membership coefficients estimated with Admixture software at K= 2, 3, 4, 7 and plotted in curcular fasihion with the membercoef.circos function of BITE;
B) Gene flow analysis using TreeMix. Nodes robustness was estimated with 100 bootstrap replicates and plotted using the treemix.bootstrap function of BITE.
![Figure 1](https://user-images.githubusercontent.com/13908985/31124928-e2e11dfc-a81c-11e7-9b5c-738a7ad61e51.jpg)


**The BITE manuscript is available at bioxriv.org.** Link to [paper](http://www.biorxiv.org/content/early/2017/08/29/181610) & [doi](https://doi.org/10.1101/181610 )



### Instructions
The package could be installed from source in R. 
The necessary dependencies are below reported. 

#### Dependencies
 * RCircos (== 1.1.3)
 * reshape2 (>= 1.4)
 * RColorBrewer (>= 1.1)
 * GenABEL (>= 1.8-0)
 * car (>= 2.1-2)

#####Trouble in installation
 * RCircos: you can find the correct version of the package [here](https://cran.r-project.org/src/contrib/Archive/RCircos/RCircos_1.1.3.tar.gz)
 * GenABEL was archived on 2018-05-25, as [here](https://cran.r-project.org/web/packages/GenABEL/index.html) reported. However, you can istall the last available version of GenABEL following the istruction [here](https://www.reddit.com/r/rprogramming/comments/98xxna/where_to_find_dependencies_for_archived_package/) reported.



### How to cite
Milanesi, M., Capomaccio, S., Vajana, E., Bomba, L., Garcia, J.F., Ajmone-Marsan, P., Colli, L., 2017. BITE: an R package for biodiversity analyses. bioRxiv 181610. doi:10.1101/181610



### Maintainers contacts
* Marco Milanesi <marco.milanesi.mm@gmail.com>
* Stefano Capomaccio <capemaster@gmail.com>
* Elia Vajana <vajana.elia@gmail.com>
* Lorenzo Bomba <lory.bomb@gmail.com>

