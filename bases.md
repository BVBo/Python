# Assignation d'une valeur à une variable

- Python est un langage dynamique et fortement typé
- **Dynamique** : pas besoin de dire à Python quel est le type de la variable 
>- a = "ville" ou a = 75 
- **Fotement typé** : on peut changer le type d'une variable à tout moment
- on ne peut pas additionner deux variables de types différents

## Affectation simple
**nom** = valeur 

## Affectation parallèle
a, b = 5, 8
inversion de valeur a, b = b, a

## Afectation multiples
a = b = c = 5

# Règles et conventions
 
- Mettre un espace avant et après le signe "="
- le nom d'une variable doit commencet par une lettre ou "_"
- le nom d'une variable ne peut contenir que des lettres, des nombres et des "_"
- l'usage des caractères spéciaux dans les noms de nos variables n'est pas permis (Python 3 accepte les accents).
- les noms de variables sonty sensibles à la casse
- nom de variables en miniscule "nom_de_famille"
- nom de variable réservés, comme "False" "True" "Print"
 
# Fonctions de base

## Fonctions de conversion
 
- int()
- str()
- Bien penser affecter le retour d'une fonction de conversion à une variable = = in(a)
 
 ## Fonction type()
 
- Permet de connaître le type d'une variable
 
## Concaténation
 
- fString

```python
a = 5
b = 10
f"La multiplicatin de {a} par {b} est égale à {a*b}!" 
#"La multiplication de 5 par 10 est égale à 50!"
```
```python
protocole = "https://"
nom_du_site = "Docstring"
extension = "fr"
url = f"{protocole}www.{nom_du_site.lower()}.{extension}"  # https://www.docstring.fr
 ```
[Fiche détaillée sur la concaténation](https://www.docstring.fr/blog/le-formatage-des-chaines-de-caracteres-avec-python/)
 
 
 
