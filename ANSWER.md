# 1.
Qu'est-ce qu'une instance Virtual Machine ?


# 2.
Qu'est-ce qu'un VNET ?
Le réseau virtuel Azure (VNet) est le bloc de construction fondamental pour votre réseau privé dans Azure. Le réseau virtuel permet à de nombreux types de ressources Azure, telles que les machines virtuelles (VM) Azure, de communiquer de manière sécurisée entre elles, avec Internet et avec les réseaux locaux. Un réseau virtuel est similaire à un réseau traditionnel que vous utiliseriez dans votre propre centre de données, mais avec les avantages supplémentaires de l’infrastructure Azure, tels que la mise à l’échelle, la disponibilité et l’isolation.

# 3.
A quoi sert un NSG ?

# 4.
- Accès aux services par l’utilisateur à la demande :
La mise en œuvre des systèmes est entièrement automatisée et c’est l’utilisateur, au moyen d’une console de commande, qui met en place et gère la configuration à distance.

- Accès réseau large bande :
Ces centres de traitement sont généralement raccordés directement sur le backbone Internet pour bénéficier d’une excellente connectivité. Les grands fournisseurs répartissent les centres de traitement sur la planète pour fournir un accès aux systèmes en moins de 50 ms de n’importe quel endroit.

- Réservoir de ressources (non localisées) :
La plupart de ces centres comportent des dizaines de milliers voire millions de serveurs et de moyens de stockage pour permettre des montées en charge rapides. Il est souvent possible de choisir une zone géographique pour mettre les données “près” des utilisateurs.

- Redimensionnement rapide (élasticité) :
La mise en ligne d’une nouvelle instance d’un serveur est réalisée en quelques minutes, l’arrêt et le redémarrage en quelques secondes. Toutes ces opérations peuvent s’effectuer automatiquement par des scripts. Ces mécanismes de gestion permettent de bénéficier pleinement de la facturation à l’usage en adaptant la puissance de calcul au trafic instantané.

- Facturation à l’usage :
Il n’y a généralement pas de coût de mise en service (c’est l’utilisateur qui réalise les opérations). La facturation est calculée en fonction de la durée et de la quantité de ressources utilisées. Une unité de traitement stoppée n’est pas facturée.

# 5.
# Qu'est-ce que l'A/B Testing ?

# 6.
# Comment programmer le cloud ?
LInfrastructure as Code (IAC) est un ensemble de mécanismes permettant de gérer, par des fichiers descripteurs ou des scripts, une infrastructure virtuelle1,2. Initialement dédié aux machines virtuelles (également nommées "Instances"), l'évolution des offres dans le domaine de la virtualisation ont permis de pouvoir gérer une infrastructure à part entière, de l'instance au réseau, incluant entre autres la gestion du DNS, du Load-Balancing, des sous-réseaux et des groupes de sécurité3.
Souvent plébiscité dans le cadre du cloud computing, l'Infrastructure as Code offre aux développeurs la possibilité de pouvoir automatiser leurs déploiements, et ainsi éviter toute configuration manuelle ; tout en évitant de devoir écrire d'eux-mêmes les appels aux interfaces de programmation. Cette technologie est donc une réponse aux besoins des entreprises en termes de passage à l'échelle des applications, mais également pour l'automatisation et la simplification des infrastructures des projets informatiques. Également, l'Infrastructure as Code rentre dans la mouvance plus générale du DevOps.

# 7.
# Quelle est la technique pour faire un déploiement sans interruption de service ?

# 8.
# Qu'est-ce que le Canary release ?
Le canary release est un pattern qui permet de faire tester les dernières modifications réalisées (appelée version N+1) à une tranche de population restreinte avant de réaliser un déploiement général de cette version.

# 9.
# Comment changer de taille de machine virtuelle ?

# 10.
# Qu'est-ce que le Blue/Green deployment ?
Le Blue-Green Deployment et l’exposition progressive offrent encore plus de souplesse et réduisent de façon drastique le risque de bogue en production.
Le principe de l’exposition progressive est assez simple : la nouvelle version de l’application est rendue disponible à un nombre restreint d’utilisateurs. Plus elle est stable et plus l’on est satisfait de sa réactivité, plus elle est accessible à un nombre important d’utilisateurs, jusqu’à une exposition complète à l’ensemble des utilisateurs.

# 11.
# Citez deux avantages du PaaS sur le IaaS ?

# 12.
# Quelle est la différence entre le PaaS et le Serverless ?
Les principales différences entre le PaaS et le Serverless sont l'évolutivité, la tarification, le temps de démarrage, l'outillage et la capacité de déploiement à la périphérie du réseau.

# 13.
# Que veut dire Serverless ?

# 14.
#  les trois propriétés désirable du Serverless ?
Les applications Serverless évoluent instantanément, automatiquement et à la demande, sans configuration supplémentaire de la part du développeur ou du fournisseur.
Une application Web Serverless peut évoluer jusqu'à arrêter son activité, puis redémarrer en réponse à un événement en quelques secondes ou millisecondes.
La facturation Serverless est extrêmement précise et les développeurs ne paient que pour ce qu'ils utilisent. Certains fournisseurs Serverless ne facturent aux développeurs que la durée exacte d'exécution de leurs fonctions, jusqu'à des fractions de seconde pour chaque instance individuelle de chaque fonction.
Le temps de lancement des applications Serverless est très rapide.

# 15.
# Comment s'appelle la plus petite unité de compute déployable en Serverless ?
