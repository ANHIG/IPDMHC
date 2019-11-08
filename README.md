--------------------------------------------------------------------------------
 IPD-MHC Database
--------------------------------------------------------------------------------

This directory contains data for the IPD-MHC database. The IPD-MHC database is a specialist sequence database for sequences of the non-human major histocompatibility complex. This directory contains the IPD-MHC flat files and documentation. 

--------------------------------------------------------------------------------
Downloading and Cloning This Repository 
--------------------------------------------------------------------------------

Due to the increasing file size for the MHC.dat, the repository now requires the use of the Git LFS tools (https://git-lfs.github.com) which handle files over 100MB. Please use these when cloning to ensure the larger files are downloaded correctly. If Git LFS is not used then large files will contain pointers to the Git LFS location rather than the data required. 

--------------------------------------------------------------------------------
File Formats 
--------------------------------------------------------------------------------

The top-level directory contains the following files; 

* LICENCE.md - a file detailing the licensing of data included in the IPD-MHC Database.
* README.md - This README file
* MHC.dat - An EMBL-ENA style format file containing data from the IPD-MHC Database, see http://www.ebi.ac.uk/ipd/imgt/hla/docs/manual.html for further details.
* MHC_gen.fasta - a copy of the file in the fasta directory, includes the DNA sequence for all alleles, which have genomic sequences available. 
* MHC_nuc.fasta - a copy of the file in the fasta directory, includes the DNA sequence for the CDS sequence of all alleles. 
* MHC_prot.fasta - a copy of the file in the fasta directory, includes the amino acid sequence for all alleles. 

--------------------------------------------------------------------------------
 CONTACTS
--------------------------------------------------------------------------------

For information on the IPD-MHC Database please see the website at:
http://www.ebi.ac.uk/ipd/mhc

For any other information please contact hla@alleles.org.

--------------------------------------------------------------------------------
 COPYRIGHT NOTICE
--------------------------------------------------------------------------------

We have chosen to apply the Creative Commons Attribution-NoDerivs License to all
copyrightable parts of our databases, which includes the sequence alignments.
This means that you are free to copy, distribute, display and make commercial
use of the databases in all legislations, provided you give us credit by citing
the following;

Robinson J, Halliwell JA, Hayhurst JH, Flicek P, Parham P, Marsh SGE:
The IPD and IPD-MHC Database: allele variant databases
Nucleic Acids Research (2015), 43:D423-431

We are strongly opposed to the mirroring of the data contained on our sites, both
hla.alleles.org and the IPD-MHC Database, and would ask that rather than mirror
the information, appropriate links are provided where applicable.

If you intend to distribute a modified version of our data, you must ask us for
permission first, please contact hla [at] alleles [dot] org for further details
of how modified data can be reproduced.

--------------------------------------------------------------------------------
 DISCLAIMER
--------------------------------------------------------------------------------

Where discrepancies have arisen between reported sequences and those stored in
the database, the original authors have been contacted where possible, and
necessary amendments to published sequences have been incorporated. Future
sequencing may identify errors and the WHO Nomenclature Committee would welcome
any evidence that helps to maintain the accuracy of the database. We therefore
make no warranties regarding the correctness of the data, and disclaim liability
for damages resulting from its use. We cannot provide unrestricted permission
regarding the use of the data, as some data may be covered by patents or other
rights. Any medical or genetic information is provided for research, educational
and informational purposes only. It is not in any way intended to be used as a
substitute for professional medical advice, diagnosis, treatment or care.

We reserve the right to use information about visitors (IP addresses), date/time
visited, page visited, referring website, etc. for site usage statistics and to
improve our services.