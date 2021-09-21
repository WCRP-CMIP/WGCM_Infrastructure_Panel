---
title: CMOR and MIP tables 
rank: 9
---
# CMOR and MIP tables

*Note that this page is a work in progress and [suggestions for improvement/additions are welcome](https://github.com/WCRP-CMIP/WGCM_Infrastructure_Panel/issues)*

## CMOR & CMOR Prepare

The Climate Model Output Rewriter (CMOR) is a library of tools for writing standards compliant data for publication to projects such as CMIP6. It provides interfaces in C, Fortran 90 and Python.

 * [CMOR 3 home](https://cmor.llnl.gov/)
 * [CMOR 3 Github](https://github.com/PCMDI/CMOR)

CMOR PrePARE is a command line tool that can be used to validate a set of prepared files against a set of MIP tables/CVs and should ideally be used as part of ESGF publication. See [here](https://cmor.llnl.gov/mydoc_cmip6_validator/) for further information.

## MIP Tables for CMOR3

CMOR3 uses a set of JSON files including an aggregation of the Controlled Vocabularies and "MIP tables", which define the structure and metadata for each variable. 
MIP tables are produced from each version of the CMIP6 data request and the Controlled Vocabularies file at the HEAD of the repository master is updated each time a change is made to the CMIP6 Controlled Vocabularies.

 * [CMIP6 MIP tables & CVs](https://github.com/PCMDI/cmip6-cmor-tables)
 * [Input4MIPs](https://github.com/PCMDI/input4MIPs-cmor-tables)
 * [obs4MIPs](https://github.com/PCMDI/obs4MIPs-cmor-tables)
 * [PCMDIobs ](https://github.com/PCMDI/PCMDIobs-cmor-tables)

## CMOR 2/1 MIP Tables

Prior to CMOR 3 a standardised text format was used for the MIP tables 

And those that work with CMOR2/1 (standard text format)
 * [cmip5-cmor-tables](https://github.com/PCMDI/cmip5-cmor-tables/)
 * [cmip3-cmor-tables](https://github.com/PCMDI/cmip3-cmor-tables/)
 * [cordex-cmor-tables](https://github.com/PCMDI/cordex-cmor-tables)
 * [ana4MIPs-cmor-tables](https://github.com/PCMDI/ana4MIPs-cmor-tables)
 * [c-lamp1-cmor-tables](https://github.com/PCMDI/c-lamp1-cmor-tables)
 * [cfmip1-cmor-tables](https://github.com/PCMDI/cfmip1-cmor-tables)
 * [iaemip1-cmor-tables](https://github.com/PCMDI/iaemip1-cmor-tables)
 * [geomip-cmor-tables](https://github.com/PCMDI/geomip-cmor-tables)
 * [lucid-cmor-tables](https://github.com/PCMDI/lucid-cmor-tables)
 * [pmip3-cmor-tables](https://github.com/PCMDI/pmip3-cmor-tables)

## MIP tables for non-WCRP projects

 * [PRIMAVERA](https://github.com/PRIMAVERA-H2020/cmip6-cmor-tables)

