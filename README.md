# DeepWalk i sistemi preporučivanja

DeepWalk [[1]](#1) je algoritam za određivanje niskodimenzionih reprezentacija
čvorova grafa koje enkodiraju informacije o sličnosti čvorova i njihovim
međusobnim odnosima. Zasnovan je na slučajnim šetnjama i Word2Vec modelu za
određivanje latentnih reprezentacija. Prikazana je njegova primena u sistemu
predviđanja korisničkih ocena filmova na *MovieLens 100K* [[2]](#2) skupu
podataka.

## Koraci
- Kreiranje grafa na osnovu podataka, pri čemu su čvorovi filmovi i korisnici
- Kreiranje korpusa - skupa slucajnih setnji kroz graf, za svaki čvor
- Primena Word2Vec modela na korpus u cilju dobijanja vektorskih reprezentacija svakog čvora
- Testiranje dobijenog modela na test skupu, korišćenjem k najbližih suseda u dobijenoj reprezentaciji čvorova

## Literatura
<a id = "1">[1]</a>
Perozzi, Bryan and Al-Rfou, Rami and Skiena, Steven. 2014.
DeepWalk: Online Learning of Social Representations.
Proceedings of the 20th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining.
DOI=http://doi.acm.org/10.1145/2623330.2623732

<a id = "2">[2]</a>
F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets:
History and Context. ACM Transactions on Interactive Intelligent
Systems (TiiS) 5, 4, Article 19 (December 2015), 19 pages.
DOI=http://dx.doi.org/10.1145/2827872

