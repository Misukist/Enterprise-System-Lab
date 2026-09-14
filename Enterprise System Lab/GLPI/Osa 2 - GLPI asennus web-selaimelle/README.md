# Osa 2 - GLPI asennus web-serverille

<br>

## Esittely

Nyt halusin GLPI visuaalisen käyttöliittymän, joten otin GLPI käyttöön verkkoselaimen kautta. Näin pystyin käyttämään GLPIä graafisen käyttöliittymän avulla komentorivin sijaan.

**Huom**: En saanut Screenshot sovellusta toimimaan tässä harjoituksessa joten dokumentaatio on suoritettu kokonaan ilman havainnollistavia kuvia.

<br>

### Osoitteen määrittely Windowsiin

Minulla oli pienimuotoisia ongelmia yhdistää Windowsilla GLPI-palvelimeen, joten määrittelin Windowsiin palvelimen osoitteen. Tämän avulla kerroin Windowsille, minkä IP-osoitteen kautta GLPI-palvelin löytyy.

Avasin Muistion järjestelmänvalvojana ja siirryin kansioon C:\Windows\System32\drivers\etc, josta avasin hosts-tiedoston. Tiedostoon lisäsin GLPI-palvelimen IP-osoitteen sekä sille määrittelemäni osoitteen misukisti.misukisti.com.

Tämän määrityksen avulla Windows osaa yhdistää kirjoittamani palvelimen nimen oikeaan IP-osoitteeseen, jolloin GLPI-palvelimeen voidaan muodostaa yhteys selaimen kautta ilman, että IP-osoitetta tarvitsee kirjoittaa suoraan.

<br>

### GLPI asennus selaimeen

Nyt osoitteeni **misukisti.misukisti.com** toimii ja pystyin aloittamaan asennuksen selaimeen. Valitsin kielen ja **asenna**. Näin checklistin joka varmistaa että kaikki vaadittavat asiat oli asennettu oikein serverille. Kaikki näytti hyvältä joten painoin jatka.

Nyt kirjauduin käyttäjällä jonka loin projektiin "**glpi**" ja salasanan jonka annoin **Huom.** muista vaihtaa se pois "root" salasanasta. Koin kuitenkin ongelmia sillä luomaani glpi mariadb tietokantaani ei oltu annettu oikeuksia localhostille. Kirjauduin Ubuntussa mariadb:hen ja ajoin komennot "GRANT ALL PRIVILEGES ON glpi.\* TO 'glpi'@'localhost';" sekä "GRANT SELECT ON mysql.time_zone_name TO 'glpi'@'localhost';" jotta glpi käyttäjällä on oikeus tietokantaan.

GLPI asennuksessa pystyin valitsemaan aikaisemmin luodun glpi-tietokannan. Tämän jälkeen asennusohjelma loi tarvittavat taulut tietokantaan ja GLPI asennus onnistui.

Asennuksen valmistuttua sain käyttöön GLPI valmiit kirjautumistunnukset eri käyttäjärooleille. Turvallisuuden parantamiseksi näiden käyttäjien oletussalasanat on hyvä vaihtaa omiin salasanoihin.

Lisäksi poistin GLPI asennuksessa käytetyn install.php-asennustiedoston, jotta asennussivua ei voi käyttää uudelleen. Tämän jälkeen GLPI oli valmis käytettäväksi ja pystyin kirjautumaan järjestelmään verkkoselaimen kautta.

<br>
