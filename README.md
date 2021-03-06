# serghiouTemplates

<div align="justify">
 
An R Markdown template that combines all templates I use and all of my pre-defined code to avoid retyping a banch of code all the time. Excited to hear about any ideas/feedback about what could be done better! 

Please reference the repository if you happen to use it :)

## Install

```{r}
library(devtools); install_github(serghiou/serghiouTemplates)
```

This is not a fully  blown package yet, so you'll have to manually install some basic dependencies using the code below.

```{r}
packages <- c("prettydoc", "tufte", "rmdformats", "epuRate"); install.packages(packages)
```


## Use

```{r}
library(serghiouTemplates)
```

## Customize

If you fork this repo (top right-hand corner), you can change the original template however you please to create your own template with your own preferences. Ideally, this would be part of the package, but at the moment there is no bandwidth to work on this.


## Other

You may enjoy a list of my favorite resources and packages for R [here](serghiou/best-of-r) (feel free to recommend packages that you do not see, but you strongly feel that you should!).


## Acknowledgements

This package would have not been possible without the great work of the community that went through the effort of creating the packages on which this meta-template depends and their dedication to open source.

</div>
