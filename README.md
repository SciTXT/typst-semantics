# typst-semantics - compact JSON-LD representation of Typst texts

Adding a semantic layer to Typst, enabeling machine interpretable and actionable scientific texts.

This implementation is based on the [JSON-LD](https://json-ld.org/) standard, which is a lightweight Linked Data format. It is easy for humans to read and write and easy for machines to parse and generate. It is based on the already existing JSON format and provides a way to help JSON data interoperate at Web-scale.


## Key Features

- text is represented as a JSON-LD object
- each word in a text is represented just once. The text is represented as a list of references to the words.
- each term in a text is represented as a reference to a concept in a controlled vocabulary / taxonomy / ontology 
- the Tpyst text and the semantic layer could be efficiently stored in a compressed file, using, e.g., the [OASIS Package Standard](docs.oasis-open.org/office/v1.2/os/OpenDocument-v1.2-os-part3.html) = a ZIP compressed file with Metadata.

