# AIHE: RNA:n sekvensointi ilman referenssigenomia

## Tarkastuslausunto

### Tehtäväalue

Geenin ilmeneminen solussa on monivaiheinen prosessi. Ensin DNA-molekyylistä tuotetaan RNA-molekyyli, josta
sitten tuotetaan proteiineja. RNA-sekvensoinnissa pyritään selvittämään, mitä RNA-molekyylejä solussa on ja
kuinka paljon kutakin RNA-molekyyliä on. RNA-sekvensointi tuottaa lyhyitä fragmentteja, joista laskennallisesti
rekonstruoidaan alkuperäinen RNA-molekyyli ja päätellään kunkin RNA-molekyylin pitoisuus. Työssä on keskitytty
RNA-sekvenssien rekonstruktioon ilman referenssigenomia.

### Kokonaisuuden hallinta
Työ on onnistunut kokonaisuus, jossa ensin esitellään aiheen biologinen tausta sekä kokeelliseen
tutkimusmenetelmään liittyvät seikat. Tämän jälkeen on esitetty de Bruijnin verkkoon perustuva
rekonstruktiomenetelmä ja esimerkki tähän tekniikkaan perustuvasta työkalusta. Lopuksi esitellään menetelmiä
RNA-molekyylien pitoisuuksien selvittämiseen. Työ kattaa laajan aihealueen, josta on onnistuneesti esitetty
olennaiset RNA-sekvensoinnin laskennalliset työvaiheet.

### Esitystekniikka
Esitystapa on viimeistelty ja työtä on miellyttävä lukea. Kuvia ja esimerkkejä on käytetty johdonmukaisesti
havainnollistamaan esitystä.

### Yleisvaikutelma
Satu Salekarin kandidaatintutkielma on erinomainen katsaus RNA-sekvensoinnin eri työvaiheisiin. Työssä on
syvällisesti pohdittu eri vaiheisiin liittyviä virhelähteitä ja niiden vaikutuksia RNA-sekvensoinnin tuloksiin.

### Arvosana: 5



## ABSTRAKTI
RNA-Seq-menetelmässä solun transkriptomi eristetään ja sekvensoidaan. Menetelmä on bioinformatiikan perustyökalu ja tärkeässä roolissa esimerkiksi geeniekspression tutkimuksessa.

Transkriptomin muodostavat RNA-molekyylit pilkkoutuvat ennen sekvensointia, ja fragmentit täytyy koostaa uudestaan sekvensoinnin jälkeen. Prosessia kutsutaan transkriptomin rekonstruktioksi. Se helpottuu, jos tutkitun lajin genomi on saatavilla, mutta aina näin ei ole. Tämä tutkielma on katsaus transkriptomin rekonstruktioon de novo eli ilman referenssigeno- mia.

De novo-rekonstruktio on mielenkiintoinen algoritminen haaste. Vakiintunut ratkaisu on hyödyntää de Bruijnin verkkoja. Ne ovat laskennallisesti tehokas ratkaisu ongelmaan, jossa rajatusta aakkostosta halutaan koostaa syklinen koostesana, jossa esiintyy jokainen mahdollinen annetun vakion k mittainen sana täsmälleen yhden kerran. Tämän ansiosta ne ovat yleishyödyllinen bioinformatiikan työväline, jolla on sovelluksia myös RNA-Seq:n ulkopuolella.

Transkriptomin rekonstruktion lisäksi RNA-Seq:ssä pyritään kvantifikaatioon eli transkriptien pitoisuuden määritykseen. Luettujen sekvenssien lukumäärää käytetään siinä korvikemuuttujana transkriptin pitoisuudesta. Sekvenssit, joita ei voida liittää yksiselitteisesti yhteen transkriptiin, tuottavat kvantifikaatiotuloksiin epävarmuutta. Jotta tulokset ovat vertailta- vissa, ne täytyy normalisoida. Erilaisia normalisointiyksikköjä ovat muun muassa RPKM, FPKM ja TPM.

RNA-Seq-menetelmä on vielä varsin nuori ja kehittyy jatkuvasti. Sekvensointiteknologioiden kolmas sukupolvi eliminoinee monia menetelmään liittyviä epävarmuustekijöitä. RNA-Seq:lle voikin ennustaa varsin valoisaa tulevaisuutta sen siirtyessä hiljalleen teini-iästä kohti täyttä aikuisuutta.
