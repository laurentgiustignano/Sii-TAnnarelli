#Diagramme de contexte
Ce diagramme définit les éléments environnants au système (donc les frontières de l’étude) et la phase de son cycle de vie dans laquelle on se situe.

#Diagrammes fonctionnels
Les fonctions qu’un système a à remplir et l’utilisation que l’on souhaite faire d’un système peuvent être décrits par des diagrammes SysML :

* le diagramme des **exigences** (requirement diagram)
* le diagramme des **cas d’utilisation** (use case diagram)
#Diagrammes comportementaux
La norme SysML a retenu plusieurs manières de décrire le comportement d’un système :

1. La liste (**séquence**) des échanges (ordres, informations…) entre un humain et le système au cours d’un cas d’utilisation
2. les différents **états** que peut prendre un système au cours de son utilisation
3. les **activités** que chaque sous-ensemble du système réalise au cours de son utilisation
Ces trois diagrammes sont complémentaires et permettent notamment d’aborder les structures algorithmiques.

#Diagrammes structurels
Deux diagrammes SysML portent sur la structure d’un système.

* Le **diagramme de définition de blocs** fonctionne un peu comme des « poupées russes » : un bloc en contient d’autres, et ceux-ci peuvent également contenir d’autres blocs, etc. Il y a donc plusieurs niveaux « hiérarchiques ». Cela permet de bien comprendre la façon dont est construit le système, et de décrire ses composants depuis un niveau très général jusqu’à la plus petite vis de fixation, par exemple.
* Le **diagramme de blocs internes**, lui, ne décrit qu’un seul niveau hiérarchique du diagramme précédent, mais s’attache à préciser les échanges entre différents blocs (des commandes ou des flux pouvant être de l’énergie, de la matière ou de l’information).