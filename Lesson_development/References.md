# Annotated open literature guide

Interoperability in Climate and Atmospheric Sciences — curated 16 October 2026.

This list separates **open-access papers**, **official specifications**, **free online books**, and **tutorials**. All entries have free-to-read pages; do not assume that all have licences allowing copies to be redistributed.

Read **Essential** sources first, then **Optional** sources. **Instructor** sources are useful for deeper interpretation or formal validation.

## 00 Foundations

### [The FAIR Guiding Principles for Scientific Data Management and Stewardship](https://www.nature.com/articles/sdata201618)
**Essential** · Open-access journal article · Wilkinson, Mark D. · 2016 · Introductory

**Why assign it:** Introduces FAIR and I1–I3; use to discuss why findable and accessible datasets need not be interpretable or directly comparable.

Persistent identifier: https://doi.org/10.1038/sdata.2016.18

### [EOSC Interoperability Framework: Report from the EOSC Executive Board Working Groups FAIR and Architecture](https://op.europa.eu/en/publication-detail/-/publication/d787ea54-6a87-11eb-aeb5-01aa75ed71a1)
Instructor background · Open report / specification · European Commission, EOSC Executive Board · 2021 · Advanced

**Why assign it:** Provides a broader interoperability framework, including technical and semantic as well as organizational dimensions; not the same taxonomy as the course.

Persistent identifier: https://doi.org/10.2777/620649

### [Pythia Foundations](https://foundations.projectpythia.org/)
**Essential** · Free online book / course · Project Pythia Community · 2023 · Introductory

**Why assign it:** Open geoscience computational textbook; use selected NetCDF/CF and Xarray chapters instead of assigning the entire book.

Persistent identifier: https://doi.org/10.5281/zenodo.7884571

### [Implementing FAIR Data Principles in the IPCC Seventh Assessment Cycle: Lessons Learned and Future Prospects](https://journals.plos.org/climate/article?id=10.1371/journal.pclm.0000533)
Optional · Open-access journal article · Stockhause, Martina, Huard, David, Al Khourdajie, Alaa et al. · 2024 · Intermediate

**Why assign it:** Shows why FAIR data stewardship and reuse matter in a real climate-science assessment workflow.

Persistent identifier: https://doi.org/10.1371/journal.pclm.0000533

## 01 Structural

### [The NetCDF User's Guide](https://docs.unidata.ucar.edu/nug/current/)
**Essential** · Free online documentation / tutorial · Unidata · n.d. · Intermediate

**Why assign it:** The authoritative explanation of NetCDF data models, dimensions, variables, attributes, encoding, and chunking.

### [NetCDF in Python: From Beginner to Pro](https://nordatanet.github.io/NetCDF_in_Python_from_beginner_to_pro/intro.html)
**Essential** · Free online book / course · Marsden, Luke · 2024 · Introductory

**Why assign it:** Practical, freely available course with NetCDF file inspection, CF metadata creation, cell methods, and file organization.

Persistent identifier: https://doi.org/10.5281/zenodo.10997447

### [xarray: N-D Labeled Arrays and Datasets in Python](https://doi.org/10.5334/jors.148)
Optional · Open-access journal article · Hoyer, Stephan, Hamman, Joseph · 2017 · Intermediate

**Why assign it:** Peer-reviewed conceptual bridge between the multidimensional NetCDF data model and its use in Python.

Persistent identifier: https://doi.org/10.5334/jors.148

### [A Data Model of the Climate and Forecast Metadata Conventions (CF-1.6) with a Software Implementation (cf-python v2.1)](https://gmd.copernicus.org/articles/10/4619/2017/)
Instructor background · Open-access journal article · Hassell, David, Gregory, Jonathan, Blower, Jon et al. · 2017 · Advanced

**Why assign it:** Excellent conceptual treatment of the distinctions and relationships between the NetCDF representation and the CF data model.

Persistent identifier: https://doi.org/10.5194/gmd-10-4619-2017

### [Table Schema Specification](https://specs.frictionlessdata.io/table-schema/)
Optional · Free online documentation / tutorial · Frictionless Data · n.d. · Introductory

**Why assign it:** Demonstrates why CSV alone lacks a fully specified machine-readable schema and how field types and constraints can be described.

### [Manual on Codes (WMO-No. 306), Volume I.2: Machine-Readable Codes](https://community.wmo.int/site/knowledge-hub/programmes-and-initiatives/wmo-information-system-wis/about-manual-codes-volume-i2/latest-version)
Instructor background · Free online documentation / tutorial · World Meteorological Organization · n.d. · Advanced

**Why assign it:** Domain-specific counterexample illustrating structured meteorological encodings such as GRIB and BUFR beyond NetCDF.

## 02 Semantic

### [NetCDF Climate and Forecast (CF) Metadata Conventions (Version 1.13)](https://cfconventions.org/Data/cf-conventions/cf-conventions-1.13/cf-conventions.html)
**Essential** · Open report / specification · Eaton, Brian, Gregory, Jonathan, Drach, Bob et al. · 2025 · Advanced

**Why assign it:** Primary normative reference on standard_name, coordinates, units, calendar, cell_methods, bounds, and semantic context. Latest stable release at research date.

Persistent identifier: https://doi.org/10.5281/zenodo.17801666

### [CF Standard Names and Other CF Controlled Vocabularies (Standard Name Table v95)](https://cfconventions.org/vocabularies.html)
**Essential** · Free online documentation / tutorial · CF Community · 2026 · Introductory

**Why assign it:** Use as a lookup exercise for physical quantities and canonical units; versioned separately from CF Conventions.

### [Assessing Semantic Interoperability in Environmental Sciences: Variety of Approaches and Semantic Artefacts](https://www.nature.com/articles/s41597-024-03669-3)
**Essential** · Open-access journal article · Di Muri, Cristina, Pulieri, Martina, Raho, Davide et al. · 2024 · Intermediate

**Why assign it:** Comparative survey of 540 environmental semantic artefacts; illuminates vocabularies, ontologies, formal representations, and governance.

Persistent identifier: https://doi.org/10.1038/s41597-024-03669-3

### [Attribute Convention for Data Discovery (ACDD), Version 1.3](https://wiki.esipfed.org/Attribute_Convention_for_Data_Discovery_1-3)
Optional · Free online documentation / tutorial · Earth Science Information Partners · n.d. · Intermediate

**Why assign it:** Shows how discovery-oriented, dataset-level descriptive metadata complement CF variable-level descriptions.

### [CfRadial: NetCDF CF Conventions for Radial Coordinate Data for RADAR and LIDAR](https://ncar.github.io/CfRadial/)
Optional · Free online documentation / tutorial · National Center for Atmospheric Research · 2018 · Intermediate

**Why assign it:** Radar-specific extension of NetCDF/CF, closely matched to the lesson’s precipitation and IDRA radar use case.

### [NERC Vocabulary Server: Controlled Vocabulary Collections](https://vocab.nerc.ac.uk/collection/)
Optional · Free online documentation / tutorial · British Oceanographic Data Centre · n.d. · Intermediate

**Why assign it:** A domain semantic-resource registry including versioned CF standard names and machine-accessible terminology.

### [IOOS Compliance Checker Documentation](https://ioos.github.io/compliance-checker/)
**Essential** · Free online documentation / tutorial · Integrated Ocean Observing System · n.d. · Intermediate

**Why assign it:** Practical validation resource for CF and ACDD; explain that syntactic conformance is not proof of full scientific comparability.

### [xarray with MetPy Tutorial](https://unidata.github.io/MetPy/latest/tutorials/xarray_tutorial.html)
Optional · Free online documentation / tutorial · Unidata, MetPy Developers · n.d. · Intermediate

**Why assign it:** Meteorological use case showing how CF-aware software can interpret units and coordinates and why metadata quality matters.

## 03 Technical - DAP

### [OPeNDAP User Guide](https://opendap.github.io/documentation/UserGuideComprehensive.html)
**Essential** · Free online documentation / tutorial · OPeNDAP · n.d. · Intermediate

**Why assign it:** Explains client–server separation, DDS/DAS (DAP2), constraint expressions, and server-side selective retrieval.

### [The Data Access Protocol Version 4 (DAP4) Specification](https://opendap.github.io/dap4-specification/DAP4.html)
Instructor background · Open report / specification · Caron, John, Davis, Ethan, Fulker, David et al. · 2016 · Advanced

**Why assign it:** Normative DAP4 architecture and protocol reference; particularly useful for distinguishing the DAP protocol from its server implementations.

### [What Is the THREDDS Data Server?](https://docs.unidata.ucar.edu/tds/current/adminguide/what_is_the_tds.html)
**Essential** · Free online documentation / tutorial · Unidata · n.d. · Introductory

**Why assign it:** Explains how THREDDS exposes one data collection through several standard data-access services, including OPeNDAP.

### [OPeNDAP User Guide: Constraint Expressions](https://www.earthdata.nasa.gov/fr/engage/open-data-services-software/earthdata-developer-portal/opendap/user-guide)
Optional · Free online documentation / tutorial · NASA Earthdata · n.d. · Intermediate

**Why assign it:** Concrete HTTP URL and constraint-expression examples for extracting subsets rather than downloading whole datasets.

## 04 Technical - APIs

### [Federated and Reusable Processing of Earth Observation Data](https://www.nature.com/articles/s41597-025-04513-y)
Optional · Open-access journal article · Mohr, Matthias, Pebesma, Edzer, Dries, Jeroen et al. · 2025 · Intermediate

**Why assign it:** Open-access research article examining openEO and interoperable workflows across providers; a case study showing what standardized APIs enable and where data/processing semantics still matter.

Persistent identifier: https://doi.org/10.1038/s41597-025-04513-y

### [OGC API - Environmental Data Retrieval: Workshop Module](https://ogcapi-workshop.ogc.org/api-deep-dive/environmental-data-retrieval/)
**Essential** · Free online documentation / tutorial · Open Geospatial Consortium · n.d. · Introductory

**Why assign it:** A guided exercise on standardized environmental web APIs, discovery, and location-specific requests.

### [OGC API - Environmental Data Retrieval Standard, Version 1.2 (OGC 19-086r9)](https://docs.ogc.org/is/19-086r9/19-086r9.html)
Instructor background · Open report / specification · Burgoyne, Mark, Blodgett, David, Heazel, Chuck et al. · 2026 · Advanced

**Why assign it:** The published 2026 standard for machine-to-machine spatiotemporal discovery and subsetting; complements DAP rather than replacing it.

### [OGC API - Common: Overview](https://ogcapi.ogc.org/common/overview.html)
Optional · Free online documentation / tutorial · Open Geospatial Consortium · n.d. · Intermediate

**Why assign it:** Provides a clear example of machine-readable API descriptions, shared paths and responses, and standardized client interoperability.

## 05 Cloud-native

### [Cloud-Optimized Geospatial Formats Guide](https://guide.cloudnativegeo.org/)
**Essential** · Free online book / course · Cloud-Native Geospatial Community · n.d. · Introductory

**Why assign it:** Illustrated open guide comparing cloud-friendly storage layouts; start with the Zarr chapter and object-storage concepts.

### [Zarr Core Specification, Version 3.1](https://zarr-specs.readthedocs.io/en/latest/v3/core/index.html)
Instructor background · Open report / specification · Zarr Developers · n.d. · Advanced

**Why assign it:** Defines Zarr arrays, groups, metadata documents, chunk grids and object stores; distinguish the format from the scientific semantic conventions.

### [Pangeo Forge: Crowdsourcing Analysis-Ready, Cloud Optimized Data Production](https://www.frontiersin.org/journals/climate/articles/10.3389/fclim.2021.782909/full)
Optional · Open-access journal article · Stern, Charles, Abernathey, Ryan, Hamman, Joseph et al. · 2022 · Intermediate

**Why assign it:** Peer-reviewed open-access analysis of reproducible pipelines for publishing analysis-ready geoscientific datasets in cloud-optimized formats; connects storage layout to reuse and computational workflows.

Persistent identifier: https://doi.org/10.3389/fclim.2021.782909

### [Virtual Zarr Cookbook (Kerchunk and VirtualiZarr)](https://projectpythia.org/kerchunk-cookbook/README.html)
**Essential** · Free online book / course · Project Pythia Community · n.d. · Intermediate

**Why assign it:** Executable notebooks showing how to expose existing NetCDF/HDF data as virtual Zarr without rewriting source files.

### [Basics of Virtual Zarr Stores](https://projectpythia.org/kerchunk-cookbook/notebooks/foundations/kerchunk-basics/)
**Essential** · Free online documentation / tutorial · Hagen, Norland Raphael · n.d. · Intermediate

**Why assign it:** One-file walkthrough using a concrete downscaled climate dataset; especially close to the course’s Kerchunk exercise.

### [Kerchunk in Practice](https://guide.cloudnativegeo.org/kerchunk/kerchunk-in-practice.html)
Optional · Free online documentation / tutorial · Cloud-Native Geospatial Community · n.d. · Intermediate

**Why assign it:** Practical notebook for virtual access to publicly available CMIP6-related NetCDF data.

## 06 AI-ready

### [Building Blocks for Interoperable, AI-Ready Geospatial Data: The Next Chapter of Spatial Data Infrastructures and Geospatial Ecosystems](https://docs.ogc.org/techpaper/26-050/26-050.html)
Instructor background · Open report / specification · Simonis, Ingo, Atkinson, Rob, Zaborowski, P. et al. · 2026 · Advanced

**Why assign it:** Recently published discussion paper directly distinguishing semantic, structural, and technical layers for AI-readiness. It is a proposal, not a normative OGC standard.

### [Recommendations for Services in a FAIR Data Ecosystem](https://www.sciencedirect.com/science/article/pii/S2666389920300696)
Optional · Open-access journal article · Publication metadata to be completed in Zotero · 2020 · Intermediate

**Why assign it:** Explains the role of APIs, domain ontologies, and repositories in machine-actionable FAIR research infrastructures.

Persistent identifier: https://doi.org/10.1016/j.patter.2020.100058

## Keeping the collection useful

In the teaching page, cite one accessible introduction and one authoritative standard per episode. Use instructor/advanced items for factual verification and version-specific details. When a standard is revised, retain its prior Zotero entry if old lesson datasets declare conformance to that version.

For a shared live library, see the accompanying `README.md` for the Zotero group and import instructions.
