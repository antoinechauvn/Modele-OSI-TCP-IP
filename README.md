## Modèle OSI

![image](https://user-images.githubusercontent.com/83721477/193522620-c422aba3-ba33-4cc9-b552-8ad78e2c820c.png)

## Modèle TCP/IP
On dit deux machines sont en liaison point-à-point
quand elles sont directement reliées par une ligne de transmission,
sans l'intermédiaire d'autres machines.

Les logiciels de même niveau OSI des deux machines DIALOGUENT
en se passant des CODES convenus conformes à un certain PROTOCOLE
par l'intermédiaire des EN-TÊTES.

### Encapsulation
![image](https://user-images.githubusercontent.com/83721477/193523187-d003504a-69eb-4c0b-83b5-8e33b2851621.png)

### PCI
PCI = ensemble de l'EN-TÊTE (et, s'il y en a un, du champ CONTROLE)

![image](https://user-images.githubusercontent.com/83721477/193535006-78264998-bae9-4635-9633-e651d6cdf704.png)


### PDU (Modèle OSI)

![image](https://user-images.githubusercontent.com/83721477/193533149-d7fbf0ad-a9c2-4929-99ea-8fa75e90b5d7.png)

PDU = unité de transmission de chaque niveau. <br>

Appliqué au système de couches du modèle OSI, le PDU :

* de la couche physique est le bit ;
* de la couche liaison est la trame ;
* de la couche réseau est le paquet ;
* de la couche transport est le segment pour TCP, et le datagramme pour UDP ;
* des couches application, présentation et session sont les données.

![image](https://user-images.githubusercontent.com/83721477/193523637-556dd7b7-8bb3-4ac0-8129-af8d9c423c2a.png)

**Attention !**<br>
Parmi les PDU échangées sur le réseau,<br>
certaines ne transportent pas les "données" de la couche supérieure,<br>
mais des paramètres, des demandes, des réponses ou des acquittements lors d'un dialogue entre couches;<br>
N'assimilons donc pas tout-à-fait PDU et DONNÉES.<br>
PDU est un concept plus général.<br>

#### Traitement d'un PDU lors d'une transmission

![image](https://user-images.githubusercontent.com/83721477/193533984-9464d498-118c-49e8-926e-8c2967a68b32.png)

#### Traitement d'un PDU lors d'une réception

![image](https://user-images.githubusercontent.com/83721477/193534025-f3a90cd0-75b1-468d-a3a9-f8878225e911.png)
