# C'est quoi Python ?

Quand on parle de **Python**, on parle souvent de deux choses étroitement liées :
- Le langage de programmation, qui est la manière d'écrire les instructions que l'ordinateur va exécuter
- Le programme/logiciel Python, qui va permettre d'exécuter des fichiers "_écrits en langage python_"

## Langage de programmation
### _Mais c'est quoi exactement un langage de programmation ?_
Un langage de programmation est un ensemble de règles qui permettent de communiquer avec un ordinateur.
Nous allons écrire des instructions dans des fichiers, en respectant les règles du langage utilisé,
et l'ordinateur va être capable de les lire, de les comprendre, et de les exécuter.

### _Pourquoi existe-t-il autant de langages de programmation ?_

Tout simplement parce que chaque langage a ses avantages et ses inconvénients, ainsi que ses spécificités.
C'est un peu comme en cuisine : en fonction de la recette et des manipulations à effectuer,
vous vous servirez d'un ustensile plutôt qu'un autre : 
On utilisera un fouet plutôt qu'une cuillère à soupe pour battre des œufs en neige, 
mais on utilisera une cuillère à soupe au lieu d'un fouet pour manger sa soupe.

Si nous prenons l'exemple des langues (français, anglais, espagnol, etc.),
chaque langue a ses propres règles, ses propres mots, ses propres façons de construire les phrases, etc. 
Il en va de même pour les langages de programmation. 
Chaque langage de programmation a ses propres règles, ses propres mots, ses propres manières de construire des programmes, etc.

### _Les atouts de Python_
Le langage Python peut être décrit par plusieurs caractéristiques :

**Haut niveau** : Python se charge de gérer les détails techniques de l'ordinateur et de l'interface avec l'utilisateur.
En Python, beaucoup d'actions d'optimisation, de sécurité, et de nettoyage sont gérées par le programme,
là où d'autres langages (comme C/C++) vous demandent de le faire vous-même.

**Interprété** : Python est équipé d'un interpréteur, qui va lire et exécuter les instructions écrites en temps réel. 
À l'inverse, un langage compilé (comme C/C++) nécessite de compiler le programme avant de l'exécuter.
La compilation consiste à traduire le programme en langage machine, qui est le langage compréhensible par l'ordinateur.

**Orienté objet** : Il existe plusieurs façons de programmer. On parle de paradigmes de programmation.
Les 3 plus communs sont :
- La programmation impérative ou procédurale
- La programmation fonctionnelle
- La programmation orientée objet

Même si Python permet de programmer de manière impérative, 
il possède de nombreuses fonctionnalités orientées objet.

**Dynamiquement typé** : À l'inverse d'un langage _"statiquement typé"_ (comme C/C++),
les variables en Python peuvent changer de type à tout moment. Par exemple :

```python
b = 1  # b est un entier
b = "Hello"  # b est maintenant une chaine de caractères
b = 1.5  # b est maintenant un nombre à virgule flottante
```

Cela présente de nombreux avantages, mais aussi quelques inconvénients dont nous parlerons plus tard.

**Généraliste** : Python peut être utilisé dans des domaines très différents :
- Écriture de scripts en tout genre
- Édition de logiciels
- Développement web
- Data-science / Intelligence artificielle


## Le logiciel Python
Python est aussi un programme. Pour faire de la programmation en python, il faut :
- Écrire des fichiers contenant des instructions écrites en langage Python
- Utiliser le programme Python pour exécuter ces fichiers

Comme tout logiciel, il vous faudra l'installer sur votre machine,
et ensuite vous pourrez l'exécuter.

### Analogie avec Microsoft Word

Pour clarifier un peu plus la distinction entre le "programme" et le "langage",
prenons l'exemple du logiciel Microsoft Word :
- Lorsque vous lancez le programme Microsoft Word, cela ouvre un document vierge
- Lorsque vous ouvrez un fichier **.docx** avec Microsoft Word, cela ouvre ce document DANS word

Pour Python, la même mécanique est disponible :
- Si vous lancez juste le programme python, cela va lancer **l'interpréteur** python
- Si vous lancez un fichier **.py** avec python, cela va :
  - Ouvrir un interpréteur python
  - Exécuter votre fichier
  - Et fermer l'interpréteur python automatiquement

## Interpréteur

Comme expliqué ci-dessus, l'interpréteur python est ce que vous allez voir lorsque
vous lancerez python ou **exécuterez** un fichier **.py** avec python. 
Il s'agit d'une fenêtre noire (type console/terminal).

Si vous lancez Python (sans préciser de fichier), l'interpréteur sera **interactif**.
Vous pourrez écrire des instructions à la main et voir en direct leur résultat.

Si vous demandez à Python d'exécuter un fichier :
- Vous ne pourrez pas interagir avec l'interpréteur (sauf si le code le permet)
- L'interpréteur va exécuter toutes les instructions du fichier, une par une
- Une fois le fichier terminé, l'interpréteur va se fermer automatiquement

Allons donc découvrir l'interpréteur python !
