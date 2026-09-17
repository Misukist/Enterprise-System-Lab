# Peruskomennot

<br>

## Esittely

Harjoittelin peruskomentoja ennen varsinaista labia. Koin että on hyvä osata perusteita jotta labin suorittaminen olisi saumattomampaa.

<br>

### komennot

**docker run:**
Luo ja käynnistää uuden kontin annetun imagen pohjalta. Jos imagea ei löydy palvelimelta, Docker hakee sen oletuksena Docker Hubista.

**docker ps:**
Listaa kaikki käynnissä olevat kontit ja hyödyllistä dataa niihin liittyen.
docker ps -a: listaa kaikki myös käytöstä poistetut kontit.

**docker stop [ name ]:**
Pysäyttää käynnissä olevan kontin.

**docker start [ name ]:**
Käynnistää aiemmin pysäytetyn kontin uudelleen.

**docker restart [ name ]:**
Käynnistää kontin uudelleen.

**docker rm [ name ]:**
Poistaa kontin listasta.

**docker images:**
Listaa kaikki saatavilla olevat imaget.

**docker rmi [image name]:**
Poistaa imagen listalta. **Huom**: image ei saa olla käytössä missään kontissa ennen kuin sen poistaa.

**docker pull:**
Lataa imagen mutta ei käynnistä konttia.

**docker logs [ name] :**
Näyttää kontin tuottamat lokitiedot. Komennolla voidaan esimerkiksi tarkistaa, mitä kontissa tapahtuu tai onko sen käynnistymisessä ongelmia.

**docker exec [ name ] [ command ]:**
Suorittaa komennon käynnissä olevan kontin sisällä. Tätä voidaan käyttää esimerkiksi kontin sisälle siirtymiseen komennolla docker exec -it [name] bash.
