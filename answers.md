# CMPS 2200 Recitation 6
## Answers

**Name:** Izzy Blair


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt    |        1340         |       826      | 0.616
alice29.txt    |         1039367     |       676374   |   0.651
asyoulik.txt    |        876253       |       606448   |  0.692
grammar.lsp    |          26047      |       17356    |  0.666
fields.c    |         78050       |       56206    |  0.720


fixed-length coding is about 2/3 as efficient as huffman, as fixed-length coding is always between 0.616 and 0.720 for the ratio.

- **e.**
The expected cost for such a document using Huffman encoding would be higher than it would be for fixed-length encoding because Huffman coding is meant for characters with different frequencies. The expected cost would just be the length of the code (logn), since all characters have the same frequency.
It would be consistent across documents so long as the character frequency is the same--if its not the same, then the cost will change.


