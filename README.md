[![Awesome](https://awesome.re/badge.svg)](https://github.com//kg-construct/awesome-kgc-tools) 

# Awesome KGC Tools

Links and description of Knowledge Graphs Construction Tools

## KGC Materializers
* [Morph-KGC](https://github.com/oeg-upm/morph-kgc) - R2RML, RML and RML-star processor to generate RDF and RDF-star knowledge graphs from heterogeneous data sources at scale.
* [Chimera](https://github.com/cefriel/chimera) - Framework based on Apache Camel to define composable semantic data transformation pipelines (lifting/lowering to/from RDF)
* [RMLMapper](https://github.com/RMLio/rmlmapper-java/) - The RMLMapper executes RML rules to generate high-quality Linked Data from multiple originally (semi-)structured data sources 
* [RMLStreamer](https://github.com/RMLio/RMLStreamer/) - The RMLStreamer executes RML rules to generate high-quality Linked Data from multiple originally (semi-)structured data sources in a streaming way. 
* [xls2rdf](https://github.com/sparna-git/xls2rdf) - converts Excel files containing a "magic line" into RDF.
* [Morph-xR2RML](https://github.com/frmichel/morph-xr2rml/) - Implementation of the xR2RML mapping language (extending R2RML and reusing RML terms) for MongoDB databases. Can be used to map JSON data but also any format that can be imported in MongoDB, in particular CSV/TSV. Was used in different projects to produce 2.4 billion triples so far.
* [SDM-RDFizer](https://github.com/SDM-TIB/SDM-RDFizer) - An efficient scaled-up RML-compliant engine for knowledge graph construction from heterogeneous data sources.
* [CARML](https://github.com/carml/carml) - An extensible RML processor to generate RDF knowledge graphs from heterogeneous data sources.
* [R2RML-F](https://github.com/chrdebru/r2rml) - An R2RML processor with support for functions in JavaScript. Allows one to transform the contents of CSV files as virtual relational tables.
* [RocketRML](https://github.com/semantifyit/RocketRML) - RML processor to generate RDF knowledge graphs from heterogeneous data sources, implemented in JavaScript.
* [PyRML](https://github.com/anuzzolese/pyrml) - Python-based engine for processing RML files.
* [FlexRML](https://github.com/wintechis/flex-rml) - A Memory-Efficient Interpreter for RML written in C++.
* [SPARQL Anything](https://github.com/SPARQL-Anything/sparql.anything) - SPARQL Anything is a tool for querying anything with SPARQL.

## KGC Virtualizers
* [Ontop](https://github.com/ontop/ontop) - Ontop is a platform to query relational databases as Virtual RDF Graphs using SPARQL (R2RML)

## KGC Pre-processors
* [MEL](https://w3id.org/kgcp/MEL-TNNT/) - (*Metadata Extractor & Loader*) - A tool to extract metadata (and textual content) from various file formats, as JSON objects.
* [Dragoman](https://github.com/SDM-TIB/Dragoman) - An efficient RML+FnO-compliant engine for translating and executing complex functions in RML mapping rules and transfer the data integration system into a function-free one. 
* [EABlock](https://github.com/SDM-TIB/EABlock) - A computational block to solve entity alignment over textual attributes in a knowledge graph creation pipeline. 
* [FunMap](https://github.com/SDM-TIB/FunMap) - Efficient preprocessing of transformation rules described in RML+FnO mappings.
* [Excel in RML](https://www.dfki.uni-kl.de/~mschroeder/demo/excel-rml/) - RMLMapper extension to support Excel spreadsheets.

## NLP for KGC
* [TNNT](https://w3id.org/kgcp/MEL-TNNT/) - (*The NLP/NER Toolkit*) - A tool that automates the extraction of categorised named entities from the unstructured information encoded in the source documents, using diverse NLP tools and NER models.

## Mapping Specifications

* [RML by KG Construction W3C Community Group](https://w3id.org/rml/portal) - Modular redesign of the RML mapping language including support for collections and containers, input/output, rdf-star, and functions.
* [YARRRML](https://rml.io/yarrrml/spec/) - YARRRML is a human-readable text-based representation for declarative generation rules.
* [J2RM](https://w3id.org/kgcp/J2RM/) - J2RM mappings and its engine compose a tool to process mappings from JSON data to RDF triples guided by an OWL2 ontology structure.
* [xls2rdf](https://skos-play.sparna.fr/play/convert?lang=en#documentation) - The documentation for the "magic line" of the xls2rdf converter.
* [xR2RML](https://www.i3s.unice.fr/~fmichel/xr2rml_specification.html) - xR2RML is a language for expressing customized mappings from various types of databases (XML, object-oriented, NoSQL) to RDF datasets.

### Previous RML version (and extensions)
* [RML](https://rml.io/specs/rml/) - The RDF Mapping Language (RML) is a mapping language defined to express customized mapping rules from heterogeneous data structures and serializations to the RDF data model. 
* [Target in RML](https://rml.io/specs/rml-target/) - Alignment between RML and Target to describe how your knowledge graph should be exported to one or multiple targets.
* [DataIO](https://rml.io/specs/dataio/) - Target, a formal model and a common representation for specifying how a Knowledge Graph should be exported to a given target
* [FnO](https://fno.io/rml/) - Function Ontology (FnO), a way to semantically declare and describe implementation-independent functions, and their relations to related concepts such as parameters, outputs, related problems, algorithms, mappings to concrete implementations, and executions.

## Mapping Editors
* [JUMA](https://opengogs.adaptcentre.ie/crottija/juma-r2rml) - Jigsaw Puzzles for Representing Mappings
* [Mapeathor](https://morph.oeg.fi.upm.es/tool/mapeathor) - Definition of Excel-based mappings and translation to [R2]RML mappings.
* [Matey](https://rml.io/yarrrrml/matey/) - Matey is a web based editor for YARRRML rules.
* [RMLEditor](https://github.com/RMLio/rmleditor-ce) - RMLEditor offers a Graphical User Interface to enable data publishers, who are domain experts, to model knowledge derived from heterogeneous distributed data.
* [RMLx Visual Editor](https://pebbie.org/mashup/rml) - A web based editor for RML rules. 
* [Square](https://square.semvis.pl/projects) - SPARQL Queries and R2RML mappings Environment
* [Map-On](https://github.com/arc-lasalle/Map-On) - A web-based editor for visual ontology mapping for R2RML documents (DEPRECATED)
* [Karma](https://usc-isi-i2.github.io/karma/) - A web-based editor for visually creating R2RML mappings in order to create RDF from databases, spreadsheets, delimited text files, XML, JSON, KML and Web APIs according to an ontology of the user's choice.

## Mapping Translators
* [YARRRML-parser](https://github.com/RMLio/yarrrml-parser) - JavaScript engine that translates from YARRRML/RML/R2RML to YARRRML/RML/R2RML
* [YATTER](https://github.com/oeg-upm/yatter) - Python engine, translating from YARRRML/RML/R2RML to YARRRML/RML/R2RML with support for RML-star and easy-to-read outputs
* [Mapeathor](https://morph.oeg.fi.upm.es/tool/mapeathor) - From Excel-based mappings to [R2]RML mappings.

## Mapping Generators
* [Spread2RML](https://www.dfki.uni-kl.de/~mschroeder/demo/spread2rml/) - Suggests RML mappings on messy spreadsheets.
* [OWL2YARRRML](https://github.com/oeg-upm/owl2yarrrml) - Generates a mapping template in YARRRML given an ontology.

## KGC Pipelines
* [KGCP](http://w3id.org/kgcp/) - "_KG Construction Pipeline_" - A suite of software artifacts to automate the creation of KGs from heterogeneous data sources.

## KG subgraph extractors
* [KGPrune](https://kgprune.loria.fr/) - An API and Web application for extracting subgraphs of interest from Wikidata based on user-input seed entities, to bootstrap a new KG.

## KGC Evaluation
* [KROWN](https://github.com/kg-construct/krown) - A Benchmark for RDF Graph Materialization
* [Data Sprout](https://www.dfki.uni-kl.de/~mschroeder/demo/datasprout/) - Excel spreadsheet generator for evaluating KG construction.
* [GTFS-Madrid-Bench](https://github.com/oeg-upm/gtfs-bench) - Benchmark to evaluate performance & scalability of declarative KG construction engines.
* [SDM-Genomics](https://doi.org/10.6084/m9.figshare.14838342.v1) - Dataset to test simple and complex mapping operations in RML.
* [LUBM4OBDA](https://github.com/oeg-upm/lubm4obda) - OBDA benchmark for inference and meta knowledge evaluation.

