<!-- ELUCENIA technical documentation · apfel · fr · no clinical/professional/rights approval -->

# Score d’Apfel (nausées et vomissements postopératoires)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/apfel)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Sexe féminin

`fem`

### Non-fumeur

`naofuma`

### Antécédent de nausées et vomissements postopératoires ou de mal des transports

`historia`

### Utilisation prévue d’opioïdes en postopératoire

`opioide`

## Édition de la méthode

Apfel simplifié 1999 : 4 facteurs, 0–4 ; pas le modèle Koivuranta

## Formule documentée

1 point par facteur : sexe féminin, non-fumeur, antécédent de NVPO ou mal des transports, opioïde postopératoire.

## Limites et population

L’Apfel simplifié de 1999 a été étudié chez des adultes sous anesthésie inhalée, sans prophylaxie antiémétique, pour les nausées ou vomissements au cours des premières 24 heures. Les probabilités de la cohorte originale ne sont pas automatiquement recalibrées pour les enfants, d’autres techniques anesthésiques ou les personnes recevant déjà une prophylaxie. La stratégie antiémétique dépend de sa propre évaluation et recommandation.

## Références

- [Apfel CC et al. A simplified risk score for predicting postoperative nausea and vomiting: conclusions from cross-validations between two centers. Anesthesiology, 1999.](https://doi.org/10.1097/00000542-199909000-00022)

- [Gan TJ et al. Fourth consensus guidelines for the management of postoperative nausea and vomiting. Anesth Analg, 2020.](https://doi.org/10.1213/ANE.0000000000004833)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Risque de NVPO d’environ 10%

La prophylaxie est généralement inutile, sauf en présence d’autres facteurs.


### 2

Risque de NVPO d’environ 39%

Prophylaxie avec 2 antiémétiques de classes différentes.


### 3

Risque de NVPO d’environ 79%

Prophylaxie multimodale avec 3 à 4 interventions ; envisager une anesthésie intraveineuse totale.

