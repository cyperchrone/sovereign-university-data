---
name: Introduction au Minage de Bitcoin
goal: Comprendre le fonctionnement de l'industrie du minage à travers un exercice pratique de réutilisation d'ASICs.
Objectives:
  - Comprendre la théorie sur le minage
  - Comprendre l'industrie du minage
  - Transformer un S9 en chauffage
  - Miner son premier satoshi
---

# Vos premiers pas dans le minage !

Dans cette formation, nous allons approfondir l’industrie du minage afin de démystifier ce sujet si complexe ! La formation est accessible pour tous et ne demande pas d’investissement initial.

La 1ère section sera théorique où avec Ajelex, nous aurons une discussion approfondie sur de nombreux thèmes autour du minage, ceci nous permettra de mieux comprendre cette industrie et les enjeux économiques et géopolitiques qui y sont liés.
Dans une deuxième section, nous attaquerons avec un cas pratique. En effet, nous allons apprendre à transformer un mineur S9 d'occasion en chauffage d'appoint maison ! À travers des guides écrits et vidéos, nous vous montrerons et expliquerons toutes les étapes pour y arriver chez vous :)

Nous espérons à travers cette vidéo vous montrer que l'industrie du minage est plus complexe qu'il y paraît et l’étudier permet de nuancer le débat écologique qui est lui lié !
Si vous avez besoin d’aide pour votre attaque, un Telegram a été créé pour les étudiants et toutes les pièces nécessaires pour y parvenir peuvent être trouvées sur notre e-commerce !

+++

# Introduction

## Bienvenue!

Bienvenue dans MINAGE 201; une introduction au minage. Ajelex, Jim & Rogzy sont heureux de vous l'offrir à 100% gratuit et de vous accompagner dans vos premiers pas concrets dans cette nouvelle industrie. En espérant que le cours vous plaise et que vous rejoigniez l'aventure du home mining !

### Aperçu du Cours

Dans ce cours la première section sera consacrée à la théorie du minage avec Ajelex. Nous discuterons en profondeur des nombreux thèmes autour du minage, ce qui nous permettra de mieux comprendre cette industrie ainsi que les enjeux économiques et géopolitiques liés.

Dans la deuxième section, nous nous lancerons dans un cas pratique fascinant, apprenant à transformer un mineur S9 d'occasion en chauffage d'appoint maison. Grâce à des guides écrits et vidéos, toutes les étapes nécessaires seront minutieusement expliquées, garantissant ainsi votre succès dans ce projet innovant.

Ce voyage d'apprentissage vous montrera que l'industrie du minage est plus complexe qu'elle n’y paraît, offrant une perspective équilibrée sur le débat écologique lié. Une aide continue sera disponible via un groupe Telegram dédié pour les étudiants, et toutes les pièces nécessaires seront facilement accessibles sur notre plateforme e-commerce.

### Curriculum:

Section Théorique :
* Explication du minage.
* L'industrie du minage.
* Les nuances de l’industrie du minage.
* Le minage dans le protocole bitcoin.
* Prix du bitcoin et le hashrate, une corrélation ?

Section Pratique : Attakai
* Introduction à Attakai.
* Guide d’achat pour un ASIC d’occasion.
* Modification du software - Réinitialiser un Antminer S9.
* Installer Braiins OS+ sur son Antminer S9.
* Configurer son Antminer S9 avec Braiins OS+.
* Remplacer les ventilateurs pour réduire les nuisances sonores
* Configuration d’une pool.
* Overclocking et Underclocking.

Prêts à débuter cette aventure captivante ? Plongeons ensemble dans le monde fascinant du home-mining !

# Tous connaitre sur le minage 

## Explication du minage

![Qu'est-ce que le minage de bitcoin ?](https://youtu.be/neEQzEQzmPQ?si=bZpP4EgGd7HkTvdX)

### Le Minage Expliqué : L'Analogie du Puzzle

Pour expliquer de manière simplifiée le concept du minage, une analogie pertinente peut être employée : celle du puzzle. Tout comme un puzzle, le minage est une tâche complexe à réaliser, mais facile à vérifier une fois complétée. Dans le contexte du minage de Bitcoin, les mineurs s'efforcent de résoudre rapidement un puzzle numérique. Le premier mineur à résoudre le puzzle présente sa solution au réseau entier, qui peut alors facilement vérifier sa validité. Cette vérification réussie permet au mineur de valider un nouveau bloc et de l'ajouter à la blockchain du Bitcoin. En reconnaissance de son travail, qui implique des coûts significatifs, le mineur est récompensé par un certain nombre de bitcoins. Cette récompense constitue une incitation financière pour les mineurs à continuer leur travail de validation des transactions et de sécurisation du réseau blockchain.

Initialement dans le réseau Bitcoin, la récompense attribuée était de 50 bitcoins toutes les dix minutes, en parallèle à la découverte d'un bloc toutes les dix minutes en moyenne par les mineurs. Cette récompense subit une division par deux tous les 210 000 blocs, soit approximativement tous les quatre ans. Cette rémunération sert de puissante incitation pour encourager les mineurs à participer au processus de minage malgré son coût énergétique considérable. En l'absence de récompense, le minage, coûteux en électricité, serait délaissé, compromettant ainsi la sécurité et la stabilité de l'ensemble du réseau blockchain.

La récompense de minage actuelle est double. D'une part, elle comprend la création de nouveaux bitcoins, passée de 50 bitcoins toutes les dix minutes à l'origine à 6,25 bitcoins aujourd'hui. D'autre part, elle inclut les frais de transaction que le mineur choisit d'inclure dans son bloc. Lorsqu'une transaction bitcoin est effectuée, des frais de transaction sont payés. Ces frais fonctionnent comme une sorte d'enchère où les utilisateurs indiquent combien ils sont disposés à payer pour que leur transaction soit incluse dans le bloc suivant. Pour maximiser leur récompense, les mineurs, agissant dans leur propre intérêt, sélectionnent les transactions les plus rentables à inclure dans leur bloc, compte tenu de l'espace limité disponible. Ainsi, la récompense de minage se compose à la fois de la génération de nouveaux bitcoins et des frais de transaction, garantissant une incitation continue pour les mineurs et assurant la pérennité et la sécurité du réseau Bitcoin.

### Les Mineurs et Leurs Outils : Exploration

Le processus de minage consiste à trouver un hash valide acceptable par le réseau Bitcoin. Ce hash, une fois calculé et trouvé, est irréversible, à l'image de patates transformées en purée. Il vérifie une certaine fonction sans possibilité de revenir en arrière. Les mineurs, en compétition, utilisent des machines pour calculer ces hashes. Bien qu'il soit théoriquement possible de trouver ce hash manuellement, la complexité de l'opération rend cette option irréalisable. Les ordinateurs, capables de réaliser ces calculs rapidement, sont donc employés, consommant toutefois une quantité significative d'électricité.

Au commencement, l’ère du CPU dominait, où les mineurs utilisaient leurs ordinateurs personnels pour le minage de Bitcoin. La découverte des avantages des cartes graphiques pour cette tâche a marqué un tournant, augmentant substantiellement le hashrate et réduisant la consommation d’énergie. Cette avancée a rapidement cédé la place à l’émergence des ASICs, des circuits intégrés spécifiquement conçus pour surpasser les capacités des moyens précédents, marquant une nouvelle phase de sophistication dans le minage. La progression ne s'est pas arrêtée là, avec l’introduction ultérieure des FPGA, des circuits encore plus spécialisés dans le minage. De nos jours, les mineurs emploient des machines exclusivement dédiées à cette opération, optimisées pour tester un nombre maximal de combinaisons avec la plus petite consommation d’énergie possible. Ces ordinateurs, incapables d’exécuter des tâches autres que le minage de Bitcoin, sont un témoignage palpable de l'évolution continue et de la spécialisation croissante de l'industrie du minage de Bitcoin. Cette constante évolution reflète la dynamique intrinsèque du Bitcoin, où un ajustement de la difficulté garantit la production d’un bloc toutes les dix minutes malgré l'augmentation exponentielle de la capacité de minage.

Pour illustrer l'intensité de ce processus, considérez un mineur typique capable de réaliser 14 TeraHash par seconde, soit 14 000 milliards d'essais chaque seconde pour trouver le hash correct. À l'échelle du réseau Bitcoin, on atteint aujourd'hui environ 300 HexaHash par seconde, soulignant la puissance collective mobilisée dans le minage de Bitcoin.


### Ajustement de la difficultyé:

L'ajustement de la difficulté est un mécanisme crucial dans le fonctionnement du réseau Bitcoin, garantissant que les blocs sont minés en moyenne toutes les 10 minutes. Cette durée est une moyenne, car le processus de minage est en réalité un jeu de probabilités, semblable à lancer des dés en espérant obtenir un certain nombre. Tous les 2016 blocs, le réseau ajuste la difficulté de minage en fonction du temps moyen mis pour miner les blocs précédents. Si le temps moyen est supérieur à 10 minutes, la difficulté est diminuée, et inversement si le temps moyen est inférieur. Ce mécanisme d’ajustement assure que la distribution des nouveaux bitcoins reste constante dans le temps, indépendamment du nombre de mineurs ou de la puissance de calcul globale du réseau.

* Exemple de la Chine:
  Le cas de la Chine illustre parfaitement ce mécanisme d’ajustement de la difficulté. La Chine, riche en énergie bon marché et abondante, était le principal hub mondial de minage de Bitcoin. En 2021, la Chine a brusquement interdit le minage de Bitcoin sur son territoire, entraînant une chute massive du hashrate global du réseau Bitcoin, de l'ordre de 50%. Cette diminution subite de la puissance de minage aurait pu perturber gravement le réseau Bitcoin, en augmentant le temps moyen de minage des blocs. Cependant, le mécanisme d’ajustement de la difficulté est intervenu, réduisant la difficulté de minage pour garantir que la fréquence de minage des blocs reste en moyenne à toutes les 10 minutes. Ce cas démontre l’efficacité et la résilience du mécanisme d’ajustement de la difficulté du Bitcoin, qui assure la stabilité et la prévisibilité du réseau, même en cas de changements brusques et importants dans le paysage du minage mondial.

### Évolution des Machines de Minage de Bitcoin

Concernant l'évolution des machines de minage de Bitcoin en Chine, il est primordial de souligner que le contexte est plus régulé qu'orienté vers un modèle d'affaires traditionnel. Les mineurs tirent leurs revenus de la validation des blocs, une tâche dont la probabilité de succès est relativement basse. Le modèle de machine actuellement en usage, le Antminer S9, bien qu'étant un modèle plus ancien lancé aux alentours de 2016, demeure en circulation sur le marché de l'occasion, se négociant aux alentours de 200 euros. Cependant, le prix des machines de minage varie en fonction de la valeur du Bitcoin, et un modèle plus récent, le Antminer S19, est actuellement estimé à environ 2000 euros.

Face à l'évolution technologique constante dans le domaine du minage, les professionnels doivent se positionner de manière stratégique. L'industrie du minage est en proie à des innovations continuelles, comme le démontre la sortie récente de la version J du S19, et celle anticipée du S19 XP, offrant des capacités de minage nettement supérieures. De plus, les améliorations ne sont pas uniquement liées aux performances brutes des machines. Par exemple, le nouveau modèle S19 XP utilise un système de refroidissement par liquide, une modification technique qui permet une amélioration significative de l'efficience énergétique. Bien que l'innovation reste une constante, les gains d'efficience futurs seront probablement moindres par rapport à ceux observés jusqu'à présent, en raison de l'atteinte d'un certain seuil d'innovation technologique.

En conclusion, bien que l'industrie du minage de Bitcoin continue de s'adapter et de se développer, les acteurs du domaine doivent anticiper des gains d'efficience plus limités à l'avenir, et ajuster leurs stratégies en conséquence. Les avancées technologiques futures, bien qu'encore présentes, se feront probablement à une échelle plus réduite, reflétant une maturité croissante du secteur.

## L'industrie du minage

![Le minage de Bitcoin trop centralisé ? Risques et solutions](https://youtu.be/xkiY8DgkcLQ?si=OvQ-IWOd4_QXh9aH)

### Les Pools de Minage

À l’heure actuelle, le minage de Bitcoin a évolué pour devenir une industrie sérieuse, substantielle, avec de nombreux acteurs désormais publics et un nombre croissant de mineurs significatifs. Cette évolution a rendu le minage presque inaccessible pour les petits acteurs en raison du coût élevé associé à l'acquisition de nouvelles machines de minage. La question se pose donc de la distribution du hashrate parmi divers acteurs du marché. La situation est complexe, car il est essentiel d’examiner à la fois la répartition du hashrate parmi différentes sociétés et parmi différents pools de minage.

Un pool de minage est un regroupement de mineurs qui unissent leurs ressources de calcul pour augmenter leurs chances de minage. Cette coopération est nécessaire car une petite machine de minage isolée est en compétition avec des géants de l'industrie, réduisant ses chances de succès à un niveau négligeable. Le minage fonctionne selon un principe de loterie, et les chances de gagner un bloc (et donc la récompense en Bitcoin) toutes les dix minutes sont extrêmement faibles pour un petit mineur individuel. En se regroupant en pools, les mineurs peuvent combiner leur puissance de calcul, trouver des blocs plus fréquemment et distribuer ensuite les récompenses de manière proportionnelle à la contribution de chaque mineur au pool.

Par exemple, si un pool trouve un bloc et remporte 6,25 bitcoins, un mineur contribuant à 1% de la puissance de calcul totale du pool recevrait 1% des 6,25 bitcoins gagnés. Cependant, il est à noter que les pools de minage prennent généralement une petite commission (généralement autour de 2%) pour couvrir les coûts de fonctionnement de la coopérative.

### les softwares utilisées par l'industrie

Dans le contexte du minage de Bitcoin, le rôle des logiciels est tout aussi crucial que le matériel. Un exemple de ceci est illustré par le rôle de Bitmain, un fabricant prolifique qui a mis au point l'Antminer S9. En plus du matériel de minage, l'industrie repose fortement sur les pools de minage collaboratifs, tels que Brainspool, qui contrôle environ 5% du hashrate global du réseau Bitcoin.

Les acteurs de cette industrie cherchent continuellement à augmenter l'efficience à travers le hardware et le software. Par exemple, un logiciel populaire utilisé dans ce contexte est BrainsOS Plus. Ce logiciel remplace le système d'exploitation d'origine de la machine de minage, permettant ainsi d'exécuter les mêmes opérations de manière plus efficiente. Avec un tel logiciel, un mineur peut augmenter l'efficience de sa machine de 25%. Cela signifie que pour une quantité d'électricité équivalente, la machine peut produire 25% de hashrate supplémentaire, augmentant ainsi les récompenses reçues par le mineur. Cette optimisation logicielle est un élément essentiel de la compétitivité dans le minage de Bitcoin, démontrant l'importance d'une approche intégrée, combinant à la fois des améliorations matérielles et logicielles pour maximiser l'efficacité et les rendements.

### La régulation et le tarrif electricité

Comme observé en Chine et ailleurs, la régulation influence considérablement le minage. Bien qu'il n’y ait pas de mineurs significatifs en France, la régulation et les tarifs d'électricité élevés en Europe constituent des obstacles importants. Les mineurs sont continuellement à la recherche d'électricité à moindre coût pour maximiser leurs gains. Ainsi, le coût élevé de l'électricité en Europe et en France ne favorise pas l'attraction des mineurs dans ces régions.

Les mineurs ont tendance à se diriger vers des régions avec des tarifs d'électricité bas, souvent dans des pays émergents ou des pays avec des surplus énergétiques. Par exemple, une grande partie du hashrate mondial se situe au Texas, aux États-Unis. Le Texas possède un réseau électrique indépendant, ne partageant pas ses ressources énergétiques avec les autres États. Cette particularité oblige le Texas à produire souvent plus d'électricité que nécessaire pour éviter toute pénurie, créant ainsi un surplus. Les mineurs de Bitcoin tirent parti de cette surproduction en s’installant au Texas, où ils peuvent miner des bitcoins à des tarifs d'électricité très bas lors des périodes de surplus énergétique. Cette situation démontre l'influence significative des régulations et des tarifs d'électricité sur le minage de Bitcoin, soulignant l'importance de ces facteurs dans la décision des mineurs sur l’emplacement de leurs opérations de minage.

### Où vont les mineurs et la gestion de l'énergie?

En soulignant l'impact des mineurs de bitcoins dans le monde de l'énergie, la trajectoire est claire: ces acteurs sont constamment à la recherche de sources d'électricité bon marché, souvent celles qui sont gaspillées ou inexploitées. Ce phénomène est manifeste dans les régions dotées de nouvelles infrastructures électriques, comme celles équipées de barrages hydroélectriques récents.

Prenons un exemple. Dans un pays en cours de construction d’un barrage, la production d'électricité démarre souvent avant que les lignes de distribution ne soient entièrement opérationnelles. Ce décalage peut engendrer un coût considérable et décourager l'investissement dans de tels projets d'infrastructure. Cependant, les mineurs de bitcoins peuvent intervenir comme une source de demande flexible, prêts à consommer cette électricité "orpheline", aidant ainsi à amortir les coûts d'infrastructure. L'implication ici est qu'on peut ainsi rentabiliser immédiatement de nouvelles installations, favorisant la création de nouvelles sources d'électricité. Ce principe s'applique également à des échelles plus petites. Que ce soit un particulier utilisant un générateur hydroélectrique sur une petite rivière ou un foyer équipé de panneaux solaires, l'excédent d'électricité produit peut être utilisé pour alimenter une opération de minage de bitcoins.

En France, par exemple, les surplus d'électricité des panneaux solaires sont réinjectés dans le réseau et les producteurs sont rémunérés par un crédit de consommation de la part d'EDF. De manière similaire, on peut imaginer un mineur opérant sur ces surplus d'électricité, s'éteignant lorsque la demande locale égale l'offre. Bien que cela puisse sembler égoïste, privilégiant la production de bitcoins plutôt que de soutenir le réseau électrique local, cela présente un autre angle : la stabilisation du réseau électrique. La gestion complexe des surplus d'électricité, avec parfois même des coûts associés à leur élimination, peut être grandement simplifiée. Les mineurs de bitcoins peuvent absorber ces surplus, agissant comme un tampon flexible, ajustant la demande plutôt que l'offre. Dans un monde où la production d'électricité à partir de sources renouvelables (peu pilotables) est en augmentation constante, les mineurs peuvent jouer un rôle clé pour assurer l'équilibre de nos réseaux électriques, tout en profitant de l'électricité bon marché ou excédentaire pour alimenter leurs opérations de minage.

### La centralisation du minage

La centralisation du minage est abordée comme un défi majeur. De grands acteurs, tels que Foundry, dominent le marché, ce qui peut potentiellement entraîner la censure des transactions. Cette centralisation peut également rendre le réseau vulnérable à des attaques, notamment l'attaque des 51%, où un acteur ou un groupe contrôle plus de 50% de la puissance de hachage du réseau, leur permettant ainsi de contrôler et de manipuler le réseau.
Risque de Régulation Il est souligné que si un pays comme les États-Unis décidait de réguler ou d'interdire certaines transactions Bitcoin, cela pourrait avoir un impact considérable sur le réseau, en particulier si une grande partie de la puissance de hachage est centralisée dans ce pays.

Pour lutter contre cette centralisation, différentes stratégies sont abordées:

* Home Mining: L'idée du Home Mining est fondée sur la décentralisation de l'activité minière. Elle encourage les individus à participer à l'activité de minage depuis leur domicile, répartissant ainsi plus largement le hashrate.
* Stratum V2 : Le protocole Stratum V2 offre une autre approche. Contrairement à son prédécesseur, Stratum V2 permet aux mineurs de choisir les transactions à inclure dans les blocs qu'ils minent. Cette capacité renforce la résistance à la censure et diminue la capacité des grandes pools de minage à dominer le réseau. En donnant plus de pouvoir aux mineurs individuels, le protocole Stratum V2 peut jouer un rôle déterminant dans la lutte contre la centralisation du hashrate.
Open-Sourcing des Logiciels de Minage
* L’open-sourcing des logiciels de minage: Ceci est une autre stratégie potentiellement efficace. En rendant les logiciels de minage accessibles à tous, les petits mineurs auraient les mêmes opportunités que les grandes entreprises de minage pour participer et contribuer au réseau de blockchain. Cette démarche encouragerait une distribution plus large du hashrate, contribuant ainsi à la décentralisation du réseau.
* Diversification des Acteurs et de la Géographie: Encourager la participation de divers acteurs de différentes régions géographiques dans le minage de cryptomonnaies peut aussi s’avérer efficace. En diversifiant géographiquement le hashrate, il devient plus difficile pour un seul acteur ou pays d'exercer un contrôle ou une influence disproportionnée sur le réseau. Cette approche peut contribuer à protéger le réseau contre les attaques potentielles et renforcer sa décentralisation.

La conclusion générale est que la décentralisation est cruciale pour la sécurité et la résilience du réseau Bitcoin. Bien que la centralisation puisse offrir des avantages en termes d'efficacité, elle expose le réseau à des risques significatifs, notamment la censure et les attaques des 51%. Des initiatives comme Takai et l'adoption de nouveaux protocoles comme Stratum V2 sont des étapes importantes vers la décentralisation et la protection du réseau Bitcoin contre ces menaces.

## Les nuances de l'industrie du minage

![Chauffer son domicile en minant des bitcoins ?](https://youtu.be/SQaK4_8M0kA?si=vZf8gR00lFZuXaKc)

### Le principe de Attakai

Dans le contexte actuel, la pratique du minage de Bitcoin en S9 peut paraître complexe, mais une analyse plus profonde ouvre la voie à des alternatives innovantes. Le principe d'Attakai se base sur une réflexion concernant l'utilisation des installations de minage dans divers types de bâtiments, tels que les écoles ou les hôpitaux. L'idée maîtresse est de disposer quelques machines de minage en divers endroits, permettant ainsi de réutiliser la chaleur émise par ces machines pour chauffer les établissements. En optant pour des modèles tels que les S19, plus performants, il serait possible de répartir l’activité de minage, favorisant ainsi une meilleure performance globale tout en contribuant utilement à la société. Cette initiative viserait à concurrencer les grandes installations minières centralisées en utilisant la chaleur dégagée par les machines de minage de façon productive et efficiente.

L'initiative Attakaï découle d’une expérimentation personnelle de minage à domicile, réalisée par deux amis désireux de participer activement au réseau de Bitcoin. Ils se heurtèrent à des obstacles majeurs, tels que le niveau sonore élevé des équipements de minage, conçus pour une utilisation industrielle et non domestique. Pour pallier ce problème, des modifications matérielles furent apportées aux machines de minage. Des ventilateurs plus performants et silencieux remplacèrent les équipements d’origine, rendant ainsi le minage à domicile plus accessible et moins dérangeant. De plus, l'ajout d'un adaptateur Wi-Fi élimina le besoin d'une connexion par câble Ethernet, simplifiant davantage le processus de minage à domicile. L’hiver, ces mineurs modifiés furent utilisés comme source de chauffage, transformant une nuisance en bénéfice.

En exposant leur projet à la communauté Bitcoin et face à l'intérêt suscité, les inventeurs d’Ataka décidèrent de publier des guides détaillés sur la plateforme Découvre Bitcoin, permettant ainsi à quiconque de reproduire leur expérience de minage à domicile. Ils envisagent désormais d’élargir ce concept au-delà du cadre domestique. L'objectif est de démontrer comment un mineur modifié peut être transformé en un chauffage d'appoint silencieux utilisable pendant l’hiver, offrant une transition douce vers une seconde partie de formation consacrée à la mise en place pratique de ces modifications, illustrée par des vidéos explicatives. La question demeure cependant de savoir si cette initiative peut être étendue à une échelle plus grande, proposant ainsi une alternative réaliste et durable aux structures de minage centralisées actuelles.

### la limite de cette decentralisation?

Bien que l'idée de décentralisation du minage via l'utilisation productive de la chaleur produite semble prometteuse, elle comporte certaines limites et des questions demeurent. Les établissements très énergivores, tels que les saunas et les piscines, pourraient bénéficier de ce concept en utilisant la chaleur produite par les mineurs pour chauffer l'eau de leurs installations. Cette pratique est déjà mise en œuvre par certains membres de la communauté Bitcoin, qui explorent différentes méthodes pour réutiliser efficacement la chaleur générée par les équipements de minage. Par exemple, une salle des fêtes pourrait théoriquement être chauffée par trois ou quatre S19, chacun consommant 3000 watts et produisant une quantité équivalente de chaleur.

Cependant, il convient de souligner que la consommation d'énergie et la production de chaleur sont équivalentes, que l'énergie soit utilisée par un radiateur électrique ou un mineur. Pour un kilowatt d'électricité utilisé, la quantité de chaleur produite sera la même dans les deux cas. La différence réside dans le fait que le mineur fournira non seulement la chaleur mais également une récompense en bitcoin, offrant ainsi une incitation économique à utiliser un mineur plutôt qu’un simple radiateur électrique. Cette récompense supplémentaire pourrait contribuer à atténuer les préoccupations liées à la consommation d'énergie élevée des mineurs.

La question de l'efficacité et de la faisabilité à long terme de l'utilisation des mineurs de bitcoin pour le chauffage reste ouverte. Les innovations continues dans le hardware de minage et dans les technologies de chauffage peuvent potentiellement ouvrir de nouvelles voies pour une utilisation plus efficace de la chaleur générée par le minage, contribuant ainsi à la viabilité de cette approche à l'avenir.

### Pourquoi Avoir des Récompenses en BTC?

La question de la récompense en bitcoin plutôt qu’en une autre devise est essentielle dans le système imaginé par Satoshi Nakamoto. La création du Bitcoin se caractérise par un plafond fixe de 21 millions d'unités. L'objectif était de trouver un moyen équitable de distribuer ces unités nouvellement créées. Les mineurs, en fournissant leur puissance de calcul pour sécuriser le réseau, en rendant toute attaque de plus en plus coûteuse, protègent ainsi efficacement le réseau Bitcoin. En retour de cette contribution cruciale, ils sont récompensés par les nouveaux bitcoins créés, facilitant ainsi la distribution des coins dans l'écosystème.

C'est un système gagnant-gagnant. Les mineurs sont rémunérés à la fois pour la sécurisation du réseau et l'approbation des transactions. Les nouveaux bitcoins créés sont donnés comme une incitation pour renforcer la sécurité, et les frais de transaction sont un revenu supplémentaire pour approuver les transactions. Ces deux éléments combinés constituent la récompense totale pour le minage. La question du futur du minage se pose en raison de la réduction programmée des récompenses de minage, diminuant de moitié tous les quatre ans, un événement connu sous le nom de "halving". D'ici 2032, la récompense du bloc sera inférieure à un bitcoin, et en 2140, aucun nouveau bitcoin ne sera créé. À ce stade, les mineurs dépendront uniquement des frais de transaction pour la rémunération. Le réseau Bitcoin devra soutenir une grande quantité de transactions, avec des frais suffisamment élevés, pour assurer la rentabilité du minage.

La montée du Lightning Network, permettant des transactions rapides et à faible coût en dehors de la chaîne principale de Bitcoin, soulève des questions sur l'avenir du minage. Le Lightning Network a le potentiel de réduire considérablement les frais de transaction, impactant ainsi le revenu des mineurs. Cependant, cela dépendra de l'adoption et de l'utilisation du Lightning Network par rapport au réseau Bitcoin principal. Dans un scénario pessimiste, les mineurs pourraient trouver rentable de miner même à perte, s'ils ont amorti leurs coûts et ont accès à une électricité bon marché. Dans un scénario plus optimiste, les frais de transaction sur le réseau Bitcoin principal pourraient rester suffisamment élevés pour maintenir la rentabilité du minage.

### Que Devrait-On Mettre dans un Bloc Bitcoin?

Concernant la question de ce qui devrait être inclus dans un bloc Bitcoin, il est crucial de considérer la nature complémentaire des différentes couches du réseau Bitcoin. Bien que le Lightning Network puisse permettre des transactions plus rapides et moins coûteuses, il dépend toujours de la couche de base du Bitcoin, souvent appelée « settlement layer », pour l’ouverture et la fermeture des canaux de paiement.

Avec la croissance prévue du Lightning Network et l'augmentation conséquente des ouvertures et fermetures de canaux, l'espace dans les blocs Bitcoin deviendra de plus en plus précieux. La communauté Bitcoin a déjà tendance à valoriser la préservation de cet espace, reconnaissant sa limitation intrinsèque. Cette prise de conscience a donné lieu à des discussions sur l’utilisation légitime ou non de l'espace des blocs, avec des préoccupations concernant le « spam » sur la blockchain par des transactions considérées comme non essentielles.

La spéculation entoure l'utilisation future de l'espace des blocs, mais il est généralement admis que c'est une ressource rare qui devrait être utilisée judicieusement. Même si l'envie est là de le combler, il est essentiel de le préserver pour assurer la viabilité à long terme du réseau Bitcoin, anticipant une augmentation future de la demande d'espace dans les blocs. Comme dans tout marché libre, l’offre et la demande réguleront l'utilisation de l'espace des blocs. Avec une offre limitée, les parties prenantes devront faire des choix éclairés sur l'utilisation de cet espace précieux pour garantir l’efficacité et la sécurité du réseau Bitcoin à long terme.

## Le minage dans le protocole bitcoin

![Qui a le pouvoir ? Bitcoin, énergie et fabricants ](https://youtu.be/4wywK6BfDw8?si=A9Cd0VHuiJa-9cMi)

Le rôle des mineurs dans le réseau Bitcoin a été un sujet de débat intense pendant la guerre des blocs. Bien qu'essentiels pour la sécurité et la fonctionnalité du réseau, les mineurs ne détiennent pas nécessairement le pouvoir ultime dans l'écosystème Bitcoin. L'équilibre entre les mineurs, les nœuds et les utilisateurs finaux garantit l'intégrité et la décentralisation du réseau.

### la guerre des bloc

Les mineurs, bien que cruciaux, n'ont pas le contrôle unilatéral du réseau Bitcoin. Lors de la guerre des blocs, de nombreux mineurs étaient opposés à certaines évolutions du réseau, soulignant la tension entre les différents acteurs de l'écosystème. La question reste de savoir comment équilibrer le pouvoir entre les mineurs, les nœuds et les utilisateurs pour assurer la sécurité à long terme de Bitcoin.
Sécurité et Équilibre de Pouvoir

Le dilemme de la sécurité de Bitcoin repose sur un équilibre délicat. Bien que les mineurs jouent un rôle essentiel dans la validation et la création de blocs, les nœuds maintiennent l'intégrité en vérifiant et en validant les transactions et les blocs. Un bloc incorrect ou frauduleux sera refusé par les nœuds, censurant ainsi le mineur et préservant la sécurité du réseau. Le pouvoir est également détenu par les nœuds et les utilisateurs du réseau Bitcoin. Les nœuds ont le pouvoir de vérification et de validation, tandis que les utilisateurs ont le pouvoir de choisir quelle chaîne de blocs utiliser. Cette distribution de pouvoir assure la décentralisation et l'intégrité du réseau Bitcoin.

La guerre des blocs a révélé l'incertitude et la tension inhérentes à la gestion du réseau Bitcoin. Bien que Bitcoin Core soit actuellement la chaîne dominante, le débat sur la gouvernance et la gestion du réseau persiste.
La Responsabilité Partagée. En fin de compte, la responsabilité est partagée entre tous les acteurs du réseau Bitcoin. Une diminution du nombre d'utilisateurs, de nœuds ou de mineurs pourrait affaiblir le réseau, augmentant le risque de centralisation et de vulnérabilité aux attaques. Chaque acteur contribue à la robustesse et à la sécurité du réseau, renforçant l'importance de maintenir un équilibre de pouvoir et de responsabilité.

### Le pouvoir des mineur

L'élégante théorie du jeu de Satoshi Nakamoto a établi une situation où chaque acteur du réseau Bitcoin est incité à agir correctement pour protéger à la fois ses propres intérêts et ceux des autres participants. Cela crée un équilibre fragile où le mauvais comportement peut être réprimandé, renforçant ainsi la sécurité et la stabilité de l'ensemble du système. Malgré cet équilibre, les États restent une menace potentielle. Comme l'indique la présentation à Surfing Bitcoin 2022, les États peuvent tenter d'attaquer l'industrie du minage, exposant le réseau Bitcoin à des risques de centralisation et d'attaque. Des scénarios hypothétiques comme une attaque militaire ciblant les installations de production de matériel de minage soulignent l'importance de la diversification géographique et industrielle pour la résilience du réseau Bitcoin.

La centralisation de la production de matériel de minage en Chine pose un autre risque. Un refus d'exporter des machines de minage ou une accumulation de hashrate pour une attaque 51% par la Chine soulignent la nécessité d'une production décentralisée et diversifiée de matériel de minage. Face à ces risques, la communauté Bitcoin explore activement des solutions. Des entreprises comme Intel envisagent de produire des équipements de minage aux États-Unis, contribuant à la décentralisation de la production. D'autres initiatives, comme celle de Block avec son Mining Development Kit (MDK) open source, visent à encourager la conception et la production décentralisées de matériel de minage, permettant une distribution plus large du hashrate.Au cœur de ces discussions se trouve la mission fondamentale de Bitcoin: être une monnaie résistante à la censure. La communauté Bitcoin s'efforce constamment de renforcer la décentralisation, la résistance à la censure et l'anti-fragilité du réseau, rejetant des propositions telles que le passage au proof of stake, qui ne s'alignent pas sur ces principes fondamentaux.

### Le Lien Physique de la preuve de travail vs la Preuve d'enjeu

Le Proof of Work (PoW) est essentiel car il représente le lien physique entre le monde réel et les bitcoins. Bien que les bitcoins soient immatériels, leur production nécessite une énergie tangible, établissant ainsi un lien vital avec le monde réel. Cette connexion assure que la production et la validation des bitcoins et des blocs ont un coût énergétique réel, ancrant ainsi le réseau Bitcoin dans la réalité physique et empêchant sa domination complète par des entités puissantes.Le PoW agit comme un rempart contre la centralisation, en veillant à ce que la participation au réseau et à la validation des transactions nécessitent un investissement en ressources tangibles. Cela empêche la monopolisation du réseau par des entités qui pourraient autrement prendre le contrôle sans aucune barrière d'entrée significative, assurant ainsi une distribution plus équitable du pouvoir et de l'influence au sein du réseau Bitcoin.
Les Limites du Proof of Stake

D'un autre côté, le Proof of Stake (PoS), bien qu'il permette la participation à petite échelle, ne garantit pas une protection équivalente contre la centralisation. Dans un réseau PoS, ceux qui détiennent déjà une grande quantité de la monnaie ont un pouvoir disproportionné, reflétant les inégalités de pouvoir existantes dans la société en général. Cette dynamique pourrait potentiellement perpétuer la centralisation et la concentration du pouvoir entre les mains de quelques-uns, contrairement aux objectifs fondamentaux de décentralisation du Bitcoin.L’argument selon lequel tout le monde peut participer au PoS, même à petite échelle, en se joignant à des pools, n'est pas nécessairement solide. Dans un réseau PoW, même un petit contributeur, avec un équipement modeste, peut participer activement et contribuer à la sécurité et à la décentralisation du réseau.

### Récapitulatif

Pour récapituler, les mineurs fortifient le réseau Bitcoin contre la censure en utilisant de l'électricité pour calculer la preuve de travail du Bitcoin, et sont récompensés par de nouveaux bitcoins et les frais de transaction. Avec la professionnalisation de l’industrie, différents acteurs émergent, jouant divers rôles, de la création des puces à la gestion des fermes de minage. Par ailleurs, la finance intervient aussi, exerçant un contrôle, en décidant qui survit pendant les différentes phases du marché. La problématique de la centralisation subsiste, avec les entités les plus riches dominant potentiellement le marché. Toutefois, des alternatives sont en cours de développement au niveau matériel et logiciel. Il appartient à chaque individu d’agir et de contribuer à la décentralisation du réseau. Bitcoin représente une occasion inouïe non seulement en termes de liberté, mais aussi d'indépendance énergétique. Malgré les controverses autour de sa consommation d'électricité, Bitcoin offre un incitatif économique pour une transition vers une utilisation plus rationnelle et abondante de l'énergie, concrétisant ce qui était auparavant un idéal écologique.

## Prix du bticoin et le hasrate, une corrélation ?

![Comment obtenir un bitcoin blanc et vierge ? ](https://youtu.be/A5MTtn4mm44?si=D1Yi0dVwkyafeHv-)

### Hashrate, prix et rentabilité

 À l'heure actuelle, le taux de hachage n'a jamais été aussi élevé, bien que le prix du Bitcoin ne soit pas à son niveau le plus élevé, se situant actuellement autour de 30 000 dollars, par rapport à un sommet antérieur de 69 000 dollars. Cette situation illustre le lien réel entre le minage et le monde physique. Durant les périodes de hausse significative des prix (bull market), la demande pour le minage de Bitcoin s'accroit considérablement, entraînant une augmentation des commandes de machines de minage auprès des fabricants tels que Avalon et Bitmain. Toutefois, la production et la livraison de ces machines ne peuvent pas être instantanées, créant ainsi une inertie dans leur mise à disposition. Les machines commandées pendant un bull market peuvent se retrouver livrées dans un contexte de baisse de prix, illustrant une asymétrie notable entre un prix bas et un taux de hachage élevé.

Cette situation démontre également la résilience du Bitcoin, souvent évaluée en fonction de son prix. Toutefois, une analyse plus profonde et pertinente de la santé de Bitcoin nécessite l'examen de son taux de hachage, un indicateur du nombre de calculs effectués par seconde dans le réseau Bitcoin. Alors que le prix du Bitcoin est susceptible de fluctuations, son coût, lié au prix de l'électricité nécessaire pour faire fonctionner les machines de minage, reste un élément clé pour comprendre la dynamique du marché du Bitcoin. En se concentrant sur le coût plutôt que sur le prix, nous obtenons une perspective plus approfondie et cohérente sur la stabilité et la viabilité à long terme du Bitcoin, ce qui révèle que, généralement, le coût du Bitcoin a été proportionnel à son prix, offrant une meilleure compréhension des fluctuations de prix et des perspectives d'avenir du Bitcoin.

###  Taux de Hachage et Récompense

Il est raisonnable de supposer que le minage établit un prix plancher en dessous duquel le Bitcoin ne peut pas descendre. Une telle baisse signifierait que les mineurs créeraient et distribueraient des Bitcoins à perte, une situation manifestement irrationnelle. Même si de nombreux facteurs influent sur le prix du Bitcoin, le coût du minage a un impact considérable sur son prix. Ce lien entre le coût de minage et le prix du Bitcoin a été clairement illustré lors de l'interdiction du minage de Bitcoin en Chine, où une baisse de 50% du taux de hachage en quelques semaines a entrainé une chute drastique du prix du Bitcoin. Cependant, quelques mois plus tard, tant le prix que le taux de hachage sont revenus à des niveaux équivalents, confirmant la corrélation entre ces deux éléments.

Cependant, se concentrer uniquement sur le prix du Bitcoin peut s'avérer trompeur. Il est donc essentiel d'étudier également son coût. Des outils tels que les calculateurs de rentabilité peuvent aider à déterminer le coût du minage d'un Bitcoin, en prenant en compte des paramètres tels que le prix de l'électricité, la difficulté actuelle et le taux de hachage. Comprendre ce coût permet d'avoir une perspective plus équilibrée et rationalisée du prix du Bitcoin. Malgré la relation apparente entre le coût de minage et le prix du Bitcoin, il est important de noter que le marché peut se comporter de manière irrationnelle. Les mineurs peuvent être contraints de vendre à perte, ce qui peut potentiellement faire baisser le prix en dessous du coût de minage. Néanmoins, cette perspective soulève un débat intéressant sur la nature volatile du Bitcoin, et met en lumière la nécessité d'une compréhension plus approfondie de ses multiples facettes au-delà de son prix de marché.

Pour évaluer correctement la santé et la décentralisation continues du Bitcoin, il serait judicieux de développer une équation englobant divers facteurs tels que le nombre de nœuds, le nombre de nœuds actifs, et le prix, afin d'obtenir un ratio ou un indicateur plus complet et précis. Bien que cela reste une idée à ce stade, une telle approche pourrait offrir une analyse plus riche et nuancée du Bitcoin par rapport aux discussions courantes basées uniquement sur le prix.

### Souveraineté before profit ? 

Pour aborder la question cruciale de la richesse via le minage, il est important de considérer diverses perspectives et approches. Les interrogations concernant la rentabilité du minage sont fréquentes, avec des questions entourant l'achat de parts d'entreprises telles que Riot ou la location de machines à miner dans des pays à faible coût énergétique comme l'Islande ou la Russie. Avant de s'aventurer dans le minage, une considération essentielle serait de comparer la profitabilité du minage à l'achat direct de Bitcoin. Si le coût de minage d'un Bitcoin dépasse le coût d'achat direct, il est généralement plus judicieux d'acheter le Bitcoin directement. Cela évite les multiples défis et coûts associés au processus de minage.

Cependant, le minage offre des avenues uniques pour s'impliquer dans l'écosystème Bitcoin. Par exemple, miner du Bitcoin en hiver peut être une manière ingénieuse de chauffer votre logement tout en générant des revenus en Bitcoin. Une autre option consiste à investir dans des entreprises qui vendent du matériel de minage et qui stockent et gèrent les machines dans des emplacements à faible coût énergétique, offrant ainsi l'accès à des tarifs électriques avantageux sans les tracas de la gestion des équipements.

Malgré ces options, le minage présente des défis significatifs. L'adage bien connu du monde des cryptomonnaies, "Pas tes clés, pas tes Bitcoins", trouve une résonance similaire dans le monde du minage : "Pas ton hashrate, pas ta récompense". Les histoires de déceptions et de machines déconnectées sont monnaie courante, avec de nombreux acteurs promettant des résultats exceptionnels mais ne les livrant pas. Les problèmes d'approvisionnement en électricité et les pannes de machines peuvent laisser les investisseurs impuissants, avec des équipements coûteux qu'ils ne contrôlent pas. Dans ce contexte, la prudence et une compréhension approfondie du secteur du minage sont cruciales avant de s'y aventurer. Bien que les opportunités de gains existent, les risques sont significatifs, et une approche informée et réfléchie est essentielle pour naviguer dans ce domaine complexe et souvent imprévisible. Il est donc vital de faire des recherches approfondies et de bien peser les avantages et les inconvénients avant de s'engager dans le minage de Bitcoin.

### Des Bitcoins Vierges

L'aspiration à posséder son propre hashrate se présente comme une voie prometteuse dans l'univers du minage. Cependant, naviguer dans cet écosystème complexe requiert une approche prudente. Le domaine est marqué par un grand nombre d'escroqueries, alimentées par un manque de compréhension du minage de la part de nombreux investisseurs. Les offres alléchantes, emballées de diverses manières, peuvent facilement induire en erreur ceux qui ne sont pas assez informés. Mais posséder son propre équipement de minage offre des avantages considérables. Outre la satisfaction personnelle de contribuer activement à la sécurisation du réseau Bitcoin et de voir les récompenses tomber sur son portefeuille, il y a l'aspect attrayant des "bitcoins vierges". Il s'agit de bitcoins fraîchement minés, qui n'ont jamais été dépensés et qui n'ont aucune histoire attachée à eux. Ces bitcoins sont souvent considérés comme plus précieux car ils n'ont jamais été "souillés", offrant une certaine garantie contre le rejet par des régulateurs ou des grandes plateformes d'échange.

La possibilité de miner ces bitcoins vierges tout en évitant les procédures de connaissance du client (KYC) est une autre valeur ajoutée. De nombreux pools de minage ne demandent pas l'identité des mineurs, permettant ainsi d'acquérir des bitcoins sans passer par des vérifications d'identité fastidieuses. Ce concept de "bitcoins blancs" est également exploré, où les bitcoins sont catégorisés en fonction de leur historique. Les bitcoins vierges sont perçus comme "blancs", ne portant aucune histoire ni association passée. Ils sont particulièrement recherchés par les gros acteurs institutionnels qui peuvent garantir la légitimité de leurs actifs numériques face aux autorités de régulation. Cependant, malgré ces avantages, il est crucial de reconnaître que l'industrie du minage reste extrêmement compétitive et volatile. Des incidents imprévus peuvent perturber les opérations de minage, et les promesses alléchantes peuvent souvent s'avérer fallacieuses. De plus, la complexité inutile des offres de minage devrait servir de drapeau rouge, incitant à une investigation plus approfondie avant d'investir.

Dans ce contexte, le choix d'une démarche autonome et éduquée en matière de minage apparaît judicieux. L'acquisition de son propre hashrate et l'investissement dans des équipements de minage personnels, tout en restant conscient des risques et des défis, peut potentiellement offrir une voie plus sûre et plus satisfaisante vers l'acquisition de bitcoins vierges, renforçant ainsi la souveraineté financière de l'individu tout en soutenant l'écosystème Bitcoin dans son ensemble.

### Miner pour du profit ou pour le réseau ?

La question est profonde et englobe plusieurs dimensions du minage de Bitcoin. L'équilibre entre la recherche de profit et la contribution à la sécurité et à la décentralisation du réseau Bitcoin est un dilemme constant pour les mineurs. Le débat se poursuit dans la communauté Bitcoin, avec des arguments solides de chaque côté.

* Miner pour le profit:
  - Pour : Les mineurs sont naturellement attirés par le potentiel de gain qu'offre le minage de Bitcoin. L'investissement dans des équipements de minage coûteux peut être rentabilisé par les récompenses de minage et les frais de transaction, surtout lorsque le prix du Bitcoin est élevé.
  - Contre : La recherche de profit peut mener à la centralisation du pouvoir de hachage si seules quelques grandes entreprises peuvent se permettre d'investir dans des équipements de minage haut de gamme. De plus, la consommation d'énergie du minage pour le profit peut avoir un impact environnemental significatif.

* Miner pour le réseau:
 - Pour : Miner pour contribuer à la sécurité et à la décentralisation du réseau Bitcoin est une initiative noble. Cela aide à renforcer la résilience du réseau et à résister à la censure et aux attaques.
 - Contre : Sans un incitatif financier suffisant, il peut être difficile pour les mineurs de continuer à soutenir le réseau, surtout s'ils opèrent à perte.

L'initiative Atakai met en avant l'importance de la contribution au réseau tout en offrant des solutions pour rendre le minage plus accessible et moins nuisible. La possibilité de miner chez soi, avec du matériel plus abordable et des solutions pour réduire le bruit et la consommation d'énergie, peut aider à démocratiser le minage de Bitcoin. Elle encourage ceux qui sont intéressés par le Bitcoin non seulement à investir et à détenir des bitcoins, mais aussi à participer activement à la sécurisation du réseau. En fournissant des équipements testés et des guides pour l'assemblage et l'installation, Atakai facilite l'entrée dans le monde du minage de Bitcoin. Ils encouragent également l'innovation et les améliorations continues, invitant la communauté à contribuer et à partager leurs idées et expériences pour améliorer le minage à domicile. Le modèle Atakai est une réponse à la question de miner pour le profit ou pour le réseau. Il ne s'agit pas seulement de réaliser des profits, mais aussi de renforcer la décentralisation et la sécurité du réseau Bitcoin, tout en permettant à davantage de personnes de participer au minage, d'apprendre et de comprendre cette industrie cruciale. Le défi de l'interdiction éventuelle du minage en Europe reste une question ouverte. Cela soulève des préoccupations sur l'avenir du minage de Bitcoin dans la région et la nécessité d'une régulation équilibrée qui reconnaisse l'importance du minage pour la sécurité et la viabilité du réseau Bitcoin tout en abordant les questions environnementales. Atakai et d'autres initiatives similaires peuvent jouer un rôle crucial dans ce débat, en montrant qu'il est possible de miner de manière plus durable et responsable, tout en contribuant positivement au réseau Bitcoin.

### Le minage interdit en Europe ?

Avec la question du potentiel d'interdiction du minage en Europe, les discussions sur la régulation deviennent de plus en plus pertinentes. Le paysage réglementaire fluctuant peut, en effet, influencer considérablement l'industrie du minage de Bitcoin. L'interdiction du minage en Europe est un scénario envisageable, notamment en considérant les précédents en Chine. Bien que des opérations de minage continuent en Chine malgré l'interdiction, l'Europe pourrait suivre un chemin similaire. Une distribution plus large du hashrate dans différentes régions pourrait aider à renforcer la communauté des mineurs en Europe, leur permettant de s'opposer efficacement aux malentendus et aux idées fausses concernant le minage, son impact environnemental et son empreinte sur le réseau électrique.

Face à des campagnes comme celles de Greenpeace et aux chiffres souvent trompeurs de certaines études, la meilleure arme reste l'information véridique. Il est essentiel d'informer le grand public et les décideurs sur la réalité du minage, sa complexité, et sa nuance, plutôt que de les laisser s'appuyer sur des clichés et des informations inexactes. Plus il y aura de personnes informées et conscientes de ce qu'est réellement le minage, mieux l'industrie pourra se défendre contre les éventuelles réglementations restrictives.

En conclusion, malgré le risque réglementaire et la possibilité d'une interdiction du minage en Europe, l'arme la plus puissante reste l'éducation et l'information. La compréhension claire et précise du minage, son fonctionnement, et son impact peut aider à démystifier l'industrie et à lutter contre la désinformation, offrant ainsi une meilleure résistance aux régulations potentiellement dommageables. L'initiative de former et d'informer les gens sur le minage, comme le fait cette discussion, est un pas dans la bonne direction pour garantir la pérennité et la croissance du minage en Europe, et partout dans le monde. Les efforts continus pour éduquer et informer sont essentiels pour assurer un avenir sûr et prospère pour l'industrie du minage de Bitcoin.

# Atelier pratique avec un S9.

## Attakai - le home-mining rendu possible et accessible !

![Introduction à Attakaï: se chauffer avec Bitcoin](https://youtu.be/U_PLo59lp-g?si=NkoEcF7ejUPGboQf)

L'initiative "Attakaï" explore le minage de Bitcoin en utilisant la chaleur générée. Le guide propose des solutions pour rendre les mineurs adaptés à une utilisation en tant que radiateurs dans les logements, offrant ainsi plus de confort et d'économies d'énergie. Le Bitcoin ajuste automatiquement la difficulté du minage et récompense les mineurs pour leur travail. Cependant, la concentration du hashrate peut poser des risques pour la neutralité du réseau. "Attakaï" offre un guide pratique pour rétrofitter les mineurs de manière économique, permettant aux participants de réduire leur facture d'électricité et d'être récompensés avec des sats sans KYC.

“Attakaï », qui signifie « la température idéal » en japonais, est le nom de l’initiative visant à découvrir le minage de bitcoin à travers la réutilisation de la chaleur lancée par @ajelexBTC et @BlobOnChain avec Découvre Bitcoin. Ce guide de retrofitting d’un ASIC servira de base pour en apprendre plus sur le minage, son fonctionnement, son histoire récente et l’économie sous-jacente.

### Pourquoi réutiliser la chaleur d’un ASIC ?

Il est important de comprendre la relation entre l’énergie et la production de chaleur dans un système électrique.

Pour un investissement de 1 kW d’énergie électrique, un radiateur électrique produit 1 kW de chaleur, ni plus ni moins. Les nouveaux radiateurs ne sont pas plus performants que les radiateurs traditionnels. Leur avantage réside dans leur capacité à diffuser la chaleur de manière continue et homogène dans une pièce, apportant ainsi plus de confort par rapport aux radiateurs traditionnels qui alternent entre une forte puissance de chauffage et une absence de chauffage, générant ainsi des variations de température régulières et de l’inconfort.

Un ordinateur, ou plus largement une carte électronique, ne consomme pas d’énergie pour effectuer des calculs, il a simplement besoin que de l’énergie circule dans ses composants pour fonctionner. La consommation d’énergie est dû à la résistance électrique des composants qui produit des pertes créant ainsi de la chaleur c’est ce qu’on appel l’effet joule.

Certaines entreprises ont eu l’idée de mutualiser les besoins en puissance de calcul et les besoins de chauffage grâce à des radiateurs/serveur. L’idée étant de distribuer les serveurs d’une entreprise en petites unités qui pourraient être placées dans des logements ou des bureaux. Cependant, cette idée rencontre plusieurs problèmes. La besoin des serveurs n’est pas liée au besoin de chauffage et les entreprises ne peuvent pas utiliser les capacités de calcul de leurs serveurs de façon flexible. Il existe aussi des limites à la bande passante que des particuliers peuvent posséder. Toutes ces contraintes ne permettent pas à l’entreprise de rentabiliser ces installations coûteuses ni de fournir une offre de serveur en ligne stable sans avoir des centres de données capables de prendre le relais quand le besoin de chauffage n’est pas présent.

> “La chaleur de votre ordinateur n’est pas gaspillée si vous devez chauffer chez vous. Si vous utilisez un chauffage électrique là où vous habitez, alors la chaleur de votre ordinateur n’est pas un gâchis. C’est le même prix si vous générer cette chaleur avec votre ordinateur.Si vous avez un autre système de chauffe moins cher que l’électrique alors le gaspillage est seulement dans la différence de coût. Si c’est l’été et que vous utilisez la climatisation alors c’est le double. a création de bitcoins devrait avoir lieu là où elle est moins chère. Peut-être que ce sera là où le climat est froid et là où le chauffage est électrique, où miner deviendrait gratuit.”
>
> Satoshi Nakamoto – 8 août 2010

Le Bitcoin et sa preuve de travail se démarquent car ils ajustent automatiquement la difficulté du minage en fonction de la quantité de calcul effectué par l’ensemble du réseau, cette quantité s’appelle le hashrate et est exprimé en hash/seconde. Aujourd’hui il est estimé à 280 Exahash/seconde, soit 280 milliards de milliards de hash/seconde. Ce hashrate représente du travail et donc une quantité d’énergie dépensée. Plus le hashrate est élevée, plus la difficulté augmente, et inversement. Ainsi, on peut activer ou désactiver un mineur Bitcoin à n’importe quel moment sans incidence pour le réseau contrairement aux radiateurs/serveurs qui nécessiterait de rester stables pour offrir leur service. Le mineur est récompensé pour le travail effectué relativement au travail des autres, aussi petite cette participation soit-elle.

En résumé, un radiateur électrique et un mineur Bitcoin produisent tout deux 1 kW de chaleur pour 1 kW d’électricité dépensée. Cependant, le mineur reçoit également des bitcoins en récompense. Indépendamment du prix de l’électricité, du prix du bitcoin ou de la concurrence de l’activité de minage sur le réseau Bitcoin, il est économiquement plus avantageux de se chauffer avec un mineur plutôt qu’avec un radiateur électrique.

![Video présentation](https://youtu.be/gKoh44UCSnE)

### La plus-value pour Bitcoin

Nous ne rentrerons pas dans les détails du fonctionnement du minage ici (ressources disponibles sur l’académie si besoin). Ce qu’il est important de comprendre, c’est la manière dont le minage participe à la décentralisation de Bitcoin.
Plusieurs technologies déjà existantes ont été ingénieusement combinées pour donner vie au consensus de Nakamoto. Ce consensus permet de récompenser économiquement les acteurs honnêtes pour leur participation au fonctionnement du réseau Bitcoin, tout en décourageant les acteurs malhonnêtes. C’est l’un des points clés qui permet au réseau d’exister de façon durable.
Les acteurs honnêtes, ceux qui effectuent du minage selon les règles, sont tous en concurrence les uns avec les autres pour obtenir la plus grande part possible de la récompense pour la production de nouveaux blocs. Cette incitation économique conduit naturellement à une forme de centralisation car des entreprises choisissent de se spécialiser dans cette activité lucrative en réduisant leurs coûts grâce aux économies d’échelle. Ces acteurs industriels ont une position avantageuse, pour l’achat, la maintenance de machines mais aussi pour la négociation de tarifs d’électricité de gros.

> “Au début, la plupart des utilisateurs exécuteraient des nœuds de réseau, mais à mesure que le réseau se développerait au-delà d’un certain point, il serait de plus en plus laissé aux spécialistes avec des fermes de serveurs de matériel spécialisé. Une batterie de serveurs n’aurait besoin que d’un seul nœud sur le réseau et le reste du LAN se connecte à ce nœud.”
>
>       - Satoshi Nakamoto – 2 novembre 2008

Certaines entités détiennent un pourcentage considérable du hashrate total dans de grandes fermes de minage. On peut observer la récente vague de froid aux États-Unis où une partie importante du hashrate a été mise hors ligne pour permettre à l’énergie d’être redirigée vers les foyers ayant un besoin exceptionnel d’électricité. Pendant plusieurs jours, les mineurs ont été incités économiquement à éteindre leurs fermes et on peut donc voir cette météo exceptionnelle sur la courbe du hashrate de Bitcoin.

Ce sujet pourrait devenir problématique et apporte un risque important pour la neutralité du réseau. Un acteur possédant plus de 51% du hashrate pourrait plus facilement censurer des transactions s’il le souhaitait. C’est pourquoi il est important de distribuer le hashrate entre de multiples acteurs plutôt que dans des entités centralisées qui pourraient être plus facilement saisies par un gouvernement, par exemple.

**Si les mineurs sont répartis dans des milliers, voire des millions de logements à travers le monde, il devient très compliqué pour un État d’en prendre le contrôle.**

À sa sortie d’usine, un mineur n’est pas approprié pour servir de radiateur dans un logement, en raison de deux problèmes principaux : un bruit excessif et l’absence de réglage. Cependant, ces problèmes peuvent être facilement résolus grâce à des modifications simples réalisées au hardware et au software, permettant d’obtenir un mineur beaucoup plus silencieux et pouvant être paramétré et automatisé comme les chauffages électriques modernes.

**Attakaï est une initiative éducative qui vous apprend à effectuer un retrofitting de l’Antminer S9 de la manière la plus économique possible.**

C’est une excellente opportunité pour apprendre en pratiquant. En plus de réduire votre facture d’électricité, vous êtes récompensé pour votre participation par des sats KYC free.

## EP 1 - Guide d’achat pour un ASIC d’occasion

### Achat d'un S9 d'occasion

Dans cet section nous allons voir les bonnes pratiques afin d’acheter un Bitmain Antminer S9 d’occasion, la machine sur laquelle ce tutoriel de retrofitting en radiateur sera basé. Ce guide fonctionne aussi pour d’autres modèles d’ASIC car il s’agit d’un guide d’achat général pour du matériel de minage d’occasion.

Le Antminer S9 est un appareil proposé par Bitmain depuis mai 2016. Il consomme 1323W d’électricité et produit 13,5 TH/s. Bien qu’il soit considéré comme ancien, il reste une excellente option pour débuter le minage. Étant donné qu’il a été produit en grande quantité, il est facile de trouver des pièces détachées en abondance dans de nombreuses régions du monde. On peut généralement l’acquérir de façon pair à pair sur des sites tels qu’Ebay ou LeBonCoin, car les revendeurs s’adressant aux professionnels ne le proposent plus en raison de sa moindre compétitivité par rapport à des machines plus récentes. Il est moins efficient que des ASIC comme le Antminer S19, proposé depuis mars 2020, mais cela en fait un matériel d’occasion abordable et plus approprié pour les modifications que nous allons effectuer.

Le Antminer S9 existe en plusieurs déclinaisons (i,j) qui apportent des modifications mineures au matériel de première génération. Nous ne pensons pas que cet élément devrait orienter votre décision d’achat et ce guide fonctionnera pour toutes ces déclinaisons.

Le prix des ASIC varie en fonction de nombreux facteurs comme le cours du prix du bitcoin, la difficulté du réseau, l’efficience de la machine et le coût de l’électricité. Il est donc difficile de donner une estimation précise pour l’achat d’une machine d’occasion. En février 2023, le prix attendu en France se situe généralement entre 100€ et 200€ mais ces prix sont susceptible de changer très rapidement

![image](assets/guide-achat/1.jpeg)

Le Antminer S9 est composé des parties suivantes :

- 3 hashboards où sont les puces qui produisent le hachage

![image](assets/guide-achat/2.jpeg)

- Une carte de contrôle comprenant un emplacement pour une carte SD, un port Ethernet et des connecteurs pour les hashboards et les ventilateurs. C’est le cerveau de votre ASIC.

![image](assets/guide-achat/3.jpeg)

- 3 câbles de data qui connectent les hashboards avec la carte de contrôle

![image](assets/guide-achat/4.jpeg)

- L’alimentation qui fonctionne en 220V et peut donc être branchée comme un appareil ménager classique

![image](assets/guide-achat/5.jpeg)

- 2 ventilateurs de 120mm

![image](assets/guide-achat/6.jpeg)

- Un cable C13 mâle

![image](assets/guide-achat/7.jpeg)

Lorsque vous achetez une machine d’occasion, il est important de vérifier que toutes les pièces sont incluses et fonctionnelles. Lors de l’échange, vous devriez demander au vendeur de mettre en marche la machine pour vérifier son bon fonctionnement. Il est important de vérifier que l’appareil s’allume correctement, puis de vérifier la connectivité à internet en branchant un câble Ethernet et en accédant à l’interface de connection de Bitmain via un navigateur internet sur le même réseau local. Vous pourrez trouver cette adresse IP en vous connectant à l’interface de votre routeur internet et en cherchant les appareils connectés. Cette adresse devrait avoir le format suivant : 192.168.x.x

![image](assets/guide-achat/8.gif)

Vérifiez également que les identifiants par défaut fonctionnent (identifiant : root, mot de passe : root). Si les identifiants par défaut ne fonctionne pas il faudra effectuer un reset de la machine.

![image](assets/guide-achat/9.jpeg)

Une fois connecté, vous devriez pouvoir voir l’état de chaque hashboard sur le tableau de bord. Si le mineur est connecté à une pool, vous devriez voir toutes les hashboards fonctionner. Il est important de noter que les mineurs font beaucoup de bruit, c’est normal. Assurez-vous également que les ventilateurs fonctionnent correctement.

Vous pouvez ensuite supprimer la pool de minage de l’ancien propriétaire pour configurer la vôtre par la suite. Si vous le souhaitez, vous pouvez également inspecter les hashboards en démontant la machine. Cependant, cette étape est plus complexe et nécessite plus de temps et certains outils. Si vous souhaitez procéder à ce démontage, vous pouvez vous référer à la partie suivante de ce tutoriel qui détaille comment le faire. Il est important de noter que les mineurs collectent beaucoup de poussière et nécessitent un entretien régulier. C’est cette accumulation de poussière et la qualité de l’entretien que vous pourrez observer en démontant la machine.
Après avoir passé en revue tous ces points, vous pouvez acheter votre machine avec un degré de confiance maximum. En cas de doute, adressez-vous à la communauté et si vous avez besoin de matériel pour réaliser ce tutoriel, n’hésitez pas à nous envoyer un message.

Pour synthétiser ce guide en une phrase : **« Ne faites pas confiance, vérifiez »**.

### Achat des pièces pour modifications hardware du S9

![image](assets/piece/1.jpeg)

Si vous êtes propriétaire d’un Antminer S9, vous savez probablement à quel point cet équipement peut être bruyant et encombrant. Cependant, il est possible de le transformer en un chauffage silencieux et connecté en suivant quelques étapes simples. Dans cet article nous allons vous présenter les équipements nécessaires pour effectuer les modifications, tandis qu’un article ultérieur expliquera en détail les étapes à suivre pour réaliser ces changements.

1. Remplacer les ventilateurs

Les ventilateurs d’origine de l’Antminer S9 sont trop bruyants pour utiliser votre Antminer en chauffage. La solution est de les remplacer par des ventilateurs plus silencieux. Notre équipe a testé plusieurs modèles de la marque Noctua et à sélectionné le Noctua NF-A14 iPPC-2000 PWM comme le meilleur compromis, attention à bien choisir la version 12V des ventilateurs. Ce ventilateur de 140mm peut permettre de produire jusqu’à 1300W de chauffage tout en maintenant un niveau de bruit théorique de 31 dB. Pour pouvoir monter ces ventilateurs de 140mm, il faudra utiliser un adaptateur 140mm vers 120mm que vous pourrez retrouver sur la boutique de DécouvreBitcoin. Et nous ajouterons également des grilles de protection 140mm.

![image](assets/piece/1.jpeg)
![image](assets/piece/2.jpeg)
![image](assets/piece/3.jpeg)

Le ventilateur de l’alimentation est également assez bruyant et doit être remplacé. Nous recommandons le Noctua NF-A6x25 PWM. Notez que les connecteurs des ventilateurs Noctua ne sont pas les mêmes que ceux d’origine, donc vous aurez besoin d’un sucre pour les connecter, 2 suffirons. Attention ici aussi à bien choisir la version 12V du ventilateur.

![image](assets/piece/4.jpeg)
![image](assets/piece/5.jpeg)

2. Ajouter un bridge WIFI/Ethernet

Au lieu d’utiliser un câble Ethernet, vous pouvez connecter votre Antminer en WIFI en ajoutant un bridge WIFI/Ethernet. Nous avons sélectionné le vonets vap11g-300 car il permet facilement de récupérer le signal WIFI de votre box Internet et de le transmettre à votre Antminer en Ethernet sans créer de sous réseau. Si vous avez des compétences en électricité pouvez l’alimenter directement avec l’alimentation du Antminer sans avoir besoin de rajouter un chargeur USB, pour cela vous aurez besoin d’un jack 5,5mmx2,1mm femelle.

![image](assets/piece/6.jpeg)
![image](assets/piece/7.jpeg)

3. Optionnel : ajouter une prise connectée

Si vous souhaitez allumer/éteindre votre Antminer depuis votre smartphone et monitorer sa consommation d’énergie, vous pouvez ajouter une prise connectée. Nous avons testé la prise ANTELA en version 16A compatible avec l’application smartlife. Cette prise connectée permet de consulter la consommation jour par jour et mois par mois et se connecte directement en WIFI à votre box Internet.

![image](assets/piece/8.jpeg)

Liste du matériel et liens

* 2X pièce 3D adapteur 140mm vers 120mm

* 2X NF-A14 iPPC-2000 PWM https://www.amazon.fr/Noctua-nf-polarized-A14-industrialppc-PWM-2000/dp/B00KESSUDW/ref=sr_1_2?__mk_fr_FR=ÅMÅŽÕÑ&crid=JCNLC31F3ECM&keywords=NF-A14+iPPC-2000+PWM&qid=1676819936&sprefix=nf-a14+ippc-2000+pwm%2Caps%2C114&sr=8-2

* 2X Grilles de ventilateurs 140mm https://www.amazon.fr/dp/B06XD4FTSQ?psc=1&ref=ppx_yo2ov_dt_b_product_details
  
* Noctua NF-A6x25 PWM https://www.amazon.fr/Noctua-nf-a6-25-PWM-Ventilateur-Marron/dp/B00VXTANZ4/ref=sr_1_1_sspa?__mk_fr_FR=ÅMÅŽÕÑ&crid=3T313ABZA5EDE&keywords=Noctua+NF-A6x25+PWM&qid=1676819329&sprefix=noctua+nf-a6x25+pwm%2Caps%2C71&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1&smid=A38F5RZ72I2JQ

* Sucre d’électricien 2,5mm2 https://www.amazon.fr/Legrand-LEG98433-Borne-raccordement-Nylbloc/dp/B00BBHXLYS/ref=sr_1_3?__mk_fr_FR=ÅMÅŽÕÑ&crid=25IRJD7A0YN2A&keywords=sucre%2Belectrique%2B2mm2&qid=1676820815&sprefix=sucre%2Belectrique%2B2mm2%2Caps%2C84&sr=8-3&th=1

* Vonets vap11g-300 https://www.amazon.fr/Vonets-VAP11G-300-Bridge-convertit-Ethernet/dp/B014SK2H6W/ref=sr_1_3_sspa?__mk_fr_FR=ÅMÅŽÕÑ&crid=13Q33UHRKCKG5&keywords=vonet&qid=1676819146&s=electronics&sprefix=vonet%2Celectronics%2C98&sr=1-3-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1

* Optionnel prise connectée ANTELA https://www.amazon.fr/dp/B09YYMVXJZ/ref=twister_B0B5X46QLW?_encoding=UTF8&psc=1


## EP 1 - Modification du software & Réinitialiser un Antminer S9

![Connecter un Antminer S9 à son réseau Wifi](https://youtu.be/y4oYURBaPqg?si=4HYDqqo9YfavJ9t6)

### Réinitialiser via le bouton « Reset »

Cette méthode peut être appliquée dans les 10 minutes après le démarrage du mineur.

Après avoir allumé le mineur pendant 2 minutes, veuillez appuyer sur le bouton « Reset » pendant 5 secondes, puis relâchez-le. Le mineur sera restauré aux paramètres d’usine dans les 4 minutes et redémarrera automatiquement (il n’est pas nécessaire de l’éteindre).

![image](assets/software/1.jpeg)

Restore via web side

Connectez-vous à l’interface utilisateur de votre mineur, cliquez sur « Upgrade » >> « Effectuer une réinitialisation », puis cliquez sur « OK » dans la fenêtre pop-up.

### Système d’exploitation d’origine

Pour cette partie, nous supposerons que la machine fonctionne, est en marche et que son système d’exploitation d’origine est installé. Nous allons voir brièvement l’interface du système d’exploitation d’origine proposée par Bitmain.

Tout d’abord, connectez vous à votre machine à travers votre réseau local :

![image](assets/software/2.gif)

Une fois sur la page de connexion, vous devrez vous connecter à l’ASIC en utilisant les identifiants par défaut :

– username: root
– password: root

(Comment reset si mot de passe par défaut ne fonctionne pas ?)

Le système d’exploitation principal est relativement basique. Avec les 4 onglets : System, Miner Configuration, Miner Status, Network. Dans l’onglet Miner Configuration vous pouvez configurer jusqu’à 3 pools de minage.

![image](assets/software/3.jpeg)

Dans l’onglet Miner Status vous pourrez observer différentes informations sur le fonctionnement de l’ASIC en direct. Le hashrate exprimé en GH/s, des informations plus précises sur la pool ainsi qu’un détail sur le statut de chaque hashboard et la vitesse des ventilateurs en rotations/minute.

![image](assets/software/4.jpeg)

## EP3 - Installer Braiins OS+ sur son Antminer S9

![Installer Braiins OS+ sur son Antminer S9](https://youtu.be/luqwlvzGsO4?si=ua2tcCwfl2CTeaJw)

Maintenant, nous allons étudier le logiciel pour ASICs Braiins OS+(https://braiins.com/os/plus). Le logiciel est développé par la société Braiins(https://braiins.com/) qui est l’entreprise mère de la pool de minage Braiins Pool'https://braiins.com/pool). Cette pool de minage possède au moment de l’écriture de ces lignes 4.39% du hashrate global( https://mempool.space/fr/mining/pool/slushpool). La société basée à Prague était anciennement nommée Slushpool et est la première pool de minage ayant débutée en novembre 2010. Aujourd’hui la société aux activités variées propose des outils d’étude de profitabilité pour le minage ( https://insights.braiins.com/en), des solutions de gestion de fermes de minage en parallèle de se son activité de pool et son logiciel d’optimisation pour ASICs. Elle propose aussi de miner à en utilisant le nouveau protocole Stratum V2(https://braiins.com/bitcoin-mining-stack-upgrade).

Nous allons donc étudier plus en détail le fonctionnement des appareils de la marque Bitmain qui sont pour l’instant les seuls modèles compatibles :

- S19, S19 Pro, S19j, S19j Pro, T19,

- 17, S17 Pro, S17+, S17e, T17, T17+, T17e & S9 [i, j]

Le logiciel Braiins OS peut être installé assez simplement sur toutes les machines citées ci-dessus. Il permettra un contrôle plus précis d’une machine en permettant de l’overclocker sur-cadençage ou de l’underclocker sous-cadençage. Il permet également un réglage fin de la fréquence de chaque puce grâce à une fonctionnalité d’optimisation automatique appelée l’autotuning. Comme chaque puce de hachage est légèrement différente du fait de son procédé de fabrication, le logiciel teste la fréquence optimale pour chacune d’entre elles afin d’obtenir une efficience (W/THs) maximum. Le logiciel annonce des performances pouvant être supérieures de 25% à celles d’origine. Selon nos mesures il est possible d’atteindre ces figures.

### Installation de Braiins OS+

Il existe plusieurs façons d’installer Braiins OS+ sur un ASIC. Vous pouvez vous référer à ce guide mais aussi à la documentation officielle de Braiins et aux tutoriels vidéo.
Installation de Braiins OS+ directement sur la mémoire du Antminer

Découvrez comment installer facilement Braiins OS+ directement sur la mémoire de votre Antminer avec BOS toolbox, en remplaçant ainsi le système d’exploitation d’origine, à travers les étapes détaillées ci-dessous. Si vous souhaitez conserver l’OS d’origine en parallèle vous pouvez installer Braiins OS+ sur un carte SD.

1. Alimentez votre Antimner et branchez le à votre Box internet
2. Télécharger BOS toolbox Windows / Linux
3. Décompressez le fichier téléchargé et ouvrez le fichier bos-toolbox.bat choisissez la langue puis après quelque instant vous verrez cette fenêtre:

![image](assets/software/5.jpeg)

4. Bos toolbox va vous permettre de facilement trouver l’adresse IP de votre Antminer et installer Braiins OS+. Si vous connaissez déjà l’adresse IP de cotre machine vous pouvez passer à l’étape 8. Autrement, aller dans l’onglet scan.

![image](assets/software/6.jpeg)

5. Habituellement sur les réseaux domestique la plage d’adresse IP se situe entre 192.168.1.1 et 192.168.1.255, mettez donc dans le champs IP range “192.168.1.0/24. Si votre réseaux est différent veuillez changer ces adresses. Puis cliquez sur “Start”

6. Attention, si le Antminer possède un mot de passe alors la détection ne fonctionnera pas. Si c’est le cas le plus simple est d’effectuer un Reset factory

7. Vous devriez voir apparaître l’ensemble des Antminer sur votre réseau, ici l’adresse IP est 192.168.1.37

![image](assets/software/7.jpeg)

8. Cliquez sur Back puis l’onglet install, rentrez l’adresse IP précédemment trouvée dans le champs Miner(s) et “admin” (ou “root”) dans le champs Password, c’est le mot de passe par défaut puis cliquer sur “Start”.

> Si l’installation ne fonctionne pas, ni avec “admin” ou “root” en Password il peut être nécessaire d’effectuer un reset factory puis essayer de nouveau.

![image](assets/software/8.jpeg)

9. Après quelques instants, votre Antminer va redémarrer et vous pourrez accéder à l’interface de Braiins OS+ à l’adresse IP en question, ici 192.168.1.37 à rentrer directement dans la barre d’adresse de votre navigateur, username par défaut “root” pas de password par défaut.

> Installation de Braiins OS+ sur une carte SD

![image](assets/software/9.jpeg)

![image](assets/software/10.jpeg)

La deuxième méthode utilise l’interface d’origine de votre Antminer. Cette méthode fonctionne pour les machines avec un système d’exploitation datant d’avant 2019.

### Interface Antminer

1. Télécharger le nouveau système d’exploitation à installer ici.
2. Comme dans la section précédente, connectez vous à votre machine à travers votre réseau local.
3. Allez dans l’onglet System puis Upgrade
4. Chargez le fichier que vous avez téléchargé et flashez l’image.

![image](assets/software/11.jpeg)

### Carte micro SD

Une seconde méthode vous permet d’utiliser une carte micro SD. Cette méthode fonctionne uniquement avec les machines avec un système d’exploitation datant d’après 2019.

1. Téléchargez le nouveau système d’exploitation à installer ici.

2. Flashez l’image téléchargée sur une carte Micro SD. pour cela, vous pouvez utiliser Etcher. Simplement copier le fichier dans la carte micro SD ne fonctionnera pas.

3. Si vous possédez un Antminer S9 et ses déclinaisons (S9i, S9j) vous devrez ajuster des “jumper” pour forcer votre ASIC à démarrer à partir du fichier contenu sur la carte micro SD plutôt que la NAND. Si vous avez un autre modèle, vous pouvez passer à la partie 4. Les jumpers se trouvent sur la carte de contrôle sur la partie supérieur de l’ASIC, à proximiter du port Ethernet. Vous devrez la retirer en la faisant glisser en arrière. Une fois la position du jumper modifiée comme sur les images ci-dessous BOOT FROM SD vous pouvez réinsérer la carte de contrôle et connecter le S9 à nouveau.

![image](assets/software/12.jpeg)

![image](assets/software/13.jpeg)

4. Insérez la carte micro SD dans l’ASIC.

5. Démarrez l’ASIC. Si la version d’installation automatique a été utilisée, le nouveau système d’exploitation sera automatiquement installé. L’installation est terminée lorsque les deux LEDs s’allument au même moment. Vous pouvez redémarrer l’ASIC et retirer la carte micro SD. Si l’autre version a été téléchargée, vous devrez laisser la carte Micro SD à l’intérieur de l’ASIC.

Pour plus d’informations sur l’installation, vous pouvez visiter cette section du site de Braiins.

## EP4 - Configurer son Antminer S9 avec Braiins OS+

![Configurer son Antminer S9 avec Braiins OS+](https://youtu.be/dK0t8M8kLYg?si=gX3660NtZsV3QL45)

Vous devrez vous connecter à votre ASIC de façon similaire. En utilisant l’adresse IP locale de votre appareil sur votre réseau à travers un navigateur.

Les identifiants par défaut sont les mêmes que le système d’exploitation d’origine.

- username: root
- password: root

Vous serez alors accueilli par le Dashboard de Brains OS+

### Dashboard

![image](assets/software/14.jpeg)

Sur cette première pages vous pourrez observer les performances de votre machine en direct.

- Trois graphiques en temps réel qui vous présente la température, le hashrate ainsi que le statut global de votre machine.
- Sur la droite le hashrate réel, la température moyenne des puces, votre efficience estimée en W/THs ainsi que la consommation électrique.
- Au dessous la vitesse de rotation des ventilateurs en pourcentage de la vitesse maximum ainsi que le nombre de rotations/minute.

![image](assets/software/15.jpeg)

- Plus bas vous trouverez une vue détaillée de chaque hashboard. La température moyenne de la board et des puces qui la compose, la tension et la fréquence.
- Un détail sur les pools de minage active dans Pools.
- Le statut de l’autotuning dans Tuner Status.
- Sur la droite des détails sur les parts transmises à la pool.

### Configuration

![image](assets/software/16.jpeg)

### System

![image](assets/software/17.jpeg)

### Quick actions

![image](assets/software/18.jpeg)

## 5. Remplacer les ventilateurs pour réduire les nuisances sonores

![Remplacer les ventilateurs pour réduire les nuisances sonores](https://youtu.be/2CNGKZiveuc?si=CSXNEK8okFTjg7sT)

Si vous êtes un bricoleur averti et que vous cherchez à transformer un mineur en chauffage, ce tutoriel est fait pour vous. Nous tenons à vous avertir que les modifications apportées à un appareil électronique peuvent présenter des risques électriques et d’incendie. Il est donc essentiel de prendre toutes les précautions nécessaires pour éviter tout dommage ou blessure.
En sortie d’usine, un mineur n’est pas vraiment utilisable comme radiateur dans un logement, car il est beaucoup trop bruyant et qu’il n’est pas réglable. Toutefois, il est possible d’effectuer des modifications simples pour résoudre ces problèmes.

> ATTENTION : Il est essentiel d’avoir préalablement installé Braiins OS+ sur votre mineur, ou tout autre logiciel ayant la capacité de réduire les performances de votre machine. Cette mesure est cruciale, car dans le but de réduire le bruit, nous allons installer des ventilateurs moins puissants, qui pourront dissiper moins de chaleur.

![image](assets/hardware/cover.jpeg)


### Matériels nécessaires

- 2 pièces 3D adapteur 140mm vers 120mm
- 2 ventilateurs Noctua NF-A14 iPPC-2000 PWM
- 2 grilles de ventilateurs 140mm
- 1 ventilateur Noctua NF-A6x25 PWM
- Sucre d’électricien 2,5mm2
- Vonets VAP11G-300
- Optionnel : prise connectée ANTELA

### Remplacement des ventilateurs

Nous allons commencer par remplacer le ventilateur de l’alimentation.

>  ATTENTION : Tout d’abord, avant de commencer, assurez-vous de bien avoir débranché votre mineur pour éviter tout risque d’électrocution.

![image](assets/hardware/1.jpeg)

Nous allons commencer par remplacer le ventilateur de l’alimentation.

Tout d’abord, retirez les 6 vis sur le côté du boîtier qui le maintiennent fermé. Une fois les vis retirées, ouvrez délicatement le boîtier pour retirer la protection plastique qui recouvre les composants.

![image](assets/hardware/2.jpeg)
![image](assets/hardware/3.jpeg)

Ensuite, il est temps de retirer le ventilateur d’origine en prenant soin de ne pas endommager les autres composants. Pour ce faire, retirez les vis qui le maintiennent en place et décollez délicatement la colle blanche qui entoure le connecteur. Il est important de procéder avec délicatesse pour éviter d’endommager les fils ou les connecteurs.

![image](assets/hardware/4.jpeg)

Une fois le ventilateur d’origine retiré, vous remarquerez que les connecteurs du nouveau ventilateur Noctua ne correspondent pas à ceux du ventilateur d’origine. En effet, le nouveau ventilateur dispose de 3 fils, dont un fil jaune qui permet de contrôler la vitesse. Cependant, ce fil ne sera pas utilisé dans ce cas précis. Pour brancher le nouveau ventilateur, il est donc recommandé d’utiliser un adaptateur spécial. Il est cependant important de noter que cet adaptateur peut parfois être difficile à trouver.

![image](assets/hardware/5.jpeg)

Si vous ne disposez pas de cet adaptateur, vous pouvez tout de même procéder au branchement du nouveau ventilateur en utilisant un sucre d’électricien. Pour cela, vous devrez couper les câbles de l’ancien et du nouveau ventilateur.

![image](assets/hardware/6.jpeg)
![image](assets/hardware/7.jpeg)

Sur le nouveau ventilateur, utilisez un cutter et coupez délicatement les contours de la gaine principale à 1cm sans coupez les gaines des câbles en dessous.

![image](assets/hardware/8.jpeg)

Puis en tirant la gaine principale vers le bas, coupez les gaines des câble rouge et noir de la même manière que précédemment. Et coupez le câble jaune à ras.

![image](assets/hardware/9.jpeg)

Sur l’ancien ventilateur il est plus délicat de découper la gaine principale sans abîmer les gaines des files rouge et noir. Pour cela, nous avons utilisé une aiguille que nous avons glissé entre la gaine principale et les fils rouges et noirs.

![image](assets/hardware/10.jpeg)
![image](assets/hardware/11.jpeg)

Une fois les fils rouges et noirs dégagés, coupez les gaines toujours délicatement pour ne pas abîmer les fils électriques.

![image](assets/hardware/12.jpeg)

Puis relier les câbles avec un sucre, le fil noir avec le noir et le fil rouge avec le rouge. Vous pouvez également rajouter du scotch d’électricien.

![image](assets/hardware/13.jpeg)
![image](assets/hardware/14.jpeg)

Une fois le branchement effectué, il est temps de mettre en place le nouveau ventilateur Noctua avec la grille et les anciennes vis, les nouvelles vis qui sont dans la boîte seront réutilisé plus tard. Assurez-vous de le placer avec la bonne orientation. Vous remarquerez une flèche sur l’un des côtés du ventilateur, qui indique le sens du flux d’air. Il est important de placer le ventilateur de manière à ce que cette flèche pointe vers l’intérieur du boîtier. Puis rebranchez le ventilateur.

![image](assets/hardware/15.jpeg)
![image](assets/hardware/16.jpeg)

> Optionnel : Si vous êtes compétent en électricité, vous pouvez ajouter directement sur la sortie d’alimentation 12V un connecteur jack 5,5 mm femelle qui permettra d’alimenter directement le bridge Wi-Fi Vonet. Cependant, si vous n’êtes pas sûr de vos compétences en électricité, il est préférable d’utiliser le connecteur USB avec un chargeur de type smartphone pour éviter tout risque de court-circuit ou de dommage électrique.

![image](assets/hardware/17.jpeg)

Une fois les branchements effectués, remettez bien le plastique du couvercle par-dessus le plastique du boîtier et pas à l’intérieur.

![image](assets/hardware/18.jpeg)

Enfin, remettez le couvercle du boîtier en place puis revissez les 6 vis sur les côtés pour maintenir le tout bien en place. Et voilà, votre boîtier d’alimentation est désormais équipé d’un nouveau ventilateur

### Remplacement des 2 ventilateurs principaux

1. Tout d’abord, débranchez les ventilateurs et dévissez-les.

![image](assets/hardware/19.jpeg)

2. Les connecteurs des nouveaux ventilateurs Noctua ne correspondent pas à ceux d’origine, mais pas de panique ! Sortez votre cutter et coupez délicatement les petites languettes en plastique pour que les connecteurs s’adaptent parfaitement à votre mineur.

![image](assets/hardware/20.jpeg)
![image](assets/hardware/21.jpeg)

3. C’est l’heure de l’installation des pièces 3D !

Fixez-les des deux côtés du mineur à l’aide des vis que vous avez retirées des ventilateurs. Vissez jusqu’à ce que la tête de vis sous rentrer dans la pièce 3D et que celle-ci soit bien maintenu en place. Attention à ne pas trop serrer, vous pourriez déformer la pièce et une des vis risque de toucher un condensateur ! Puis coupez délicatement les petites languettes en plastique pour que les connecteurs s’adaptent parfaitement à votre mineur.

![image](assets/hardware/22.jpeg)

4. Passons maintenant aux ventilateurs.

Fixez-les sur les pièces 3D à l’aide des vis fournies la boîte. Attention au sens de circulation de l’air, les flèches sur les côtés des ventilateurs vous indiqueront la direction à suivre. Allez du côté du port Ethernet à l’autre côté. Voir photo ci-dessous

![image](assets/hardware/23.jpeg)
![image](assets/hardware/24.jpeg)
![image](assets/hardware/25.jpeg)

5. Dernière étape : branchez les ventilateurs et fixez les grilles par-dessus avec les vis qui n’ont pas été utilisées dans la boîte du ventilateur de l’alimentation. Vous en avez seulement 4 mais 2 par grille dans des angles opposés suffiront. Vous pouvez également chercher d’autres vis similaires dans un magasin de bricolage si besoin.

![image](assets/hardware/26.jpeg)
![image](assets/hardware/27.jpeg)

En attendant de pouvoir offrir un casing plus sexy à votre nouveau chauffage, vous pouvez attacher le boîtier et l’alimentation ensemble avec des colliers de serrage d’électricien.

![image](assets/hardware/28.jpeg)

Et pour la touche finale, branchez le bridge Vonet sur le port Ethernet à son alimentation. Si ce n’est pas encore fait, vous pouvez suivre ce tutoriel pour paramétrer votre bridge.

![image](assets/hardware/29.jpeg)

Et voilà, bravo ! Vous venez de remplacer l’ensemble de la partie mécanique de votre mineur. Vous devriez maintenant entendre beaucoup moins de bruit.

## EP 6 Configuration d’une pool

![Rejoindre une pool de minage avec un Antminer S9](https://youtu.be/wM-dRog6mls?si=5GIFBgeqncePasZj)

On peut imaginer une pool de minage comme une coopérative agricole. Les agriculteurs mettent en commun leur production pour réduire la variance de l’offre et de la demande et ainsi obtenir des revenus plus stables pour leur exploitation. Une pool de minage fonctionne de la même manière et la matière première mise en commun sont des hash. En effet, la découverte d’un seul hash valide permet la création d’un bloc et ainsi de remporter la coinbase ou la récompense aujourd’hui de 6,25 BTC plus les frais des transactions inclus dans le bloc. Si vous minez seul, vous ne serez récompensé que lorsque vous trouverez un bloc. Étant en compétition contre tous les autres mineurs de la planète, vous auriez donc très peu de chances de remporter ce grand loto et vous devriez malgré tout payer les frais associés à l’utilisation de votre mineur sans aucune garantie de réussite. Les pools de minage viennent répondre à cette problématique en mutualisant la puissance de calcul de plusieurs (milliers) de mineurs et en partageant la récompense de ces derniers en fonction du pourcentage de participation au hashrate de la pool lorsqu’un bloc a été trouvé. Pour visualiser vos chance de miner un block de miner un block seul vous pouvez utiliser cet outil. En rentrant les informations d’un Antminer S9 on voit que les chances de trouver un hash permettant la création d’un block sont de 1/24 777 849 chaque bloc ou de 1/ 172 068 par jour. Il faudrait en moyenne (avec un hashrate et une difficulté constante) 471 ans pour trouver un bloc.

Malgré tout, comme dans Bitcoin tout est probabilité, il arrive parfois que des “solo miner” soit récompensés pour cette prise de risque : Solo Bitcoin Miner Solves Block With Hash Rate of Just 10 TH/s, Beating Extremely Unlikely Odds – Decrypt

Si vous aimez jouer, vous pouvez essayer, mais notre guide ne s’orientera pas dans cette direction. Au lieu de cela, nous allons nous concentrer sur la pool de minage qui convient le mieux à nos besoins pour créer un système de chauffage.

Les considérations à avoir en choisissant une pool de minage sont le fonctionnement des récompenses de la pool, qui peuvent être différentes, ainsi que le montant minimum avant de pouvoir retirer les récompenses sur une adresse. Par exemple, Braiins, qui propose le logiciel dont nous parlons ici, propose également une pool. Cette pool a un système de récompense appelé “Score” qui encourage les mineurs à miner pendant de longues périodes. La participation inclut un facteur de temps d’activité qui est exprimé avec un “scoring hashrate”. Dans notre cas, où nous souhaitons un système de chauffage qui peut être allumé pendant quelques minutes seulement, ce n’est pas le système de récompense idéal. Nous préférons plutôt un système de récompense qui nous donne une récompense égale pour chaque participation. De plus, le montant minimum de retrait pour Braiins Pool est de 100 000 sats et On-Chain. Nous perdons donc quelques sats en frais de transaction et une partie de notre récompense peut être bloquée si nous ne minons pas suffisamment pendant l’hiver.

Le modèle de récompense qui nous intéresse est le PPS, qui signifie « pay-per-share ». Cela signifie que le mineur recevra une récompense pour chaque partage valide. Il existe également une variante de ce système, le FPPS (Full Pay Per Share), qui divise non seulement la récompense de la coinbase, mais aussi les frais de transaction inclus dans le bloc. Les pools de minage que nous vous recommandons pour connecter votre minage/chauffage sont Linecoin Pool (FPPS) et Nicehash (PPS).

- Nicehash : L’avantage de Nicehash est que le retrait peut être effectué en utilisant Lightning avec des frais minimes. De plus, le montant minimum de retrait est de 2000 sats. L’inconvénient est que Nicehash utilise son hashrate pour la blockchain la plus rentable, sans donner vraiment le contrôle à l’utilisateur et elle ne participe donc pas forcément au hashrate de Bitcoin.

- Lincoin : L’avantage de Linecoin est le nombre de fonctionnalités proposées, telles qu’un tableau de bord détaillé, la possibilité de faire des retraits avec un Paynym (BIP 47) pour une meilleure protection de la vie privée, et l’intégration d’un bot Telegram ainsi que des automatisations directement configurables dans l’application mobile. Cette pool ne mine que des blocs Bitcoin mais le montant minimum pour retirer reste élevé à 100 000 sats. Nous examinerons plus en détail l’interface d’une de ces pools dans un prochain article.

Pour configurer une pool dans Braiins 0S+, il faudra créer un compte dans l’une des pool de votre choix. Ici nous allons prendre l’exemple de Lincoin :

![image](assets/software/19.jpeg)

Une fois votre compte créé, cliquez sur Connect To Pool

Ensuite copiez l’adresse Stratum ainsi que votre username :

![image](assets/software/20.jpeg)

Vous pouvez à présent retourner dans l’interface de Braiins OS+ afin de rentrer ces identifiant. Pour le mot de passe, vous pouvez laisser le champ vide.

![image](assets/software/21.jpeg)

## EP 7- Overclocking et Underclocking

![Optimiser les performances de son Antminer S9 avec l'auto-tunning](https://youtu.be/yh8U9Ay1i-E?si=JXC7dr2eRsTbWDKi)

L’overclocking et l’autotuning consiste tous les deux à ajuster les fréquences sur les cartes de hachage pour améliorer les performances de l’ASIC. La différence entre les deux réside dans la complexité de ces réglages de fréquence.

L**overclocking** est un ajustement simple qui consiste à augmenter la fréquence sur les cartes de hachage pour augmenter le taux de hachage de la machine. L’underclocking, quant à lui, consiste à diminuer la fréquence d’horloge d’un circuit intégré en dessous de sa fréquence nominale En réduisant la fréquence d’horloge d’un ASIC par l’underclocking, on réduit également la chaleur générée par le matériel. Cela permet de diminuer la vitesse des ventilateurs nécessaires pour refroidir l’ASIC, car ils n’ont pas à travailler aussi dur pour maintenir une température appropriée. En réduisant la vitesse des ventilateurs, le bruit généré par l’ASIC est également réduit. Cela peut être particulièrement utile pour les utilisateurs qui utilisent des ASIC à la maison et qui cherchent à minimiser les perturbations sonores causées par le matériel de minage.

Il est important de noter que l’underclocking peut entraîner une réduction des performances de l’ASIC, il est donc important de trouver un bon équilibre entre les performances et le bruit.

Braiins OS+ prend en charge l’overclocking, l’underclocking des ASICs et l’autotuning. Il permet aux utilisateurs de régler la fréquence d’horloge de leur matériel de manière flexible pour maximiser les performances ou économiser de l’énergie selon leurs préférences.

### Optimiser les performances de son Antminer S9 avec l'auto-tunning

Avant 2018, les mineurs avaient deux moyens de gagner un avantage dans leur activité : trouver de l’électricité à un coût raisonnable et acheter du matériel plus efficace. Cependant, en 2018, une nouvelle avancée a été découverte dans le domaine des logiciels et des micrologiciels miniers, appelée AsicBoost. Cette technique permet aux mineurs de réduire leurs coûts d’environ 13% en modifiant le micrologiciel exécuté sur leurs appareils.

Aujourd’hui, il existe une nouvelle avancée dans le secteur des logiciels et des micrologiciels miniers appelée autoréglage (ou autotuning) qui offre un avantage encore plus important qu’AsicBoost. Les ASIC sont composées de nombreuses petites puces informatiques qui effectuent le hachage. Ces puces sont faites de silicium, le même élément largement utilisé dans les semi-conducteurs et autres composants microélectroniques. La compréhension clé ici est que toutes les puces de silicium ne sont pas identiques – chacune peut varier légèrement dans ses propriétés électriques. Les fabricants de matériel le savent et publient les spécifications de performances de leurs machines minières en fonction de la limite inférieure de leurs tolérances. En d’autres termes, les fabricants connaissent la fréquence qui fonctionne le mieux pour les puces moyennes et ils utilisent cette fréquence de manière uniforme pour toutes les puces de la machine.

Cela met une limite supérieure au taux de hachage qu’une machine peut avoir. L’autoréglage est un processus dans lequel des algorithmes évaluent les fréquences optimales pour le hachage puce par puce, au lieu de traiter l’ensemble de la machine comme une seule unité. Cela signifie qu’une puce de meilleure qualité qui peut effectuer plus de hachages par seconde obtiendra une fréquence plus élevée, et une puce de qualité inférieure qui peut effectuer relativement moins obtiendra une fréquence plus faible. Le réglage automatique par puce est essentiellement un moyen d’optimiser les performances d’un ASIC via le logiciel et le micrologiciel qui y sont exécutés.

Le résultat final est un taux de hachage plus élevé par watt d’électricité, ce qui signifie des marges bénéficiaires plus importantes pour les mineurs. La raison pour laquelle les machines ne sont pas distribuées avec ce type de logiciel est que la variance par machine n’est pas souhaitable, car les clients veulent savoir exactement ce qu’ils obtiennent et il est donc une mauvaise idée pour les fabricants de vendre un produit qui n’a pas des performances constantes et prévisibles d’une machine à l’autre. En outre, le réglage automatique par puce nécessite des ressources de développement considérables, car il est complexe à mettre en place. Les fabricants dépensent déjà beaucoup de ressources pour développer leurs propres firmwares. Il existe des solutions logicielles qui permettent de mettre en place l’autotuning, comme Braiins OS+. En plus d’améliorer les performances de l’ASIC jusqu’à 20%.

# Conclusion

## Comment allez plus loins dans le minage

### Bonus sur le NerdMiner! 

A faire 

### Interveiw sur le sujet 

A faire 

### Allez plus loin

A faire