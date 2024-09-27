##  TP1 : Les premiers pas de bébé B1 ##

# 🌞 Adresses IP de ta machine : 

PS C:\Users\fabdj> ipconfig

Carte réseau sans fil Wi-Fi :
   Adresse IPv4. . . . . . . . . . . . . .: 10.33.77.147(préféré)
Carte Ethernet Ethernet 10 :
Adresse IPv4. . . . . . . . . . . . . .: 192.168.56.1(préféré)

# 🌞 Si t'as un accès internet normal, d'autres infos sont forcément dispos... :

PS C:\Users\fabdj> ipconfig /all
 Passerelle par défaut. . . . . . . . . : 10.33.79.254
 Serveurs DNS. . .  . . . . . . . . . . : 8.8.8.8
 Serveur DHCP . . . . . . . . . . . . . : 10.33.79.254

# 🌞 Envoie un ping vers... :

PS C:\Users\fabdj> ping 10.33.79.254

Envoi d’une requête 'Ping'  10.33.79.254 avec 32 octets de données :
Délai d’attente de la demande dépassé.
Délai d’attente de la demande dépassé.
Délai d’attente de la demande dépassé.
Délai d’attente de la demande dépassé.

Statistiques Ping pour 10.33.79.254:
    Paquets : envoyés = 4, reçus = 0, perdus = 4 (perte 100%),

------------------------------------------------------------------
PS C:\Users\fabdj> ping 127.0.0.1

Envoi d’une requête 'Ping'  127.0.0.1 avec 32 octets de données :
Réponse de 127.0.0.1 : octets=32 temps<1ms TTL=128
Réponse de 127.0.0.1 : octets=32 temps<1ms TTL=128
Réponse de 127.0.0.1 : octets=32 temps<1ms TTL=128
Réponse de 127.0.0.1 : octets=32 temps<1ms TTL=128

Statistiques Ping pour 127.0.0.1:
    Paquets : envoyés = 4, reçus = 4, perdus = 0 (perte 0%),
Durée approximative des boucles en millisecondes :
    Minimum = 0ms, Maximum = 0ms, Moyenne = 0ms
 
## 🌞 On continue avec ping. Envoie un ping vers... : 

PS C:\Users\fabdj> ping 10.33.77.147

Envoi d’une requête 'Ping'  10.33.77.147 avec 32 octets de données :
Réponse de 10.33.77.147 : octets=32 temps<1ms TTL=128
Réponse de 10.33.77.147 : octets=32 temps<1ms TTL=128
Réponse de 10.33.77.147 : octets=32 temps<1ms TTL=128
Réponse de 10.33.77.147 : octets=32 temps<1ms TTL=128

Statistiques Ping pour 10.33.77.147:
    Paquets : envoyés = 4, reçus = 4, perdus = 0 (perte 0%),
Durée approximative des boucles en millisecondes :
    Minimum = 0ms, Maximum = 0ms, Moyenne = 0ms

-------------------------------------------------------------------
PS C:\Users\fabdj> ping 10.33.77.179

Envoi d’une requête 'Ping'  10.33.77.179 avec 32 octets de données :
Réponse de 10.33.77.179 : octets=32 temps=12 ms TTL=128
Réponse de 10.33.77.179 : octets=32 temps=32 ms TTL=128
Réponse de 10.33.77.179 : octets=32 temps=18 ms TTL=128
Réponse de 10.33.77.179 : octets=32 temps=9 ms TTL=128

Statistiques ping pour 10.33.77.179:
    Paquets : envoyés = 4, reçus = 4, perdus = 0 (perte 0%),
Durée approximative des boucles en millisecondes :
    Minimum = 9ms, Maximum = 32ms, Moyenne = 17ms

--------------------------------------------------------------------
PS C:\Users\fabdj> ping google.com

Envoi d’une requête 'ping' sur google.com [142.250.178.142] avec 32 octets de données :
Réponse de 142.250.178.142 : octets=32 temps=15 ms TTL=117
Réponse de 142.250.178.142 : octets=32 temps=16 ms TTL=117
Réponse de 142.250.178.142 : octets=32 temps=16 ms TTL=117
Réponse de 142.250.178.142 : octets=32 temps=16 ms TTL=117

Statistiques Ping pour 142.250.178.142:
    Paquets : envoyés = 4, reçus = 4, perdus = 0 (perte 0%),
Durée approximative des boucles en millisecondes :
    Minimum = 15ms, Maximum = 16ms, Moyenne = 15ms

-----------------------------------------------------------------------
PS C:\Users\fabdj> ping google.com

Envoi d’une requête 'ping' sur google.com [142.250.178.142] avec 32 octets de données :
Réponse de 142.250.178.142 : octets=32 temps=15 ms TTL=117
Réponse de 142.250.178.142 : octets=32 temps=16 ms TTL=117
Réponse de 142.250.178.142 : octets=32 temps=16 ms TTL=117
Réponse de 142.250.178.142 : octets=32 temps=16 ms TTL=117

Statistiques Ping pour 142.250.178.142:
    Paquets : envoyés = 4, reçus = 4, perdus = 0 (perte 0%),
Durée approximative des boucles en millisecondes :
    Minimum = 15ms, Maximum = 16ms, Moyenne = 15ms

------------------------------------------------------------------------

## 🌞 Faire une requête DNS à la main

PS C:\Users\fabdj> nslookup www.google.com
Serveur :   dns.google
Address:  8.8.8.8

Réponse ne faisant pas autorité :
Nom :    www.google.com
Addresses:  2a00:1450:4007:80d::2004
          142.250.75.228
 



