# h2 DORA the Explora

Viikon läksyjen tarkemmat tehtävänannot luettavissa [täältä](https://terokarvinen.com/tunkeutumistestaus/#h2-dora-the-explora).

## x) Tiivistelmiä

:warning:Kannattaa muistaa tallentaa, jos vaikka sattuis tilttaamaan. -nimim. Tilttasprkl:warning:

### x-1) Marko Buuri, DORA and TLPT testing - Lecture for Haaga-Helia on 31 March 2026

- DORA(Digital Operation Resilience Act) on EU:n sääntö, jonka tarkoitus on varmistaa, että finanssialan yritykset kestävät kyberhäiriöitä.
- DORA koskee suurta määrää toimijoita (yli 20 000) sekä niiden IT-kumppaneita.
- DORA vaatii yrityksiltä kahta testaustyyppiä:
  - Peruskyberturvatestausta kaikille.
  - Kehittyneempää hyökkäyssimulaatiota (TLPT) vain tärkeimmille toimijoille.
- TLPT-testit (Threat-Led Penetration Testing) simuloivat oikeita kyberhyökkäyksiä, jotta nähdään miten hyvin yritys puolustautuu.
- TIBER-EU on Euroopan keskuspankin kehittämä malli, joka ohjaa näiden hyökkäyssimulaatioiden toteutusta.
- Suomessa käytetään TIBER-FI-mallia, joka on sovitettu DORA-vaatimuksiin.
- Testausprojektiin osallistuu useita rooleja, kuten:
  - Uhkia tiedusteleva ja hyökkäysskenaarioita suunnitteleva Threat Intelligence.
  - Hyökkääjiä simuloiva Red Team.
  - Puolustava Blue Team.
  - Projektia ohjaava Control Team.
- Testausprosessi etenee kolmessa päävaiheessa:
  - Valmistelu
  - Testaus (uhkatiedustelu + hyökkäys)
  - Lopetus ja raportointi
- Koko testiprojekti kestää yleensä noin 12–18 kuukautta.
- Testauksen tarkoitus ei ole “murtaa järjestelmää”, vaan oppia, miten suojaukset toimivat ja miten niitä voidaan parantaa.

Marko Buurin esityksen kaikki diat luettavissa [täältä](https://terokarvinen.com/buuri-2026-dora-and-threat-lead-penetration-testing/buuri-2026-dora-and-threat-lead-penetration-testing--teros-pentest-course.pdf).

### x-2) DORA artiklat 26 ja 27

#### TLPT-testauksesta (art. 26)
- Suurempien rahoitusalan toimijoiden on tehtävä kyberhyökkäyksiä simuloiva testaus vähintään 3 vuoden välein
- Testaus kohdistuu kriittisiin toimintoihin ja oikeisiin järjestelmiin, myös ulkoistettuihin
- Yritys vastaa testauksesta, vaikka mukana olisi ulkoisia palveluntarjoajia
- Tarvittaessa voidaan tehdä yhteistestaus usean yrityksen kesken
- Testauksen aikana on suojattava tiedot ja estettävä häiriöt
- Lopuksi:
  - Tehdään raportti ja korjaussuunnitelma
  - Viranomainen antaa hyväksynnän
- Viranomaiset päättävät, ketkä yritykset testataan riskien perusteella

#### Testaajista (art. 27)
- Testaajien pitää olla:
  - Päteviä, luotettavia, sertifioituja (tai riittävä pätevyys, kokemus ja ) ja vakuutettuja.
- Ulkoisia testaajia käytetään pääsääntöisesti.
  - Vaatimuksena vähintään joka kolmannessa testissä.
- Sisäiset testaajat sallitaan vain tietyin ehdoin:
  - Viranomaisen hyväksyntä.
  - Riittävät resurssit.
  - Ei eturistiriitoja (riippumattomuus testattavista toiminnoista).
  - Uhkatiedustelu (threat intelligence) tulee olla ulkopuoliselta toimijalta.
- Kaikki testauksen data on käsiteltävä turvallisesti ilman lisäriskejä.

Lisää DORA:n artikloista voi lukea [täältä](https://eur-lex.europa.eu/eli/reg/2022/2554/oj/eng#art_26).

### x-3) TIBER-FI - 5.4 Red Team Testing
- Testisuunnitelman hyväksymisen jälkeen alkaa Red Team -testaus, jossa simuloidaan oikeita kyberhyökkäyksiä valittuihin kriittisiin toimintoihin.
- Testaus etenee kahdessa vaiheessa:
  - Testisuunnitelman laatiminen (RTTP, Red Team Test Plan).
  - Varsinainen aktiivinen testaus.
- Hyökkäys etenee tyypillisesti vaiheittain:
  - Tiedon keruu -> valmistelu -> hyökkäyksen käynnistys -> murtautuminen -> liikkuminen järjestelmissä -> tavoitteiden saavuttaminen.
- Testin tarkoitus on jäljitellä todellisia hyökkääjiä mahdollisimman realistisesti.
  - Rajoitteet, kuten aika, resurssit ja eri säännöt vaikuttavat testien realistisuuteen.
- Yritys voi antaa testaajille lisätietoa (grey box-testaus), mikä yleensä parantaa testin hyötyä.
  - Esim. rajallisessa ajassa saadaan kohdennetumpaa ja tehokkaampaa testausta.
- Jos testaus ei etene (esim. ajan tai suojauksen takia), testaajille voidaan antaa lisäapua (Leg-Up), jotta testin tavoitteet saavutetaan.
- Testin aikana myös uhkatiedustelua voidaan päivittää jatkuvasti, jotta testaus olisi tehokkaampaa.

Lisää TIBER-FI-ohjeistuksesta voi lukea [täältä](https://www.suomenpankki.fi/globalassets/bof/en/money-and-payments/the-bank-of-finland-as-catalyst-payments-council/tiber-fi/tiber-fi-2.0-procedures-and-guidelines.pdf).

### x-4) Marko Buuri - Releasing Your Inner TIBER in Regulated Adversary Simulations

Vapaaehtoinen tehtävä, tällä kertaa tallennettu soittolistaan.

Video katsottavissa [täältä](https://www.youtube.com/watch?v=z6KIEEknKjM).



## Lähteet

Tero Karvinen
- https://terokarvinen.com/tunkeutumistestaus/#h2-dora-the-explora

Marko Buuri
- https://terokarvinen.com/buuri-2026-dora-and-threat-lead-penetration-testing/buuri-2026-dora-and-threat-lead-penetration-testing--teros-pentest-course.pdf
- https://www.youtube.com/watch?v=z6KIEEknKjM

EU EUR-Lex tietokanta
- https://eur-lex.europa.eu/eli/reg/2022/2554/oj/eng#art_26

Suomen Pankki
- https://www.suomenpankki.fi/globalassets/bof/en/money-and-payments/the-bank-of-finland-as-catalyst-payments-council/tiber-fi/tiber-fi-2.0-procedures-and-guidelines.pdf

# KONE TILTTAS, KANDEE TALLENTAA AINA VÄLILLÄ RIPPISTÄ PRKL :ASD
