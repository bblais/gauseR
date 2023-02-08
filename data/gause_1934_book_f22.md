# Paramecium competition experiment

A dataset containing the abundances of two Paramecium species
grown in monoculture and mixture. Note, is for the same experiment
as gause_1934_science_f02_03, except that data were digitized separately,
and therefore have small variations. These might be useful for
estimating observation error in the data digitization process.
"Volume" refers to a standardized index, meant to make the abundances
of species comparable based on their relative sizes.

### A data frame with 72 rows and 4 variables:

- **Paper**: Paper from which data are drawn
- **Figure**: Figure number in paper
- **Day**: Day of experiment
- **Species1**: Name of Species 1
- **Volume_Species1**: Volume of Paramecium caudatum
- **Species2**: Name of Species 2
- **Volume_Species2**: Volume of Paramecium aurelia
- **Treatment**: Treatments: Pa and Pc moncultures, or mixture

### Source: Gause (1934) The Struggle for Existence. Dover Publications; Reprint edition.
### Filename: gause_1934_book_f22.csv from https://github.com/adamtclark/gauseR