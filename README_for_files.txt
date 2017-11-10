// July 21, 2015
// Daniel Larremore
// Harvard T.H. Chan School of Public Health
// http://danlarremore.com


// README for data associated with publication:

	"A network approach to analyzing highly recombinant malaria parasite genes"
	Daniel B. Larremore, Aaron Clauset, and Caroline O. Buckee. 
	PLoS Computational Biology 9(10), e1003268, (2013).

	Available at http://danlarremore.com/

// Contact
	Dan Larremore
	http://danlarremore.com
	

// Contents:
	* HVR_n.txt
		9 networks derived from the same set of 307 genetic sequences from var genes of malaria parasites. Each network is in a separate .txt file as a list of pairs of adjacent vertices. Note that all 9 networks share the same set of vertices, but different edges. In other words, vertex n of HVR1 corresponds to the same gene as vertex n of HVR2, HVR3, etc. 
	* metadata_CysPoLV.txt
		P. falciparum var genes can be divided into six "Cys-PoLV" groups, based on sequence content. See the paper and references therein for meaning and derivation. Six categories are labeled with integers 1,2,...,6. Ordering is the same as the HVR_n.txt networks.
	* metadata_UPS.txt
		P. falciparum var genes can be divided into groups based on their upstream promoter sequence (UPS). The three groups A, B, and C are labeled with integers 1, 2, and 3, respectively. Some sequences did not have any UPS identified, and these are labeled with NaN. Ordering is the same as the HVR_n.txt networks.
	* rask_et_al_DBLa.fasta
		Fasta format for the 307 sequences. These come from Rask et al. Ordering is the same as the HVR_n.txt networks.


// How to Cite: 
	* Cite network data set as: Larremore, D. B., Clauset, A., and Buckee, C. O. (2013). A Network Approach to Analyzing Highly Recombinant Malaria Parasite Genes. PLoS Computational Biology, 9(10), e1003268.
	* Cite original (larger, non-network) genetic data set as: Rask, T. S. et al. (2010). Plasmodium falciparum Erythrocyte Membrane Protein 1 Diversity in Seven Genomes â€“ Divide and Conquer. PLoS Computational Biology, 6(9), e1000933.

