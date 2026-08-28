## Osa 3 - Käyttäjähallinta

<br>

## Esittely

Projekti oli edennyt siihen vaiheeseen, että toimialueelle voitiin alkaa luoda käyttäjiä ja ryhmiä sekä määrittää niille käyttöoikeuksia ja ryhmäkäytäntöjä. Tässä osiossa keskityttiin käyttäjähallinnan perusteisiin sekä Active Directoryn käyttöoikeuksien hallintaan.

### VM luominen projektiin

Loin Virtuaali koneen, jolle voin configuroida luomiamme GPO:ita. En aijo käydä yksityiskohtaisesti läpi miten loin virtuaalikoneen, sillä sen periaate on sama kuin osa-1 luomamme windows-serveri. Latasin kokeiluversion windows-11 ISO tiedoston ja boottasin sen virtuaalikoneen CD-asemalta sekä eurasin ruudulle ilmestyviä asennusohjeita. On tärkeää että Windows versio on joko Pro tai Enterprise versio sillä vain näissä Windows versioissa on mahdollisuus liittyä domainiin.

![asennus](images/asennus.png)

### Mitä ongelmia kohtasin ja miten ratkoin sen

Vaikka sainkin VM asennuksen kuulostamaan helpolta kohtasin kuitenkin ongelman ISO-tiedoston kanssa. Olin huomaamattani onnistunut lataamaan ARM64-arkkitehtuurille tarkoitetun tiedoston eikä tästä syystä VM suostunut boottaamaan latausta. Hetken forumeita tutkittuani löysin ongelman ja latasin oikean iso tiedoston x64-arkkitehtuuriin sopivaksi.
