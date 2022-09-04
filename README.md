# `corr_OCR_NER` - Impact de la correction automatique d'OCR sur la REN

Ce dépôt répertorie les données et les scripts pour l'évaluation de l'impact de la correction automatique du texte océrisé sur la tâche de reconnaissance d'entités nommées dans un corpus bruité.



## *Workflow*

<p align="center">
  <img src="img/workflow_corr_ocr_ren.jpg">
</p> 


## Structure du dépôt

```
├── .ipynb_checkpoints
├── csv_corr
│     ├── EN_corr_lg_3.csv
│     ├── EN_corr_lg_6.csv
│     ├── EN_corr_lg_9.csv
├── csv_non_corr
│     ├── EN_non_corr_lg_3.csv
│     ├── EN_non_corr_lg_6.csv
│     ├── EN_non_corr_lg_9.csv
├── diffs
│     ├── README.md
│     ├── changements.txt
│     ├── changements_types.csv
│     ├── diff.html
├── img
│     ├── diff_html
│     ├── map_corr.png
│     ├── map_non_corr.png
│     ├── workflow_corr_ocr_ren.jpg
├── scripts
│     ├── README.md
│     ├── extraire_EN_xml_csv.ipynb
│     ├── jamspell_xml_txt.ipynb
├── tanagra
│     ├── README.md
│     ├── tanagra_corr.csv
│     ├── tanagra_non_corr.csv
├── test
│     ├── 5401000_r.xml
│     ├── 5406000_r.xml
│     ├── 5408000_r.xml
│     ├── 5416000_r.xml
│     ├── 5419000_r.xml
│     ├── 5426000_r.xml
│     ├── 5427000_r.xml
│     ├── 5428000_r.xml
│     ├── 5431000_r.xml
├── txt_corr
│     ├── txt_corr_3_out.txt
│     ├── txt_corr_6_out.txt
│     ├── txt_corr_9_out.txt
├── txt_non_corr
│     ├── txt_non_corr_3.txt
│     ├── txt_non_corr_6.txt
│     ├── txt_non_corr_9.txt
├── .gitignore
├── README.md
```



## Données

* `csv_corr` : les tableurs répertoriant les EN après la correction d'OCR
* `csv_non_corr` : les tableurs répertoriant les EN avant la correction d'OCR
* `diffs` : les différences entre les EN avant et après la correction post-OCR
* `img` : les illustrations
* `scripts` : les scripts de l'extraction des EN avec [`spacy`](https://spacy.io/models/fr) et de la correction post-OCR avec [`jamspell`](https://github.com/bakwc/JamSpell)
* `tanagra` : les listes des EN cartographiées par [Tanagra](https://obtic.sorbonne-universite.fr/tanagra/home) avant et après la correction post-OCR
* `test` : les fichiers XML-TEI sources
* `txt_corr` : les fichiers .txt corrigés
* `txt_non_corr` : un fichier texte brut extrait à partir de la balise `<body>` des fichiers `test` 



## Remerciements

Les données issues du projet TGB (*Très Grande Bibliothèque*) sont fournies grâce à Motasem Alrahabi. 

Merci également à Motasem Alrahabi et à Glenn Roe pour leur encadrement et leur aide précieuse sur la problématisation de la recherche de ce travail.



## Contact
Ljudmila PETKOVIC : ljudmila.petkovic[at]etu.sorbonne-universite.fr

Motasem ALRAHABI : motasem.alrahabi[at]sorbonne-universite.fr

Glenn ROE : glenn.roe[at]sorbonne-universite.fr



## Citer ce dataset

Ljudmila Petkovic, Motasem Alrahabi & Glenn Roe - *corr_OCR_NER : Impact de la correction automatique d'OCR sur la REN*, 2022, Paris : Sorbonne Université | ObTIC https://github.com/ljpetkovic/corr_OCR_NER.



## Licence

![68747470733a2f2f692e6372656174697665636f6d6d6f6e732e6f72672f6c2f62792f322e302f38387833312e706e67](https://user-images.githubusercontent.com/56683417/115237678-2150d080-a11d-11eb-903e-5a26587e12e1.png)





