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

<<<<<<< HEAD
=======

>>>>>>> 4a85d5a90f1c6cd98b6b5ad0700a29f3bd3567f7
------------------------------------------------------------------------

## 🌞 Faire une requête DNS à la main PS C:\Users\fabdj> nslookup www.thinkerview.com Serveur : bbox.lan Address: 192.168.1.254

<<<<<<< HEAD
Réponse ne faisant pas autorité : Nom : www.thinkerview.com Addresses: 2a06:98c1:3121::2 2a06:98c1:3120::2 188.114.96.2 188.114.97.2

PS C:\Users\fabdj> nslookup www.wikileaks.org Serveur : bbox.lan Address: 192.168.1.254
=======
nslookup www.thinkerview.com Serveur : bbox.lan Address: 192.168.1.254

Réponse ne faisant pas autorité : Nom : www.thinkerview.com Addresses: 2a06:98c1:3121::2 2a06:98c1:3120::2 188.114.96.2 188.114.97.2

PS C:\Users\fabdj> nslookup www.wikileaks.org Serveur : bbox.lan Address: 192.168.1.254

Réponse ne faisant pas autorité : Nom : wikileaks.org Addresses: 51.159.197.136 80.81.248.21 Aliases: www.wikileaks.org

PS C:\Users\fabdj> nslookup www.torproject.org Serveur : bbox.lan Address: 192.168.1.254

Réponse ne faisant pas autorité : Nom : www.torproject.org Addresses: 2a01:4f9:c010:19eb::1 2620:7:6002:0:466:39ff:fe32:e3dd 2a01:4f8:fff0:4f:266:37ff:fe2c:5d19 2620:7:6002:0:466:39ff:fe7f:1826 2a01:4f8:fff0:4f:266:37ff:feae:3bbc 116.202.120.166 116.202.120.165 204.8.99.146 204.8.99.144 95.216.163.36
## 🌞 Effectue un scan du réseau auquel tu es connecté
nmap.xml
##  🌞 Changer d'adresse IP : 

Carte réseau sans fil Wi-Fi :

   Suffixe DNS propre à la connexion. . . : lan
   Adresse IPv4. . . . . . . . . . . . . .: 192.168.1.28
   Masque de sous-réseau. . . . . . . . . : 255.255.255.0
   Passerelle par défaut. . . . . . . . . : 192.168.1.254

Carte réseau sans fil Wi-Fi :

   Suffixe DNS propre à la connexion. . . :
   Adresse IPv4. . . . . . . . . . . . . .: 192.168.1.50
   Masque de sous-réseau. . . . . . . . . : 255.255.255.0
   Passerelle par défaut. . . . . . . . . : 192.168.1.254
>>>>>>> 4a85d5a90f1c6cd98b6b5ad0700a29f3bd3567f7

Réponse ne faisant pas autorité : Nom : wikileaks.org Addresses: 51.159.197.136 80.81.248.21 Aliases: www.wikileaks.org

PS C:\Users\fabdj> nslookup www.torproject.org Serveur : bbox.lan Address: 192.168.1.254

Réponse ne faisant pas autorité : Nom : www.torproject.org Addresses: 2a01:4f9:c010:19eb::1 2620:7:6002:0:466:39ff:fe32:e3dd 2a01:4f8:fff0:4f:266:37ff:fe2c:5d19 2620:7:6002:0:466:39ff:fe7f:1826 2a01:4f8:fff0:4f:266:37ff:feae:3bbc 116.202.120.166 116.202.120.165 204.8.99.146 204.8.99.144 95.216.163.36
## 🌞 Effectue un scan du réseau auquel tu es connecté
nmap.xml

##  🌞 Changer d'adresse IP : 

Carte réseau sans fil Wi-Fi :

   Suffixe DNS propre à la connexion. . . : lan
   Adresse IPv4. . . . . . . . . . . . . .: 192.168.1.28
   Masque de sous-réseau. . . . . . . . . : 255.255.255.0
   Passerelle par défaut. . . . . . . . . : 192.168.1.254

Carte réseau sans fil Wi-Fi :

   Suffixe DNS propre à la connexion. . . :
   Adresse IPv4. . . . . . . . . . . . . .: 192.168.1.50
   Masque de sous-réseau. . . . . . . . . : 255.255.255.0
   Passerelle par défaut. . . . . . . . . : 192.168.1.254

   .