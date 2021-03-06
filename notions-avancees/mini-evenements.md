# Mini-évènements

Il existe actuellement 15 types des mini-évènements différents dans le bot. Voici quelques informations au sujet des mini-évènements qui vous permettront d'aborder avec une vision plus stratégiques cette fonctionnalité.

### ![:shopping\_cart:](https://discord.com/assets/3f0519f01b411bfdaf3fe311ea34b74c.svg) Mini-shop :

**Taux d'apparition :** 5%

Vous permet d'acheter un item pour pas cher. \(60 % du prix\). Il n'est pas possible d'obtenir des items de rareté supérieure à spécial. Si vous achetez un item mais que vous n'acceptez pas de remplacer votre objet, l'item sera racheté par le vendeur pour un prix réduit à son prix d'achat.

{% hint style="warning" %}
Attention une faible proportion de vendeurs sont des arnaqueurs et tenteront de vous vendre des items pour bien trop cher !
{% endhint %}

![Un exemple de mini-shop](../.gitbook/assets/image%20%2845%29.png)

### ![:service\_dog:](https://discord.com/assets/92f89f0c4724cd564fc307a5dd20e18a.svg)  Interaction avec un familier :

**Taux d'apparition :** 6.25% - Nécessite d'avoir un familier équipé pour apparaître.

Réalise une interaction entre le propriétaire d'un familier et son familier. ce mini-évènement peut être positif ou négatif en fonction de l'affection du familier. Les familiers plus rares permettent d'obtenir de meilleures récompenses.

| Récompense | Nombre d'étoiles du familier | Probabilité |
| :--- | :--- | :--- |
| Argent \(20 à 70\) | 3 | Élevée |
| Nourriture | 1 | Moyenne |
| Item | 5 | Faible |
| Points de vie \(1 à 5\) | 4 | Moyenne |
| Rien ne se passe | 1 | Très élevée |
| Un peu d'affection \(1 à 3\) | 2 | Moyenne |
| Temps \(5 à 20 minutes\) | 3 | Faible |
| Points bonus \(20 à 70\) | 1 | Moyenne |
| Badge | 6 | Très faible |

{% hint style="success" %}
Si un familier est dressé, il compte dans le calcul des récompenses accessibles comme ayant une étoile en plus
{% endhint %}

| Malus | Probabilité |
| :--- | :--- |
| Perte de vie \(1 à 5\) | Moyenne |
| Perte d'argent \(20 à 70\) | Moyenne |
| Perte de temps \(5 à 20 minutes\) | Moyenne |
| Perte d'affection \(1 à 3\) | Moyenne |
| Fuite du familier | Très faible |

![Un exemple d&apos;interaction avec un familier.](../.gitbook/assets/image%20%2844%29.png)

### ![:dog2:](https://discord.com/assets/8b285f94106efc8fbb076980806d4462.svg)  Trouver un familier : 

**Taux d'apparition :** 2.5% 

Le joueur découvre un familier qui le rejoint dans son aventure. Si le joueur a déjà un familier, le nouveau est placé dans le refuge de la guilde du joueur.

{% hint style="danger" %}
Si il n'y a plus de place dans le refuge de la guilde du joueur et que ce dernier possède déjà un familier alors cet évènement ne rapportera pas de nouveau familier.
{% endhint %}

Voilà les probabilités d'obtention pour chaque rareté de familiers :

| 1![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg) | 2![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg) | 3![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg) | 4![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg) | 5![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg) |
| :--- | :--- | :--- | :--- | :--- |
| 87.6% | 9.64% | 1.664% | 0.65% | 0.446% |

![Ne me demandez pas comment elle &#xE9;tait mont&#xE9;e l&#xE0; haut](../.gitbook/assets/image%20%2857%29.png)

### ![:grey\_exclamation:](https://discord.com/assets/4d5be7b6873ad2b627eef85496c92fcd.svg) Trouver un équipement : 

**Taux d'apparition :** 2.5% 

Le joueur découvre un équipement aléatoire. Il n'est pas possible d'obtenir des objets légendaires ou mythiques dans ce mini-évènement.

![Exemple de d&#xE9;couverte d&apos;un &#xE9;quipement](../.gitbook/assets/image%20%2858%29.png)

### ![:walking:](https://discord.com/assets/660f8acc8164369d9d5f2ba84c490670.svg)  Rien ne se passe :

**Taux d'apparition :** 15% 

Ce mini-évent affiche simplement une phrase d'encouragement pour le joueur.

![Un exemple du mini-&#xE9;v&#xE8;nement &quot;Rien ne se passe&quot;](../.gitbook/assets/image%20%2861%29.png)

### ![:confounded:](https://discord.com/assets/e6fe72eb79ef6258554b1385259df5d1.svg)  Petit malheur :

**Taux d'apparition :** 10% 

Parfois, tout ne se passe pas comme prévu. Certains mini-évènements amènent à de petits malus.

| Malus | Effet |
| :--- | :--- |
| Perte de vie |  1 à 5 points de vie perdus |
| Perte d'argent | 10 à 50 d'argent perdus |
| Perte de temps aléatoire | 1 à 24 minutes perdues |

![Un exemple de petit malheur](../.gitbook/assets/image%20%2860%29.png)

### ![:scream:](https://canary.discord.com/assets/81195a9847a459acbb2b680a70357728.svg)   Gros malheur :

**Taux d'apparition :** 1.25% 

Parfois, tout ne se passe pas comme prévu. Certain mini-évènements amènent à de gros malus. Heureusement, cela reste très rare !

| Malus | Effet |
| :--- | :--- |
| Perte de vie |  5 à 30 points de vie perdus |
| Perte d'argent | 50 à 250 d'argent perdus |
| Altération d'état | Le joueur peut être touché par une altération d'état |

![Un exemple de gros malheur](../.gitbook/assets/image%20%2863%29.png)

### ![:speech\_balloon:](https://canary.discord.com/assets/df8b5c1e4abb97e748071aeb28f1ba38.svg)  Interaction avec un joueur sur le même trajet

Il est possible de rencontrer d'autres joueurs sur le même trajet en voyageant. Ce mini-évènement permet de discuter avec un joueur que vous croisez que vous suivez ou que vous précédez ! 

Il existe une multitude de phrases en fonction de la situation de la personne que vous croisez ! 

Voilà la liste des caractéristiques qui peuvent être exploitées :

* Top 10
* Top 50
* Top 100
* Top 1
* Guilde puissante
* Débutant 
* Niveau 50 ou plus
* Inactif
* Même classe que le joueur
* Même guilde
* Membre du staff
* Point du classement de la semaine
* Peu de vie
* Beaucoup de vie
* Mieux classé
* Moins bien classé
* Riche
* Pauvre
* Duplication de potion
* Familier
* Chef de guilde
* Aîné de guilde
* Classe du joueur
* Altération d'état
* Inventaire du joueur

![Un exemple d&apos;interaction avec un autre joueur](../.gitbook/assets/image%20%2862%29.png)

