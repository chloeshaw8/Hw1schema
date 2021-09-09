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
        "title": "gene name"
        "description": "abbreviated name of genes",
        "examples": [
          "DDX58",
          "C3"
         ]},{
         "type": "object",
         "title": "length"
         "description": "length of gene in base pairs",
         "examples": [
          "50392",
          "709234"
          ]},{
          "type": "object",
          "title": "accession number",
          "description": "accession number for gene given on ncbi",
          "examples": [
            "010293",
            "109201"
            ]}
        }
       }
}
