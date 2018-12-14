# ptra
Protein Translation
Problem
The 20 commonly occurring amino acids are abbreviated by using 20 letters from the English alphabet (all letters except for B, J, O, U, X, and Z). Protein strings are constructed from these 20 symbols. The RNA codon table shows the encoding from each RNA codon to the amino acid alphabet.

The Translate tool from the SMS 2 package can be found here in the SMS 2 package

A detailed list of genetic code variants (codon tables) along with indexes representing these codes (1 = standard genetic code, etc.) can be obtained here.

For now, when translating DNA and RNA strings, we will start with the first letter of the string and ignore stop codons.

Given: A DNA string s of length at most 10 kbp, and a protein string translated by s.

Return: The index of the genetic code variant that was used for translation. (If multiple solutions exist, you may return any one.)
