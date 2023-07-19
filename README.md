# Lessons for an Invisible Future - Data Files and Analysis Scripts

This repository holds the data files and analysis scripts used for the case studies in the paper:

Barton, C Michael, Emili Aura-Tortosa, Oreto Garcia-Puchol, Julien Riel-Salvatore, and Isaac Ullah, 2023. Lessons for an Invisible Future from an Invisible Past: Risk and Resilience in Deep Time. _The Holocene_, In press.

The data and script are copyrighted (c) 2023 by C Michael Barton, Arizona State University. They are openly available for reuse under an MIT license.
See the CITATION.cff file for this repository for proper citation.

## Data Files:
CSV format. All data in Unicode UTF-8 character set. Quotes around long strings that may contain comma delimter.
* __c14dates.csv__: Radiocarbon dates from the western Mediterranean, updated from those used in the following paper:
  * Barton, C.M., Aura Tortosa, J.E., Garcia-Puchol, O., Riel-Salvatore, J.G., Gauthier, N., Vadillo Conesa, M., Pothier Bouchard, G., 2018. Risk and resilience in the late glacial: a case study from the western Mediterranean. _Quaternary Science Reviews_ 184, 68–84. https://doi.org/10.1016/j.quascirev.2017.09.015
* __Hominin_demography.csv__ and __Hominin_demography_trajectories.csv__: Output of agent based modeling experiments also described in the following paper:
  * Barton, C.M., Riel-Salvatore, J., 2012. Agents of change: modeling biocultural evolution in Upper Pleistocene western Eurasia. _Advances in Complex Systems_ 15, 1150003-1-1150003–24. https://doi.org/10.1142/S0219525911003359
* __icecores.csv__: Data from GRIP and GISP ice cores published by:
  * Rasmussen, S.O., Seierstad, I.K., Andersen, K.K., Bigler, M., Dahl-Jensen, D., Johnsen, S.J., 2008. Synchronization of the NGRIP, GRIP, and GISP2 ice cores across MIS 2 and palaeoclimatic implications. _Quaternary Science Reviews_ 27, 18–28. https://doi.org/10.1016/j.quascirev.2007.01.016

## R Scripts
* __RRDT.Rmd__: RMarkdown script (using R version 4.2.3) used to generate figures and analyses from the data files in this repository
* __RRDT.nb.html__: HTML Notebook output of the RRDT.Rmd RMarkdown for quick reference to the work
