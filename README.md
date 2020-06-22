![Schermafbeelding 2020-06-14 om 22 04 50](https://user-images.githubusercontent.com/45489420/84602952-2274f980-ae8b-11ea-8d25-4f0100efaadc.png)

Voor onze opdracht Glory Days heb ik per week een samenvatting geschreven! Benieuwd naar een uitgebreide versie? Bekijk dan 
[hier](https://docs.google.com/document/d/1e8KzVPMDIAajii31_TKOLhqhy8-tFEEQpqsSTnobEUg/edit?usp=sharing) mijn product biografie.

## Glory Days

<details>
<summary> <b>Week 1</b> </summary>
<br>
De eerste week stond voor ons vooral in het teken van ontwerpen en het begrijpen van de (scope van de) opdracht. We hebben de debriefing geschreven en het eerste ontwerp gemaakt. We zijn ieder begonnen met schetsen en hebben hieruit de beste ontwerpkeuzes combineerd tot een prototype. Het is leuk om te zien hoe iedereen vanuit een ander perspectief naar de app kijkt! Ook als we feedback krijgen van de opdrachtgever, is het erg interessant om hun mening te horen. 

Ook hebben we natuurlijk een planning gemaakt door een project aan te maken op GitHub. Binnen dit project gebruiken we issues die we koppelen aan een lijst binnen het project! Ik wist zelf niet dat dit laatste kon.
</details>

<details>
<summary> <b>Week 2 </b></summary>
<br>
Vanaf deze week zijn we echt begonnen met het bouwen van de app. Voordat we begonnen met bouwen, heeft Marjolein ons uitgelegd hoe we het beste kunnen samenwerken binnen een repository op verschillende branches. Hierbij heeft ze ook uitgelegd hoe je te werk gaat op je terminal met Git! Erg leerzaam, maar ik heb er wel wat moeite mee aangezien het allemaal nieuwe dingen zijn. Daarom had ik nog even een tutorial gekeken waardoor ik het wat beter begreep.

Het is fijn om weer even aan de slag te gaan met alle stof die we geleerd hebben tijdens de minor. Ik merk dat er wat dingen waren weggezakt die nu weer naar boven komen. 

Ook zijn we bezig geweest met SASS voor CSS. Ik had hier al een Crash Course over geschreven voor de weekly geek, maar was ER in praktijk nog niet aan toegekomen. Fijn om te zien dat dit even makkelijk werkt in theorie als in praktijk!

Ook hebben we regels gemaakt over onze manier van coderen.. Denk aan het gebruiken van enkele of dubbele aanhalingtekens. Op advies tijdens de code reviews hebben we hiervoor ESLint gebruikt. Ik had hier nog nooit van gehoord! Maar op deze manier hanteren we "onze code syntax" als je gaat coderen. 

Tenslotte ben ik vrijdag aan de slag gegaan met een recorder. Ik heb eerst research gedaan en kwam erachter dat er een API is om media te streamen. Vervolgens heb ik een tutorial gevolgd waarbij je de user kan opnemen. Hierbij wordt de video én de audio gestreamd, opgenomen en opgeslagen. 

Kortom: een leerzame week!
</details>

<details>
<summary> <b>Week 3</b> </summary>
<br>
Deze week begon iets moeizamer: we hadden allemaal veel errors van de ESLint. Hier hebben we het over gehad en Marjolein heeft de regels aangepast zodat we minder errors hebben. 

We begonnen deze week op dinsdag en hebben eigenlijk t/m donderdag gecodeerd. Op technisch vlak zijn we opgeschoten: De Spotify API werkt en de conversational UI is ook af! 

Ik ben daarnaast verder gegaan met de microfoon recorder en heb de audio gescheiden van de video! Ik had de tutorial nog een keer bekeken waardoor ik de code beter begreep. Hierdoor ging het aanpassen van de code iets makkelijk (alhoewel het nogsteeds best complex is). Toen ik deze code wilde toevoegen aan ons prototype, deed de start button het echter niet direct: de button stond binnen een form waardoor het automatisch als submit-button werd gezien. Daardoor refreshde de pagina en deed de recorder het niet. Als je het attribuut `type` met de waarde `"button"` toevoegd, wordt het niet als een submit button gezien! Toen werkte het wel. Ook heb ik deze button aangepast naar een geanimeerde microfoon button gemaakt die goed aangeeft wanneer er gerecord wordt.

Ik had wel het idee dat er nog iets miste bij de voice recorder, dus ik heb nog een timer toegevoegd met JavaScript. Het viel mij op dat ik me hierbij wel een beetje kon focussen op Functional Programming: ik heb de functies opgesplitst en samengevoegd binnen één functie die wordt uitgevoerd als de gebruiker op de microfoon button klinkt.

Op donderdagavond hebben we nog de code van de conversational UI's samengevoegd met GIT. Hierbij heeft Marjolein me geholpen. We hebben in principe mijn branch gemerged naar de master branch. Er waren geen conflicten omdat ik alleen nieuwe code heb geschreven en geen code heb aangepast.

Op vrijdagochtend hebben we feedback van de opdrachtgever gekregen. Daarna hebben we allemaal op vraag van de opdrachtgever een UI design ontworpen en de beste ontwerpkeuzes eruit gehaald. Deze hebben we samengevoegd tot een clean digitaal prototype.

Tenslotte heb ik de Product Biografie weer bijgewerkt!</details>

<details>
<summary><b> Week 4</b> </summary>
<br>
In het begin van de week zijn we vooral bezig geweest met het verwerken van de feedback van afgelopen vrijdag. Zo heb ik samen met Marissa en Marjolein het complete design van onze app aangepast. Ook hebben we een beetje "gespeeld" met de typografieën en kleuren. 

Daarna zijn we vooral gaan coderen. Hierbij hebben we de schermen verdeeld. Ik heb hiervoor het overzicht herinneringen scherm gemaakt en het detailscherm waarbij een share button zit. Ook ben ik aan de slag gegaan met een slider, iets wat ik eigenlijk nog niet echt had gemaakt. Het was simpeler dan ik dacht, de slider kon gewoon gemaakt worden met HTML en CSS. Hierbij is het vooral belangrijk welke attributen je gebruikt en welke value je geeft.

Ook heb ik een design review gehad met Koop wat betreft de slider. Hij had nog wat tips over de interactie.

Tijdens het bouwen van de app vallen je natuurlijk ook weer details op, die ook moeten worden aangepast. Zo had ik eerst een gradient color met een opacity over een foto gedaan. Echter had dit nog een mooier effect als de foto zwart wit was. Het kwam erop neer dat je een filter over een gefilterde afbeelding doet. Maar hoe je doe je dit precies? Ik had een div element aangemaakt die als overlay werkte. Het is soms tijdens het coderen even puzzelen, maar er is bijna altijd wel een oplossing.

Tenslotte hebben we donderdagavond alles samengevoegd, zodat we vrijdagochtend een mooie prestatie konden laten zien aan onze opdrachtgever. Dit ging ons best goed af. Helaas wist ik nog niet alle GIT commands uit mijn hoofd, dus ik heb ondertussen wat aantekeningen gemaakt en in mijn notities gezet. 

Ook heb ik de tone of voice aangepast voor in onze app. Denk aan "je" i.p.v "u", of "speciaal voor Alex" i.p.v "suggesties".

Op vrijdagochtend hebben we ons prototype gepresenteerd, het zag er al als een geheel uit. Ik heb aantekeningen gemaakt tijdens onze feedbacksessie. Het begint al een geheel te worden en de opdrachtgever is erg positief over ons! 
</details>

<details>
  <summary><b> Week 5</b> </summary>
<br>
This is how you dropdown.
</details>



## Reflectie Glory Days
Ik vond het super leerzaam om te werken aan Glory Days in samenwerking met vier andere studenten. Zo had ik nog nooit een project gehad waarin je samen werkt aan de code en heb ik geleerd hoe ik samen moet werken via GIT. Daarnaast was het een interessante opdracht waarbij we voornamelijk de hoofdfunctionaliteit hebben kunnen realiseren. We hadden in de eerste week veel ideeën, maar helaas hadden we geen tijd meer om dit daadwerkelijk uit te voeren. 

Ook zijn we aan de gang gegaan met het ontwerp, waarbij we voornamelijk op een conversational UI focussen. Dit was af en toe ook een uitdaging om sommige elementen op de juiste plek te krijgen. Daarnaast had ik van tevoren een SASS Crash Course gevolgd om dit vervolgens toe te passen tijdens de meesterproef. 

Kortom: ik heb veel geleerd en kijk met trots terug op dit project!


## Learning goals per vak (criteria)
Tijdens dit project hebben we veel stof van de afgelopen maanden kunnen toepassen. Dit is wat ik voornamelijk heb geleerd / toegepast:
* Web app from scratch: Ik had bij het vak hele lange functies gemaakt die eigenlijk beter opgesplitst moesten worden in kleinere functies. Dit heb ik toegepast bij het maken van de slider en bij het maken van de timer (die bij de microfoon hoort). Kortom: functional programming is afgevinkt van mijn wishlist.

* CSS to the rescue: css is meer dan alleen stijling en kan ook interactief worden toegepast. Zo heb ik bijvoorbeeld een interactieve slider gemaakt, waarbij de label van kleur verandert op basis van de input. Ook heb ik SASS geleerd, en kwam ik erachter dat je met `mix-blend-mode` een element kan "blenden" met de parent element. Ook ben ik aan de slag gegaan met de eenheid `rem`: dit is namelijk gelijk aan de grootte van het lettertype die in de root staat van de HTML. Tenslotte kwam ik erachter dat je `calc()` makkelijk kan gebruiken om bijvoorbeeld de breedte van een element te bepalen met een simpel rekensommetje.

* Browser Technologies: progressive enhancement is erg belangrijk. De app moet voor iedereen werken. Wij hebben vanuit de core functionaliteit gewerkt. Zo heb ik fallback gemaakt voor de microfoon: `navigator.mediaDevices` wordt namelijk niet door elke browser ondersteund. Een kleine enhancement hierbij is dat als de gebruiker klikt op de microfoon, wordt er een herhalende animatie "afgespeeld" die aangeeft dat er opgenomen wordt. Ook heb ik een fallback gemaakt voor `navigator.share()`. Deze wordt heel slecht ondersteund.

* Progressive web apps: natuurlijk hebben we een progressive web app gemaakt met een service worker. Ook hebben we de code geminified zodat het criticial rendering path korter wordt. Het enige verschil hierbij is dat we tijdens de meesterproef een andere minifier hadden gebruikt dan die ik bij het vak heb toegepast.

* Web design: web design is voor ons in zekere zin heel erg belangrijk geweest. Wij hebben namelijk een app ontwikkelt voor Alzheimer patiënten. Maar dit zijn natuurlijk niet de gebruikers. Wij hebben daarom in de eerste week ook veel informatie ontvangen van de opdrachtgever (study situation). De app moest simpel, vriendelijk en duidelijk zijn voor de gebruikers. Daarnaast hebben wij niet alleen een app gemaakt <u>voor</u> de opdrachtgever maar <u>met</u> de opdrachtgever. Wij ontwerpen samen, en hebben samen een mooi resultaat neergezet.

* Real time web: helaas heb ik niet zoveel geleerd wat betreft het vak real-time web.

Ik heb ook geleerd hoe je met branches aan de slag kan binnen GitHub met GIT. Echter heb ik dit niet toegewezen aan een vak, aangezien we hier ons niet zo mee bezig hebben gehouden gedurende de minor. Om te samen te werken is dit zeker wel belangrijk.

## Wishlist
Voordat ik begon aan de meesterproef, had ik een paar learningsgoals voor mezelf opgesteld:
- [x] Met SASS werken 
- [x] Functional programming
- [ ] Aan de slag met een database
- [x] Samenwerken in GitHub

Helaas heb ik niet genoeg tijd gehad om mij verder te verdiepen in databases. 


## Bronnen
* [Git & GitHub Tutorial for Beginners #8 - Branches](https://www.youtube.com/watch?v=QV0kVNvkMxc&amp=&index=8)
* [Start using Git on the command line](https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html)
* [Capturing and Saving User Audio or Video with JavaScript](https://www.youtube.com/watch?v=K6L38xk2rkk)
