## Quick links to resources

Below you will find a convenient list of important or relevant websites and resources that are mentioned in this Manual. Links are organized by category.

#### General links and guides {.unnumbered}

* [OBIS home page](https://obis.org/)
* [Darwin Core term OBIS Checklist](checklist.html#darwin-core-term-checklist-for-obis)
* [OBIS FAQ](FAQ.html)
* [OBIS Slack](https://join.slack.com/t/obishq/shared_invite/zt-1yiucrrrq-RZRPU7c4rm7OungiBseWVA)
* [OBIS GitHub helpdesk](https://github.com/iobis/helpdesk)
* [List of OBIS nodes](https://obis.org/about/nodes/)
* `r fontawesome::fa(name="youtube", fill="red")` [OBIS How-To Use & Publish Data YouTube series](https://www.youtube.com/playlist?list=PLlgUwSvpCFS4TS7ZN0fhByj_3EBZ5lXbF): this series covers topics including but not limited to:
  * How to construct [eventIDs](https://www.youtube.com/watch?v=Upt6LPJ0Bn8&list=PLlgUwSvpCFS4TS7ZN0fhByj_3EBZ5lXbF&index=2&t=6s),
  * How to create and format the [Event](https://www.youtube.com/watch?v=jyy6QO_p7v8&list=PLlgUwSvpCFS4TS7ZN0fhByj_3EBZ5lXbF&index=4), [Occurrence](https://www.youtube.com/watch?v=G_AmAmS7ILc&list=PLlgUwSvpCFS4TS7ZN0fhByj_3EBZ5lXbF&index=5), and [eMoF](https://www.youtube.com/watch?v=EjM0HRrF1B4&list=PLlgUwSvpCFS4TS7ZN0fhByj_3EBZ5lXbF&index=6) tables,
  * How to access data from OBIS using the  [Mapper](https://www.youtube.com/watch?v=9PSPEtqgjUI&list=PLlgUwSvpCFS4TS7ZN0fhByj_3EBZ5lXbF&index=11&t=1s) or [R](https://www.youtube.com/watch?v=8Ep4fGICQWU&list=PLlgUwSvpCFS4TS7ZN0fhByj_3EBZ5lXbF&index=12),
  * How to [conduct taxon matching](https://www.youtube.com/watch?v=jJ8nlMlg-cY&list=PLlgUwSvpCFS4TS7ZN0fhByj_3EBZ5lXbF&index=16),
  * How to [quality control check a dataset](https://www.youtube.com/watch?v=sNzipC6-r90&list=PLlgUwSvpCFS4TS7ZN0fhByj_3EBZ5lXbF&index=7),
  * How to [publish data to OBIS using the IPT](https://www.youtube.com/watch?v=i2P8mjo128o&list=PLlgUwSvpCFS4TS7ZN0fhByj_3EBZ5lXbF&index=8)
  * How to [publish an OBIS dataset to GBIF](https://www.youtube.com/watch?v=HciufRG9hiI&list=PLlgUwSvpCFS4TS7ZN0fhByj_3EBZ5lXbF&index=10)
  * How to use the [OBIS MapTool](https://www.youtube.com/watch?v=XM23WEvE364&list=PLlgUwSvpCFS4TS7ZN0fhByj_3EBZ5lXbF&index=14)
* [Darwin Core term Quick Reference Guide](https://dwc.tdwg.org/terms/)
* [Darwin Core text guide](https://dwc.tdwg.org/text/)
* [Publishing DNA-derived data guide](https://docs.gbif.org/publishing-dna-derived-data/en/)
* De Pooter et al. 2017. Toward a new data standard for combined marine biological and environmental datasets - expanding OBIS beyond species occurrences. Biodiversity Data Journal 5: e10989. hdl.handle.net/10.3897/BDJ.5.e10989
* Duncan et al. (2021). A standard approach to structuring classified habitat data using the Darwin Core Extended Measurement or Fact Extension. EMODnet report.  <https://emodnet.ec.europa.eu/en/seabed-habitats-guidance-standard-approach-structuring-classified-habitat-data-using-darwin-core>

#### Data Access & Mapping/Georeferencing Tools {.unnumbered}

* [OBIS Mapper](https://mapper.obis.org/): map-based tool for obtaining OBIS data, allowing various filters to be applied
* [R package robis](https://github.com/iobis/robis)
* [OBIS MapTool](https://obis.org/maptool/#): used for generating WKT strings, georeferencing, etc.
* [Wellknown Text (WKT) visualization](https://wktmap.com/): tool to visualize WKT strings
* [Full OBIS Data export](https://obis.org/data/access/): also includes a list of which fields are appended/modified when data is published to OBIS
* [OBIS API](https://api.obis.org/): API interface, note that the result previews from executing functions are frequently incomplete and only provide the first ~10 results
* [Marine Regions Gazetteer](https://www.marineregions.org/gazetteer.php?p=search): a standard list of geographic names with information and maps; can be used to assist georeferencing, particularly for marine locations
* [Coordinate Conversion Tool](https://obis.shinyapps.io/coordinates): used to convert coordinates from degrees minutes seconds to decimal degrees
* [Getty Thesaurus of Geographic Names](https://www.getty.edu/research/tools/vocabularies/tgn/): search interface for place names

#### Controlled vocabulary {.unnumbered}

* `r fontawesome::fa(name="youtube", fill="red")` [OBIS YouTube Vocabulary series](https://www.youtube.com/playlist?list=PLlgUwSvpCFS4hADB7Slf44V1KJauEU6Ul): this series demonstrates how to use the [vocabulary decision tree](vocabulary#selecting-p01-codes-for-measurementtypeid) in conjunction with the SeaDataNet P01 facet search in order to find/select vocabularies for eMoF measurements
* [SeaDataNet P01 facet search](https://vocab.seadatanet.org/p01-facet-search): recommended interface to search for P01 codes used to populate measurementTypeID field. Note that the free text search is best used by supplying one search term at a time (it does not search the same way we use Google)
* [OBIS GitHub repository for vocabulary](https://github.com/nvs-vocabs/OBISVocabs/issues): use this repository to request new terms for measurements related to OBIS data
* [Darwin Core Basis of Record Vocabulary](https://rs.gbif.org/vocabulary/dwc/basis_of_record_2022-02-02.xml): definitions for terms used to populate basisOfRecord
* [OBIS MoF viewer](https://mof.obis.org/): this tool allows you to search for all measurements or facts published in OBIS, but it **should NOT** be used as reference to select vocabularies. See the [vocabulary](vocabulary.html#map-emof-measurement-identifiers-to-preferred-vocabulary) section of the Manual for additional help
* [MeasurementOrFact statistics summary by Node](https://r.obis.org/mof/): this page provides a summary for each dataset by OBIS node, summarizing the % of missing measurementTypeID, measurementValueID, and measurementUnitIDs
* [NERC Vocabulary Server](https://vocab.nerc.ac.uk/search_nvs/): interface to search through the entire NERC Vocabulary Server to find vocabulary terms. As with the SeaDataNet facet search, the search does not function the same way Google does and you may have to adjust how you search for terms.

#### Tools for Taxonomy & Dates {.unnumbered}

* [WoRMS Taxon match tool](https://www.marinespecies.org/aphia.php?p=match): used to match a list of species names to taxonomic authority and obtain LSIDs for species
* [GBIF Name parser](https://www.gbif.org/tools/name-parser): tool to divide scientific names into their components and to check them against the taxonomic backbone used by GBIF
* [OBIS Guidelines for Historical Data](common_formatissues.html#historical-data)
  * [Chronometric Age Extension](https://chrono.tdwg.org/)
* [Canadensys Date parser](https://data.canadensys.net/tools/dates#:~:text=Use%20this%20tool%20to%20parse,a%20tab%20or%20a%20pipe.): tool to parse dates into component parts

#### Data QC Tools & Links {.unnumbered}

* [List of Quality Checks conducted by OBIS](https://github.com/iobis/obis-qc) on published data
* [List of QC Flags](https://github.com/iobis/obis-qc/blob/master/obisqc/util/flags.py) implemented by OBIS
* [obistools](https://github.com/iobis/obistools) R package for conducting QC checks on OBIS data
* [pyobistools](https://jiasu.xzqcsaa.nyc.mn/cioos-siooc/pyobistools) python package for QC tools
* [LifeWatch & EMODnet Biology QC tool](https://rshiny.lifewatch.be/BioCheck/)
* [Hmisc R package](https://hbiostat.org/r/hmisc/) for summarizing data, useful for checking data quality and outliers

#### Template Tools {.unnumbered}

* GBIF Excel templates: [Event table](https://ipt.gbif.org/manual/en/ipt/latest/sampling-event-data#templates) and [Occurrence table](https://ipt.gbif.org/manual/en/ipt/latest/occurrence-data#templates)
* [Excel to Darwin Core Standard (DwC) Tool](https://zenodo.org/record/6453921#.Y9KsQkHMKmU): a macro Excel spreadsheet for setup, data entry, data validation and file export to DwC (Darwin Core Standard) files. Creates templates for Event, Occurrence, MeasurementsOrFacts, Extended MeasurementsOrFacts (EMoF), and Simple Multimedia tables.
* [Darwin Core Template Generator for Event and Occurrence tables](https://sios-svalbard.org/aen/template-generator/): allows selection of DwC terms to generate template for Event and Occurrence tables, developed by Luke Marsden, & Olaf Schneider

#### Publishing Tools & Links {.unnumbered}

* [Integrated Publishing Toolkit (IPT) User Manual](https://ipt.gbif.org/manual/en/ipt/latest/): manual with more details on how to use the IPT for publishing datasets
* [Ecological Metadata Language (EML) guide](https://eml.ecoinformatics.org/)
  * [EML R package](https://docs.ropensci.org/EML/): assists with creating EML files in R, assumes some existing familiarity with EML
  * [ezEML](https://ezeml.edirepository.org/eml/auth/login): form-like interface for generating EML files. Offers dataset attachment but this is not required to generate the EML. Note that this is also an repository which offers data
  * [Jinja EML template generator](https://jinja.palletsprojects.com/en/3.1.x/): can be used to create tailored EML templates that you can reuse for your datasets. A template may be a good  option for you if there are several EML elements which will not need to be changed each time. Code used is similar to Python
* [Become a  GBIF publisher](https://www.gbif.org/become-a-publisher): crucial step for publishing your dataset to GBIF as well as OBIS
