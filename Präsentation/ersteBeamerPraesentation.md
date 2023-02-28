% Präsentation in Markdown
% Referent: Giner Dirk
% Date: \today


---
theme: "Frankfurt"
header-includes:
colortheme: "whale"
fonttheme: "structureitalicserif"
author: Dirk Giner
---

# Erste Folie
Dies ist eine mit Markdown erstellte Präsentation und übersetzt mit Pandoc in eine Beamer-Präsentation als PDF.
````bash
pandoc -t beamer <filename.mc> -o <präsentationname.pdf>
````

# Aufzählung mit Formatierung
- Punkt 1 mit *kursivem text*
- Punkt 2 mit **fettem Text**
- Punkt 3 mit ~~durchgestrichenen Text~~

# Formeln und Quoting
>**Merke**
>Markdown und Pandoc sind cool und mächtig.
>$$ \int_a \limits^\infty\frac{x²2-a}{e^{x-b}} dx $$

# Bilder einbinden

````
![Mort](mort.PNG)
````
![Mort](mort.PNG)
````
![Mort](mort-madagascar.gif)

````
![Mort](mort-madagascar.gif)