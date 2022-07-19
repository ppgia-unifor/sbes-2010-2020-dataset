# SBES 2010 - 2020 language and citations dataset

This dataset is availanle as a [csv file](sbes-2010-2020-dataset.csv). It contains the language and citation data for all the papers published in the Research Track of the Brazilian Symposium on Software Engineering (SBES) from 2010 to 2020. The dataset was created in March 2022 by semi-automatically collecting, verifying and classifying SBES publication and citation data from dblp and Google Scholar, respectively. Please note the any pertinent citation data made available by Google Scholar after that date is NOT included in the dataset.

The dataset contains the following data items:

Data item | Description
--- | ---
*year* | Year of publication
*paper_id* | Unique paper identification
*paper_title* | Paper title
*paper_authors* | List of the paper's authors
*paper_language* | Paper's language of publication
*citation_id* | Unique citation identification
*citation_info* | Citation's authors, title, and publication venue
*citation_year* | Citation's year of publication
*citation_validity* | Citation validity label (possible values are `valid` and `invalid`)
*citation_origin* | Citation origin label (possible values are `self`, `community_nat` and `community_int`)
*citation_type* | Citation type label (possible values are `conference`, `journal`, `msc_phd`, `pre_print`, and `other`)
*citation_scope* | Citation scope label (possible values are `national_sbes`, `national_other`, and `international`)
*citation_longevity* | Number of years between the publication of the cited paper and the publication of the citation (only computed for valid citations)
