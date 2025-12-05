# Programmiertagebuch

📘 Projekt: Scriptara – Eine Einführung in HTML, CSS & JavaScript
👨‍💻 Autor: Théo Alpen (dev-theoa)
🗓️ Zeitraum: 8.10.2025 – heute

⸻

# Tag 1 – 13.10.2025

## 🎯 Ziel des Tages

Die grundlegende Struktur für das Projekt anlegen und alle notwendigen Dateien erstellen.

## 💻 Was ich gemacht hab

- Ich habe ein neues GitHub-Repository namens dev-theoa/scriptara erstellt.
- Danach habe ich die Ordnerstruktur angelegt: einen src-Ordner für die Quellcodes und einen assets-Ordner für Bilder und andere Dateien.
- Anschließend habe ich eine index.html erstellt und darin die Basisstruktur eingefügt (DOCTYPE, Head, Body).
- Ich habe außerdem eine leere style.css und eine script.js Datei angelegt, damit ich später CSS-Stile und JavaScript einfügen kann.

## 🧠 Was ich gelernt habe

Ich habe die grundlegenden Funktionen von Git und GitHub verstanden, z. B. wie man ein Repository erstellt und Dateien organisiert.

## ⚙️ Probleme / Herausforderungen

- GitHub Repository erstellen
_Da ich davor kaum Erfahrung mit GitHub hatte, war es anfangs schwierig zu verstehen, wie ein Repository erstellt wird. Ich habe mehrere YouTube-Videos angeschaut und konnte dadurch nachvollziehen, wie GitHub funktioniert. Danach hat es problemlos geklappt._

## ✅ Nächste Schritte

- Die Startseite (`index.html`) mit Inhalt füllen.
- Weitere Assets wie Bilder oder Logos vorbereiten.
- Mein Programmierwissen Schritt für Schritt erweitern.

## 🖼️ Codebeispiel

Grundstruktur meiner `index.html`
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

⸻

# Tag 2 – 14.10.2025

## 🎯 Ziel des Tages

Eine funktionierende Navigationsleiste erstellen.

💻 Was ich gemacht hab

- Ich habe in der index.html eine erste Navigationsleiste mit dem <nav>-Element gebaut.
- Darin habe ich mehrere leere Links (<a href="#">) eingefügt, damit ich später Seiten verlinken kann.
- Außerdem habe ich begonnen, mich intensiver mit CSS zu beschäftigen, um die Leiste gestalten zu können.

## 🧠 Was ich gelernt habe

- Wie man mit dem :hover-Effekt das Verhalten eines Elements beim Darüberfahren verändert.
- Erste Einblicke in CSS-Positionierung und Flexbox (bin aber noch unsicher).
- Grundlagen zu CSS-Animationen und Transitions (ebenfalls noch unsicher).
- Allgemeine Grundlagen zum Aufbau einer Navigationsleiste.

## ⚙️ Probleme / Herausforderungen

- Navigationsleiste erstellen
_Da ich noch keine Erfahrung mit Navigationsleisten hatte, musste ich mir verschiedene Tutorials ansehen. Die Videos haben mir gezeigt, wie viele verschiedene Varianten es gibt._
- Styling mit CSS
_Ich habe gemerkt, dass mir viele CSS-Grundlagen noch fehlen, um die Leiste so zu gestalten, wie ich es mir vorstelle. Deshalb habe ich mir gezielt Erklärvideos angeschaut, um z. B. Flexbox, Positionierung oder Animationen besser zu verstehen._

## ✅ Nächste Schritte

- Die Startseite weiter ausbauen.
- Assets wie Logos oder Bilder hinzufügen.
- Weiter an meinen HTML- und CSS-Kenntnissen arbeiten.

## 🖼️ Codebeispiel

Hover-Effekt für die Navigationslinks
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

⸻

# Tag 3 – 20.10.2025

## 🎯 Ziel des Tages

Die Navigationsleiste verbessern und professioneller gestalten.

## 💻 Was ich gemacht hab

- Ich habe die erste Navigationsleiste gelöscht, weil sie mir nicht gefallen hat.
- Danach habe ich eine neue Leiste mithilfe eines <header>-Elements aufgebaut.
- Ich habe dafür zwei Container erstellt: einen für das Logo und einen für die Navigationslinks.
- Die Links wurden wieder mit <a href="#"> angelegt.
- Zur Orientierung habe ich den CSS-Code aus einem YouTube-Tutorial übernommen und analysiert.

## 🧠 Was ich gelernt habe

- Ich habe das Konzept von Flexbox in CSS besser verstanden (über die App Mimo).

## ⚙️ Probleme / Herausforderungen

- Neue Navigationsleiste umsetzen
_Ich wusste immer noch nicht genau, wie man eine Navigation richtig strukturiert. Deshalb habe ich beschlossen, die Variante aus dem Tutorial nachzubauen. Dabei habe ich den Code Zeile für Zeile nachvollzogen. Durch mein neues Flexbox-Wissen konnte ich vieles einfacher verstehen._

## ✅ Nächste Schritte

- Die Homepage vollständig ausarbeiten.
- Neue Assets (Logos, Bilder etc.) erstellen.
- Weiter CSS- und HTML-Wissen aufbauen.

## 🖼️ Codebeispiel

Mein neues `<header>`-Element
```html
<header>
        <div class="logo"><a href="index.html"><img src="../assets/full_transparent2.png" alt="Scriptara" /></a></div>
        <div class="links">
            <a href="#about">About</a>
            <a class="html" href="#">HTML</a>
            <a class="css" href="#">CSS</a>
            <a class="js" href="#">JavaScript</a>
        </div>
</header>
```

⸻

# Tag 4–5 – 22.10./23.10.2025

## 🎯 Ziel des Tages

- Die Homepage endgültig gestalten.
- Die Seite für verschiedene Bildschirmgrößen optimieren.

**Im heutigen Eintrag beziehe ich mich häufiger auf das [YouTube-Tutorial](https://www.youtube.com/watch?v=euG1_R2o_Bg&t=126s) (Link: `https://www.youtube.com/watch?v=euG1_R2o_Bg&t=126s`).**

## 💻 Was ich gemacht hab

- Homepage neu gestaltet
_Ich war mit dem bisherigen Design unzufrieden und habe deshalb fast alles neu aufgebaut. Einige alte `<div>`-Elemente habe ich gelöscht und stattdessen zwei neue Container erstellt: `container hero` und `container intro`. Danach habe ich mir erneut das Tutorial angesehen und verstanden, wie die Struktur dort aufgebaut ist. Dieses Wissen habe ich genutzt, um eigene Elemente einzufügen und das Layout an meine Idee anzupassen._
- Responsives Design umgesetzt
_Auf verschiedenen Geräten wurde die Seite falsch dargestellt. Die Navigation war zu breit, sodass man horizontal scrollen musste. Im Tutorial habe ich gelernt, wie man den `@media`-Operator verwendet, um für bestimmte Bildschirmbreiten eigene CSS-Regeln zu setzen. Ich habe dies ausprobiert und Elemente z. B. unter 700 px ausgeblendet. Dadurch passte sich die Seite viel besser an kleinere Geräte an._

## 🧠 Was ich gelernt habe

- Weitere Flexbox-Anwendungen (über Mimo).
- Wie man den `@media`-Operator verwendet, um Webseiten responsive zu machen.
- Einsatz von Box-Shadows und Text-Shadows in CSS.

## ⚙️ Probleme / Herausforderungen

_ Anpassung für verschiedene Bildschirmbreiten
_Die Seite sah auf kleineren Displays schlecht aus, besonders wegen der Navigation, die über den Rand hinausragte. Mit `@media only screen and (max-width: 700px)` konnte ich einzelne Elemente gezielt umgestalten oder ausblenden. Dafür habe ich den Links vorher eigene Klassen gegeben (`html`, `css`, `js`), sodass ich sie leichter ansprechen konnte. Auch im Footer habe ich ähnliche Techniken benutzt, um überflüssige Inhalte auszublenden, wenn der Bildschirm zu klein war._

## ✅ Nächste Schritte

- Weitere Assets erstellen
_z. B. ein Willkommensbild, auf dem Scriptara im Intro-Bereich winkt_
- Eine Kurs-Seite entwickeln, auf der man die verschiedenen Bereiche (HTML, CSS, JS) auswählen kann
- Weiter Programmierkenntnisse vertiefen

## 🖼️ Codebeispiel

`@media`-Operator bei unter 700px
```css
@media only screen and (max-width: 700px) {
    .container.hero .hero-left .title {
        font-size: 30px;
        text-align: center;
    }

    .container.hero .hero-right {
        display: none
    }

    .container.hero .hero-left .caption {
        font-size: 16px;
        text-align: center;
    }

    .container.hero .hero-left .links a {
        font-size: 14px;
        padding: 7px 20px;
    }

    .container.hero .hero-left .links {
        justify-content: center;
    }

    header .links a.html,
    header .links a.css,
    header .links a.js {
        display: none;
    }

    .container.intro .box .box-left img {
        width: 200px;
    }

    .container.intro .box .box-right .title {
        font-size: 30px;
    }

    footer {
        flex-direction: column;
    }
}
```
