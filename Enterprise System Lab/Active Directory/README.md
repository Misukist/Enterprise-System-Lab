# ACTIVE DIRECTORY

<br>

## Esittely

Haluan aloittaa Enterprise Systems Lab -projektini nimenomaan Active Directoryn parissa, sillä se on yksi yritysympäristöjen keskeisimmistä identiteetin- ja käyttäjähallintajärjestelmistä. Active Directory on edelleen laajasti käytössä organisaatioissa, joten sen käytännön osaaminen on tärkeä taito järjestelmäasiantuntijan, IT-tuen ja infrastruktuuritehtävien näkökulmasta.

Projektissa tulen tekemään alusta alkaen toimivan Windows Server -ympäristön, johon toteutan Active Directory Domain Services -palvelun sekä siihen liittyvät keskeiset palvelut, kuten DNS:n, DHCP:n, käyttäjä- ja ryhmähallinnan, Group Policy -käytännöt, tiedostojen jaot sekä Windows-asiakaskoneen liittämisen toimialueeseen. ja dokumentoin koko projektin virheitä myöten tähän.

Dokumentoin projektin vaihe vaiheelta GitHubiin, mukaan lukien arkkitehtuurin, käyttöönoton, kohtaamani haasteet sekä niiden ratkaisut. Tavoitteena on oppia käytännön järjestelmähallintaa ja rakentaa samalla portfolio, joka kuvastaa osaamistani yritysympäristöjen ylläpidossa.

<br>

## Virtuaaliympäristön käyttöönotto

Tässä osiossa valmistelen Active Directory -labraa varten tarvittavan virtuaaliympäristön. Käyn läpi VMware Workstation Pron asennuksen, Windows Server -asennusmedian lataamisen, virtuaalikoneen luonnin sekä käyttöjärjestelmän asennuksen.

<br>

### VMwaren Workstationin asennus

Ensimmäiseksi haasteekseni tuli selvittää mikä VMware Workstation versio olisi minulle sopiva ja onko erot huomattavia esimerkiksi yrityskäytössä. Päädyin valitsemaan uusimman VMware Workstation Pro 26H1-version, sillä se tarjoaa tuen uusimmille käyttöjärjestelmille ja sisältää useita suorituskykyyn sekä käytettävyyteen liittyviä parannuksia. Lisäksi versio on maksutta käytettävissä myös henkilökohtaiseen ja kaupalliseen käyttöön, joten se soveltuu erinomaisesti tämän laboratorion virtualisointialustaksi.

Itse asennus onnistui exe:n kautta kivuttomasti ilman ongelmia.

![VMware Workstation Pro 26H1](images/vmware_version.png)

<br>

### Windows Server ISO lataus

Seuraavaksi latasin Windows Server 2022 Evaluation -ISO-tiedoston Microsoftin virallisilta sivuilta. Evaluation-versio soveltuu erinomaisesti laboratorioympäristöön, sillä se tarjoaa kaikki tarvittavat ominaisuudet Active Directoryn ja muiden palveluiden käyttöönottoon ilman erillistä lisenssiä.

<br>

### Virtuaalikoneen luonti

<br>

### Windows Serverin asennus

<br>
