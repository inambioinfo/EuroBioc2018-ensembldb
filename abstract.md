# `ensembldb`: coordinate mapping between the genome, exome, transcriptome and proteome

The `ensembldb` package provides functions to create and use Ensembl-based
annotation databases. Along with genomic coordinates of all genes, transcripts
and exons for a certain species, these `EnsDb` databases contain also protein
related annotations including the protein's amino acid sequence, Uniprot
accessions and protein domains within the amino acid sequences. Beginning with
version 2.4, `ensembldb` provides also functions for the mapping of arbitrary
positions between the genome, exome, transcriptome and proteome. This
presentation showcases this new functionality which enables for example the
mapping of the position of genetic variants to the corresponding amino acid in
the encoded protein or the identification of genomic regions encoding certain
peptides within a protein.
