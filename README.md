![](http://www.r-pkg.org/badges/version-ago/SteinerNet)
![](http://cranlogs.r-pkg.org/badges/grand-total/SteinerNet)

The Steiner Tree Approach refers to a method used in graph theory and network design to find the most efficient way to connect a set of points (nodes), potentially using extra intermediate points (called Steiner points) to minimize the total connection cost.


# SteinerNet V2
This is the library of SteinerNet for R. 

Steiner Tree Approach for Graph Analysis

This library is made in the R programming language. 

This version of SteirNet (v2) works with igraph.

### Older versions
older versions of SteirNet up to (v1.3) work with igraph0.

## Installation
### Versions > 3.0.0
To get the latest version of the package and install it from CRAN run the following command:

```
install.packages("SteinerNet")
```

Version 3 and above is maintained here: [https://github.com/cran/SteinerNet](https://github.com/cran/SteinerNet)

### SteinerNet V2

To use this library, these libraries need to be included:
### RBGL http://www.bioconductor.org/packages/release/bioc/html/RBGL.html

For that run: 
```
source("https://bioconductor.org/biocLite.R")

biocLite("RBGL")
```

### igraph  https://cran.r-project.org/web/packages/igraph/index.html

```
install.packages("igraph")
```

##### igraph0 for versions upto 1.7 

Download and manually install the latest version from here https://cran.r-project.org/src/contrib/Archive/igraph0/igraph0_0.5.7.tar.gz

### limma http://bioconductor.org/packages/release/bioc/html/limma.html

For that run: 
```
source("https://bioconductor.org/biocLite.R")

biocLite("limma")
```
## Version History on Cran
```
https://cran.r-project.org/src/contrib/Archive/SteinerNet/
```

# Citation
To use this package in your work, cite this article as:

```
@article{sadeghi2013steiner,
  title={Steiner tree methods for optimal sub-network identification: an empirical study},
  author={Sadeghi, Afshin and Fr{\"o}hlich, Holger},
  journal={BMC bioinformatics},
  volume={14},
  pages={1--19},
  year={2013},
  publisher={Springer},
  doi = {https://doi.org/10.1186/1471-2105-14-144}
}
```

