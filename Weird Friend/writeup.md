# WEIRD FRIEND

| Info | Value |
| :--- | :-----: |
| Categories | #Misc #Easy |
| Final Score | 87 |
| Total Solve (Rate) | 95/692 (13.7%) |

## Description

My weird friend did it again! I gave him my list of questions and asked him for a quick response. He took things literally and this is what he gave me!? Can you make any sense of it?

## Attachments
weird_friend.txt

## Writeup

The word "quick response" leads me to "QR Code". By entering the content into [Binary to QR Code Tool](https://bahamas10.github.io/binary-to-qrcode/), we get the QR code.

Well ... IT people are lazy as we don't want to type the flag our own so we downloaded the QR code (`qr.png`) and entered it into CyberChef, using the Parse QR Code and normalize image tool, we get our flag.

## Flag
`TFCCTF{why_ar3_QR_C0d3s_s0-complicated!?o00o0f}`