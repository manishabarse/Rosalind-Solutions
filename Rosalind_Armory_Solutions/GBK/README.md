# Problem

GenBank comprises several subdivisions:

  1.  `Nucleotide:` a collection of nucleic acid sequences from several sources.
  2.  `Genome Survey Sequence (GSS):` uncharacterized short genomic sequences.
  3.  `Expressed Sequence Tags, (EST):` uncharacterized short cDNA sequences.

Searching the Nucleotide database with general text queries will produce the most relevant results. You can also use a simple query based on protein name, gene name or gene symbol.

To limit your search to only certain kinds of records, you can search using GenBank's Limits page or alternatively use the Filter your results field to select categories of records after a search.

If you cannot find what you are searching for, check how the database interpreted your query by investigating the Search details field on the right side of the page. This field automatically translates your search into standard keywords.

For example, if you search for Drosophila, the Search details field will contain (Drosophila[All Fields]), and you will obtain all entries that mention Drosophila (including all its endosymbionts). You can restrict your search to only organisms belonging to the Drosophila genus by using a search tag and searching for Drosophila[Organism].

**Given:** A genus name, followed by two dates in YYYY/M/D format.

**Return:** The number of Nucleotide GenBank entries for the given genus that were published between the dates specified.

`Sample Dataset`

Anthoxanthum   
2003/7/25     
2005/12/27     

`Sample Output`

7
