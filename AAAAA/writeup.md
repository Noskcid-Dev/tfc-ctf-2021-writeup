# AAAAA

| Info | Value |
| :--- | :-----: |
| Categories | #Forensics #Warmup |
| Final Score | 50 |
| Total Solve (Rate) | 236/692 (34.1%) |

## Description

AAAAA. That's all

## Attachment
AAAAA

## Writeup

Upon opening the file, except a bunch of code that I don't understand, I spotted `IHDR` (a magic hash that represents a png file). Therefore, I uploaded the file to CyberChef and used "Extract File" tool, which gives me the flag in png (see extracted_at_0x7d0.png). Doing a bit character recognition by hand, we get the flag :)

## Flag
`TFCCTF{Gr4phic_d3sign_is_my_p455ion}`