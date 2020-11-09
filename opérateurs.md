# Opérateurs mathématiques

- Modulo % : nombre résiduel d'une opération
- Division : Donne un float
- Division entière : nombre entier arrondi d'une opération mathématique
- Puissance **

Pour des calculs plus complexe impotes le module **math**
```python
import math
```
Une fois le module importé, vous pouvez utiliser toutes les fonctions contenues à l'intérieur du module, en préfixant la fonction du nom du module. Par exemple pour calculer une racine carrée :
```python
racine = math.sqrt(16)
print(racine)
#4.0
```

# Opérateurs d'assignation

Incrémenter : 
```python
i += 1
```

# Opérateurs de comparaison

Signe | Définition | Utilisation
--- | --- | ---
=     | Affectation d'une valeur à une variable| `a = 5`
\>=    | Supérieur ou égal à| `x >= 5`
\<=    | Inférieur ou égal à| `y <= 5`
==    | Egal à| isTrue( x == y)
!=    | Différent de| isTrue( x != y)

## Différence entre is et =

```python
a is b
```
Ce code vérifie si l'objet a et l'objet b sont identiques, c'est à dire qu'il on la même adresse id en mémoire
```python
a = 1000
b = 1000
a == b
```
Ce code vérifie si les variables ont la même valeur.Particularité : les nombres [-5;256] ont le même id en mémoire

```python
a = 256
b = 256
a == b
```



# Opérateurs logiques(OR, AND et NOT)

CONDITION 1 | Opérateur | CONDITION 1| = | RESULTAT |
--- | --- | --- | --- | ---
=     | TRUE | and | xxx | yyyy
