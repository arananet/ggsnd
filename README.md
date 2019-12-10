# ggsnd
GameGear Sound board replacement with stereo output.

This tiny board allow to add or replace a broken GameGear sound board damaged by capacitor leak. It has been redesigned to use a TDA2822 smd version and also has been simplified for better and easy build.

The original GameGear soundboard has only mono output, because GG has only one speaker, but with this board you can add a second 4 ohm speaker and have stereo output, the same as when we use a headphone.

# Note

This is a work in progress, several testing must be made but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board. USE AT YOUR OWN RISK!

If you like the project, buy me a beer or at least say thanks :) info@arananet.net


# Images

<img src="https://github.com/arananet/ggsnd/blob/master/images/top.png?raw=true" width="400">
<img src="https://github.com/arananet/ggsnd/blob/master/images/bottom.png?raw=true" width="400">

# BOM 

| Part            | Value                   | Package                        |
| --------------- | ----------------------- | ------------------------------ |      
|  C1             | 10uf                   | C0805                           |
|  C2             | 100UF                  | E2-5                            |
|  C3             | 100UF                  | E2-5                            |
|  C4             | 100UF                  | E2-5                            |
|  C5             | 100UF                  | E2-5                            |
|  C6             | 100nf                  | C0805                           |
|  C7             | 100nf                  | C0805                           |
|  IC1            | TDA2822D013TR          | SOIC127P600X175-8N              |
|  R1             | 4.7R                   | R0805                           |
|  R2             | 4.7R                   | R0805                           |
|  R3             | 10K                    | RK10J12E0A0A (5 pin std pot)    |
|  AUDIO2         | AUDIO-JACK             | 3.5mm Standard Jack             |

# Updates

10/12/2019 Initial release.

# Gerber info

Gerbers are available on the gerbers folder. 1.6mm standard pcb is compatible with the design and the GG.

# License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
