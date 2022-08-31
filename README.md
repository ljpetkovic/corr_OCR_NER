# corr_OCR_NER

- AF



# *Workflow*

```
![Figure](workflow_corr_ocr_ren.jpg)
```

- Pour retirer les lignes vides après l’extraction du texte brut à partir de la balise `<body>` :

  `ex -s +'v/\S/d' -cwq txt_non_corr.txt`

