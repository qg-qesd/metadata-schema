# Queensland Environmental Science Data - Metadata Schema
This is the repository for the QDCAT semantic web based metadata schema for the Queensland Environmental Science Data (QESD) Catalogue. The QDCAT schema is a profile of the DCAT2 scheme and includes some additional components of particular relevance to environmental science data in Queensland. 

The QDCAT schema can be viewed [here](./QDCAT-Profile.md).

## Why a metadata schema
Sharing data resources among different organisations, researchers, governments and citizens requires the provision of metadata. This is irrespective of the data being open or not. Metadata can include:

- Descriptive information used for discovery and identification, e.g. title, abstract, author, keywords
- Structure, e.g. how pages form chapters, versions, relationships
- Administrative information to help manage a resource, e.g. permissions, when and how it was created
- Reference information e.g. the content and quality of statistical data
- Statistical (process) metadata, e.g. descriptions of processes that collect, process, or produce statistical data.

Standards to describe and manage metadata are important to facilitate scientists recording metadata of value.

A meta-data schema is a comprehensive set of elements for a dataset including its required fields, field types, definitions and structures. Schemas are usually domain-specific or suit a type of information resource. They include procedural rules (a framework) which ensure a standardised approach to both metadata creation and use, which in turn facilitates discoverability, interoperability and access (FAIR data principles). The framework includes processes for creating, controlling, enhancing, attributing, defining and managing the metadata schema. 

## Why DCAT2
DCAT is an acronym for the Data Catalogue Vocabulary. DCAT2 builds on the original DCAT, adding data services, time and space properties, qualified relations and packaging. New DCAT implementations should adopt DCAT2. DCAT2 is used to describe datasets and allow movement of records between and across catalogues. DCAT2 can be used to describe datasets, data services and data catalogues.

Many of the other major schemas have mapping applied to automatically convert metadata to DCAT2. E.g. mapping ISO 19115 to DCAT2 to Schema.org.

## DCAT2 classes
DCAT2 has six main classes that describe the key components of the catalog and its resources.

- **Catalog**: a collection of metadata about datasets and data services.
- **Dataset**: a dataset is a collection of data published or curated by a single agent.
- **Distribution**: represents an accessible form of a dataset, such as a downloadable file.
- **Data Service**: a data service is a collection of operations accessible through an interface that provide access to dataset/s or data processing functions.
- **Catalog Record**: is primarily concerned with the registration of information, such as who added the item and when.
- **Resource**: represents a dataset, a data service or any other resource that may be described by a metadata record in a catalog. Not intended to be used directly, is a parent class for datasets, data services and catalogs; other types of resources would become additional sub-classes of resource.
