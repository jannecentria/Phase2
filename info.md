# Project Phase 2 – Basic Structure and Main Functionalities

**Kurssi:** IT00AK35-3003 Web-kehittämisen jatkokurssi – Päivätoteutus  
**Tekijät:** Janne Raappana ja Matias Nisula  
**Työskentelymuoto:** Parityö  
**Päivämäärä:** 13.4.2025

---

## Projektin kuvaus

Pelilista on yksinkertainen verkkosovellus, jossa käyttäjät voivat luoda ja selata listoja suosikkipeleistään. Kukin peli sisältää nimen, alustan, julkaisuvuoden ja kuvauksen. Sovellus toimii mobiilissa ja tietokoneella, ja siinä on käyttöliittymä, jonka kautta pelit lisätään, haetaan ja poistetaan.

---

## 1. Environment

- Paikallinen kone
- Node.js ja SQLite asennettuna
- Käytetty komentoriviä ja selainta testaukseen

---

## 2. Backend

- Node.js + Express -pohjainen palvelin
- REST API-endpointit: GET, POST, DELETE
- Palvelee JSON-muotoista dataa frontendille

---

## 3. Frontend

- HTML + CSS + JavaScript (ei frameworkia)
- Responsiivinen käyttöliittymä
- Lomakkeet pelien lisäämiseen ja listojen selaamiseen
- Hakutoiminto ja yksityiskohtien katselu

---

## 4. Database

- SQLite-pohjainen `games.db`
- Taulu `games`, jossa kentät: id, name, platform, release, description
- Data tallennetaan pysyvästi tietokantaan

---

## 5. Basic structure and architecture

- Selkeä tiedostorakenne: `frontend/`, `backend/`, `db/`
- Frontend ja backend eriytetty loogisesti
- Moduulipohjainen rakenne
- Kommentoitu ja dokumentoitu koodi

---

## 6. Functionalities

- Pelin lisääminen lomakkeella
- Pelien katselu listana
- Hakutoiminto (filtteröinti nimellä)
- Yksittäisen pelin tietojen tarkastelu
- Pelin poistaminen
- Lomakkeen piilotus/näyttö
- Dynaaminen lista frontendissä

---

## 7. Code quality and documentation

- Koodi jaettu loogisiin osiin
- Jokainen funktio kommentoitu suomeksi
- Ei turhaa koodia tai toistoa
- Yksinkertainen, mutta laajennettavissa

---

## 8. Testing and error handling

- Kaikki päätoiminnot testattu manuaalisesti
- Virheenkäsittelyä mm. tyhjissä kentissä
- Backend tarkistaa POST-pyynnön datan
- Ei kaatumisia väärällä syötteellä

---

## 9. User interface and interaction

- Yksinkertainen ja selkeä käyttöliittymä
- Toimii hyvin sekä tietokoneella että puhelimella
- Käyttäjä näkee pelit heti ja voi lisätä uusia
- Lomake on piilotettavissa → siisti näkymä
- Kaikki käyttöliittymän toiminnot helposti löydettävissä

---

