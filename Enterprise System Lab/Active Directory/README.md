# ACTIVE DIRECTORY

<br>

## Esittely

Halusin aloittaa Enterprise Systems Lab -projektini nimenomaan Active Directoryn parissa, sillä se on yksi yritysympäristöjen keskeisimmistä identiteetin- ja käyttäjähallintajärjestelmistä. Active Directory on edelleen laajasti käytössä organisaatioissa, joten sen käytännön osaaminen on tärkeä taito järjestelmäasiantuntijan, IT-tuen ja infrastruktuuritehtävien näkökulmasta.

Projektissa tein alusta alkaen toimivan Windows Server -ympäristön, johon toteutin Active Directory Domain Services -palvelun sekä siihen liittyvät keskeiset palvelut, kuten DNS:n, DHCP:n, käyttäjä- ja ryhmähallinnan, Group Policy -käytännöt, tiedostojen jaot sekä Windows-asiakaskoneen liittämisen toimialueeseen. ja dokumentoin koko projektin virheitä myöten tähän.

Dokumentoin projektin vaihe vaiheelta GitHubiin, mukaan lukien arkkitehtuurin, käyttöönoton, kohtaamani haasteet sekä niiden ratkaisut. Tavoitteena on oppia käytännön järjestelmähallintaa ja rakentaa samalla portfolio, joka kuvastaa osaamistani yritysympäristöjen ylläpidossa.

Jaoin projektin moneen alakategoriaan sen helppolukuisuuden ja selkeämmän rakenteen vuoksi.

**Osio 1: Projektin perusta**  
Ensimmäisessä osiossa rakensin Active Directory -ympäristön pohjan. Tähän kuului virtuaaliympäristön luominen, Windows Serverin asennus, Active Directoryn käyttöönotto, toimialueen määrittäminen sekä ensimmäisen OU-rakenteen luominen. Loin myös ensimmäiset testikäyttäjät ja ryhmät tulevia osia varten.

**Osio 2: Ryhmäkäytäntöjen määrittäminen**  
Toisessa osiossa keskityin Active Directoryn ryhmäkäytäntöjen (GPO) luomiseen ja toimintaan. Tässä vaiheessa keskityin vain ryhmäkäytäntöjen toimintaan, jotka sitten myöhemmässä osassa otin käyttöön.

**Osio 3: Käyttäjähallinta**
Kolmannessa osassa otin käyttöön ryhmäkäytännöt luomilleni käyttäjille. Loin myös lisää käyttäjiä ja tutustuin siihen, miten eri OU määritellään eri ryhmäkäytäntöjä.

**Osio 4: Tiedostojen jakaminen**
Neljännessä osassa tutustuin tiedostojen jakamiseen ja näkymiseen eri käyttäjäryhmien välillä. Osiossa tutustuin paikalliseen ja verkon väliseen jakamiseen ja niiden eroavaisuuksiin.

**Osio 5: Tietoturvakäytäntöjen toteuttaminen**
Viidennessä osassa opettelin hyviä tietoturvakäytäntöjä, mitä tulee käyttäjähallintaan. Määrittelin muun muassa käytäntöjä salasanoille, kirjautumisille ja etäyhteyksille.

**Osio 6: Palvelutili**
Kuudennessa ja viimeisessä osiossa harjoittelin Service Accountin luomista serverille. Konfiguroin sille yksinkertaisen GPO ja automatisoin sen kirjautumisen.

<br>

Lähteet:
EastCharmer: https://www.youtube.com/watch?v=GsmJowwIh8Q&list=PLAdEnQWAAbfXMY2D4HVZOe-ChfTKmaJfQ
Microsoft Learn: https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview?utm_source=chatgpt.com
