# HerpesDRG-DB

A database of herpesvirus antiviral drug resistance mutations. 
 Part of the [HerpesDRG](https://www.biorxiv.org/content/10.1101/2020.05.15.097907v2) resource.


### Content
This repository simply contains this README, a LICENSE and the database in tab separated format.

The database contains the link between:
- a mutation
    - in a gene
    - from a virus
    - with a strain name
- to the fold-change in sensitivity it provides
    - compared to a reference strain
    - against one or several antiviral drugs
- as reported in a peer-reviewed article
    - that used a certain assay
    - that can be found with this doi
- with accomodating notes & metadata

If you wish to use this database outside of the the HerpesDRG R package, it is important you filter for rows where the column "status" == "A" ( for active).




### Contributing

We see this as a resource that should be openly discussed and maintained, therefore we encourage researchers to propose changes or additions. Please do so by starting an issue, then either submitting a pull request linked to the issue or describing the changes you want made.


### Getting help

If you have any questions either:
 - Start a GitHub issue using the Issue tab above. This initiates an open discussion
 - E-mail [Oscar Charles](oscar.charles.18@ucl.ac.uk)
