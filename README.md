# 🎬 Movies Project

Tento projekt vznikl jako součást **Engeto kurzu programování v JavaScriptu**.  
Cílem bylo procvičit práci s DOM, API, událostmi a validací formulářů.

---

## 🧩 Popis projektu

Projekt obsahuje dvě hlavní stránky:

### 1. **Movies (movies.html)**
Uživatel si může vybrat kategorii filmů z rozbalovacího seznamu (např. *Girl*, *Boy*, *Avengers*, *Horor*).  
Po výběru se pomocí **TVmaze API** načtou filmy a na stránce se zobrazí jejich náhledové obrázky.

Použité API:  
[`https://api.tvmaze.com/search/shows?q=`](https://api.tvmaze.com/search/shows?q=)

### 2. **Sign in (signin.html)**
Jednoduchý formulář pro přihlášení, který obsahuje:
- jméno a příjmení  
- e-mail  
- heslo a jeho potvrzení  

Při psaní hesla probíhá kontrola, zda se obě hesla shodují.  
Pole se podle výsledku zvýrazní barvou (pomocí CSS tříd `input-content-ok` a `input-content-not-ok`).

---

## 🛠️ Použité technologie

- **HTML5**  
- **CSS3** (soubor `style.css` a `query.css` pro responzivní design)  
- **JavaScript (ES6)**  
  - práce s DOM  
  - fetch API  
  - event listenery  
  - validace formuláře  

---

# 🎬 Movies Project

This project was created as part of the **Engeto JavaScript programming course**.  
The main goal was to practice working with the DOM, APIs, events, and form validation.

---

## 🧩 Project Description

The project contains two main pages:

### 1. **Movies (movies.html)**
The user can select a movie category from a dropdown menu (e.g. *Girl*, *Boy*, *Avengers*, *Horror*).  
After selecting, the app fetches data from the **TVmaze API** and displays movie posters on the page.

Used API:  
[`https://api.tvmaze.com/search/shows?q=`](https://api.tvmaze.com/search/shows?q=)

### 2. **Sign in (signin.html)**
A simple sign-in form that includes:
- first name and last name  
- email  
- password and password confirmation  

While typing the password, the form checks if both passwords match.  
The input fields are highlighted based on the result (using CSS classes `input-content-ok` and `input-content-not-ok`).

---

## 🛠️ Technologies Used

- **HTML5**  
- **CSS3** (`style.css` and `query.css` for responsive design)  
- **JavaScript (ES6)**  
  - DOM manipulation  
  - fetch API  
  - event listeners  
  - form validation  
