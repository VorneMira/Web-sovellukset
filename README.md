
# Web-sovellukset 2020 

## Valmistaudu jaksoon
Tee GitHubiin repositorio nimeltä Web-sovellukset ja sen alle kaksi kansiota: 
  * Tutorial
  * Projekti


Tutorial-tehtävät nimetään tehtävän mukaan, esim. teht1.html ja palautetaan GitHubiin Tutorial-tehtävät kansioon. Projektia on koko jakson ajan laajentuva tehtävä, jonka seuraava versio voidaan tallentaa edellisen päälle.


## Sisältö ja tehtävät
1. **Tehtävä: HTML tutorial**
  * Katso tutorial: https://youtu.be/UB1O30fR-EE
  * Tee HTML-sivu videon ohjeiden mukaisesti.
  * Palauta GitHubiin Tutorial -kansioon.  
2. **Tehtävä: Projektin HTML** 
  * Aloita koko jakson kestävä, Websovelluksena toteutettu, Yhteystieto-projekti tekemällä kuvan mukainen HTML-sivu. Nimeä se index.html

![HTML](HTML.png)



2. CSS
video
videon CSS
projektin CSS

3. BOOTSTRAP
video
videon Bootstrap
projektin bootstrap

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