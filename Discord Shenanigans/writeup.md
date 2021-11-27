# DISCORD SHENANIGANS

| Info | Value |
| :--- | :-----: |
| Categories | #Misc #Easy |
| Final Score | 87 |
| Total Solve (Rate) | 95/692 (13.7%) |

## Description

We considered giving you a free flag. However, we decided against it. In general, we would never do that! Or would we? That's the beginning of a good CTF! Discord is the new Twitter.

To be able to solve this challenge, you'll need to join our discord. Link in the Rules page.

## Writeup
Upon checking, the message that is suspicous and at the "beginning of a good CTF" is located at #general, which contains the content of:

```Ｉ dｏn't ｔｈｉnk ｓο ｅⅰtｈeｒ. Τｈey ｓhｏuｌｄ worｋ ｈａrdeｒ foｒ ｔｈese ｆlａｇｓ！ Ｗｈｅｎ I wａs tｈeіr age, Ｉ had tｏ tｒaνeｌ tｈοusａnｄｓ οｆ milｅｓ to get them!```

By the tips/reminder from the challenge authour in Discord, we know that there are a way to hide messages in Twitter's tweets, we googled it and found the [tool](https://holloway.nz/steg/), entering the message and we get: `th1s_5t3g0_fl4g_w45_n0t_h1dden_w3ll    `, putting it in the flag format and removing the spaces, we get the flag!

## Flag
`TFCCTF{th1s_5t3g0_fl4g_w45_n0t_h1dden_w3ll}`