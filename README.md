# DeepWalk i sistemi preporučivanja


## Primena DeepWalk algoritma na sistem za preporučivanje (movie-lense skup).

## Koraci:
- Kreiranje grafa na osnovu movie-lense100k skupa podataka, pri cemu su cvorovi filmovi i korisnici
- Kreiranje korpusa - skupa slucajnih setnji kroz graf, za svaki cvor
- Primena word2vec na korpus u cilju dobijanja vektorskih reprezentacija svakog čvora
- Testiranje dobijenog modela na test skupu, korišćenjem k najblizih suseda u dobijenoj reprezentaciji čvorova


## Literatura:
- "DeepWalk: Online Learning of Social Representations", Bryan Perozzi, Rami Al-Rfou, Steven Skiena