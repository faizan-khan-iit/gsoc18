# Google Summer of Code 2018: Animint2
Project Summary Report


##### Organization: [R Project for Statistical Computing](https://github.com/rstats-gsoc)

##### Student: [Vivek Kumar](https://github.com/vivekktiwari)

##### Mentors: [Toby Dylan Hocking](https://github.com/tdhock) and [Faizan Khan](https://github.com/faizan-khan-iit)

------------------------------------

### Abstract
`animint2` is an R library that allows you to create interactive and animated multi-layer, multi-plot data visualizations designed with ggplot2. `animint2` renders using javascript library D3.js. It helps in understanding patterns in large and multi-variate datasets. The aim of the project was to document, render, debug the already exsiting `animint2` which the latest version of `animint` 

------------------------------------

### Introduction
The initial motive behind this GSoC project was to translate Animint Designer Manual to animint2 code, and create additional chapters to further document animint2 usage. The objective was to compile a designer manual for animint2 package that will outline different function, resolve issues and guide user to the package. So far there was no proper equivalent documentation to animint2. This was to be the official documentation on animint2 package of R Language. The `ggplot2` dependency has been a major issue as `animint2` is dependent on it. Further work done by past contributors reduced the dependency which resulted in two separate packages `ggplot2Animint` and `animint2`. `ggplot2Animint` is `animint2` specific package used to support the changes needed which were not accepted earlier. As we moved long in the project, movtive changed to continue the work on `animint2` done by fellow contributors and make package ready for CRAN submissions.

------------------------------------

### First Evaluation
During the first evaluation, major work involved cleaning the `animint2` code and documentation for making it ready for cran submission. (animint2 issue [#12](https://github.com/tdhock/animint2/issues/12)). This included removing outdated package version, declaring global variable, parameters and basic documentation. As we moved forward, it was decided to first clean `ggplot2Animint` code and internals first on which `animint2` is dependent. It was planned to submit both packages for cran. The further work on cleaning `ggplot2Animint` was done on [cran branch of faizan khan's rep of forked ggplot2](https://github.com/faizan-khan-iit/ggplot2/tree/cran).

------------------------------------

### Second Evaluation
After cleaning `ggplot2Animint` code for cran submission, we started testing using the package with different packages including `ggplot2` which resulted in failed testcases (Issue [#4](https://github.com/faizan-khan-iit/ggplot2/issues/4)).



------------------------------------

### Final Evaluation

```
# Older syntax

# New syntax
```


------------------------------------

### Link to commits
The links to all the commits are given below:

------------------------------------

### Future Work

