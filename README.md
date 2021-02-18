# Ordonnancement-des-Patients-aux-SUA

Les problématiques d’ordonnancement des patients au sein des SUA peuvent apparaître à divers niveaux : 
amont, intra ou aval. L’ordonnancement a pour objectif d’améliorer et/ou de mieux organiser les Services des Urgences. 

Il faut cependant être prudent lorsque l’on emploie le terme “améliorer”. Si l’on souhaite réduire le temps d’attente, 
“améliorer” signifie simplement rendre les opérations plus rapides. Si nous prenons l’exemple d’une intervention chirurgicale, 
l’ordonnancement va probablement faire travailler plus longtemps le chirurgien et moins de temps les aidants alors 
qu’en pratique, les aidants sont là pour diminuer au maximum le temps d’intervention du chirurgien. Ils sont nécessaires
et leurs absences ralentiraient fortement le déroulement d’une opération et pourraient même engendrer des complications. 
Il faut donc être précis quant à l’utilisation de l’ordonnancement aux SUA. La solution que nous présentons dans ce projet 
vise notamment à optimiser les temps d'attente jugés superflus, telle que l’attente primaire ou le fait de trouver un lit 
disponible à un patient par exemple, sans risquer de mettre en danger les patients en ne prenant pas de décision sur la
répartition du personnel médical.

Dans ce prrojet, on propose notamment un ordonnancement des patients aux SUA suivant un algorithme génétique, puis ensuite un 
algorithme de liste afin de pouvoir comparer leurs résutlats. Finalement, ces algorithmes sont exploités dans un modèle de système
multi-agents visant de simuler les interactions qui se passent entre les personnels des urgences, afin d'optimsier au mieux l'ordre
de passage des patients pour effectuer leurs soins. 

Pour cela, le respect de plusieurs critères est exigé : 
  - le degré de gravité des patients, défini par leur CCMU
  - le temps d’attente primaire des patients, c’est-à-dire leur temps d’attente durant l’enregistrement et/ou en attendant le diagnostic primaire
  - l’ordre de précédence des tâches de soins, autrement dit les tâches de soins ne doivent se permuter entre elles
