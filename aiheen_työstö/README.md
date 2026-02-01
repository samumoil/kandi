# Fault-tolerant ETL

## Hakusanoja

SCOPUS "fault tolerant etl"
 -> 11 osumaa

SCOPUS "fault tolerance etl"
 -> 12 osumaa

UEF PRIMO "fault tolerant etl" + saatavilla verkosta
 -> 12 osumaa

UEF PRIMO "ai-driven etl"
 -> 72 osumaa

## Tutkimuskysymys

```Millaisia teknisiä ja arkkitehtuurisia ratkaisuja ETL-prosessissa kannattaa käyttää, jotta prosessi on mahdollisimman vikasietoinen?```

## Pohdintaa hakusanoista

Tavoite on selvittää, millaisia teknisiä ja arkkitehtuuriratkaisuja kannattaa tehdä, jotta ETL-prosessi on mahdollisimman vikasietoinen ja resilientti.

Toisaalta, mitä ovat uhat? Mitkä asiat voivat kaataa ETL-putken? Mitä vastaan em. teknisiä ja arkkitehtuuriratkaisuja tehdään ja mitä halutaan välttää?

### Uhat
- Heterogeeninen data
- Väärän muotoinen data
- (Sähkö)katkokset ja osa datasta puuttuu
- Joku taho kyselee tietokannasta samaan aikaan kun sinne ollaan puskemassa uutta dataa
- Prosessia on vaikea siirtää toiseen palveluun, jos ETL-palveluntarjoaja vaihtuu
- ETL-prosessin hallinnasta vastaavat henkilöt vaihtuvat ja tapahtuu tietokatko -> dokumentaatio

### Muita huomioita
- Hyväksytäänkö vajaa datasetti vai vaaditaanko koko setin täydellinen käsittely?

