# Cantus Codex Builder
Anyone who ever organized a [cantus](https://en.wikipedia.org/wiki/Cantus), knows that building a Codex always takes a lot of time. Most of the time, you just recycle an old codex from an earlier Cantus and just settle with the fact that not all songs are in there. Or you spend hours and hours searching for lyrics, only to find shamefull mistakes after printing. 

Not anymore! This repository functions as an archive for most popular cantus songs, in order to make it incredibly easy to build the perfect Codex in minutes.

## How to make a codex
It is very easy to build your own Codex. Simply edit `main.tex` to set a title and image for the Codex, and include the preferred songs using `\input{}` statements. 

Naturally, you can make further changes, for example in the `regularum.tex` file(s). Also, you can make changes to or include your own songs. With sufficient knowledge of LaTeX, this should not be too hard.

Note that [Overleaf](https://www.overleaf.com/) supports opening projects directly from GitHub, which works like a charm!

### Printing
Here are some instructions on how to properly print the PDF as a A5 paper booklet (so on A4 paper sheets), as this is always a challenge.

- Make sure to open the PDF file in Adobe Acrobat PDF reader, as it has a 'booklet' printer setting. 
- Print
- Select 'booklet' as printer setting
- Select 'landscape orientation'
- Print with a 'center staple and fold' option. For example, on a Konica Minolta C754e PS MFP (or similar models, those are very common for many Dutch universities), the full driver should have this as finishing option if the correct options are installed to the device and set in the driver settings (for example, LU-301, FS-535 + JS-602 + SD-512, PK-521 (2/4-Hole)).
- Select grey scale if you pay per page and want to save money. 
- Please, please, always try a single copy first to verify settings.

It is also possible to print booklets without opening the file in Adobe Acrobat, from some Linux systems. In that case, select 'fit to page size', 'booklet' and paper size 'A5'. If you want A5 booklets, the driver will automatically choose A4 paper size for A5 booklets (and choosing A4 paper size will result in A3 paper being used).

Note that for proper printing, the number of pages in your final document should be a multiple of 4 (note that the cover page has page number 0). 

## Contributing
Just as a proper Cantus relies on the community, this repository also heavily relies on the community's contributions! We strongly invite you to add all popular (or unpopular) cantus songs to this repository in a proper way. Please create a PR when you want to add a song and it will gladly be merged, so for the future, other people can use it too. 

Also if you happen to find any typos or other errors in lyrics, please fix them and create a PR!

If there are lyrics missing, you can also create an issue. 

## Intelectual property
I do not posses any form of intelectual property on the songs from which the lyrics are included in this repository (with some exceptions). Many songs will have expired copyright and or be in the public domain. For the songs that are under copyright, we appeal to Fair Use of the material. 

We try to credit the authors of all lyrics. 
