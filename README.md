# SWI23-Labo1-MAC-Sec

## Partie 1 - beacons, authenfication

### 1 Deauthentication attack

aireplay-ng -0 1 -a 38:35:fb:40:04:94 -c a6:11:51:62:fd:5a wlan0mon

a) Utiliser la fonction de déauthentification de la suite aircrack, capturer les échanges et identifier le Reason code et son interpretation.

**Question :** quel code est utilisé par aircrack pour déauthentifier un client 802.11. Quelle est son interpretation ?

**Question :** A l'aide d'un filtre d'affichage, essayer de trouver d'autres trames de déauthentification dans votre capture. Avez-vous en trouvé d'autres ? Si oui, quel code contient-elle et quelle est son interpretation ?
