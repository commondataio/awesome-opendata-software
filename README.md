# Awesome opendata software  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Awesome list of the software tools related to opendata: data catalogs, ingestion tools, data prep tools and so on.

This awesome list is a part of Common Data Index project and is derived from Registry of data portals https://registry.commondata.io

### Table of contents

* [Data catalogs](#data-catalogs)
  - [Open data portals](#open-data-portals)
  - [Geodata catalogs](#geodata-catalogs)
  - [Research data repositories](#research-data-repositories)
* [Standards](#standards)
  - [Common data standards](#specific-data-standards)
  - [Spatial data standards](#spatial-data-standards)
  - [APIs specifications](#apis-specifications)
  - [Statistics specifications](#statistics-specifications)
  - [Specific data standards](#specific-data-standards)
  - [Data containers](#data-containers)
  - [Metadata standards](#metadata-standards)
* [Tools](#tools)
  - [Data refining](#data-refining)
  - [Data packaging](#data-packaging)
  - [Statistics tools](#statistics-tools)

## Data catalogs

### Open data portals

#### Open source
* [CKAN](https://ckan.org) - CKAN is an open-source DMS (data management system) for powering data hubs and data portals. CKAN makes it easy to publish, share and use data. It powers hundreds of data portals worldwide. 
* [DKAN](https://getdkan.com) - DKAN is a community-driven, free and open source open data platform that gives organizations and individuals ultimate freedom to publish and consume structured information.
* [JKAN](https://jkan.io) - A lightweight, backend-free open data portal, powered by Jekyll 
* [uData](https://github.com/opendatateam/udata) - Customizable and skinnable social platform dedicated to (open)data by Etalab
* [Aleph](https://github.com/alephdata/aleph) - Aleph is a tool for indexing large amounts of both documents (PDF, Word, HTML) and structured (CSV, XLS, SQL) data for easy browsing and search.
* [Magda](https://github.com/magda-io/magda) -  A federated, open-source data catalog for all your big data and small data 


#### Commercial
* [EntryScape catalog](https://entryscape.com/en/products/catalog/) - DCAT AP compliant data catalog
* [Junar](https://junar.com) - Junar data platform, SaaS product and US-based company
* [OpenDataSoft](https://www.opendatasoft.com) - The all-in-one platform that empowers your whole team to accelerate wider data usage and generate value in your ecosystems. The French company and SaaS data portal
* [Socrata](https://www.tylertech.com/products/socrata) - SaaS data platfrom popular in US and Canada. Socrata was acquired by Tyler Technologies in 2018 and is now the Data and Insights division of Tyler. 
* [Tablion Data Portal](https://www.aristotlemetadata.com/products/tablion-data-portal/) - commercial data portal software from Aristotle Metadata, Australia
* [TriplyDb](https://triply.cc) - TriplyDB integrates your organization's data assets into a standards-compliant knowledge graph. 

### Geodata catalogs

#### Open source
* [Esri Geoportal server](https://github.com/Esri/geoportal-server) - Geoportal Server is a standards-based, open source product that enables discovery and use of geospatial resources including data and services. **Not updated anymore**
* [Geoblacklight](https://geoblacklight.org) - A multi-institutional open-source collaboration building a better way to find and share geospatial data
* [Geonetwork](https://geonetwork-opensource.org) - GeoNetwork is a catalog application to manage spatially referenced resources.
* [Geonode](https://geonode.org) - GeoNode is a web-based application and platform for developing geospatial information systems (GIS) and for deploying spatial data infrastructures (SDI).
* [Geoportal.rlp](https://github.com/mrmap-community/GeoPortal.rlp) - A complete SDI-Suite for the management of OWS (WMS / WFS, CSW), metadata (iso19139), users, organizations, and licences.
* [Geoserver](https://geoserver.org) - GeoServer is an open source server for sharing geospatial data.
* [Open Geoportal](http://opengeoportal.io/software/open-geoportal/) - The Open Geoportal (OGP) is a collaboratively developed, open source, federated web application to rapidly discover, preview, and retrieve geospatial data from multiple organizations. 
* [OpenDataCube](https://www.opendatacube.org) - The Open Data Cube (ODC) is an Open Source Geospatial Data Management and Analysis Software project that helps you harness the power of Satellite data.
* [Oskari](https://www.oskari.org) - geoportal open source software from Finland Kadaster, incubating in Open Geo 
* [PyCSW](https://pycsw.org) - Python based CSW server, actively used as standalone service
* [Stac-server](https://github.com/stac-utils/stac-server) - A Node-based STAC API, AWS Serverless, OpenSearch

#### Commercial
* [ArcGIS Hub](https://hub.arcgis.com) -an easy-to-configure cloud platform that organizes people, data, and tools to accomplish initiatives and goals. Esri SaaS product
* [ArcGIS Server](https://enterprise.arcgis.com/en/server/latest/get-started/windows/what-is-arcgis-for-server-.htm) - ArcGIS Server is the server software component in ArcGIS Enterprise that makes your geographic information available to other users in your organization, and optionally to any Internet user.
* [Carto](https://carto.com) - SaaS mapping service with possibility of creating of geodata portals
* [ERDAS Apollo](https://hexagon.com/products/erdas-apollo) - Enables enterprise data management, discovery and delivery for geospatial data
* [Koordinates](https://www.koordinates.com) - Koordinates is a geospatial data management platform inspired by cracking GIS data out of vendor silos.
* [MetaGIS](https://www.metagis.se) - commercial GIS server/portal from Sweden and popular in Sweden
* [OrbisMAP](https://www.orbismap.ru) - Russian geoportal product


### Research data repositories

#### Open source

* [DataCat](https://github.com/datalad/datalad-catalog) - DataLad Catalog is a free and open source command line tool, with a Python API, that assists with the automatic generation of user-friendly, browser-based data catalogs from structured metadata.
* [Dataverse](https://dataverse.org) -  Open source research data repository software
* [Djehuty](https://github.com/4TUResearchData/djehuty) -  The 4TU.ResearchData repository system 
* [DSpace](https://dspace.lyrasis.org) - The Software of Choice for Academic, Non-profit & Commercial Organizations Building Open Digital Repositories. Used to create research data repositories too. 
* [EPrints](https://www.eprints.org) - open source research data repository popular in United Kingdom
* [Galaxy](https://usegalaxy.org) - open source bioinformatics research management platform
* [InvenioRDM](https://inveniosoftware.org/products/rdm/) - The turn-key research data management repository
* [IPT](https://github.com/gbif/ipt) - GBIF Integrated Publishing Toolkit (IPT). Data catalog software integrated into GBIF ecosystem.
* [Islandora](https://www.islandora.ca) - digital documents open source repository used by universities and libraries, could include datasets
* [LibreCat](https://github.com/LibreCat/LibreCat) -  A publication management system. Used to create research data repositories too.
* [MyCoRe](https://www.mycore.de) - MyCoRe (portmanteau of My Content Repository) is an open source repository software framework for building disciplinary or institutional * [MyTardis](https://www.mytardis.org) - MYTARDIS: Research data management for instrument dataj
repositories, digital archives, digital libraries, and scientific journals.
* [NYU Data catalog](https://github.com/nyuhsl/data-catalog) - The NYU Data Catalog facilitates researchers’ access to large datasets available either publicly or through institutional or individual licensing. It also includes descriptions of internally-generated research datasets from NYU researchers. 
* [Samvera](https://samvera.org) - another digital documents open source repository software, actively used by libraries around the world
* [Weco](https://github.com/RCOSDP/weko) - Weko3 is a repository software based on invenio3. 

#### Commercial

* [Converis](https://clarivate.com/products/scientific-and-academic-research/research-analytics-evaluation-and-management-solutions/converis/) - research data management product by Clarivate
* [DataOne Hosted Repo](https://www.dataone.org/hosted-repo/) - online catalog and SaaS hosted repositories
* [Elsevier Digital Commons](https://www.elsevier.com/solutions/digital-commons) - Elsevier product to manage research output, similar to Elsevier Pure but less complicated.
* [Elsevier Pure](https://www.elsevier.com/solutions/pure) - Pure is a Research Information Management System (RIMS) or Current Research Information System (CRIS). 
* [Esploro](https://exlibrisgroup.com/products/esploro-research-services-platform/) - research outputs management system from Exlibris Group
* [Figshare](https://figshare.com) - cloud based open access repository software and service
* [Omega-PSIR](https://www.omegapsir.io) - research management information system from Poland and used by Poland universities

### Microdata catalogs

#### Open source

* [NADA Data Catalog](https://nada.ihsn.org) - An open-source software designed for researchers to browse, search, compare, apply for access and download research data.

### Statistics and indicators databases

#### Open source
* [OpenSDG](https://open-sdg.org) - Open SDG. An open source, free-to-reuse platform for managing and publishing data and statistics related to the UN Sustainable Development Goals (SDGs).
* [PxWeb](https://www.scb.se/en/services/statistical-programs-for-px-files/px-web/) -  PxWeb is used for publishing statistics in a data base at the web and is since 1 January 2016 free of charge for government agencies and municipalities, international NSI:s and international organisations of statistics. 
* [.Stat Suite](https://siscc.org/stat-suite/) - The .Stat Suite is a standard-based, componentised, open source platform for the efficient production and dissemination of high-quality statistical data. The product is based on the General Statistical Business Process Model (GSBPM) and the Statistical Data and Metadata eXchange (SDMX) standards. 

#### Commercial

* [PublishMyData](https://pages.tpximpact.com/swirrl) - RDF-based open statistical data product. Acquired by TPX Impact

### Metadata catalogs

#### Open source
* [Fusion Metadata Registry](https://www.sdmx.io/fmr/) - open source metadata catalog used by European Union authorities and some countries statistical agencies. Open source by request

## Standards

### Common data standards
* [CSV](https://datatracker.ietf.org/doc/html/rfc4180) -  Common Format and MIME Type for Comma-Separated Values (CSV) Files
* [XML](https://www.w3.org/XML/) - Extensible Markup Language (XML) is a simple, very flexible text format derived from SGML (ISO 8879). Originally designed to meet the challenges of large-scale electronic publishing, XML is also playing an increasingly important role in the exchange of a wide variety of data on the Web and elsewhere.
* [JSON](https://www.json.org/json-en.html) - JSON (JavaScript Object Notation) is a lightweight data-interchange format.
* [NDJSON/JSON lines](http://ndjson.org) - NDJSON is a convenient format for storing or streaming structured data that may be processed one record at a time. It works well with unix-style text processing tools and shell pipelines.
* [XLS](https://www.loc.gov/preservation/digital/formats/fdd/fdd000510.shtml) - The Microsoft Excel Binary File format, with the .xls extension and referred to as XLS or MS-XLS, was the default format used for spreadsheets in Excel through Microsoft Office 2003. It is not open data format since it's proprietary, but it's _defacto_ very common.
* [XLSX](https://www.loc.gov/preservation/digital/formats/fdd/fdd000398.shtml) - The Open Office XML-based spreadsheet format using .xlsx as a file extension has been the default format produced for new documents by versions of Microsoft Excel since Excel 2007. It is not open data format since it's proprietary, but it's _defacto_ very common.
* [NETCDF](https://nsidc.org/data/user-resources/help-center/what-netcdf) - NetCDF (network Common Data Form) is a set of interfaces for array-oriented data access and a freely distributed collection of data access libraries for C, Fortran, C++, Java, and other languages. The netCDF libraries support a machine-independent format for representing scientific data. Common for scientific data.
* [CDF](https://www.loc.gov/preservation/digital/formats/fdd/fdd000226.shtml) - CDF is a conceptual data abstraction for storing, manipulating, and accessing multidimensional data sets. The basic component of CDF is a software programming interface that is a device-independent view of the CDF data model. Common for scientific data.
* [Apache Parquet](https://parquet.apache.org/) - Apache Parquet is an open source, column-oriented data file format designed for efficient data storage and retrieval. It provides efficient data compression and encoding schemes with enhanced performance to handle complex data in bulk. Parquet is available in multiple languages including Java, C++, Python, etc.... It's still uncommon for open data portals but common for public ML data catalogs.
* [RDF](https://www.w3.org/RDF/) - The Resource Description Framework (RDF) is a general framework for representing interconnected data on the web. RDF statements are used for describing and exchanging metadata, which enables standardized exchange of data based on relationships.

### Spatial data standards
* [CSW](https://www.ogc.org/standard/cat/) - Catalogue services support the ability to publish and search collections of descriptive information (metadata) for data, services, and related information objects. Open Geospatial Consortium standard. 
* [ESRI Rest API](https://developers.arcgis.com/rest/) - ArcGIS REST APIs used to query data from ArcGIS Enterprise products
* [FITS](https://www.loc.gov/preservation/digital/formats/fdd/fdd000317.shtml) - FITS is a file format designed to store, transmit, and manipulate scientific images and associated data. 
* [GeoJSON](https://geojson.org) - GeoJSON is a format for encoding a variety of geographic data structures. In 2015, the Internet Engineering Task Force (IETF), in conjunction with the original specification authors, formed a GeoJSON WG to standardize GeoJSON. RFC 7946 was published in August 2016 and is the new standard specification of the GeoJSON format, replacing the 2008 GeoJSON specification.
* [GeoPackage](https://www.loc.gov/preservation/digital/formats/fdd/fdd000419.shtml) - Specifications in the family of GeoPackage formats (see GeoPackage_family) specify GeoPackages for exchange and GeoPackage SQLite Extensions that permit direct use, without intermediate format translations, of vector geospatial features and/or tile matrix sets of earth images and raster maps at various scales. 
* [GeoTIFF](https://www.ogc.org/standard/geotiff/) - This OGC Standard defines the Geographic Tagged Image File Format (GeoTIFF) by specifying requirements and encoding rules for using the Tagged Image File Format (TIFF) for the exchange of georeferenced or geocoded imagery. Open Geospatial Consortium standard. 
* [GML](https://www.ogc.org/standard/gml/) - The OpenGIS® Geography Markup Language Encoding Standard (GML) The Geography Markup Language (GML) is an XML grammar for expressing geographical features.
* [KML](https://www.ogc.org/standard/kml/) - KML is an XML language focused on geographic visualization, including annotation of maps and images.
* [ShapeFile](https://doc.arcgis.com/ru/arcgis-online/reference/shapefiles.htm) - A shapefile is an Esri vector data storage format for storing the location, shape, and attributes of geographic features. It is stored as a set of related files and contains one feature class.
* [WCS](https://www.ogc.org/standard/wcs/) - A Web Coverage Service (WCS) offers multi-dimensional coverage data for access over the Internet. WCS Core specifies a core set of requirements that a WCS implementation must fulfill. Open Geospatial Consortium standard. 
* [WFS](https://www.ogc.org/standard/wfs/) - The Web Feature Service (WFS) represents a change in the way geographic information is created, modified and exchanged on the Internet. Rather than sharing geographic information at the file level using File Transfer Protocol (FTP), for example, the WFS offers direct fine-grained access to geographic information at the feature and feature property level. Open Geospatial Consortium standard. 
* [WMS](https://www.ogc.org/standard/wms/) - The OpenGIS® Web Map Service Interface Standard (WMS) provides a simple HTTP interface for requesting geo-registered map images from one or more distributed geospatial databases. Open Geospatial Consortium standard. 

### APIs specifications
* [OpenAPI](https://www.openapis.org) - The OpenAPI Specification is a specification language for HTTP APIs that provides a standardized means to define your API to others.

### Statistics specifications
* [DDI](https://ddialliance.org) - The Data Documentation Initiative (DDI) is an international standard for describing the data produced by surveys and other observational methods in the social, behavioral, economic, and health sciences.
* [SDMX](https://sdmx.org) - A global initiative to improve Statistical Data and Metadata eXchange

### Specific data standards
* [Fiscal data package](https://specs.frictionlessdata.io/fiscal-data-package/) - Fiscal Data Package is a lightweight and user-oriented format for publishing and consuming fiscal data. Fiscal data packages are made of simple and universal components. They can be produced from ordinary spreadsheet software and used in any environment.
- [GTFS (General Transit Feed Specification)](https://developers.google.com/transit/gtfs) - defines a common format for public transportation schedules and associated geographic information. GTFS "feeds" let public transit agencies publish their transit data and developers write applications that consume that data in an interoperable way.
- [IATI Standard](https://iatistandard.org/en/) - The IATI Standard is a set of rules and guidance on how to publish useful development and humanitarian data. 
- [Open Contracting Data Standard (OCDS)](https://standard.open-contracting.org/latest/en/) - The Open Contracting Data Standard (OCDS) enables disclosure of data and documents at all stages of the contracting process by defining a common data model.


### Data containers
* [BagIt](https://datatracker.ietf.org/doc/html/rfc8493) - BagIt is a set of hierarchical file layout conventions designed to support storage and transfer of arbitrary digital content. A "bag" consists of a directory containing the payload files and other accompanying metadata files known as "tag" files.
* [BioCompute Objects](https://github.com/biocompute-objects/BCO_Specification) - BCOs are represented in JSON (JavaScript Object Notation) formatted text, adhearing to JSON schema draft-07. The JSON format was chosen because it is both human and machine readable/writable. For a detailed description of JSON see www.json.org.
- [COMBINE](https://co.mbine.org) - The “COmputational Modeling in BIology NEtwork” (COMBINE) is an initiative to coordinate the development of the various community standards and formats for computational models.
* [DataCrate](https://github.com/UTS-eResearch/datacrate) - Data Crate is based on the Bagit packaging spec, with additional human and machine readable metadata in JSON-LD.
* [Frictionless standards](https://specs.frictionlessdata.io/) - A Data Package is a simple container format used to describe and package a collection of data (a dataset).
- [ReproZIP](https://www.reprozip.org/) - ReproZip can automatically pack your research along with all necessary data files, libraries, environment variables and options into a self-contained bundle.
- [RO-CRATE](https://www.researchobject.org/ro-crate/) - RO-Crate is a community effort to establish a lightweight approach to packaging research data with their metadata. It is based on schema.org annotations in JSON-LD, and aims to make best-practice in formal metadata description accessible and practical for use in a wider variety of situations, from an individual researcher working with a folder of data, to large data-intensive computational research environments.

### Metadata standards
* [ Asset Description Metadata Schema, ADMS](https://ec.europa.eu/isa2/solutions/asset-description-metadata-schema-adms_en/) - metadata management of a European public administration or service and want to explore, (re-)use or share semantic assets (metadata or reference data)
* [CKAN API](https://docs.ckan.org/en/2.9/api/) - defacto metadata standard for most open data portals
* [CSVW - CSV on the Web](https://csvw.org) - CSV on the Web (CSVW) standard to add metadata to describe the contents and structure of comma-separated values (CSV) data files
* [DataCite Metadata Schema](https://schema.datacite.org/) - The DataCite Metadata Schema is a list of core metadata properties chosen for an accurate and consistent identification of a resource for citation and retrieval purposes, along with recommended use instructions.
* [DCAT](https://www.w3.org/TR/vocab-dcat-2/) - DCAT is an RDF vocabulary designed to facilitate interoperability between data catalogs published on the Web. This document defines the schema and provides examples for its use.
* [DCAT-US](https://resources.data.gov/resources/dcat-us/) - DCAT-US Schema v1.1 (Project Open Data Metadata Schema). The metadata schema specified in this memorandum is based on DCAT, a hierarchical vocabulary specific to datasets. 
* [DCAT-AP 1.1](https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/solution/dcat-application-profile-data-portals-europe/release/11) - The DCAT Application profile for data portals in Europe (DCAT-AP) is a specification based on W3C's Data Catalogue vocabulary (DCAT) for describing public sector datasets in Europe. Version 1.1
* [DCAT-AP 2.1.1](https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/solution/dcat-application-profile-data-portals-europe/release/211) - The DCAT Application Profile for data portals in Europe (DCAT-AP) is a specification based on W3C's Data Catalogue vocabulary (DCAT) for describing public sector datasets in Europe. Version 2.1.1
* [DCAT-AP IT](https://schema.gov.it/lode/extract?url=https://w3id.org/italia/onto/DCAT) - This is version 2.0 of the ontology of the Italian application profile for the metadata that describe catalogues and data of Italian Public Administrations (DCAT-AP_IT).
* [DCAT-AP.de](https://www.dcat-ap.de) - DCAT-AP.de is the common German metadata model for the exchange of open administrative data. On this platform you will find the current version of the specification documents, sample files and DCAT-AP.de's own vocabularies.
* [Dublin Core](https://www.dublincore.org/) - the most common digital objects description standard
* [EU Vocabularies](https://op.europa.eu/en/web/eu-vocabularies) - European Reference data catalogue
* [Google Search. Dataset (Dataset, DataCatalog, DataDownload) structured data](https://developers.google.com/search/docs/appearance/structured-data/dataset) - Google search description on implementation of Schema.org Dataset
* [INSPIRE](https://inspire.ec.europa.eu/metadata/6541) -  According to Article 5(1) of INSPIRE Directive 2007/2/EC, EU Member States shall ensure that metadata are created for the spatial data sets and services corresponding to the themes listed in Annexes I, II and III, and that those metadata are kept up to date. 
* [ISO 19115:2003](https://www.iso.org/standard/26020.html) - ISO 19115:2003 defines the schema required for describing geographic information and services. It provides information about the identification, the extent, the quality, the spatial and temporal schema, spatial reference, and distribution of digital geographic data.
* [Schema.org Dataset](https://schema.org/Dataset) - A body of structured information describing some topic(s) of interest.

### Additional data standards resources
* [Digital Curation Centre list of metadata standards](https://www.dcc.ac.uk/guidance/standards/metadata/list) - list of Metadata Standards 
* [FairSharing registry standards](https://fairsharing.org/search?fairsharingRegistry=Standard) - curated list of metadata standards

## Tools

### Data refining
* [OpenRefine](https://github.com/OpenRefine/OpenRefine) -  OpenRefine is a free, open source power tool for working with messy data and improving it

### Data packaging
* [bdbag](https://github.com/fair-research/bdbag) - The bdbag utilities are a collection of software programs for working with BagIt packages that conform to the BDBag and Bagit/RO profiles.
* [datalad](https://github.com/datalad/datalad) - DataLad makes data management and data distribution more accessible. To do that, it stands on the shoulders of Git and Git-annex to deliver a decentralized system for data exchange.
* [Frictionless Framework](https://github.com/frictionlessdata/framework) -  Data management framework for Python that provides functionality to describe, extract, validate, and transform tabular data 


### Quality management
* [Schema.org validator](https://validator.schema.org/) - helps to validate schema.org descriptions, including Dataset

### Data publishing
* [Datasette](https://github.com/simonw/datasette) -  An open source multi-tool for exploring and publishing data

### Statistics tools 
* [RSDMX](https://github.com/opensdmx/rsdmx) -  Tools for reading SDMX data and metadata in R 

