# Inhaltsverzeichnis

Hier wollen wir die interne Verknüpfung zu Inhalten innerhalb einer HTML-Datei üben, indem wir ein Inhaltsverzeichnis erstellen.

## Aufgaben

Verwende die bereitgestellte Datei `index.html`, um die folgenden Aufgaben zu lösen.

### Aufgabe 1

- Füge das Attribut `id` mit dem Wert **title** zum Element `<h1>` hinzu
- Füge unter dem letzten `<p>`-Element für jedes `<section>`-Element den folgenden HTML-Code hinzu:

```html
<a href="#title">Zurück nach oben</a>
```

### Aufgabe 2

- Füge allen `<h2>`- und `<h3>`-Elementen auf der Seite eine eindeutige `id` hinzu
- Benenne die `id` so aussagekräftig wie möglich
- Erstelle direkt unter dem Element `<h1>` ein Element `<h2>` mit dem Text **Inhaltsverzeichnis**

### Aufgabe 3

Unter dem neuen Element `<h2>`:

- Erstelle eine geordnete Liste `<ol>`.
- Erstelle ein `<li>`-Element für jedes `<h2>`-Element auf der Seite und für jedes `<li>`-Element:
  - Erstellen ein Ankerelement `<a>`.
  - Fülle jedes `<a>`-Element mit dem Text des `<h2>`-Elements
  - Füge das Attribut `href` mit dem richtigen Link zum Element `<h2>` hinzu – unter Verwendung der von dir erstellten ID

> Wenn auf jeden Link geklickt wird, sollte die Seite zur entsprechenden Überschrift scrollen

### Aufgabe 4

Die Überschrift **History** (dt. "Geschichte") (`<h2>`) hat auch Unterüberschriften (`<h3>`). Diese müssen ebenfalls verlinkt werden.

- Erstelle innerhalb des `<li>`-Elements für die Überschrift **History** eine neue geordnete Liste `<ol>`.
- Erstelle ein `<li>`-Element für jedes `<h3>`-Element unter der Überschrift **History**. Für jedes `<li>`-Element:
  - Erstelle ein Ankerelement `<a>`.
  - Fülle jedes `<a>`-Element mit dem Text des `<h3>`-Elements
  - Füge das Attribut `href` mit dem richtigen Link zum Element `<h3>` hinzu – unter Verwendung der von dir erstellten ID

> Wenn auf jeden Link geklickt wird, sollte die Seite zur entsprechenden Überschrift scrollen
