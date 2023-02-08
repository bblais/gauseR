# Paramecium competition experiment

A dataset containing the abundances of two Paramecium species
grown in monoculture and mixture. Note, is for the same experiment
as gause_book_1934_f22, except that data were digitized separately,
and therefore have small variations. These might be useful for
estimating observation error in the data digitization process.
"Volume" refers to a standardized index, meant to make the abundances
of species comparable based on their relative sizes.

### A data frame with 63 rows and 4 variables:

- **Paper**: Paper from which data are drawn
- **Figure**: Figure number in paper
- **Day**: Day of experiment
- **Species1**: Name of Species 1
- **Volume_Species1**: Volume of Paramecium caudatum
- **Species2**: Name of Species 2
- **Volume_Species2**: Volume of Paramecium aurelia
- **Treatment**: Treatments: Pa and Pc moncultures, or mixture

### Source: Gause (1934) Experimental Analysis of Vito Volterra's Mathematical Theory of the Struggle for Existence. Science 79:16-17.
### Filename: gause_1934_science_f02_03.csv from https://github.com/adamtclark/gauseR