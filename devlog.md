# Programmiertagebuch

> 📘 Projekt: Scriptara: Eine Einführung in HTML, CSS & JavaScript  
> 👨‍💻 Autor: Théo Alpen (dev-theoa) 
> 🗓️ Zeitraum: 8.10.2025 – heute

---

## Tag 1 – 13.10.2025

### 🎯 Ziel des Tages

> Grundstruktur der Dateien und Codes erstellen

---

### 💻 Was ich gemacht hab

> - erstelle  GitHub Repository `dev-theoa/scriptara`
> - erstelle src & assets Ordner und organisiere Dateien
> - erstelle `index.html` mit Grundstruktur
> - erstelle `style.css`
> - erstelle `script.js`

---

### 🧠 Was ich gelernt habe

> - Grundkenntnisse im Bereich Git & GitHub

---

### ⚙️ Probleme / Herausforderungen

> - GitHub Repository erstellen
    > _Da ich keine Erfahrungen im Bereich GitHub habe, schaue ich mir Erklärvideos auf YouTube an. Es gelingt mir, die Grundkenntnisse über GitHub zu erhalten und ein GitHub Repository zu erstellen._

---

### ✅ Nächste Schritte

> - erstelle homepage in `index.html`
> - erstelle assets (logos, bilder, etc.)
> - Programmierwissen ausbauen

---

### 🖼️ Codebeispiel
_Grundstruktur der `index.html`_

```html
<!DOCTYPE html>
<html lang="en-US">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">
        <title>Scriptara</title>
    </head>
    <body>
        
        <script src="script.js"></script>
    </body>
</html>
```

---

## Tag 2 – 14.10.2025

### 🎯 Ziel des Tages

> - Navigationsleiste erstellen

---

### 💻 Was ich gemacht hab

> - erstelle Navigationsleiste mit `<nav>` in `index.html`
> - bette leere Links (`<a href="#">`) in die Navigationsleiste ein
> - CSS Kenntnisse ausbauen

---

### 🧠 Was ich gelernt habe

> - Stile von CSS Elemente mit `:hover` verändern
> - (CSS Positions & Flexboxes) _noch nicht sicher_
> - (CSS Transitions & Animationen) _noch nicht sicher_
> - (Navigationsleiste ersstellen (HTML & CSS)) _noch nicht sicher_

---

### ⚙️ Probleme / Herausforderungen

> - Erstellen einer Navigationsleiste in HTML
    > _Bisher habe ich noch nicht gelernt, wie man eine Navigationsleiste erstellt. Ich habe mir mehrere Erklärvideos auf YouTube angeschaut und verschiedene Varianten gesehen, um eine Navigationsleiste in HTML zu erstellen._
> - Verändern dies Stiles einer Navigationsleiste in CSS
    > _Aktuell fehlt es mir an Kenntnissen von CSS, um die Navigationsleiste im Stil so zu bearbeiten, wie ich es gerne hätte. Ich habe mir mehrere Videos auf YouTube angesehen und habe mir die Bereiche in CSS genauer angeschaut, die für das Erstellend der Navigationsleiste zum Vorteil wären. Darunter zählen Positionen & Flexboxen in CSS oder auch Animationen. Zudem habe ich Videos gesehen, die sich direkt mit dem erstellen einer Navigationsleiste in HTML und CSS befassen._

---

### ✅ Nächste Schritte

> - erstelle homepage in `index.html`
> - erstelle assets (logos, bilder, etc.)
> - beginne mit dem Erstellen des HTML Turoials
> - Programmierwissen ausbauen

---

### 🖼️ Codebeispiel
_Hovereffekt für Links in der Navigationsleiste in CSS_

```css
nav a {
    color: white;
    text-decoration: none;
    margin-left: 5px;
    transition: background 0.2s;
    border-radius: 7px;
    padding: 4px 5px;
}

nav a:hover {
    background: #333;
}
```

---

## Tag 3 – 20.10.2025

### 🎯 Ziel des Tages

> - Navigationsleiste erstellen

---

### 💻 Was ich gemacht hab

> - lösche alte Navigationsleiste
> - erstelle Navigationsleiste mit `<header>` in `index.html`
> - erstelle `logo` und `links` Container mit `<div>`
> - bette leere Links (`<a href="#">`) in `links` Container ein
> - übernehme `style.css` aus [Erklärvideo](https://www.youtube.com/watch?v=euG1_R2o_Bg&t=126s)

---

### 🧠 Was ich gelernt habe

> - Flexbox in CSS

---

### ⚙️ Probleme / Herausforderungen

> - Navigationsleiste in HTML & CSS
    > _Bisher habe ich noch nicht gelernt, wie man eine Navigationsleiste erstellt. Ich habe mich dazu entschlossen, die Navigationsleiste aus einem bestimmten [Erklärvideo](https://www.youtube.com/watch?v=euG1_R2o_Bg&t=126s) (Link: `https://www.youtube.com/watch?v=euG1_R2o_Bg&t=126s`) nachzuprogammieren und abzuändern. Dazu habe ich die Anweisungen, den `header` und weitere Elemente zu erstellen, befolgt und dabei versucht, Schritt für Schritt den Code zu verstehen. Durch mein gelerntes Wissen über Flexbox in CSS fiel mir dies recht leicht._

---

### ✅ Nächste Schritte

> - erstelle homepage in `index.html`
> - überarbeite Stile der Navigationsleiste in `style.css`
> - erstelle assets (logos, bilder, etc.)
> - beginne mit dem Erstellen des HTML Turoials
> - Programmierwissen ausbauen

---

### 🖼️ Codebeispiel
_`<header>` in `index.html`_

```html
<header>
    <div class="logo">Scriptara</div>
    <div class="links">
        <a href="#">HTML</a>
        <a href="#">CSS</a>
        <a href="#">JavaScript</a>
    </div>
</header>
```
