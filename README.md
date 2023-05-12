<center>
    <img src="Logo-Olist.png" alt="logo">
</center>

# Segmentation-clients-site-e-commerce

Dans le cadre de la mission confiée par Olist, j'ai travaillé sur la **segmentation des clients de l'entreprise afin de fournir à l'équipe d'e-commerce des informations exploitables pour leurs campagnes de communication**. 

Mon objectif était de comprendre les différents types d'utilisateurs en utilisant leurs comportements et leurs données personnelles.

J'ai utilisé des **méthodes non supervisées** pour regrouper les clients ayant des profils similaires. Ces catégories de segmentation pourront être utilisées par l'équipe Marketing pour optimiser leurs communications.

**Précisions** : seuls **3% des clients du fichier de données ont effectué plusieurs commandes** et qu'il était essentiel de différencier les bons et moins bons clients en termes de commandes et de satisfaction.

En tenant compte de ces informations, j'ai créé un notebook pour expérimenter différentes approches de modélisation et de segmentation. J'ai testé divers **algorithmes de clustering** pour identifier les groupes de clients les plus pertinents:
* **ACP**
* **K-means**
* **Classification mixte (K-means et CAH)**
* **K-prototypes**

En parallèle, j'ai également réalisé un **notebook de simulation pour déterminer la fréquence optimale de mise à jour du modèle de segmentation** afin de le maintenir pertinent. Cette information sera utilisée pour proposer un contrat de maintenance à Olist.

Il est important de noter que tout le code développé respecte la **convention PEP8** afin d'être utilisable par Olist. La lisibilité, la modularité et l'efficacité du code ont été prises en compte tout au long du projet.
