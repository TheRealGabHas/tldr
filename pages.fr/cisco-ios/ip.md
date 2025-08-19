# ip

> Gère les configurations IP.
> Accessible en mode de configuration.
> Plus d'informations : <https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/ipaddr/command/ipaddr-cr-book.html>.

- Définir la version de SSH :

`ip ssh version {{2}}`

- Définir l'adresse de l'appareil (Effectué sous la commande `ìnterface`) :

`ip address {{10.0.0.1}} {{255.255.255.0}}`

- Définir que l'adresse est déterminée avec DHCP (Effectué sous la commande `ìnterface`) :

`ip address dhcp`

- Définir un nom de domaine :

`ip domain-name {{example.com}}`
