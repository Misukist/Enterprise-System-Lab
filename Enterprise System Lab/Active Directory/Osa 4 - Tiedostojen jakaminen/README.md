# Osa 4 - Tiedostojen jakaminen

<br>

## Esittely

Tässä osiossa määrittelin keille tietyt tiedostot näkyvät. Osiossa tutustuttiin Verkon sekä paikallisen tiedostojen jakamisen toimintaan.

<br>

## Tiedostojen jakamisen valmistelut

Loin local disk C:n juureen kansion "SHARED" jolle määrittelin oikeudet. Haluan määritellä myöhemmin tarkempia oikeuksia kansioiden sisällä tiettyihin tiedostoihin johon yleinen oikeus ei ole pätevä vaan joudun käyttämään NTSF ominaisuutta jolla pystyy piilottamaan tiedostoja käyttäjiltä.

Menin kansion asetuksiin (**properties**) ja sieltä **Sharing**. Nyt pystyin määritellä kelle kansio jaetaan ja valitsin kaikille domain käyttäjille **Domain Users**

![sharing](images/shared.png)
