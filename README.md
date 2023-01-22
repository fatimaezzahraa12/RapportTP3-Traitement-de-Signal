# RapportTP3-Traitement-de-Signal
Réalisé par :Fatima Ezzahraa Chadni

# Thème :Synthèse et analyse spectrale d’une gamme de musique
-Objectifs: 
-Comprendre comment manipuler un signal audio avec Matlab, en effectuant certaines opérations classiques sur un fichier audio d’une phrase enregistrée via un smartphone.

-Comprendre la notion des sons purs à travers la synthèse et l’analyse spectrale 
d’une gamme de musique.

-Travail Demandé: Réaliser un script Matlab commenté qui contient le travail réalisé avec les représentations graphique expliquées sur le travail Effectué.
# Manipulation 1:Jeu de Mots.
On commence par charger le fichier à l'aide de la commande audioread(),puis on l'écoute en utilisant la commande sound(x,fs).
Comme c'est mentionné dans le script,on essaie de diviser la fréquence d'échantillonnage du signal.Après l'avoir écouté,on remarque que le son devient compressé.
Ensuite, on multiplie le signal par 2 et on remarque après l'écout du signal qu'il devient dilaté.

![jexudemots](https://user-images.githubusercontent.com/120644217/213922518-1597b9b3-f6e1-4594-841a-01d9447e38e3.PNG)

-Représentation temorelle du signal :

![jeuxdemotsgraphe](https://user-images.githubusercontent.com/120644217/213922661-6857bcb0-adc2-41a2-8fea-2b46e09c6a87.PNG)

À ce stade , on passe à décortiquer notre signal en portions de mots , comme il est mentioné dans la figure ci-dessous.

![divi](https://user-images.githubusercontent.com/120644217/213923026-74b67983-8ba0-46bc-a1b4-2e30f3cdc48d.PNG)

On essaie de réarranger ce vecteur pour écouter la phrase synthétisée « Rien ne sert de partir à point, il faut courir ».

![reassembler](https://user-images.githubusercontent.com/120644217/213923264-aa478ba5-1928-4524-b257-9c96a9095c40.PNG)
# Manipulation 2: Synthèse et analyse spectrale d’une gamme de musique.
La première étape consiste à générer la gamme musicale [do,re,mi,fa,sol,la,si,do]
Pour ce faire on génère chaque note musicale séparément,suivant la fréquence qui lui est associée.Puis on réassemble le tout pour reconstituer la gamme musicale complète.

![ki](https://user-images.githubusercontent.com/120644217/213923829-4600408e-5a89-4365-8bc1-de4504215c62.PNG)

![notem](https://user-images.githubusercontent.com/120644217/213923968-dbd82631-1b04-4e82-835c-26f4aff60a96.PNG)

# Analyse du spectre de la gamme musicale.

![signalAnalyser](https://user-images.githubusercontent.com/120644217/213924207-d345392c-e50d-4b40-98c3-fc750326e2ab.PNG)

Ce graphe représente la gamme de fréquences que contient le signal.






