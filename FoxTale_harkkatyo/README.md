# **Harjoitustyö | Fox's Tale**

Vähäisen peliohjelmointikokemuksen takia päätin tehdä tutoriaalin mukaisen pelin, Fox’s Talen. Kyseessä on 2D peli, jossa hahmo kerää timantteja, yrittää olla astumatta piikkeihin ja osumatta sammakkoihin, jotka vähentävät hahmon terveyttä.

![](FoxTale_harkkatyo/Screenshots/003_game.png)

## Linkit
* [Linkki WebGL buildiin studentilla](https://student.labranet.jamk.fi/~N2927/ttos0700-peliohjelmointi/Foxs_tale)
* [Linkki Udemyn tutoriaaliin](https://www.udemy.com/course/unityplatformer/) (maksullinen sisältö)
## Käytetyt ohjelmat

* Visual Studio Code 1.55.3
* Unity Unity 2020.2.3f1

## Opitut asiat

* Tasojen järjestyksen vaikutus pelin toimivuuteen ja selkeyteen
* Sprite importtien asetukset, kun kyseessä on 2D-peli
* ”Sorting layerien” lisääminen ja käyttö
* Tilemapsien käyttäminen
* Prefabsien luonti ja uudelleenkäyttö
* Animaatiokäyrien käyttö
* Kameran asetukset siten, että se seuraa tai ei seuraa hahmoa
* Canvas-ominaisuuden käyttö esimerkiksi navigaation luonnissa
* Dynamic vs kinematic RigidBody asetuksien merkitys
* Tagien käyttö
* Random.Range -funktion käyttö
* Colliderien käyttö eri tarkoituksissa (capsule, circle, composite, tilemap…)
* Audiomixerin käyttö
* Audioiden käyttäminen tehosteina
* C#-kielen käyttäminen peliohjelmointiin


## Ongelmat

Ajankäytöstä suurin osa meni debuggaamiseen. Vaikka noudatin orjallisesti tutoriaalia, koodi ei jostain syystä aina antanut oikeita toimintoja. Opin tietenkin paljon juuri sen takia, että ongelmia oli ratkottavana jatkuvasti ja oli kehittävää huomata, että itse pystyi ratkomaan ongelmat koodissa ja itse pelimoottorissa. Buildaamisessa oli ongelmia, kun tein WebGL-buildia, mutta lopulta onnistuin, kun siirsin projektikansion c: -aseman juureen. 

Seuraava error-koodi aiheutti päänvaivaa ja varmasti osoitti osaamattomuuden:

> "NullReferenceException: Object reference not set to an instance of an object"

En saanut kyseistä virheilmoitusta pois ja sen takia esimerkiksi mustan ruudun ilmestyminen hahmon kuoleman jälkeen ”fade-efektinä” ei lähtenyt toimimaan. Lopulta päädyin poistamaan ne koodipätkät, mitkä aiheuttivat ongelmia, koska ne eivät lähteneet muutenkaan toimimaan. Muut toiminnot kyllä pelittivät ja peli on varsin kiva pelattava. 

## Ajatuksia
Tämä peli osoittautui mielenkiintoiseksi kehitettäväksi. Vaikka tasolta toiselle pääsy ei ehtinyt loppuharjoitustyöhön, tätä projektia on pakko jatkaa kehittämällä omia ja vaikeampia tasoja, sen verran tässä tuli opittua pienessä hetkessä.
Antaisin työstä rehellisesti sanoen itselleni ykkösen (1), koska riman alitushan tämä oli lähinnä kevään tiukan aikataulun takia lähinnä pelin oman koodin puuttumisen suhteen. Olisi ollut mukava kehittää vaikka samankaltainen peli omilla grafiikoilla, jos aikaa olisi ollut enemmän.

