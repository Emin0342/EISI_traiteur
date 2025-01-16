# Review code Colas

- EX3 : 

Malheureusement, le code ne peut pas run et je ne peux pas le tester.

Colas a utiliser des print pour afficher ce qu'il était sencé afficher : 
```python      
entete = [' '*10, 'moy', 'min', 'max']
ligne1 = ['chambrefroide01', 3.4, 2.5, 6.4]
ligne2 = ['chambrefroide02', 2.8, 2.5, 4.1]
ligne3 = ['chambrefroide03', 2.7, 2.5, 3.6]

print(entete)
print(ligne1)
print(ligne2)
print(ligne3)
```

Python a de base une fonction max() et min() mais colas a essayer de créer les siennes et il a essayer de les appelé sans arguments alors que la fonction 'maximum(champ)' et 'minimum(champ)' prennent un argument.


```python
moyenne = sum(champ[3])/len(champ[3])
```
ici une variable moyenne est initialisé mais elle n'est pas utilisé et elle est calculé de manière incorrecte car il n'y a pas de boucle pour parcourir les éléments du csv.

