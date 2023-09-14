# Needleman-Wunsch-Algorithm
In this project we are going to implement a specific algorithm which is 
called ”Needleman-Wunsch”.
This algorithm is used to find the global sequence alignment (not the local 
alignment) between two DNA sequences or between two protein sequences.
After implement it we need to test it:
 - Firstly we want to test it using two homologous genes that are differing 
around 10% and the testing should be using two different scoring 
functions(match, mismatch, gap).
For these two homologous I chose a gene called ”lysine acetyltransferase 5 
(KAT5)” also known as “TIP60” from Humans(Homo Sapiens)(ref:1) and 
Sperm Whales(Physeter catodon)(ref:2) because this exact gene is quite 
similar between these two species, and it’s an interesting gene.
What is ”lysine acetyltransferase 5 (KAT5)” exactly?
The protein encoded by this gene belongs to the MYST family of histone 
acetyl transferases (HATs) and was originally isolated as an HIV-1 TATinteractive protein. HATs play important roles in regulating chromatin 
remodeling, transcription and other nuclear processes by acetylating histone 
and nonhistone proteins. This protein is a histone acetylase that has a role in 
DNA repair and apoptosis and is thought to play an important role in signal 
transduction. Alternative splicing of this gene results in multiple transcript 
variants. (ref: 3).
 - Secondly we are going to do the same thing as above but with other two 
sequences, Human Insulin Protein and Hamster Insulin Protein.
