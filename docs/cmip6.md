---
title: CMIP6 information 
rank: 2
---
# CMIP6 Technical information

*Note that this page is a work in progress and [suggestions for improvement/additions are welcome](https://github.com/WCRP-CMIP/WGCM_Infrastructure_Panel/issues)*

This page provides links to technical and scientific information about CMIP6

## CMIP6 Science definition

* [Overview of CMIP6, Eyring et al. (2016)](https://gmd.copernicus.org/articles/9/1937/2016/)
* [GMD Special issue on CMIP6 design](https://gmd.copernicus.org/articles/special_issue590.html): Presents papers on each of the MIPs
* [WCRP: Description of each CMIP6 MIP](https://www.wcrp-climate.org/modelling-wgcm-mip-catalogue/modelling-wgcm-cmip6-endorsed-mips)


## AR6 data information

* [AR6_WG1_priority_variables_Public_v1.0](https://docs.google.com/spreadsheets/d/1H2qXofwjOpCospDcj9LRokpz0HGysRcDK2HmNSJoqyk)
* [CMIP6 aerosols & land](https://docs.google.com/spreadsheets/d/1y91pk_18aFcKVt5kFelNZHHupCaeyJFh3r5QKWL8EPI)

## CMIP6 Guidance

* [PCMDI Guidance for modellers](https://pcmdi.llnl.gov/CMIP6/Guide/modelers.html)
* [PCMDI Guidance for data managers](https://pcmdi.llnl.gov/CMIP6/Guide/dataManagers.html)
* [PCMDI Guidance for data users](https://pcmdi.llnl.gov/CMIP6/Guide/dataUsers.html)
* [CMIP6 Controlled Vocabularies](https://github.com/WCRP-CMIP/CMIP6_CVs)
   * [CMIP6 Experiment ID table](https://wcrp-cmip.github.io/CMIP6_CVs/docs/CMIP6_experiment_id.html)
   * [CMIP6 Institution ID table](https://wcrp-cmip.github.io/CMIP6_CVs/docs/CMIP6_institution_id.html)
   * [CMIP6 Source ID (model name) table](https://wcrp-cmip.github.io/CMIP6_CVs/docs/CMIP6_source_id.html)
* [CMIP6 Global attributes description](http://goo.gl/v1drZl)

## Data availability and summary information

* [Data holdings summary](https://pcmdi.llnl.gov/CMIP6/ArchiveStatistics/esgf_data_holdings/)
* ESGF data usage and publication metrics:
  * [Model and institute summary](http://esgf-ui.cmcc.it/esgf-dashboard-ui/data-archiveCMIP6.html)
  * [Data usage metrics](http://esgf-ui.cmcc.it/esgf-dashboard-ui/cmip6.html)
  * [ESGF wide statistics](http://esgf-ui.cmcc.it/esgf-dashboard-ui/federated-view.html)
* [ES-Doc CMIP6 Errata system](https://errata.es-doc.org)

## ESGF search indices

* [USA, PCMDI/LLNL](https://esgf-node.llnl.gov/projects/cmip6/)
* [France, IPSL](https://esgf-node.ipsl.upmc.fr/projects/cmip6-ipsl/)
* [Germany, DKRZ](https://esgf-data.dkrz.de/projects/cmip6-dkrz/)
* [UK, CEDA](https://esgf-index1.ceda.ac.uk/projects/cmip6-ceda/)

## CMIP6 Data Request

The CMIP6 data request defines all the quantities from CMIP6 simulations that should be archived. 
This includes both quantities of general interest needed from most of the CMIP6-endorsed model intercomparison projects (MIPs) and quantities that are more specialized and only of interest to a single endorsed MIP. 
The complexity of the data request has increased from the early days of model intercomparisons, as has the data volume. 
In contrast with CMIP5, CMIP6 requires distinct sets of highly tailored variables to be saved from each of the more than 300 experiments. 

For full details see the [CMIP6 data request page]({{ site.baseurl }}{% link CMIP6/data_request.md %})

## CMOR

The Climate Model Output Rewriter (CMOR) is a library of tools for writing standards compliant data for publication to projects such as CMIP6. It provides interfaces in C, Fortran 90 and Python. 
For information on CMOR and associated MIP tables see the [CMOR and MIP tables]({% link cmor_and_mip_tables.md %}) page.

## ES-Doc

ES-Doc provides a number of services to CMIP6 participants and data users;

 * [ES-Doc Home](https://es-doc.org)
 * [Experiment descriptions](https://search.es-doc.org/) (select document type = Experiment)
    * Descriptions of the requirements of a given experiment and forcing data required
 * [Model descriptions](https://explore.es-doc.org/) or [here](https://search.es-doc.org/) (select document type = model):
    * These documents describe the scientific configuration of models used for CMIP6
 * [Errata Service](https://errata.es-doc.org): 
    * The ES-Doc Errata service allows data owners<sup>1</sup> to document issues with published data and to document why multiple versions exist on ESGF (e.g. extension of a dataset)
    * [ES-Doc errata client documentation](https://es-doc.github.io/esdoc-errata-client/)


<sup>1</sup>This service is due to be extended in late 2021 to allow data users to post errata.

## Citation services

To be updated

[//]: # From the ESGF search results the citation information for a particular dataset provides a set of information along with the DOI and a link to the citation search landing page. 
[//]: # For example, a [search](http://esgf-node.llnl.gov/search/cmip6/?mip_era=CMIP6&activity_id=CMIP&institution_id=MOHC&source_id=UKESM1-0-LL&experiment_id=amip) for UKESM1-0-LL amip simulation data will return a DOI of [doi:10.22033/ESGF/CMIP6.5857](https://doi.org/10.22033/ESGF/CMIP6.5857) which resolves to the corresponding page in the citation service. 
[//]: # From the `Related data` section of that page, selecting `MOHC UKESM1.0-LL model output prepared for CMIP6 CMIP` and clicking on `Show` leads to the citation page for [all DECK (CMIP) MOHC UKESM1-0-LL data with DOI doi:10.22033/ESGF/CMIP6.5857](https://doi.org/10.22033/ESGF/CMIP6.5857).

## Persistent Identifiers

Each file published is required to have a unique ``tracking_id`` as a global attribute. 
These IDs can be found from the `PID` section of the ESGF search results, e.g. `hdl:21.14100/b0857338-4f4d-3ac3-8d5e-6ded5b8894d3` and can be resolved via <http://hdl.handle.net/> to give information on where the corresponding file / data set can be found.

## CMIP6 Publication hub

Authors can find and add references to papers using CMIP6 data via the [Publication hub](https://cmip-publications.llnl.gov/view/CMIP6/).


