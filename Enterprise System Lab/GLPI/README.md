# GLPI

<br>

## Esittely

Projektin tavoitteena on rakentaa labraympäristöön GLPI-pohjainen IT-palvelunhallintajärjestelmä. GLPI asennetaan Ubuntu Server -virtuaalikoneelle, jonka yhteydessä käytetään MariaDB-tietokantaa.

Järjestelmään liitetään Windows-virtuaalikone GLPI Agentin avulla, jolloin sen laitteisto- ja ohjelmistotiedot voidaan kerätä automaattisesti GLPI. Projektissa harjoitellaan myös käyttäjien, laitteiden ja IT-tikettien hallintaa.

Projektin lopputuloksena on toimiva helpdesk-ympäristö, jossa käyttäjä voi tehdä tukipyynnön ja IT-ylläpitäjä voi käsitellä, seurata ja ratkaista tikettejä GLPI kautta.

**Osio 0: Projektin perusta**  
Ensimmäisessä osiossa rakensin 2 virtuaalikonetta. Toisen GLPI serveriksi (Ubuntu) ja toisen käyttäjäkis GLPI serverille (Windows 11). Molemmat virtuaalikoneet asennettiin ja ajettiin vm workstation ympäristössä.

**Osio 1: GLPI asennus Ubuntulle**  
Toisessa osioissa asensin GLPIä varten tarvittavat komponentit ja määrittelin ne projektin tarpeiden mukaisesti. Asennukseen kuuluivat muun muassa Ubuntu Server, Apache, PHP ja MariaDB sekä GLPI tarvitsemat asetukset ja tiedostorakenteet.
