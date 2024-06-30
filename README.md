# typst-semantics

Adding a semantic layer to Typst, enabeling machine interpretable and actionable scientific texts


## Overview and Motivation

There is currently a large movement in **science** to make scientific texts machine "understandable" / interpretable and actionable (e.g. in the *FAIR data movement*). 
A common path many scientists and developers follow is to relate each well defined term in a (scientific) text with a corresponding term from an *Ontology* or *Taxonomy*.  By doing so, the text receives a context and each word receives a well defined meaning (=semantics).
This enhanced text representation would enable computer programs to "understand" the context of a text and concrete meaning of a certain word in a sentence. This semantic information could, e.g., be used to display further information about a certain concept to the user, or to enable machine learning or AI to interpret the content of a text much more accurately. 

## Example Text with semantics annotations

The following text is an example text from the medical realm with references (in this case as CURIs) to external resources that define or explain the terms in more details
(the given Links in brackets should only be shown to the user, when she/he moves over a certain term, they should ideally not appear while editing a **Typst** document - or they should be at least hide-able).

`**Oxytocin** is a [peptide hormone](wikidata:Peptide_hormone) and [neuropeptide](wikidata:Neuropeptide) normally produced in the [hypothalamus](wikidata:Hypothalamus) and released by the [posterior pituitary](ncit:Posterior_pituitary).[[4]](https://en.wikipedia.org/wiki/Oxytocin#cite_note-4) [...] **Oxytocin** is released into the bloodstream as a hormone in response to [sexual activity](https://en.wikipedia.org/wiki/Human_sexual_activity) and during childbirth [...]`


## Repository structure

Within this repository, different implementations should be explored, discussed and compared.

Each **Branch** represents a certain implementation as a Proof-of-Concept.

## Discussions

Please use the **Issues** section to discuss the different implementations and to propose new ideas or improvements.


