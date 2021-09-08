# Hw1schema
{
"$schema": "http://json-schema.org/draft-07/schema#",
"$ID": 
"Description": "Various characteristics of genes in homosapiens"
"type": "Object"
"required": [
"Name",
"Length",
"Accession Number"
],
"Properties": {
"Name":{
"Type": "string",
"Title": "Name",
"Description": "Name of gene abbreviated",
"Results":[
"DDX58",
"ACE2",
"TP53",
"INS-IGF2",
"HBB"
]},
"Length": {
"Type": "string",
"Title": "Length of gene",
"Description": "Length of gene in base pairs",
"Results": [
"78023",
"90962",
"32772",
"39098",
"10106"
]},
"Accession": {
"Type": "string",
"Title": "Accession number",
"Description": "Accession number of gene",
"Results": [
"046918",
"12575",
"017013",
"050578",
"059281"
]}
}
}
