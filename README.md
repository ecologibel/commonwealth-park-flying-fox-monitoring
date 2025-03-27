# **Commonwealth Park flying-fox monitoring**

Here we present the workflows and datasets used in the analyses conducted for the journal article Wilson *et al*. (in prep) "*Hanging in there: the highs and lows of a flying-fox camp in a novel landscape*".

This work was conducted as part of the [Australasian Bat Society's (ABS)](https://www.ausbats.org.au/) flying-fox surveys at [Commonwealth Park](https://www.nca.gov.au/attractions/commonwealth-park#) in the Australian Capital Territory (ACT), on behalf of the [National Capital Authority (NCA)](https://www.nca.gov.au/environment/national-land/conservation-land-management/commonwealth-park-grey-headed-flying-fox).

## Background

Australian flying-foxes (*Pteropus* spp., also known as fruit bats) are the largest flying mammals, and their energy for flight is reliant upon the sugar-rich nectar of native hardwoods, many native seed-heavy fruits and berries, and more recently, introduced species of fruits found in urban backyards and orchards. It is the unique combination of their diet and mobility that makes them keystone species - they serve an ecologically significant role as seed dispersers and pollinators. However their effectiveness is reliant on large populations; so they may cease to function as dispersers long before they become rare. 

Due to substantial decreases in their national populations, the [grey-headed flying-fox (GHFF)](https://australian.museum/learn/animals/bats/grey-headed-flying-fox/) (*Pteropus poliocephalus*) is listed as vulnerable under the Australian [EPBC Act 1999](https://www.dcceew.gov.au/environment/biodiversity/threatened/species/flying-fox-policy-statement#:~:text=The%20grey%2Dheaded%20flying%2Dfox,Act%201999%20(%20EPBC%20Act).), and the [little red flying-fox (LRFF)](https://australian.museum/learn/animals/bats/little-red-flying-fox/) (*Pteropus scapulatus*) is considered stable. For the GHFFs, the national legislation affords threatened species protections and safeguards to prevent a decline in their population.

In the Australian Capital Territory (ACT), [Commonwealth Park](https://www.nca.gov.au/attractions/commonwealth-park#) has been occupied by flying-foxes (FFs) seasonally every year since 2003, and the [Australasian Bat Society Inc](https://www.ausbats.org.au/) (ABS) has been surveying the camp since then. In 2012, the ABS entered into an agreement with the NCA to monitor this camp. Since 2013 the ABS has also been providing quarterly census survey data to the ACT and Commonwealth Governments as part of the [National Flying-fox Monitoring Program](https://www.dcceew.gov.au/environment/biodiversity/threatened/species/flying-fox-monitoring#:~:text=The%20National%20Flying%2Dfox%20Monitoring%20Program%20(NFFMP)%20is%20designed,flying%2Dfoxes%20in%20eastern%20Australia.). The survey methodology is consistent with the [CSIRO Commonwealth Flying-fox census method](http://www.environment.gov.au/biodiversity/threatened/species/pubs/310112-monitoring-methodology.pdf).

## Repository structure

This repository follows an organised structure for clarity and reproducibility:
- `archive`: superseded datasets and workflows 
- `input`: raw and reference datasets (e.g., tables, spatial files) 
- `output`: results from analyses (e.g., tables, plots, maps) 
- `.gitattributes`: repository-specific Git settings 
- `.gitignore`: files to exclude from version control 
- `analyses.Rmd`: R Markdown with analysis workflows 
- `project.Rproj`: RStudio project file for consistent setup 
- `README.md`: project overview and usage guide 
- `tutorial.html`: rendered summary of analyses and results 

## Licence

Unless otherwise stated, all code in this repository is licensed under the MIT License. We kindly ask that you cite the relevant publication(s) or this repos if you reuse or adapt our code.