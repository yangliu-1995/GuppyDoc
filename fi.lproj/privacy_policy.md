# Guppy Tietosuojakäytäntö

** Voimaantulopäivä: 23. huhtikuuta 2026**

Guppy on offline-tilassa toimiva paikallinen musiikkisoitin. Yksityisyys on keskeinen osa Guppy:n suunnittelua: kaikki musiikkisi, kuunteluhistoriasi ja henkilökohtaiset tietosi pysyvät laitteessasi. Emme käytä palvelimia, emmekä kerää, lataa tai jaa tietojasi millään tavalla.

Tämä käytäntö selittää, mitä Guppy käyttää laitteessasi, miksi se käyttää sitä ja mitä hallintaa sinulla on.

## Tiedot, joita emme kerää

Guppy **ei** kerää, lataa tai jaa mitään seuraavista meidän tai kolmannen osapuolen kanssa:

- Tilitiedot, nimi, sähköpostiosoite, puhelinnumero tai mikä tahansa henkilökohtainen tunniste.
– Laitetunnisteet, mainostunnisteet tai sijaintitiedot.
– musiikkitiedostosi, sanat, kuvitus, kuunteluhistoria, suosikit tai soittolistat.
– käyttöanalytiikka, telemetria tai virheraportit.

Guppy ei integroi kolmannen osapuolen analytiikka-, mainonta- tai seuranta-SDK:ita.

## Mitä Guppy käyttää laitteessasi

Guppy käyttää vain seuraavia kohteita laitteessasi, kun käytät aktiivisesti liittyvää ominaisuutta. Jokainen pääsy on aidattu Apple:n järjestelmän lupakehotteilla, ja kaikki tapahtuu paikallisesti laitteellasi.

### Paikallinen musiikki ja tiedostot

- Guppy lukee musiikki- tai sanoitustiedostoja vain, kun valitset ne nimenomaisesti järjestelmän tiedostovalitsimen kautta.
- Guppy voi **käyttää vain nimenomaisesti valitsemiasi tiedostoja**. Se ei skannaa tai lue muita tiedostoja laitteessasi.

### Valokuvat

- Guppy käyttää valokuvakirjastoasi vain, kun päätät tuoda siitä taideteoksia tai sanoituksia.
- Guppy käyttää järjestelmän valokuvavalitsinta (PHPicker), joka antaa Guppy pääsyn **vain tiettyihin valitsemiisi kuviin**. Guppy ei koskaan pyydä täydellistä valokuvakirjaston käyttöä.

### Paikallinen verkko

Guppy käyttää paikallista verkkoasi vain seuraaviin ominaisuuksiin, jotka olet erikseen ottanut käyttöön. Kaikki yhteydet rajoittuvat paikalliseen verkkoosi tai itse määrittämiisi kohteisiin; mitään ei ole ladattu meille tai millekään kolmannelle osapuolelle:

- **Laitteiden välinen siirto**: siirrä musiikkia ja sanoituksia kahden laitteen välillä, joissa on Guppy samassa paikallisessa verkossa.
- **Selainlataus puhelimeen**: käynnistä tilapäisesti paikallinen HTTP-palvelu puhelimessasi, jotta voit ladata tiedostoja samassa verkossa olevasta selaimesta. Tämä palvelu toimii vain, kun ominaisuus on auki.
- **WebDAV**: muodosta yhteys WebDAV-palvelimeen, jonka määrität itse musiikin selaamista tai tuontia varten.
- **Subsonic-yhteensopivat palvelimet**: muodosta yhteys Subsonic-palvelimeen, jonka määrität itse musiikin selaamista tai tuomista varten.

Kaikki antamasi palvelinosoitteet, käyttäjätunnukset ja salasanat tallennetaan vain laitteellesi (tunnistetiedot säilytetään järjestelmässä Keychain), eikä niitä koskaan ladata.

## Kolmannen osapuolen palvelut

Kun päätät muodostaa yhteyden palvelimeen WebDAV tai Subsonic, tuloksena oleva tiedonvaihto tapahtuu laitteesi ja määrittämäsi palvelimen välillä, ja sitä säätelee kyseisen palvelun oma tietosuojakäytäntö. Guppy ei ole mukana missään tiedon keräämisessä tai välittämisessä tämän suoran vuorovaikutuksen lisäksi.

## Sinun velvollisuutesi ja musiikin tekijänoikeus

- Guppy **toistaa vain** paikallista musiikkia, jonka olet jo laillisesti omistanut tai jonka käyttö on valtuutettu.
- Guppy **ei tarjoa mitään musiikin lataus-, haku- tai jakelupalvelua**. Tuomasi kaikki musiikki, sanoitukset ja taideteokset.
- Olet yksin vastuussa sen varmistamisesta, että sinulla on tarvittavat oikeudet tai lisenssit kaikkeen tuomaasi musiikkiin, sanoituksiin tai taideteokseen. Olet vastuussa kaikista seurauksista, jotka johtuvat luvattoman sisällön tuomisesta tai käytöstä.

## Lasten tietosuoja

Guppy ei kerää henkilötietoja keneltäkään käyttäjältä, mukaan lukien lapsilta.

## Muutokset tähän käytäntöön

Jos tämä käytäntö päivitetään, sovelluksen sisäinen asiakirja päivitetään ja yläreunassa oleva "Voimaantulopäivä" tarkistetaan.

## Ota yhteyttä

Jos sinulla on kysyttävää tästä käytännöstä, ota meihin yhteyttä osoitteessa:

`yangliu-1995@outlook.com`
