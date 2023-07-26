# Wireshark
Installation de Wireshark et analyse de trames ethernet

1. Protocol **ARP - ICMP**/Colonne 5


2. - Adresses IP 10.1.1.1 et 10.1.1.2
 - Adresses MAC 66:68:00 (00:50:79:66:68:00), Dst: Private_66:68:01 (00:50:79:66:68:01)


3. Barre de filtre d'affichage écrire **not arp**


4.  Info de la liste des paquets pour la ligne  (33	0.001031	10.1.1.1	10.1.1.2	ICMP	98	
Echo (ping) request  id=0xb78e, seq=1/256, ttl=64 (reply in 4)


5. Le paquet N°8 est une réponse au paquet N°7 (Echo (ping) reply  
 id=0xb98e, seq=3/768, ttl=64 (request in 7)
