# Projet ACV

## UF et flux de référence

- Unité fonctionnelle choisie : \
	Ecrire et stocker des données sur 10 m² de papier dans de bonnes conditions selon un usage adapté

 - Flux de référence : \
 	Surface disponible
 	Aptitude à l'écriture
 	Résistance dans le temps

#### Surface

Nombre de pages : 100 \
Surface d'une page : $21 \times 29,7 = 623,7 cm² = 6,237 \times 10^{-2} m²$ \
Surface totale : $100 \times 6,237 \times 10^{-2}  = 6,237 m²$ 

On obtient donc le nombre d'unités fonctionnelles de surface suivant : $\frac{10}{6,237} \approx 1,60 \ \text{UF}$

#### Aptitude à écrire

Transpercement : 3 -> 1 pt \
Opacité : 82% -> 3 pt 

#### Résistance

Nombre d'éléments : 2 pièces -> 1 pt \
Grammage : entre 200 et 350 g/m² -> 3 pt \
Type : Polypropylène -> 4 pt \
Revêtement : Plastique -> 2 pt \
Liaison : spirale -> 3 pt 

#### Flux

Total de points : 17 pt \
Max de points : 25 pt 

$\tau_{performance} = \frac{17}{25} = 0,68$ 

Flux de référence = $\frac{1,6}{0,68} = 2,35$

### Allocation

L'entreprise produit 90 000 cahiers A4 et 30 000 cahiers A5, on décide donc de compter chaque cahier A5 comme étant un demi cahier A4. On obtient un total équivalent à 105 000 cahiers A4. 

| Flux           | Quantité pour 1 UF  |
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

## Kilométrage moyen

Somme pondérée : $\frac{25667\*367+11667\*668+7000\*672+26883\*456+14000\*504+19833\*114}{25667+11667+7000+26883+14000+19833} = \frac{43492955}{105050} \approx 414 \ \text{km}$

Chaque cahier parcours donc environ 414 km.

## ACV d'un cahier

Masse d'un cahier : $\frac{61799+3536+1321+253+418+104+1883}{105000} \approx 0.65 \ \text{kg}$

### Hypothèses

1) On a décidé de négliger l'encre, dans un premier temps parce que on l'a pas trouvé et dans un deuxième temps parce que la masse d'encre sur le cahier est inférieure à 0,4% de la masse totale d'un cahier.

2) Pour le kilométrage, on a décidé de faire une somme pondérée sans compter le fait que les cahiers ne peuvent pas tous être envoyés en un trajet jusqu'à leur destination. 

### Résultats

| **Indicateur**                         | **Pondération** | **Normalisation** | **Données** | **Données normalisées** | **Données pondérées** | **Pourcentage**    | **Somme cumulée** |
| -------------------------------------- | --------------- | ----------------- | ----------- | ----------------------- | --------------------- | ------------------ | ----------------- |
| Radiation ionisante                    | 5,01            | 4,22E+03          | 1,54E+01    | 0,00364928909952607     | 0,0182829383886256    | 52,8722448258271   | 52,8722448258271  |
| Épuisement des ressources énergétiques | 8,32            | 6,50E+04          | 6,29E+01    | 0,000967692307692308    | 0,0080512             | 23,2831839441373   | 76,1554287699644  |
| Changement climatique (CO2)            | 21,06           | 8,10E+03          | 1,53        | 0,000188888888888889    | 0,003978              | 11,5039380129395   | 87,6593667829039  |
| Particules fines                       | 8,96            | 5,95E-04          | 8,14E-08    | 0,000136806722689076    | 0,00122578823529412   | 3,54484461433233   | 91,2042113972362  |
| Formation photochimique d’ozone        | 4,78            | 4,06E+01          | 6,17E-03    | 0,000151970443349754    | 0,000726418719211823  | 2,10072295556855   | 93,3049343528048  |
| Épuisement des ressources minérales    | 7,55            | 6,36E-02          | 5,85E-06    | 9,19811320754717E-05    | 0,000694457547169811  | 2,0082947650225    | 95,3132291178273  |
| Acidification                          | 6,20            | 5,56E+01          | 6,17E-03    | 0,000110971223021583    | 0,000688021582733813  | 1,98968266448826   | 97,3029117823156  |
| Eutrophisation terrestre               | 3,71            | 1,77E+02          | 1,80E-02    | 0,000101694915254237    | 0,00037728813559322   | 1,09107574783356   | 98,3939875301491  |
| Eutrophisation marine                  | 2,96            | 1,95E+01          | 1,99E-03    | 0,000102051282051282    | 0,000302071794871795  | 0,873558371961412  | 99,2675459021105  |
| Eutrophisation eau douce               | 2,80            | 1,61E+00          | 1,07E-04    | 6,64596273291926E-05    | 0,000186086956521739  | 0,538142989653758  | 99,8056888917643  |
| Usage des terres                       | 7,94            | 8,19E+05          | 5,68        | 6,93528693528694E-06    | 5,50661782661783E-05  | 0,15924532463137   | 99,9649342163957  |
| Appauvrissement de la couche d'ozone   | 6,31            | 5,36E-02          | 1,03E-07    | 1,92164179104478E-06    | 1,21255597014925E-05  | 0,0350657836043658 | 100               |


On obtient un impact final de **34,5 mPt/cahier** soit **57,5 mPt/kg**. Ce résultat nous paraît cohérent avec les moyennes que nous trouvé pour un cahier. Les indicateurs les plus touchés sont les radiations ionisantes, l'épuisement des ressources énergétiques et le changement climatique (CO2).
### Étude de sensibilité

1) Kilométrage

En utilisant non plus une moyenne pondérée mais la médiane des distances, on obtient une valeur de kilométrage de 480 km au lieu de 414 km soit une augmentation de 16%.

On obtient un impact de **34,7 mPt/cahier** soit une augmentation de 0,5%. On note aussi que les indicateurs principaux non pas changé après cette modification.

Ces valeurs nous indiquent que l'impact environnemental d'un cahier n'est pas très sensible au kilométrage de la distribution.

2) Fabrication

On cherche maintenant à savoir si cette valeur est sensible au type d'attache utilisée. On utilise maintenant des agrafes.

Le flux de référence n'est pas modifié car les agrafes et la spirale ont le même nombre de points dans le tableau des critères de notation.

On obtient un impact de **32,8 mPt/cahier** soit une diminution de 5% ce qui n'est plus négligeable, d'autant plus que c'est positif pour l'environnement. 

# Conclusion

Dans cette étude, nous avons pu étudier l'impact environnemental d'un cahier. Nous avons pu déterminer que celui influence principalement les **radiations ionisantes**, l'**épuisement des ressources énergétiques** et le **changement climatique**, par sa <u>fabrication</u> plus que par sa distribution. Un des axes d'amélioration trouvé pour réduire l'impact est de changer la façon de relier les pages entres elles, en utilisant par exemple des agraffes au lieu de spirales. Le score trouvé est assez élevé, il suffit en effet de ***29*** cahiers pour dépasser l'impact environnemental d'un européen sur un an, d'où l'intérêt d'imprimer les feuilles d'examen en recto-verso ;) .
