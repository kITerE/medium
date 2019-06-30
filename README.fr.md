<img align="left" src="https://i.imgur.com/M5T1BL9.png">  
<br/><br/>

FAI décentralisé indépendant pour nos amis

## Je suis un utilisateur
Pour vous connecter au nœud de réseau existant «Medium», vous devez [sélectionner votre ville](https://github.com/medium-isp/medium/tree/master/ru) et rechercher l'opérateur le plus proche de chez vous.

Pour vous connecter, vous devez créer une nouvelle connexion avec les paramètres suivants: SSID - «Moyen» (sans guillemets), type d'authentification - sans mot de passe.

Attention, le réseau "Moyen" par défaut est caché des regards indiscrets; dans la liste des réseaux disponibles, il ne sera pas affiché tant que vous ne créez pas une nouvelle connexion avec les paramètres ci-dessus.

Pour tester le réseau, essayez de visiter la page [medium.i2p](http://medium.i2p) après la connexion.

## je suis un opérateur
Pour élever votre nœud de réseau moyen, vous avez besoin des éléments suivants:
* Accès internet
* Routeur gratuit
* Temps libre et enthousiasme

### Étape 1. Connexion au réseau I2P
Tout d'abord, vous devez vous connecter au réseau I2P. Vous pouvez le faire avec [i2pd](https://github.com/PurpleI2P/i2pd/wiki/Using-i2pd).

### Étape 2. Distribuez la connexion
Une fois la connexion établie, vous devez configurer votre routeur sans fil de sorte que tout le trafic passe par un proxy situé sur le serveur sur lequel le service i2pd a été activé. Il est supposé qu'il est déployé dans le réseau domestique local. Par exemple, 192.168.0.1:4444.

Faites particulièrement attention au fait que, pour l'authenticité, le réseau doit avoir les paramètres suivants: SSID - Moyen, sans mot de passe, le réseau est masqué.

### Étape 3. Bloquer le trafic
En fonction du modèle de votre routeur, refusez tout trafic en relation avec Internet externe.

### Étape 4. Ajout d'un point à la liste publique
Après avoir terminé la configuration de votre point d'accès et testé son fonctionnement, vous pouvez l'ajouter à [liste publique](https://github.com/medium-isp/medium/blob/master/CONTRIBUTING.md).
