---
layout: page
title: Miniprojekti
title_long: 'Miniprojekti'
permalink: /miniprojekti/
inheader: yes
---

### Ajankohtaista

<div style="color:black; border-style: solid; border-width: thick; border-color: green; padding: 10px; margin-bottom: 15px; padding: 10px; background-color: #F1EFEF;">

  <ul>
    <li>
      Miniprojektilla on 5 aloitustilaisuutta, ja jokaisen on tarkoitus osallistua niistä yhteen
      <ul>
        <li>ti 14-16</li>
        <li>ke 14-16</li>
        <li>ke 16-18</li>
        <li>to 10-12</li>
        <li>to 14-16</li>
      </ul>
    </li>
    <li>
      Ilmoittaudu (eli kerro aikatoiveesi) viimeistään sunnuntaina 10.11. klo 23:59 osoitteessa
  <a href="https://study.cs.helsinki.fi/assembler/course/c7e5da85-981e-4145-b444-4bc28d8e3da9">https://study.cs.helsinki.fi/assembler/course/c7e5da85-981e-4145-b444-4bc28d8e3da9</a>
      <ul>
        <li>Valitse ajat jotka sopivat sinulle myös kolmen seuraavan viikon asiakastapaamisiin</li>
      </ul>
    </li>
  </ul>

</div>

### Johdanto

- Kurssin viikoilla 4-7 tehdään miniprojekti
- **Kurssin läpipääsy edellyttää hyväksyttyä osallistumista miniprojektiin** tai sen [hyväksilukemista](/osa0#miniprojektin-hyv%C3%A4ksilukeminen)

- Projekti tehdään noin 4-6 hengen ryhmissä
- Projektissa ohjelmoidaan jonkin verran, **pääpaino ei ole ohjelmoinnissa** vaan systemaattisen prosessin (tästä lisää myöhemmin) noudattamisessa.
- **Jokaisen ryhmän jäsenen on tarkoitus tehdä kunkin sprintin aikana töitä noin 6 tuntia projektin eteen**
  - Asiakastapaamisiin menevää aikaa ei lasketa viikoittaiseen työaikaan!
- Ryhmä tekee kussakin sprintissä sen minkä se sprinttiin varatussa ajassa pystyy tekemään, ei enempää eikä vähempää
  - Kuuden tunnin työajan reilu ylittäminen siis **ei ole** järkevää, se on suorastaan kiellettyä

### Ryhmän muodostaminen

- Ryhmät muodostetaan 11.11. alkavalla viikolla pidettävissä aloitustilaisuuksissa
  - aloitustilaisuuden kesto on noin 2 tuntia
- Aloitustilaisuuksien alustava aikataulu
  - ti 14-16
  - ke 14-16
  - ke 16-18
  - to 10-12
  - to 14-16
- Ilmoittautuminen miniprojektiin (eli sopivaan aloitustilaisuuteen) alkaa noin 5.11.  
- Aloitustilaisuuteen tullessa on syytä tuntea materiaalin osien 1 ja 2 asioista ainakin seuraavat:
  - Scrum
  - sprintti
  - user story
  - product backlog
  - sprint backlog
  - hyväksymäkriteeri
  - definition of done
- Tämä dokumentti ja miniprojektin [arvosteluperusteet](/miniprojektin_arvosteluperusteet) on myös syytä lukea huolellisesti ennen aloitustilaisuutta

### Työn eteneminen

Seuraavien viikkojen asiakastapaaminen (sprintin katselmointi ja uuden sprintin suunnittelu) tapahtuu saman 2h sisällä missä aloitustilaisuus pidetään. Tilaisuuden kesto on 30 minuuttia. Aika kerrotaan palautussovelluksen välilehdeltä [miniproject]({{site.stats_url}}/miniproject)

#### viikko 3 (11-15.11.)

- Ryhmä muodostuvat/muodostetaan
- Ryhmät tapaavat asiakkaan aloitustilaisuuksissa
- Projekti tulee rekisteröidä palautussovellukseen <{{site.stats_url}}>.
  - **Yksi ryhmäläinen** kirjautuu järjestelmään, menee välilehdelle _miniprojects_
    - Luo projektin _create project_ -napista avautuvasta lomakkeesta
    - Ja jakaa muille ryhmäläisille luodun projektin id:n
  - **Muut ryhmäläiset** kirjautuvat järjestelmään ja liittyvät id:n avulla ryhmään _join project_ -napista avautuvasta lomakkeesta
  - **Jokaisen ryhmäläisen on oltava rekisteröitynyt projektiin viimeistään ensimmäisen sprintin lopuksi pidettävässä asiakastapaamisessa.**
    - Ne ryhmäläiset joita ei ole rekisteröity ensimmäisen sprintin asiakastapaamiseen mennessä, eivät saa ryhmälle sprintistä tulevia pisteitä

#### viikko 4 (18-22.11.)

- Sprintin 1 katselmointi ja sprintin 2 suunnittelu

#### viikko 5 (25-29.11.)

- Sprintin 2 katselmointi ja sprintin 3 suunnittelu

#### viikko 6 (2-5.12.)

- Sprintin 3 katselmointi ja sprintin 4 suunnittelu

#### viikko 7 (9-13.12.)

- Loppudemot (jokainen ryhmä osallistuu yhteen tilaisuuteen)
  - ke 11.12. klo 12-14 B123
  - to 12.12. klo 12-14 CK112
- Jokainen ryhmä osallistuu yhteen loppudemoon
- Ei erillistä asiakaspalaveria

### Toteutettava ohjelmisto

Paljastuu aloitustilaisuudessa...

### Tekniset ja prosessiin liittyvät vaatimukset

- Ryhmä laatii yhdessä asiakkaan kanssa _product backlogin_
  - Vaatimukset kirjataan backlogiin user storyinä
- Sprintin suunnittelun yhteydessä ryhmä sitoutuu toteuttamaan sopivan määrän backlogin kärjessä olevista user storyistä
  - Jokaisen ryhmäläisen "työaika" on 6 tuntia viikossa
    - Työajan ylittävä sankarikoodaus ei ole suositeltavaa, se on jopa kiellettyä
  - Ryhmä sitoutuu ainoastaan niihin storyihin, jotka se kuvittelee kykenevänsä toteuttamaan sprintissä **definition of donen** määrittelemällä laatutasolla. Definition of done on määritelty alla
  - Kannattaa huomata, että storyihin sitoutuminen ei tarkoita sitä, että ne on pakko tehdä valmiiksi. Ohjelmistoja tehdessä sattuu ja tapahtuu ennakoimattomia asioita, ja aina suunnitelmat eivät toteudu.
  - Asiakkaalle ei kannata luvata liikaa, ja varsinkin ensimmäisten sprinttien aikana arvioissa on otava varovainen, konfiguroimiseen, testaamiseen ja ryhmän järjestäytymiseen tulee kulumaan paljon aikaa
- Ryhmä ylläpitää _sprint backlogia_
  - User storyt jaetaan sprintin suunnittelussa teknisen tason tehtäviksi eli _taskeiksi_ jotka sijoitetaan sprint backlogiin
  - Ryhmä tekee päivittäin jäljellä olevan työajan arviointia ja dokumentoi tämän sprintin burndown-käyränä
  - Sprint backlogista tulee ilmetä kunkin taskin osalta
    - jäljellä olevan työajan estimaatti
    - taskin tila (esim. aloitettu, ohjelmoitu, testauksessa, valmis)
    - taskin tekijä(t)
- Ryhmä toteuttaa jatkuvaa integraatiota (continuous integration)
  - Oletusarvoisesti kannattaa käyttää laskareista 1 tuttua GitHub Actionsia
- Koodi on talletettu GitHubiin
- Projektin GitHub-repositoriolla on järkevä README.md

#### Product ja sprint backlog

- Backlogissa vaatimukset ilmaistaan järkevästi muotoiltuna user storyinä
  - **miniprojektissa ei ole tarvetta estimoida user storya**, ainoastaan sprintissä olevien taskien työmäärä estimoidaan
- Kuten edellä todettiin sprint backlogista tulee ilmetä kunkin taskin osalta
  - jäljellä olevan työajan estimaatti
  - taskin tila (esim. aloitettu, ohjelmoitu, testauksessa, valmis)
  - taskin tekijä(t)
- Backlogit voi toteuttaa esim. Google Docs -spreadsheetinä, mallia voi ottaa seuraavista:
  - erään ohtuprojektin [backlogit](https://docs.google.com/spreadsheets/d/13RzIZI2NFFuV0zdRjrrfoC-CrootK8AZNuHS571Wlxo/edit#gid=1)
  - <http://www.mountaingoatsoftware.com/scrum/sprint-backlog> (tämä on sikäli huono, että siitä eivät ilmene taskin tekijät)
- Backlogit voi tehdä Google Docsin sijaan myös johonkin backlogien ylläpitämiseen tarkoitettuun työkaluun
  - kannattaa varmistaa, että työkalu kuitenkin tukee edellä lueteltuja vaatimuksia
  - esim. <https://trello.com> ei tue Scrum-tyylisiä backlogeja oikeastaan ollenkaan, ja **Trelloa kannattaakin välttää tässä projektissa**

#### Definition of done

Seuraavassa lähtökohta definition donelle. Ryhmän tulee määritellä GitHub-repositorioon oma, omiin lähtökohtiin sopiva DoD

- User storyille tulee määritellä hyväksymiskriteerit, jotka dokumentoidaan sprintistä 2 alkaen [Robot-frameworkin](/robot_framework/) syntaksilla
  - hyvänä käytänteenä on laittaa README:stä linkki hyväksymäkriteerit määritteleviin tiedostoihin
- Toteutetun koodin testikattavuuden tulee olla kohtuullinen
- Asiakas pääsee näkemään koko ajan koodin ja testien tilanteen CI-palvelusta
- Koodin ylläpidettävyyden tulee olla mahdollisimman hyvä
  - järkevä nimeäminen
  - järkevä/selkeä ja perusteltu arkkitehtuuri
  - yhtenäinen koodityyli (noudattaa pylintin avulla määriteltyjä sääntöjä)

#### Repositorio ja README

README:ssa tulee löytyä ainakin seuraavat asiat:

- Linkit backlogeihin (backlogeista tulee olla luettavissa olevat versiot julkisessa internetissä)
- Linkki CI-palveluun
- Linkki sovelluksen toimivaan versioon (jos sovellus on verkossa)
- Jos kyse työpöytäsovelluksesta, tulee ohjelmalle olla asennus- ja käyttöohje
- Työlle tulee määritellä lisenssi <https://help.github.com/articles/licensing-a-repository/>

### Vihjeitä ryhmätyöskentelyyn

Melko varma resepti epäonnistumiseen on huono kommunikaatio. Tehkää siis asioita mahdollisimman paljon yhdessä, mieluiten paikanpäällä tai jos se ei onnistu niin esim. Discordin voice chatissa. Ylipäänsä on hyvä kommunikoida ryhmälle mitä lähtee tekemään ja milloin on saanut sen valmiiksi, tällöin vältytään päällekkäisyyksiltä. Erityisesti projektin alkuvaiheessa esim. GitHub-actionsia konfiguroitaessa yhdessä tapahtuvaan työskentelyyn kannattaa panostaa. Projektin kuluessa omatoiminenkin työskentely muuttuu jo helpommaksi jos ja kun ryhmä on sopinut työskentelyn periaatteista ja pelisäännöistä.

Pariohjelmointi/konfigurointi on havaittu erittäin hyödylliseksi. Voikin olla hyvä idea, että jokaista user storyä työstää aina kaksi henkilöä.

Jokaiselle asialle, kuten vaikkapa README.md-tiedostolle, project backlogille ja sprint backlogille kannattanee nimetä joku vastuuhenkilö joka varmistaa, että ryhmä hoitaa asian. Asian X vastuuhenkilö ei välttämättä siis tee asiaa itse, vaan varmistaa että se tulee tehdyksi.

Pitäkää ohjelma koko ajan toimintakykyisenä. On erittäin huono idea koittaa saada viikon aikana eri ihmisten koodaamat tuotokset integroitua tunti ennen asiakaspalaveria...

### Teknologisia vihjeitä

- Kokonaan uusien teknologioiden opettelu miniprojektin yhteydessä ei ole järkevää
- **Mahdollisten ulkoisten kirjastojen käyttöönotto, testien tekeminen ja CI:n konfigurointi tulee viemään ainakin alussa todella paljon aikaa**
- Komentoriviltä toimiva sovellus on teknologioiden suhteen riskittömin vaihtoehto
  - **HUOM:** Komentoriviltä toimivat sovellukset on syytä tehdä siten, että niiden IO-operaatiot eli tulostaminen ja syötteen lukeminen on eriytetty omaan injektoitavaan luokkaan viikon 1 laskareissa käsitellyn [riippuvuuksien injektointi](/riippuvuuksien_injektointi_python/) -esimerkin tapaan. Jos näin ei toimita tulee sprintistä 2 alkaen tehtävä käyttöliittymän läpi tapahtuva testaus olemaan erittäin haastavaa
- Web-pohjaiselle sovellukselle voi ottaa mallia kurssin [esimerkkisovelluksesta](https://github.com/ohjelmistotuotanto-hy/todo-web)
- Jos haluatte käyttää tietokantaa, on Tikapestakin tuttu _SQLite_ hyvä vaihtoehto
  - SQLiten käyttöön Pythonilla löytyy ohjeita ainakin [Ohjelmistotekniikka-kurssin](https://ohjelmistotekniikka-hy.github.io/python/toteutus#tietojen-tallennus) materiaalista
  - Ohjelmistotekniikka-kurssin [todo-sovellus](https://github.com/ohjelmistotekniikka-hy/python-todo-app) on esimerkkisovellus SQLiten tietokannan käytöstä Python-projektissa
  - Huomaa, että jos tarkoituksena on julkaista sovellus jossain pilvipalvelussa, SQLiteä parempi vaihtoehto on _PostgreSQL_. Mallia PostgreSQL:n käyttöön Python-sovelluksessa voi ottaa esimerkiksi seuraavasta tälle kurssille tehdystä [esimerkkisovelluksesta](https://github.com/ohjelmistotuotanto-hy/todo-web)
- Viikon 3 laskareista kannattaa ottaa mallia Robot Frameworkilla tapahtuvaan storyjen testaamiseen (vaaditaan sprintistä 2 alkaen)
- Pythonin Tkinter-kirjastolla tehtyjen käyttöliittymien automatisoitu testaaminen on täysi mysteeri, sen takia kannattanee välttää kirjaston käyttöä

### Työn arvostelu

Arvosteluperusteet löytyvät [täältä](/miniprojektin_arvosteluperusteet/)
