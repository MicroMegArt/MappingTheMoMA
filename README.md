# MappingTheMoMA

The Museum of Modern Art MoMA have made available the CSV spreadsheet of the entire collections on its [GitHub repository]([url](https://github.com/MuseumofModernArt/collection)) but these files do not include geographical coordinates. 
Therefore, it was necessary to geo-reference the objects, which totalled 153,648 for MoMA. 
The MoMA provides geographical information in the ‘Artist Bio’ field, composed as follows: in brackets, the museum indicates the artist's nationality, then the date of birth and, if the artist is deceased, the year of death. 
The decision has been made, although this is open to debate, to geolocate works on the basis of the artist's nationality, provided that this is unambiguous. 
A ‘reconciliation’ stage with the Wikidata API was conducted on OpenRefine, in order to place artworks in countries. This enabled the coordinate locations to be extracted from the Wikidata database. The technical steps are outlined in a tutorial available [online]([url](https://github.com/ChristopheCariniSiguret/Cartographie_OpenRefine_Palladio_tutoriel/blob/main/Tutoriel_cartogaphie.pdf)) This repository provides the final output file, with the coordinate locations and the Wikidata identifiers. 
Coordinates have been allocated to 99.95\% of the MoMA collection.
