# LOST MY HEAD

| Info | Value |
| :--- | :-----: |
| Categories | #Misc #Medium |
| Final Score | 50 |
| Total Solve (Rate) | 153/692 (22.1%) |

## Description

Oh no! Help! I've lost my head! Can you tell me the street name of the trash bin I lost it in? Maybe I can still find it...

Flag format: TFCCTF{street_name_and_street_number_as_seen_on_google_maps_separated_by_underscores}

## Attachments

img.heic

## Writeup

Upon downloading the image, I checked the image properties (metadata) by online metadata checking [tool](https://www.metadata2go.com/), and found the GPS location, as it said street name and street number as seen on Google Map in the description.

Upon entering the GPS Latitude and Longitude into Google Map (`46°46'50.74"N, 23°36'54.26" E`), we get the [location](https://www.google.com/maps/place/46%C2%B046'50.7%22N+23%C2%B036'54.3%22E/@46.7807611,23.6128835,17z/data=!3m1!4b1!4m5!3m4!1s0x0:0xb2a384aea2227f9f!8m2!3d46.7807611!4d23.6150722), formatting into the flag and we're done!

## Flag
`TFCCTF{Simon_Musat_4}`