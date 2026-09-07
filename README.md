# Business Plan - BUT Informatique S5/S6

## Compilation
    latexmk -pdf main.tex

Sur Overleaf : importer le .zip, definir `main.tex` comme document principal,
compilateur **pdfLaTeX**.

## Structure
- `main.tex` : squelette du dossier, appelle chaque section
- `preambule.tex` : styles, couleurs, commandes reutilisables (a modifier une seule fois)
- `sections/` : un fichier par etape, dans l'ordre du dossier du professeur
- `img/` : logos et captures d'ecran
- `annexes/` : documents de recherche a joindre

## A faire avant le premier rendu
1. Deposer `logo-urca.png`, `logo-iut.png`, `logo-entreprise.png` dans `img/`
   puis decommenter les `\includegraphics` dans `sections/00-page-de-garde.tex`
2. Renseigner `\nomentreprise` dans `preambule.tex` (etape VI)
3. Renommer le PDF final :
   BP_Info_S5_Barthelemy_Antoine_Agbe_Simisola_NomEntreprise.pdf
