# SYM_LABO_03 Jee Mathieu, Kopp Olivier, Silvestri Romain

## NFC : 

### A partir de l’API Android concernant les tags NFC4, pouvez-vous imaginer une autre approche pour rendre plus compliqué le clonage des tags NFC ? Est-ce possible sur toutes les plateformes (Android et iOS), existe-il des limitations ? Voyez-vous d’autres possibilités ?

## Codes-barres : 

### Comparer la technologie à codes-barres et la technologie NFC, du point de vue d'une utilisation dans des applications pour smartphones, dans une optique :

### • Professionnelle (Authentification, droits d’accès, stockage d’une clé)

### • Grand public (Billetterie, contrôle d’accès, e-paiement)

### • Ludique (Preuves d'achat, publicité, etc.)

### • Financier (Coûts pour le déploiement de la technologie, possibilités de recyclage, etc.)

## Balise iBeacon

### Les iBeacons sont très souvent présentés comme une alternative à NFC. Pouvez-vous commenter cette affirmation en vous basant sur 2-3 exemples de cas d’utilisations (use-cases) concrets.

Le principal avantage qu'a les iBeacon par rapport aux balises NFC est la portée de diffusion, en effet la portée d'une balise iBeacon peu atteindre une centaine de mètres. 

Voici quelque exemple d'utilisation qui peuvent être intéressante a implémenter avec des balise iBeacon : 

- visite dans un musée : 

  on peut imaginer une application qui réagit en fonction de la distance par rapport a différentes balise placée dans un musée, lorsque l'on se rapproche d'une œuvre, l'application nous montre ces détails.

- file d'attente à un guichet : 

  On pourrais implémenter une application permettant de prendre un ticket lorsque l'on se rapproche d'une file d'attente ( par exemple à la poste ). L'application attendrais que la balise l'a contact avant de proposer à l'utilisateur de prendre un ticket virtuel.

- Offre promotionnel dans un magasin : 

  Lorsque l'utilisateur se trouve dans un magasin, on peut placer des balises iBeacon permettant de diffuser des pub cohérentes en fonction de l'emplacement où il se trouve. Certains magasin l'on d'ailleurs déjà fais comme par exemple en Finlande avec la chaine K-supermarket. 

## Capteur : 

### Une fois la manipulation effectuée, vous constaterez que les animations de la flèche ne sont pas fluides, il va y avoir un tremblement plus ou moins important même si le téléphone ne bouge pas.

### Veuillez expliquer quelle est la cause la plus probable de ce tremblement et donner une manière (sans forcément l’implémenter) d’y remédier.