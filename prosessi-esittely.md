# Ohtu-kisalli projektin prosessiesittely

## Scrum artefaktit

* Backlog
  * [vanha](https://docs.google.com/spreadsheets/d/1fngPoH89ZXEGQo65SlD75FXpr3f-YjzylzEgXCqN1jQ/edit#gid=0)
  * [uusi](https://trello.com/b/khJuqE9a/product-backlog)
* Taskboard
  * [trello](https://trello.com/b/Llh06XVS/ohtu-kisalli)
  * [trello vanhat](https://trello.com/ohtukisalli)
* Taskeihin jako
  * [kuva](https://drive.google.com/file/d/0B1wLG72sys_STF9GYjQ3NFZBWEU/view?usp=sharing)
  * [kuva2](https://drive.google.com/file/d/0B1wLG72sys_SNzdrQjBfUDc4bTA/view?usp=sharing)
* Storyjen muoto
  * ks [trello](https://trello.com/b/khJuqE9a/product-backlog)
* Hyväksymiskriteerien muoto
  * ks [trello](https://trello.com/b/khJuqE9a/product-backlog)
* Estimointi
  * Ks. trello [taskit](https://trello.com/b/Llh06XVS/ohtu-kisalli)
  * Ks. [burndown](https://www.burndownfortrello.com/)
  * Ks. Backlog [estimaatit](https://trello.com/b/khJuqE9a/product-backlog)
* Definition of done
  * [drivessä](https://docs.google.com/document/d/1eTyUjT8rQvBWOGFAobeOJKGN3qU0LiBdK6p5i7BTWTQ/edit#)
  
## Workflow
 
* CI
  * Ks. server [travis](https://github.com/OhtuKisalli/kisallioppiminen.server#travis)
  * Ks. front [master](https://github.com/OhtuKisalli/ohtukisalli.github.io)
* Staging
  * [Heroku](https://pure-inlet-98383.herokuapp.com/)
* Lokaalikehitys
  * Ks. front readme
* Testaus
  * Front-työkalut
    * Jasmin
  * Back-työkalut
    * Rspec
* Tuotanto
  * Digital ocean, ubuntu 16.04, sudo-oikeudet
  * Docker
* Versionhallinta
  * Featurebranchit
  * dev/share ks [kuva](https://drive.google.com/drive/folders/0B1wLG72sys_SME5aSWFZRjF0d3c)
  * Puhdas master  
  * Pull requestit
    * ei käytössä (vielä)
  * Code revies
    * ei käytössä (vielä)

## Palaverit

* **Sprint planning**
  * [Steps](https://github.com/OhtuKisalli/project-info/blob/master/Sprint-planning-memo.md)
  * Maanantaisin n. klo 17
  * Noin 1 tunti
  * Sisältö
    * Demo
    * Uudet storyt
    * Toteutukseen valinta
  * Hyväksymiskriteerit jälkikäteen
    * Uusi backlog tuo parannusta?
* **Daily**
  * Noin 2 krt/vk
  * 15 min
  * Mitä olen tehnyt
  * Mitä teen seuraavaksi
  * Post-it lapulle askarruttavat aiheet
* **Retro**
  * Mad/Sad/Glad
  * 5min lappujen kirjoitusta
  * Lappujen esittely
  * Ennen asiakaspalaveria
  * [Kuva](https://drive.google.com/drive/folders/0B1wLG72sys_SM05GcEFIdVgtZkU)
  * Seurattavat laput

## Työskentely
* 2 viikon sprintit
* Tapaamisia 2-3 krt / vk
* Ma+Ti paikanpäällä, loppuviikko + vkl etänä
* Kommunikaatio
  * Trello: kommentit taskiin
  * [Slack](https://ohtu-k.slack.com/messages)
    * kanavat, integraatiot
* Pariohjelmointi/yksin
  * 10%-20% pariohjelmointi
* Tuntikirjanpito
  * [Google docs](https://docs.google.com/spreadsheets/d/180-vFs-bMMX5TbqWguWX8CcJY1d9pP2HliAgFIHWH1I/edit)
  * Excel-laskurit &rarr; Burndown jäljellä olevalla työajalle
  
## Muuta

* Tech-stack
  * Front
    * Html5 + JQuery
    * Jekyll template engine
    * .scss tyylit
    * bootstrap
    * google kirjautuminen
  * RestAPI - [hyvä artikkeli](http://softwareengineering.stackexchange.com/questions/270898/designing-a-rest-api-by-uri-vs-query-string)
  * BackendAPI [dokumentaatio](https://docs.google.com/document/d/1NivINt2Pj7I66VPD99HeDnT9LGFb32-2YCBa1Jmjv8w/edit#heading=h.yy9v1pary3ma)
  * Back
    * Docker
    * Ruby On Rails
    * Postgres
    * SQLite devauksessa
* Valinnat
  * Front: legacy
  * RoR: 4/5 osasi
  * REST kiva opetella ja sopi legacy frontin kanssa käyttöön
  * Docker käskettiin ottaamaan :D
  * GitHub muokkausmahdollisuus toive
* Asiakkaan taitotaso
  * Opiskellut ehkä sivuaineena tkt
  * Helpottanut asiakaspalavereita
  * Vapaat kädet tiimillä
