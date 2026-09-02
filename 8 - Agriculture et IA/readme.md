# Agriculture, alimentation et santé: IA dans OneHealth

De nombreuses applications sont en cours de développement, basées sur des sources de données toujours plus nombreuses:
satallites, drones, capteurs de température, vent, humidité etc...

Ces applications sont presque toujours présentées comme des enjeux de **rendement**. Elles sont
aussi des enjeux de **santé** : la santé humaine, la santé animale et celle des écosystèmes ne se
traitent pas séparément. Ce qui est épandu dans un champ se retrouve dans un corps ; un antibiotique
donné à un troupeau produit des résistances chez l'humain ; une moisissure dans un silo devient
une toxine dans une assiette.
Qu'est ce que l'IA peut apporter (ou pas) dans cette problématique?


## Agriculture et statistiques

Le developpement de l'agriculture moderne est passé (et passe encore) par les statistiques pour distinguer les proverbes ancestraux parfois approximatifs des traitements significativement efficaces.

Le XXe siècle marque une transition forte dans l'approche des sciences de la vie (médecine, agronomie, ...) reposant notamment sur les statistiques (et une politique productiviste).

https://books.openedition.org/psorbonne/105227?lang=fr

https://www.agreste.agriculture.gouv.fr/agreste-web/

Aujourd'hui la question du productivisme se pose en parallèle des défis du XXIe siècle

https://www.citeco.fr/agriculture-du-xxie-siecle-face-au-double-defi-alimentaire-et-environnemental
[un article assez orienté]

**Pistes possibles**
- L'IA et son lointain ancêtre des statistiques sont-ils seulement utile du point de vue productiviste?


## IA, diagnostic et comptage

Détecter la nature des plantes, le type de ravageurs, compter les animaux dans un parc, mesurer la densité et la maturité des pousses en champs ou en laboratoire... Autant d'application relative à l'analyse d'image.

[cf sujet spécifique sur la vision par ordinateur]


https://plantnet.org

https://agrio.app/Une-application-pour-detecter-les-maladies-et-les-parasites-des-plantes/

https://eolab.cnes.fr/projets/estimation-de-rendements-agricoles-des-grandes-cultures

L'IA est aussi critique sur l'analyse des séries temporelles, en particulier dans le domaine de la prédiction de rendement.


https://www.tanoraa.fr/use-cases/agriculture/prediction-du-rendement-agricole-transformer-la-data-science-en-une-revolution-verte

https://www.academia.edu/download/37651378/JEEER_Vol_15_No_3_2014.pdf#page=61



## Robotique


Developpent de la robotique pour une agriculture de précision: 

https://www.dilepix.com

https://tscf.clermont.hub.inrae.fr/themes-de-recherche/methodes-et-outils-innovants-pour-la-transition-agroecologique

https://vitibot.fr

https://www.youtube.com/watch?v=1QsvcAE7UL4

https://ecorobotix.com/fr/


## IA et traitements phytosanitaires

L'IA est-elle une solution pour réduire l'usage des produits phytosanitaire... Ou un prétexte pour ne pas avoir à agir sur la régulation de l'usage de ces produits... Ou les deux?

https://agriculture.gouv.fr/france-2030-lintelligence-artificielle-au-coeur-des-nouveaux-appels-projets-pour-le-monde-agricole


https://www.terre-net.fr/materiels-agricoles/article/861094/ia-et-laser-le-desherbage-facon-star-wars-arrive-dans-les-champs

https://alliance-harvest.com

**Questions ouvertes** : une réduction de 90 % du volume épandu sur une parcelle équipée
change-t-elle l'exposition de l'agriculteur, celle des riverains, celle du consommateur — dans
les mêmes proportions ? Que coûte l'équipement, et qui peut se l'offrir ? Une technologie de
réduction accessible aux seules grandes exploitations est-elle un progrès sanitaire ou un
déplacement du problème ?


## Santé animale, élevage de précision et antibiorésistance

L'élevage de précision consiste à instrumenter les animaux (capteurs d'activité, de rumination,
de température, caméras, analyse du son) pour détecter un animal malade le plus tôt possible.
L'enjeu sanitaire est direct : traiter **l'individu** plutôt que le troupeau, donc réduire l'usage
d'antibiotiques 

- https://www.inrae.fr/actualites/antibioresistance
- https://www.inrae.fr/actualites/seule-sante-humains-animaux-ecosystemes-lanses-inrae-renouvellent-leur-partenariat

L'IA intervient aussi en **épidémiosurveillance** : détection précoce et modélisation de la
diffusion des zoonoses et des épizooties (influenza aviaire, fièvre catarrhale, peste porcine
africaine), c'est-à-dire à l'interface exacte entre santé animale et risque pandémique humain.

**Questions ouvertes** : un troupeau sous surveillance continue, est-ce un progrès du bien-être
animal ou son inverse ? Les mêmes capteurs servent à détecter la maladie et à optimiser la
productivité : peut-on séparer les deux usages ? Qui est propriétaire des données de santé
animale — l'éleveur, le fabricant du capteur, le vétérinaire, la coopérative ?


## De la parcelle à l'assiette : sécurité sanitaire des aliments

L'IA s'installe dans le contrôle sanitaire de la chaîne alimentaire : détection de contaminants
et de mycotoxines, tri optique des lots, prédiction du risque microbiologique à partir de données
massives, traçabilité et déclenchement des rappels de produits.

- L'Anses et le Cnam ont créé une unité de recherche dédiée à l'exploitation des données massives
  pour la sécurité sanitaire des aliments : https://www.anses.fr/en/content/using-artificial-intelligence-improve-food-safety-anses-and-cnam-create-metabiot-dedicated
- Les mycotoxines, un risque cancérogène régulé : https://www.anses.fr/en/content/review-mycotoxins
- Détection des mycotoxines par IA, revue de littérature : https://pmc.ncbi.nlm.nih.gov/articles/PMC11507438/

**Questions ouvertes** : un contrôle prédictif — cibler les lots à analyser au lieu d'échantillonner
au hasard — améliore-t-il la sécurité sanitaire ou crée-t-il des angles morts ? 


## Ouverture : alimentation, nutrition et santé publique

En bout de chaîne, ce sont des algorithmes qui interviennent entre l'aliment et le mangeur :
notation nutritionnelle et applications de scan, recommandation de recettes et de produits,
nutrition dite personnalisée. 

**Questions ouvertes** : une note synthétique sur un emballage est-elle une information de santé
publique ou une simplification qui déforme ? Que vaut une « nutrition personnalisée » fondée sur
des corrélations ?