<h1 style="font-weight:normal" align="center">
  &nbsp;“Hands–On Data Visualization with ggplot2”&nbsp;
</h1>

<div align="center">

&nbsp;&nbsp;&nbsp;
<a href="https://www-cedricscherer.com"><img border="0" alt="Blog" src="https://assets.dryicons.com/uploads/icon/svg/4926/home.svg" width="35" height="35"></a>&nbsp;&nbsp;&nbsp;
<a href="mailto:info@data-vizard.com"><img border="0" alt="Email" src="https://assets.dryicons.com/uploads/icon/svg/8009/02dc3a5c-6504-4347-85fb-3f510cfecc45.svg" width="35" height="35"></a>&nbsp;&nbsp;&nbsp;
<a href="https://twitter.com/CedScherer"><img border="0" alt="Twitter" src="https://assets.dryicons.com/uploads/icon/svg/8385/c23f7ffc-ca8d-4246-8978-ce9f6d5bcc99.svg" width="35" height="35"></a>&nbsp;&nbsp;&nbsp; 
<a href="https://www.instagram.com/cedscherer/"><img border="0" alt="Instagram" src="https://assets.dryicons.com/uploads/icon/svg/8330/62263227-bb78-4b42-a9a9-e222e0cc7b97.svg" width="35" height="35"></a>&nbsp;&nbsp;&nbsp;
<a href="https://www.behance.net/cedscherer"><img border="0" alt="Behance" src="https://assets.dryicons.com/uploads/icon/svg/8264/04073ce3-5b98-4f32-88d3-82b2ef828066.svg" width="35" height="35"></a>&nbsp;&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/cedricpscherer/"><img border="0" alt="LinkedIn" src="https://assets.dryicons.com/uploads/icon/svg/8337/a347cd89-1662-4421-be90-58e5e8004eae.svg" width="35" height="35"></a>&nbsp;&nbsp;&nbsp;
<a href="https://www.buymeacoffee.com/z3tt"><img border="0" alt="BuyMeACoffee" src="https://www.buymeacoffee.com/assets/img/guidelines/logo-mark-3.svg" width="35" height="35"></a>&nbsp;&nbsp;&nbsp;

</div>
<br>

### Material for the Pearson Live Training Session for O’Reilly

To get a copy of all the material, clone this repository to a directory of your choice.  
If you are not familiar how to clone a repository, have a look [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository) or download and unpack [this zip folder](https://github.com/z3tt/hands-on-ggplot2-training/archive/refs/heads/main.zip).  
  
To run any of the materials locally on your own machine, you will need the following:

#### Installation

- A recent version of **R** (download from [here](https://cloud.r-project.org/)) 
- A recent version of **RStudio**, (download from [here](https://rstudio.com/products/rstudio/download/#download))
- The following R packages:
  + [`tidyverse`](https://www.tidyverse.org/) (includes [`ggplot2`](https://ggplot2.tidyverse.org/))
  + [`cowplot`](https://wilkelab.org/cowplot/index.html)
  + [`ggforce`](https://ggforce.data-imaginist.com/)
  + [`ggrepel`](https://ggrepel.slowkow.com/)
  + [`ggtext`](https://wilkelab.org/ggtext/)
  + [`magick`](https://docs.ropensci.org/magick/)
  + [`patchwork`](https://patchwork.data-imaginist.com/)
  + [`ragg`](https://ragg.r-lib.org/)
  + [`rnaturalearth`](https://docs.ropensci.org/rnaturalearth/)
  + [`sf`](https://r-spatial.github.io/sf/)

You can install all required R packages at once by running the following code in the R command line:

```{r install, eval=FALSE, echo=TRUE}
# Package names
packages <- c("tidyverse", "cowplot", "ggforce", "ggrepel", "ggtext", "magick", "patchwork", "ragg", "rnaturalearth", "sf")
install.packages(packages)
```

To run the code, open up Rstudio. Copy–paste the code in the **console pane** and hit enter. Several messages should pop up. Scan these messages that are returned for errors and troubleshoot them if necessary. Warnings and other informational messages can be ignored.

#### Starting with the Training

Double-click on the `hands-on-ggplot2.Rproj` file. Rstudio opens up with the working directory set to the same folder (where the Rproj file is placed). Now, you can open any script from the files pane—we start with `01-grammar.Rmd`.
