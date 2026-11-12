# python-statistiques-boucles
Fonctions de statistiques écrites en Python sans bibliothèque ainsi que l'usage de boucles for et while

## Contenu

Le notebook `BOUCLES ET FONCTIONS_Exercices.ipynb` regroupe 11 exercices :

- accumuler une valeur (somme, compteur) ;
- filtrer et construire des listes avec `append` ;
- chercher un élément et s'arrêter dès qu'on le trouve ;
- utiliser une boucle `while`.

## Exemple

```python
def moyenne_valide(notes):
    valides = []
    for note in notes:
        if 0 <= note <= 20:
            valides.append(note)
    if len(valides) == 0:
        return 0
    return sum(valides) / len(valides)

print(moyenne_valide([12, 15, -1, 18, 25, 9]))   # 13.5
```

## Ce que j'ai appris

Les boucles, les accumulateurs, la position du `return`, et le débogage de mes propres erreurs.

## Outils

Python, Jupyter, VS Code.
