# GLPI

<br>

## Esittely

Projektin tavoitteena on rakentaa labraympäristöön GLPI-pohjainen IT-palvelunhallintajärjestelmä. GLPI asennetaan Ubuntu Server -virtuaalikoneelle, jonka yhteydessä käytetään MariaDB-tietokantaa.

Järjestelmään liitetään Windows-virtuaalikone GLPI Agentin avulla, jolloin sen laitteisto- ja ohjelmistotiedot voidaan kerätä automaattisesti GLPI. Projektissa harjoitellaan myös käyttäjien, laitteiden ja IT-tikettien hallintaa.

Projektin lopputuloksena on toimiva helpdesk-ympäristö, jossa käyttäjä voi tehdä tukipyynnön ja IT-ylläpitäjä voi käsitellä, seurata ja ratkaista tikettejä GLPI kautta.

**Osio 0: Projektin perusta**  
Ensimmäisessä osiossa rakensin 2 virtuaalikonetta. Toisen GLPI serveriksi (Ubuntu) ja toisen käyttäjäkis GLPI serverille (Windows 11). Molemmat virtuaalikoneet asennettiin ja ajettiin vm workstation ympäristössä.

**Osio 1: GLPI asennus Ubuntulle**  
Toisessa osiossa asensin GLPIä varten tarvittavat komponentit ja määrittelin ne projektin tarpeiden mukaisesti. Asennukseen kuuluivat muun muassa Ubuntu Server, Apache, PHP ja MariaDB sekä GLPI tarvitsemat asetukset ja tiedostorakenteet.

**Osio 2: GLPI asennus web-selaimelle**  
Tässä osiossa asensin GLPI web-selaimella käytettävään muotoon. Määritin tarvittavat palvelut ja asetukset, jotta GLPIä voidaan käyttää selaimen kautta. Lopuksi viimeistelin GLPI asennuksen ja varmistin, että järjestelmään pystyi kirjautumaan onnistuneesti ja tietoturvallisesti.

**Osio 3: Käytön harjoittelu**
Kolmannessa osiossa harjoittelin käytännössä ohjelman käyttöä ja esimerkin avulla simuloitiin oikeaa IT-tuen tilannetta.

Lähteet:
GLPI:n omat dokumentaatiot ja tutoriaalit:
https://help.glpi-project.org/tutorials
https://www.youtube.com/watch?v=Dc0dy1Z6MyM

<br>

### Mitä opin?

- Ubuntu serverin käyttöä ja käyttöönottoa
- Oman GLPI-palvelimen asentamista ja ylläpitoa
- GLPI käyttöä ja käyttäjähallintaa
- Tikettien luomista, käsittelyä ja ratkaisemista
- SSH-yhteyden muodostamista sisäverkossa

<br>
