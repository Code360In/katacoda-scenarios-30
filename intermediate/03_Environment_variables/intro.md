## Definities en theorie

Deze course gaat over omgevingsvariabelen, of in het Engels, environment variables. Hieronder volgt eerst een uitleg over deze variabelen en waarom je ze zou moeten gebruiken. Deze informatie is gebaseerd op [dit](https://medium.com/chingu/an-introduction-to-environment-variables-and-how-to-use-them-f602f66d15fa) zeer nuttige artikel hierover.

**Omgevings variabelen**

De twee fundamentele componenten van iedere programmeertaal of sofware toepassing zijn *variabelen* en *constanten*. Zij kunnen de uitkomst van een berekening beinvloeden afhankelijk van de waarde die ze is toegekend. Het verschil tussen variabelen en constanten is dat variabelen tijdens de uitvoering van een programma kan worden aanfgepast en een constante niet.

Een omgevings variabele is een variabele waarvan de waarde buiten een programma om wordt gezet. Typisch gezien is dit een functionaliteit van een besturingssysteem zoals Windows of Linux. Een omgevingsvariabele bestaat uit een sleutel (key) en een waarde (value) paar. Hieronder staan enkele voorbeelden:

`DATABASE_HOST=localhost:3306`

`ADMIN_USERNAME=root`

Deze omgevings variabelen maken het mogelijk om configuratie van applicatie te scheiden en applicaties anders te laten functioneren op basis van de omgeving waar ze op draaien en de waarde van de variabelen die al daar gezet zijn. 

In de beginner workshop hebben we geleerd dat containers gevirtualiseerde applicatie(deeltjes) zijn. Omgevingsvariabelen zijn dus de manier om containers van variabelen te voorzien.

## Overzicht

Aan het einde van deze oefening kun je het volgende met **omgevingsvariabelen**:

* Via het `run` command aan container doorgeven
* Via een `env-file` aan een container doorgeven
* In een `Dockerfile` gebruiken
* In een `Dockerfile` (voor)definieeren 