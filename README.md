# Hw1schema
{
  "$schema": "http://json-schema.org/draft-07/schema#",
  "$ID": "https://raw.githubusercontent.com/chloeshaw8/Hw1schema/main/README.md",
  "type": "object",
  "title": "gene characteristics",
  "description": "characteristics of genes in homo sapiens",
  "required": [
    "data",
   ],
  "properties": {
    "keywords": {
      "type": "array",
      "description": "characteristics of various genes",
      "items": {
        "type": "object",
        "description": "abbreviated name of genes, length of gene in base pairs, accession number of gene",
        "examples": [
          "DDX58",
          "C3",
          "718293",
          "109291"
         ]}
        }
       }
}
