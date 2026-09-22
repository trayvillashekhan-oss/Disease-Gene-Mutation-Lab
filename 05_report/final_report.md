FINAL REPORT

From Gene Mutation to Disease: G6PD Deficiency

Name: Shekhan Fredianne C. Trayvilla
Gene: G6PD
Disease: Glucose-6-phosphate dehydrogenase deficiency
Reference transcript: NM_001042351.3
Reference protein: NP_001035810.1


**INTRODUCTION**

G6PD deficiency is an inherited condition caused by changes in the G6PD gene. The G6PD gene produces the glucose-6-phosphate dehydrogenase enzyme, which is important in protecting cells, especially red blood cells, from oxidative stress.

In this activity, the G6PD gene was used to observe how a DNA sequence change can affect the resulting protein. The documented mutation analyzed was NM_001042351.3:c.563C>T, also known as the G6PD Mediterranean variant. This mutation results in the protein change p.Ser188Phe.

The activity also included an artificial mutation, c.563del, to compare the effect of a one-nucleotide deletion with the documented single-nucleotide substitution.


**OBJECTIVES**

The objectives of this activity were to obtain and translate the normal G6PD coding sequence, reproduce a documented G6PD mutation, compare the wild-type and mutant protein sequences, and observe how different types of mutations can affect a predicted protein.

Another objective was to create an artificial mutation and compare its effect with the documented mutation.


**REFERENCE SEQUENCE**

The reference transcript used in the activity was NM_001042351.3 and the corresponding reference protein was NP_001035810.1. The wild-type coding sequence was obtained from NCBI and had a length of 1548 bp.

The wild-type CDS was uploaded to Galaxy and translated using SeqKit in reading frame 1. The resulting predicted protein contained 515 amino acids. The first 10 amino acids were MAEQVALSRT and the last 10 amino acids were TYKANNPHKL.

**DOCUMENTED MUTATION**

The documented mutation analyzed in this activity was NM_001042351.3:c.563C>T, which is associated with the G6PD Mediterranean variant. This mutation involves the substitution of C with T at CDS position 563.

The nucleotide substitution changed the codon from TCC to TTC. As a result, serine at amino acid position 188 was changed to phenylalanine, giving the protein change p.Ser188Phe.

The mutant CDS remained 1548 bp long because no nucleotide was inserted or deleted. After translation in Galaxy using frame 1, the predicted mutant protein was still 515 amino acids long. There was no change in the reading frame and no premature stop codon. Therefore, the documented mutation was classified as a missense mutation.


**WILD-TYPE AND DOCUMENTED MUTANT COMPARISON**

The wild-type and documented mutant proteins were aligned using MAFFT in Galaxy. The alignment showed that the sequences were the same except for the amino acid change at position 188.

The wild-type protein contained serine at this position, while the documented mutant contained phenylalanine. There were no insertions or deletions, and the amino acids after the mutation remained in the same reading frame.


**MOLECULAR CONSEQUENCE**

The c.563C>T mutation changes one nucleotide in the G6PD coding sequence. This changes the codon from TCC to TTC and replaces serine with phenylalanine at amino acid position 188.

G6PD normally helps produce NADPH through the pentose phosphate pathway. NADPH is important for maintaining the antioxidant protection of red blood cells. Changes that reduce normal G6PD enzyme activity can make red blood cells more vulnerable to oxidative stress. This can contribute to the effects seen in G6PD deficiency.

The Galaxy analysis in this activity directly showed the sequence change from Ser188 to Phe. The possible effects on enzyme activity and the disease phenotype are based on published information about G6PD deficiency and should not be interpreted as being directly measured by the translation analysis.


**ARTIFICIAL MUTATION**

For the second experiment, an artificial one-nucleotide deletion was created by deleting C at CDS position 563. The artificial mutation was written as c.563del.

Before translation, it was predicted that deleting one nucleotide would cause a frameshift. The CDS length decreased from 1548 bp to 1547 bp.

After translating the artificial mutant in Galaxy, the prediction was supported. The deletion shifted the reading frame and changed many amino acids after the mutation site. Premature stop codons also appeared in the translated sequence.


**COMPARISON OF THE THREE SEQUENCES**

The wild-type sequence represented the normal reference sequence. The documented c.563C>T mutation was a missense mutation that changed one amino acid without shifting the reading frame.

In comparison, the artificial c.563del mutation had a much larger effect on the predicted protein sequence. Since one nucleotide was deleted, the reading frame shifted and many downstream amino acids became different. Premature stop codons were also observed.

These results show that even mutations occurring at the same CDS position can produce very different sequence effects depending on the type of DNA change.


**CONCLUSION**

This activity showed how changes in a DNA sequence can affect the predicted protein product. The documented G6PD Mediterranean mutation c.563C>T changed the codon from TCC to TTC and resulted in the missense change p.Ser188Phe. It did not change the reading frame or predicted protein length.

The artificial c.563del mutation caused a frameshift and changed many downstream amino acids, with premature stop codons appearing in the translated sequence. Comparing the two mutations showed that the type of mutation plays an important role in determining its effect on the protein sequence.

Galaxy tools such as SeqKit and MAFFT made it possible to translate and compare the sequences. However, the computational translation predicts protein sequences and does not directly measure actual protein expression, stability, or function.

****REFERENCES****

National Center for Biotechnology Information. ClinVar. G6PD c.563C>T (p.Ser188Phe), G6PD Mediterranean, Variation ID 100057.

National Library of Medicine. MedlinePlus Genetics. G6PD gene.

National Library of Medicine. MedlinePlus Genetics. Glucose-6-phosphate dehydrogenase deficiency.

Vulliamy, T., et al. (1988). Diverse point mutations in the human glucose-6-phosphate dehydrogenase gene cause enzyme deficiency and mild or severe hemolytic anemia. Proceedings of the National Academy of Sciences, 85(14), 5171-5175.

National Center for Biotechnology Information. Nucleotide database. G6PD transcript variant 2, NM_001042351.3 and protein NP_001035810.1.
