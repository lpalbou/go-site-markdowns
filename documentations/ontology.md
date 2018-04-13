# Ontology Documentation
---

The Gene Ontology defines the universe of concepts relating to gene functions (‘GO terms’), and how these functions are related to each other (‘relations’). It is constantly revised and expanded as biological knowledge accumulates. The GO describes function with respect to three aspects: *molecular function* (molecular-level activities performed by gene products), *cellular component* (the locations relative to cellular structures in which a gene product performs a function), and *biological process* (the larger processes, or ‘biological programs’ accomplished by multiple molecular activities).

Ongoing revisions to the ontology are managed by a team of senior ontology editors with extensive experience in both biology and computational knowledge representation. Ontology updates are made collaboratively between the GOC ontology team and scientists who request the updates. Most requests come from scientists making GO annotations (these typically impact only a few terms each), and from domain experts in particular areas of biology (these typically revise an entire ‘branch’ of the ontology comprising many terms and relations). We invite researchers and computational scientists to submit requests for either new terms or new relations in the ontology.

The GO ontology is structured as a directed acyclic graph where each term has defined relationships to one or more other terms in the same domain, and sometimes to other domains. The GO vocabulary is designed to be species-agnostic, and includes terms applicable to prokaryotes and eukaryotes, and single and multicellular organisms.

In an example of GO annotation, the gene product "cytochrome c" can be described by the *Molecular Function* term "oxidoreductase activity", the *Biological Process* term "oxidative phosphorylation", and the *Cellular Component* terms "mitochondrial matrix" and "mitochondrial inner membrane".

## Ontologies
### Molecular Function
Molecular function terms describes activities that occur at the molecular level, such as "catalytic activity" or "binding activity". GO molecular function terms represent activities rather than the entities (molecules or complexes) that perform the actions, and do not specify where, when, or in what context the action takes place. Molecular functions generally correspond to activities that can be performed by individual gene products, but some activities are performed by assembled complexes of gene products. Examples of broad functional terms are "catalytic activity" and "transporter activity"; examples of narrower functional terms are "adenylate cyclase activity" or "Toll receptor binding".

It is easy to confuse a gene product name with its molecular function; for that reason GO molecular functions are often appended with the word "activity".

### Cellular Component
These terms describe a location, relative to cellular compartments and structures, occupied by a macromolecular machine when it carries out a molecular function. There are two ways in which biologists describe locations of gene products: (1) relative to cellular structures (e.g., cytoplasmic side of plasma membrane) or compartments (e.g., mitochondrion), and (2) the stable macromolecular complexes of which they are parts (e.g., the ribosome). Unlike the other aspects of GO, cellular component concepts refer not to processes but rather a cellular anatomy.

### Biological Process
A biological process term describes a series of events accomplished by one or more organized assemblies of molecular functions. Examples of broad biological process terms are "cellular physiological process" or "signal transduction". Examples of more specific terms are "pyrimidine metabolic process" or "alpha-glucoside transport". The general rule to assist in distinguishing between a biological process and a molecular function is that a process must have more than one distinct steps.

A biological process is not equivalent to a pathway. At present, the GO does not try to represent the dynamics or dependencies that would be required to fully describe a pathway.

## Details about the ontologies
* [Ontology Structure](http://geneontology.org/page/ontology-structure): information about the structure of GO terms and the ontology.
* [Ontology Relations](http://geneontology.org/page/ontology-relations): documentation on the inter-term relations used in GO
* [Cellular Component Ontology](http://geneontology.org/page/cellular-component-ontology-guidelines): Rules governing content and stylistic aspects of GO terms in the cellular component ontology.
* [Molecular Function Ontology](http://geneontology.org/page/molecular-function-ontology-guidelines): Rules governing content and stylistic aspects of GO terms, standard definitions and term relationships in the molecular function ontology.
* [Biological Process Ontology](http://geneontology.org/page/biological-process-ontology-guidelines): Rules governing content and stylistic aspects of GO terms, standard definitions and term relationships in the biological process ontology.
* [Species-Specific Terms](http://geneontology.org/page/species-specific-terms): How the Gene Ontology deals with words or phrases where the meaning varies depending on the organism.
* Documentation on specific areas of the ontology:
    * [Membrane proteins](http://geneontology.org/page/membrane-proteins)
    * [Membranes and envelopes](http://geneontology.org/page/membranes-and-envelopes)
    * [Protein complexes](http://geneontology.org/page/protein-complexes)
    * [Cell Cycle](http://geneontology.org/page/cell-cycle)
    * [Development](http://geneontology.org/page/development)
    * [Metabolic processes](http://geneontology.org/page/metabolic-process)
    * [Other organisms and viruses](http://geneontology.org/page/other-organisms-and-viruses)
    * [Regulation](http://geneontology.org/page/regulation)
    * [Detection and Response to stimulus](http://geneontology.org/page/detection-and-response-stimulus)
    * [Sensory perception](http://geneontology.org/page/sensory-perception)
    * [Transport and transporters](http://geneontology.org/page/transport-and-transporters)
* [GO Slim Guide](http://geneontology.org/page/go-slim-and-subset-guide): information about GO slims, cut-down versions of the ontologies useful for providing an overview of GO