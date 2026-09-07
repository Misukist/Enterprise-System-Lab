# GLPI

<br>

## Esittely

Projektin tavoitteena on rakentaa labraympäristöön GLPI-pohjainen IT-palvelunhallintajärjestelmä. GLPI asennetaan Ubuntu Server -virtuaalikoneelle, jonka yhteydessä käytetään MariaDB-tietokantaa.

Järjestelmään liitetään Windows-virtuaalikone GLPI Agentin avulla, jolloin sen laitteisto- ja ohjelmistotiedot voidaan kerätä automaattisesti GLPI. Projektissa harjoitellaan myös käyttäjien, laitteiden ja IT-tikettien hallintaa.

Projektin lopputuloksena on toimiva helpdesk-ympäristö, jossa käyttäjä voi tehdä tukipyynnön ja IT-ylläpitäjä voi käsitellä, seurata ja ratkaista tikettejä GLPI kautta.

**Osio 0: Projektin perusta**  
Ensimmäisessä osiossa rakensin 2 virtuaalikonetta. Toisen GLPI serveriksi (Ubuntu) ja toisen käyttäjäkis GLPI serverille (Windows 11). Molemmat virtuaalikoneet asennettiin ja ajettiin vm workstation ympäristössä.
