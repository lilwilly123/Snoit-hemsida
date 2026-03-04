Snöit – Din guide till fjällen

Live-demo: https://snoit.eu

Snöit är en modern och snabb webbapplikation som samlar realtidsdata för skandinaviska skidorter på ett och samma ställe. Applikationen är byggd med fokus på användarvänlighet, prestanda och mobilanvändning, så att användare snabbt kan få aktuell information även när de befinner sig i backen.

Funktioner
Realtidsdata för snödjup

Hämtar aktuella siffror för både terräng och pist direkt från officiella källor.

Detaljerade väderprognoser

Visar temperatur och vindstyrka för både dal och topp genom integration med Open-Meteo API.

Lift- och backstatus

Ger en enkel överblick över hur många liftar och nedfarter som är öppna för tillfället.

Interaktiva pistkartor

Möjlighet att se liftarnas position direkt på kartan genom ett specialbyggt koordinatsystem.

Mobile-first design

Fullt responsiv layout optimerad med CSS Grid och Flexbox för att fungera bra på moderna smartphones.

Teknisk stack

Frontend
Vanilla JavaScript (ES6+)
HTML5
CSS3 (Grid och Flexbox)

Backend
Node.js
Express

Datahämtning
Web scraping med Fetch och Regex
REST API-integrationer

Hosting
Frontend: Vercel
Backend: Render

Installation och lokal körning

Om du vill köra projektet lokalt på din dator:

Klona repot:

git clone https://github.com/lilwilly123/snoit-hemsida.git

Gå in i projektmappen:

cd snoit-hemsida

Installera beroenden:

npm install

Starta backend-servern:

node server.js

Öppna appen:

Öppna filen index.html direkt i din webbläsare eller använd Live Server i VS Code.
