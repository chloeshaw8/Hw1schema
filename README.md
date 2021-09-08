# Hw1schema
{
  "$schema": "http://json-schema.org/draft-07/schema#",
  "$ID": 
  "type": "object",
  "description": "Characteristics of genes in homo sapiens",
  "required": [
    "data",
   ],
  "properties": {
    "keywords": {
      "type": "array",
      "description": "keywords to identify characteristics of genes",
      "items": {
        "type": "object",
        "description": "Abbreviated name of genes, length of gene in base pairs and accession number of genes",
        "examples": [
          "DDX58",
          "78023",
          "12575"
         ]}
        }
       }
}
