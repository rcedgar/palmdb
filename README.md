![PALMdb](http://drive5.com/images/palmdb_header.png)

## Introduction

**PALM**db is a database of viral polymerase palmprint (barcode) sequences classified by (1) taxonomy and (2) operational taxonomic units (OTUs) obtained by sequence clustering.

### Palmprint sequence

![PALMdb](http://drive5.com/images/palm_structure_figure.png)

The palmprint is a ~100aa segment of the viral polymerase gene delineated by the conserved catalytic motifs "A" and "C" in the palm sub-domain.

## Files

Releases are posted in sub-directories named `YYYY-MM-DD` giving the date the release was posted. Files are in FASTA (for sequences) or tab-separated values (TSV, for annotations). Files and formats are subject to change between releases.

```
YYYY-MM-DD/
	+--- acc_taxid.tsv         # 1. source accession 2. NCBI TaxID
	+--- acc_u.tsv             # 1. source accession 2. unique sequence identifier u<nnn>
	+--- otu_centroids.fa      # OTU centroid sequences
	+--- sources.fa            # palmprints from all source databases
	+--- species_ncbi_ictv.tsv # 1. species name 2. bothdbs/onedb 3. NCBI TaxID 4. ICTV Version.SortID
	+--- taxon.tsv             # 1. NCBI TaxID 2. name 3. clade names superkingdom...species
	+--- u_otu.tsv             # 1. u<nnn> 2. u<nnn> of OTU centroid
	+--- uniques.fa            # unique sequences from sources.fa, relabeled as u<nnn>
```
