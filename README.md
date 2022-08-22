#QSPdatabase  
Microbes are able to monitor their population density through the release of pheromones known as quorum sensing (QS) signals. With the development of High-throughput sequencing technology, a specific database for QS-related sequences annotation is urgently needed.Here, Hidden Markov Models for 38 kinds of QS-related proteins were built using a total of 4024 collected seed sequences. Based on both homolog search and keywords confirmation against the NR database, we established a Quorum Sensing related protein (QSP) database including 809721 protein sequences and 186133 nucleotide sequences.

##QSP_pro.fasta  
This file contains all protein sequences in fasta format. The QS type of each sequences is labelled using "QStype%" ahead of the accession number.  
e.g.
>&gt;LuxI%WP_171430487.1 acyl-homoserine-lactone synthase AbaI [Acinetobacter lactucae]  
MEALVMNVIAGFQNNFSEGLYTKFKNYRYRVFVEYLGWELNCPNHEELDQFDKVDTAYVV
AQDEEFNIIGCARLLPTTQPYLLGEIFPQLLNGMPIPCSPKIWELSRFSAMDFSNPPSSA
SHAVSSPVSIAILQEAINFARKQGAKQLITTSPLGVERLLRAAGFRAHRAGPPMVIDGYS
MFACLIEV

##QSP_nuc.txt  
This file contains all nucleotide sequences in table format seperated by "\t".  
e.g.
>Column I: LuxI #QS Type  
Column II: KUJ85314.1 #Protein accession number  
Column III: N-acyl-L-homoserine lactone synthetase [Ruegeria marisrubri] #Protein annotation  
Column IV: LQBQ01000002.1 #Nucleotide accession number  
Column V: ATGAGTTTTCGCAGCATGCATGAACACGGCACGCTGCTTACGAAGTATCTCGAGGCGCGAAAATCCATCTTCATCGACCGATTGCACTGGCAGGTGGGCGAAGTCGATGGGATGGAGTTCGACCAGTATGACACGCCGGCCTGCCGCTGGGTGGTGCTCCATGAATTCGGTGAGATAATCGGTGGGGTGCGACTGCTCCCTACCACGGCAGAATGCGGTATCTATAGCTACATGTTGCGAGATGCGCAGAGGGGCCTCCTCGCGAGTTTGCCGACGGATGTGCTGTTTTTCGAAGCACCGGTAAATCCGAATATCTGGGAGGCCTCGCGATTCTTCATCACGGATATCGTTCCGTCGGCGCGCCGAGCCGTCGTTCAGCAAGAGCTGTTTCGCAACATGACGCTGGCTGCGAAGGAAAACGGCGCATCCAGGTTGCTTGGGATCGTCCCCGCAGTTTGGTCCCGGTGGTCGCGGCGACTGGGGGTTGGGGCCACACCCATTGGCGCGAAATTCTCTATTGACGGAACCGTCAGTCAATCCGTGTTGTTCAATATTTATGGCCATACGAACTAG #Nucleotide sequence

##QSP_subtype_information.txt  
This file contains the subtype information of proteins and the blastp result with seed sequences.  
e.g.
>Acylase%MBK8282738.1	HSLs-Acylase-AiiC	31.1	823	486	22	33	807	57	846	1.38e-105	336

##QSP_seed.fasta  
This file contains seed sequences in fasta format.  
e.g.
>&gt;AHKs-CqsA-CqsA  
MSDKPKTKPLPSFVEGRLDFYIQDLIEQNENQKHLVLGKRPQQGAVVMQSNDYLSLSHNL
QIQQAHRDAIYEHDDNVVMSAIFLQDDDSKPAFETQLAEYVGMGSCLLSQSGWAANIGLL
QTICPPETPVYIDFFAHMSLWEGIRAAGAQAHPFMHNNMNHLRKQIQRNGSGVIVVDSVY
STIGTIAPLRDIYEMAREFDCALVVDESHSLGTHGPNGSGLVKALELTEQVDFITVSLAK
TFAYRAGAILGPEKLARTLPFVAFPAIFSSTVLPQEIVRLEKTLEVIRSADDKRTMLFKR
AKELRTGLKQIGFHIRSESQIVALECGSERNTERVRDFLEERNVFGAVFCRPATGKNKNI
IRFSINADMTSRDIDHVLTACQEAYNHPELEFA

##Cite  
QSP: an open sequence database for quorum sensing related gene analysis with an automatic annotation pipeline.  