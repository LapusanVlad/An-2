# Hangman Solver

Solver automat pentru jocul Hangman.

## Cerințe
- Python 3.6+
- librarii os, csv si random

## Cum rulez
```bash
python src/PR1.py

Structura input:
game_id;pattern;cuvant_tinta
1;******RA**;ICONOGRAFĂ
2;*A**C****;FAGOCITUL

Structura output se generează results/out.csv cu:
game_id,total_incercari,cuvant_gasit,status,secventa_incercari
1,9,ICONOGRAFĂ,OK,e i o n g f r a ă

Limitări:
Folosește randomizare parțială
Uneori propune direct cuvântul
