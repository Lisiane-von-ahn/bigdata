# bigdata

Premières manipulations avec
Spark

Objectifs
● Prendre en main le fonctionnement de Spark
○ Découverte avec les listes
○ Exploration avec les textes
Compétences
● Je manipule des données avec PySpark

.1 — Configuration de votre environnement
5h — Présentiel
Ça y est, vous avez installé votre environnement de travail, il est temps maintenant d’explorer les
différentes choses que vous pouvez faire avec PySpark !
En creusant sur différents sites vous comprenez qu’il faut configurer votre environnement avec
SparkContext et SparkConf. Vous vous plongez dans la doc pour mettre en place votre
environnement.
Au fil de vos lectures vous comprenez de plus en plus l’intérêt de Spark et de sa parallélisation des
traitements, vous vous dites que ce serait une bonne idée de trouver quelque chose pour mesurer
le temps de traitement et faire des comparaisons !


.2 — Découverte de Spark avec les listes
5h — Présentiel
Maintenant que vous avez mis en place votre environnement, vous décidez de commencer à
explorer les différentes fonctionnalités de Spark sur des listes. Plusieurs questions vous viennent
en tête au fil de vos recherches documentaires.
Vous commencez par créer une liste très simple pour tester les différentes fonctions :
l = [1,2,3,4,5]
Vous vous demandez quelles manipulations vous pouvez faire dessus en vous remémorant vos
premiers cours de Python…
- comment distribuer ma liste dans le RDD ?
- spark lazy evaluation : qu’est-ce que ce truc ?