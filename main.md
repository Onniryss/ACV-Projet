# Projet ACV

## To-do list

- [x] unité fonctionnelle
- [x] flux de référence
- [x] proposer un type d'allocation physique
- [x] déterminer les flux pour un cahier
- [ ] kilométrage moyen pour la distribution d'un cahier

## UF et flux de référence

> <u>Unité fonctionnelle choisie</u>
>	Ecrire et stocker des données sur 10 m² de papier dans de bonnes conditions selon un usage adapté

> <u>Flux de référence</u>  
> 	surface disponible
> 	aptitude à l'écriture
> 	résistance dans le temps

#### Surface

Nombre de pages : 100
Surface d'une page : $21 \times 29,7 = 623,7 cm² = 6,237 \times 10^{-2} m²$ 
Surface totale : $100 \times 6,237 \times 10^{-2}  = 6,237 m²$
Nombre d'unités fonctionnelles de surface : $\frac{10}{6,237} \approx 1,60$

#### Aptitude à écrire

Transpercement : 3 -> 1 pt
Opacité : 82% -> 3 pt
#### Résistance

Nombre d'éléments : 2 pièces -> 1 pt
Grammage : entre 200 et 350 g/m² -> 3 pt
Type : Polypropylène -> 4 pt
Revêtement : Plastique -> 2 pt
Liaison : spirale -> 3 pt

#### Flux

Total de points : 17 pt
Max de points : 25 pt

$\tau_{performance} = \frac{17}{25} = 0,68$

Flux de référence = $\frac{1,6}{0,68} = 2,35$

### Allocation

L'entreprise produit 90 000 cahiers A4 et 30 000 cahiers A5, on décide donc de compter chaque cahier A5 comme étant un demi cahier A4. On obtient un total équivalent à 105 000 cahiers A4.

| Flux           | Quantié pour 1 UF   |
| -------------- | ------------------- |
| papier recyclé | 1,38312047619048    |
| couverture     | 0,0791390476190476  |
| spiral (acier) | 0,0295652380952381  |
| encre          | 0,00566238095238095 |
| carton         | 0,0093552380952381  |
| PE             | 0,00232761904761905 |
| Bois           | 0,0421433333333333  |
| conso elec     | 3,9032380952381     |
| gaz            | 234,127142857143    |
| pétrole        | 0                   |
