# GGSND
GameGear Sound board replacement with stereo output.

This tiny board allow to add or replace a broken GameGear sound board damaged by capacitor leak. It has been redesigned to use a TDA2822 smd version and also has been simplified for better and easy build.

The original GameGear soundboard has only mono output, because GG has only one speaker, but with this board you can add a second 4 ohm speaker and have stereo output, the same as when we use a headphone.

# Note

### THIS DESIGN OR THE RESULTING PCB IS PROHIBITED TO SALE ON EBAY.

This is a work in progress, several testing must be made but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board. USE AT YOUR OWN RISK!

If you like the project or want to support it, you can buy me a beer or a KO-FI :) 
[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H51MPWG)


# Images

<img src="https://github.com/arananet/ggsnd/blob/master/images/top.png?raw=true" width="400">
<img src="https://github.com/arananet/ggsnd/blob/master/images/bottom.png?raw=true" width="400">

# BOM 

| Part            | Value                   | Package                             |
| --------------- | ----------------------- | ----------------------------------- |      
|  C1             | 10uf                   | C0805                                |
|  C2             | 100UF - 16v                | ELECTROLYTIC CAPACITOR 2.54 mm, diameter 6 mm                                 |
|  C3             | 100UF - 16v                  | ELECTROLYTIC CAPACITOR 2.54 mm, diameter 6 mm                                |
|  C4             | 100UF - 16v                 | ELECTROLYTIC CAPACITOR 2.54 mm, diameter 6 mm                                 |
|  C5             | 100UF - 16v                 | ELECTROLYTIC CAPACITOR 2.54 mm, diameter 6 mm                                 |
|  C6             | 100nf                  | C0805                                |
|  C7             | 100nf                  | C0805                                |
|  IC1            | TDA2822D               | SOIC-8                  |
|  R1             | 4.7R                   | R0805                                |
|  R2             | 4.7R                   | R0805                                |
|  R3             | 10K                    | RK10J12E0A0A (5 pin standard pot)    |
|  AUDIO2         | AUDIO-JACK             | 3.5mm Standard Jack                  |
|  SPK1           | SPK1                   | B2B-PH-K-S(LF)(SN) JST 2 pin         |
|  SPK2           | SPK2                   | B2B-PH-K-S(LF)(SN) JST 2 pin         |
|  CONN1          | CONN1                  | B6B-PH-K-S(LF)(SN) JST 6 pin         |

Note: JST connectors from the audioboard are now obsolete but those proposed can be valid but maybe need to be modified to plug the original connectors.

# Updates

10/12/2019 Initial release.

# Gerber info

Gerbers are available on the gerbers folder.

# PCB information for manufacturers.

Layers : 2 layers

Dimensions : 31 x 55 mm

Blind/Buried Via: No

Material : Normal FR-4 Board TG140

Thickness : 1.2 mm

Surface Finish : HASL lead free

Silkscreen : Any color


# License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
