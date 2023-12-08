# Genomicanalysis
You are working on a genetics research project and have been tasked with creating a C program to analyze genetic 
sequences. Genetic sequences are represented as strings of characters (A: Adenine, T: Thymine, C: Cytosine, and G: 
Guanine), where each character represents a nucleotide in the DNA sequence. 
You need to develop a C program that performs basic analysis on genetic sequences provided by the user. The program 
will use dynamic memory allocation to store the genetic sequences and arrays to store the analysis results. The program 
will have the following functionalities: 
1. Input Genetic Sequences: The program should prompt the user to input a number of genetic sequences. Each 
sequence should be stored dynamically in memory. 
2. Analysis Functions: 
a. Count Nucleotides: Write a function that takes a genetic sequence as input and counts the occurrences of 
each nucleotide (A, C, G, and T) in that sequence. Store the counts in an array. 
b. Calculate GC Content: Write a function that calculates the GC content (the percentage of G and C 
nucleotides) of a genetic sequence. Store the GC content in an array. The GC content of a DNA sequence 
is calculated using the following formula: 
𝐺𝐶 𝐶𝑜𝑛𝑡𝑒𝑛𝑡 = 
𝑁𝑢𝑚𝑏𝑒𝑟 𝑜𝑓 𝐺 𝑎𝑛𝑑 𝐶 𝑛𝑢𝑐𝑙𝑒𝑜𝑡𝑖𝑑𝑒𝑠
𝑇𝑜𝑡𝑎𝑙 𝑛𝑢𝑚𝑏𝑒𝑟 𝑜𝑓 𝑛𝑢𝑐𝑙𝑒𝑜𝑡𝑖𝑑𝑒𝑠 × 𝟏𝟎𝟎
3. Display Results: After analyzing all the input sequences, display the analysis results for each sequence. 
Display the counts of each nucleotide and the calculated GC content.
