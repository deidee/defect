# ![defect](https://deidee.com/logo.png?str=defect)

Wij hebben het liever niet, maar het komt voor dat er ergens een serverfout plaatsvindt. In zulks geval willen wij eigenlijk alle afhankelijkheden laten vallen, maar wij willen de bezoeker nog wél informeren.

Deze repository is bedoeld om eenvoudige html-pagina’s in te richten die kunnen worden gebruikt als een webserver een statuscode in de 500-reeks geeft. Deze zouden zo min mogelijk afhankelijk moeten zijn van omgevingsvariabelen.

Of een webapplicatie nu WordPress of Symfony, php of Python, Apache of NGINX draait; als andere zaken omvallen, zouden deze foutmeldingen in zoveel mogelijk gevallen overeind moeten blijven.

## Tips

- Laadt geen externe bestanden zoals stylesheets en JavaScript in.
- Maak geen gebruik van preprocessing.
- Maak geen verbinding met een database of API.
- Houdt de pagina licht (weinig resources).
- Houdt geen statistieken bij.
- Praat niet expliciet met cookies of sessies die mogelijk aanwezig zijn.
