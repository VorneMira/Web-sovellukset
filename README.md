
# Web-sovellukset 2020 

## Valmistaudu jaksoon
Tee GitHubiin repositorio nimeltä Web-sovellukset ja sen alle kaksi kansiota: 
  * Tutorial
  * Projekti


Tutorial-tehtävät nimetään tehtävän mukaan, esim. teht1.html ja palautetaan GitHubiin Tutorial-tehtävät kansioon. Projektia on koko jakson ajan laajentuva tehtävä, jonka seuraava versio voidaan tallentaa aina edellisen päälle.


## Sisältö ja tehtävät
1. **Tehtävä: HTML tutorial**
  * Katso tutorial: https://youtu.be/UB1O30fR-EE
  * Tee HTML-sivu videon ohjeiden mukaisesti.
  * Palauta GitHubiin Tutorial -kansioon.  
2. **Tehtävä: Projektin HTML** 
  * Aloita koko jakson kestävä, Websovelluksena toteutettu, Yhteystieto-projekti tekemällä kuvan mukainen HTML-sivu. 
  * Nimeä HTML-sivu nimellä index.html ja palauta repositoriosi Projekti-kansioon.

![HTML](HTML.png)


3. **Tehtävä: CSS tutorial**
  * Katso tutorial: https://youtu.be/yfoY53QXEnI
  * Tee videon tyylitiedostoharjoitus.
  * Palauta GitHubiin Tutorial -kansioon.
4. **Tehtävä: Projektin CSS** 
  * Tee projektisi index.html tiedostoon ulkoinen tyylitiedosto. Muokkaa:
    * Taustakuva
    * Otsikoiden fontti, väri ja koko. Keskitä otsikot keskelle sivua. 
    * Leipätekstin fontti tyyli ja koko.
    * Tee listan bulleteista kuvia.
    * Tee jokaisesta sivun osiosta div, jossa on pyöreät kulmat ja taustakuvasta erottuva taustaväri: Phonebook, Add a new, Numbers
    * Muokka lomakkeiden kenttien reunojen väriä.
    * Tee nappuloista mustia valkoisella tekstillä.
    * Palauta GitHubiin Projekti-kansioon.

5. **Tehtävä: BOOTSTRAP**
  * Katso tutorial: https://youtu.be/yfoY53QXEnI
  * Tee videon Bootstrap-harjoitus.
  * Palauta GitHubiin Tutorial -kansioon.
6. **Tehtävä: Projektin Bootstrap** 
  * Tee projektisi index.html sivun ylälaitaan Bootstrap navbar
    * Lisää vasempaan reunaan logo
    * Lisää erilliset linkit jokaiseen tutorial-tehtävään
    * Tee navbarista collabsible

4. JAVASCRIPT
video
videon JavaScript

5. JSON
video
video JSON

6. REACT JS
video
videon React
projektin react

7. NODE.JS
video
videon Node
projektin node

8. Projekti
Tee projektiin lisää -toiminnallisuus.
Puhelinluettelon yhteystietojen jälkeen lomake, josta voit lisätä lisää yhteystietoja.

9. Projekti
Tee projektiin poista -toiminnalisuus.
Puhelinluettelon jokaisen tulostettavan yhteystiedon perään Poista -nappula.

10. Projekti
Tee projektiin filter -toiminnallisuus.

11. Projekti
Tee projektiin Notification -toiminnallisuus
- Yhteystieto lisätty
- Liian lyhyt nimi
- Liian lyhyt puhelinnumero
- Nimi tai numero puuttuu
- Yhteystieto poistettu 
- Errorit
- Notification poistuu sivulta 5 sek. kuluttua.

12. Projekti
- Toggle -toiminnallisuus
- Näytä / piilota uuden yhteystiedon lisäyslomake nappia painamalla.

## Dokumentaatio   
* [Vaatimusmäärittely](https://github.com/MiraVorne77/ot-harjoitustyo/blob/master/dokumentaatio/vaatimusmaarittely.md)
* [Arkkitehtuurikuvaus](https://github.com/MiraVorne77/ot-harjoitustyo/blob/master/dokumentaatio/arkkitehtuuri.md)
* [Työaikakirjanpito](https://github.com/MiraVorne77/ot-harjoitustyo/blob/master/dokumentaatio/tyoaikakirjanpito.md)
* [Käyttöohje](https://github.com/MiraVorne77/ot-harjoitustyo/blob/master/dokumentaatio/kayttoohje.md)
* [Testausdokumentti](https://github.com/MiraVorne77/ot-harjoitustyo/blob/master/dokumentaatio/testausdokumentti.md)

## Releaset
[Viikko 5](https://github.com/MiraVorne77/ot-harjoitustyo/releases/tag/Viikko5)

[Viikko 6](https://github.com/MiraVorne77/ot-harjoitustyo/releases/tag/Viikko6)

[Final](https://github.com/MiraVorne77/ot-harjoitustyo/releases/tag/Final)

## Komentorivitoiminnot

### Testaus

Testit suoritetaan komennolla

```
mvn test
```

Testikattavuusraportti luodaan komennolla

```
mvn jacoco:report
```

Kattavuusraporttia voi tarkastella avaamalla selaimella tiedosto _target/site/jacoco/index.html_

### Suoritettavan jarin generointi

Komento

```
mvn package
```

Generoi hakemistoon target suoritettavan jar-tiedoston Address_book-1.0-SNAPSHOT.jar

### Checkstyle

Tiedostoon checkstyle.xml määrittelemät tarkistukset suoritetaan komennolla

```
mvn jxr:jxr checkstyle:checkstyle
```
Mahdolliset virheilmoitukset selviävät avaamalla selaimella tiedosto target/site/checkstyle.html

### JavaDoc
JavaDoc generoidaan komennolla

```
mvn javadoc:javadoc
```

JavaDocia voi tarkastella avaamalla selaimella tiedosto target/site/apidocs/index.html