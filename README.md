[![](https://quay.io/repository/biocontainers/biobb_io/status)](https://hub.docker.com/r/mmbirb/acpype)
[![](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/3787)
[![](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# ACPYPE container

### Introduction
ACPYPE docker and singularity containers used for [biobb_chemistry](https://github.com/bioexcel/biobb_chemistry) BioExcel Building Blocks modules.

### Docker Use

* Installation:


        docker pull mmbirb/acpype:latest


* Usage:


        docker run mmbirb/acpype:latest <command>

### Singularity Use

* Installation:


        singularity pull --name acpype.sif shub://bioexcel/acpype_container


* Usage:


        singularity exec acpype.sif <command>


### Copyright & Licensing
This software has been developed in the [MMB group](http://mmb.irbbarcelona.org) at the [BSC](http://www.bsc.es/) & [IRB](https://www.irbbarcelona.org/) for the [European BioExcel](http://bioexcel.eu/), funded by the European Commission (EU H2020 [823830](http://cordis.europa.eu/projects/823830), EU H2020 [675728](http://cordis.europa.eu/projects/675728)).

* (c) 2015-2020 [Barcelona Supercomputing Center](https://www.bsc.es/)
* (c) 2015-2020 [Institute for Research in Biomedicine](https://www.irbbarcelona.org/)

Licensed under the
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), see the file LICENSE for details.

### Acknolegements
The singularity container has been built through [singularity hub](https://singularity-hub.org/).

![](https://bioexcel.eu/wp-content/uploads/2019/04/Bioexcell_logo_1080px_transp.png "Bioexcel")
