---
marp: true
theme: gaia

---
<style>

</style>

# Üdvözlünk a Kir-Dev webalapok tanfolyamán!

---

# Kir-Dev

- Webfejlesztés 2001 óta
- KIR - Kollégiumi Információs Rendszer fejlesztők és üzemeltetők
- Simonyi Károly Szakkollégium tagja
- Közösség
---
# Projektjeink
- PéK - Profilok és Körök
- TanulóSCH
- SCHPincér
- InduláSCH
- GólyaKörte weboldal
---
# Mit lehet megtanulni?
- Szerveroldali technológiák
  - NodeJS
  - Ruby On Rails
  - SpringBoot
-  Kliensoldali technológiák
   -  alpok: HTML, CSS, JS
   -  haladó: ReactJS
- Üzemeltetetés
  - webszerverek konfigurálása, CI/CD, konténerizáció
---
# Hogyan tanulhatok? :rocket:
- komprehenzív ábra:
```

          /     NodeJS    \         | projektezés
webalapok - Ruby on Rails - ReactJS | workshop-ok
          | mentorálás ------------ | review rendszer

```
- gyűlések (csütörtök 20:00 - 1319)

---
<!-- Nagyvonalas áttekintés, mielőtt ráközelítünk a konkrétumokra
Cél, hogy lássák, hogy illik bele a nagy egészbe, amivel most foglalkozunk. -->
# Welcome to the web 
- webalkalmazások
- kliens-szerver model
- HTTP
- REST
---
# Webalkalmazások
- mi a celja egy webalkalmazásnak? (adat/élmény vezérelt)
- front-end
  - HTML, CSS, JS
  - keretrendszerek - React, Boostrap
- back-end 
  - webszerver NodeJS, Ruby on Rails
  - adatbázis
  - cache (Redis), async (Sidekiq), search engine (Elastic Search)
---

# Kliens-szerver model
- webszerverek szolgáltatásokat nyújtanak
- kliensek igénybe szeretnék venni ezeket
- kliens által kezdeményezett

---
# HTTP protokoll
- request - response cycle
- alkotóelemei - a fejlécek 
  - URL
  - METHOD 
  - status
  - body
- állapotmentes 
---

# URL
- url részei
- https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_URL
---

# HTTP METHODS
- Gyakoriak
  - GET
  - POST
  - PUT
  - PATCH
  - DELETE
- Egyéb
  - HEAD
  - CONNECT
  - TRACE
  - OPTIONS
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods
---

# HTTP status
- gyakran hasznalt kódok
- https://http.cat/
---

<!-- Itt ez a rengeteg METHOD és STATUS code, mire mit kell küldeni?. -->
# REpresentational State Transfer 
- röviden REST
- beveált módszerek gyűjteménye, nem szabvány
- Resourceful Routing

---
# REST alapja: a CRUD műveletek
- Create
- Read (összes/megadott erőforrás)
- Update
- Delete
- egyszerű műveletkből komplex funkciók
  - internet bank, raktár menedzsemnt alkalmazások
---

# CRUD életciklus
- new create index show edit update index destoy 
- képeket betenni
- egymásba ágyazott erőforrások /blogs/1/comments/1

---
# REST a Crud-on túl
- saját útvonalak, a konvencióknak megfelelően
  - /product/1/buy
- egyszerüsített útvonalak
  - /login
---


# REST gone wrong - minden get, fura státuszkódok
- GET /product/1/delete
  - 200/OK - body: "Something went wrong!" 
---
# Kezdetek: A kliens oldal
- HTML, CSS és JS
---
# HTML
- első verzió: 1993
  -  Tim Berners-Lee
  -  formázott dokumentumok
- napjainkban
  - interaktív alkalmazások
  - többféle böngésző és eszköz
---
# HTML 
- HyperText Markup Language
- jelölőnyelv
- alpja a tag-ek
  - tag neve, tulajdonságok (attributes), tartalom
```html
<button class="small-button">Click Me</div>
```
- a tag-ek egymásba ágyazhatók
  
```html
<div class="card">
  <h4 class="title">Lorem</h4>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
</div>

```
---
# HTML struktúra
- html
  - head
    - oldal címe
    - hivatkozások
    - meta adatok
  - body
    - oldal tartalma  

---

# CSS
- Cascading Style Sheets
  - HTML elemek stílusainak beállítása
  - szabályok = selector + deklarációk
  - Cascading - szabályok kiértékelése

---
# GIT, a programmer's best friend
- mire jó?
- alap parancsok
- tool-ok
- teljesen új világ nyílik meg
  - vercel
---
# Források, segédanyagok

---
# Köszönöm a figyelmet!

---
# Várunk titeket!
- tanfolyam utáni társasozáson
- a tanfolyam következő alkalmán jövő héten
- a gyűléseken csütörtökönként 20:00-tól a 1319-ben
- elérhetőség: kir-dev@sch.bme.hu


