# SEA LANGUAGE 2

| Info | Value |
| :--- | :-----: |
| Categories | #Crypto #Easy |
| Final Score | 50 |
| Total Solve (Rate) | 189/692 (27.3%) |

## Description

That's just another way to......

## Attachment
sl2.txt

## Writeup

Upon opening the message, I am pretty sure it is morse code again. Using CyberChef "From Morse Code" tool, it returned me nothing, so I started looking about the Morse code again.

Upon looking, I've spotted that each word are seperated by 8 dots or underscores, which means they're probably coded in binary, I know the flag starts from TFCCTF, so I converted T to ASCII Binary by CyberChef, which proves that I am right, dot represents 0 and underscore represents 1. Using a basic find and replace function, and inserting that into CyberChef with "From Binary", we get the flag!

## Flag
`TFCCTF{w417_4_m1nu73..._7h15_1s_n07_m0rs3!!!!!r1gh7?}`