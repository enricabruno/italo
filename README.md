# ITALO (Iconographic and Textual Architecture for Literary Observations)

**ITALO** is a framework for the computational modelling and critical analysis of Italo Calvino’s *Il castello dei destini incrociati* (*The Castle of Crossed Destinies*, 1973), a seminal masterpiece of Italian combinatory literature.

By adopting the XD methodology, the project is built on the alignment of [ODI](https://odi-documentation.github.io/materials/), a customised ontology developed for the description and representation of Calvino's *macchina narrativa combinatoria* of the first collection of *Il castello dei destini incrociati*. Specifically, ODI is aligned following this structure: 

* **Bibliographic Layer:** `LRMoo` (WEMI stack) and `RDA` properties to manage the structural breakdown of the work (Editions, Stories/Chapters).
* **Constraint Layer:** `DeSMòS` for the taxonomic classification of constraint-based writing procedures.
* **Iconographic & Narrative Layer:** `CIDOC CRM`, `ViR` (to parse the visual components of the artwork), and `GOLEM` (to map fictional characters, events, and settings).

## What does the project do?

1. **Models literary constraints (*Contraintes*):** It formalises the formal-structural and semantic-diegetic Oulipian rules (such as the magic square and lipophony) employed by Calvino as generative mechanisms for the text.
2. **Operationalises semantic perspectivism:** It handles the narrative phenomenon where a single physical tarot card changes its role, character, or event radically depending on the specific story and direction it is read within the matrix.
3. **Bridges visual items and text:** It establishes a unified documentation path connecting the book's bibliographic data, the historical iconography of the visual artefact (the card), and the exact textual excerpt supporting that interpretation.

