Voor dit project maak je een eigen URL shortener.
Een URL shortener is een dienst die kortere aliassen genereert voor URL's.
Dit komt bijvoorbeeld van pas wanneer je lange links wil gebruiken in een bericht met een karakterlimiet of wanneer je een URL nodig hebt die makkelijk met de hand in te geven is.
Een van de populairste voorbeelden van een URL shortener is Bitly.
Deze biedt onder andere de mogelijkheid om zelf de kortere versie van een link vast te leggen en om QR-codes te genereren.
Onze URL shortener zal in plaats daarvan pseudowillekeurige links genereren.
Hoewel we niet de schaal van Bitly voor ogen hebben, zullen we wel een aantal relatief eenvoudige, maar doeltreffende optimalisaties toevoegen.

Om dit te realiseren, zullen we verschillende concepten en libraries nodig hebben:

- het web framework Flask, zodat de gebruiker naar een site kan surfen om nieuwe aliassen te registeren, samen met Jinja om Pythoncode te scheiden van HTML en CSS
- SQLite om de geregistreerde aliassen persistent te bewaren
- function decorators om goed gebruik te maken van Flask en om memoïsatie toe te passen, een techniek die onze dienst een pak efficiënter kan maken
- random number generation om pseudowillekeurige URL’s te genereren
- logging om op te volgen dat alles naar behoren werkt en om eventuele fouten op te sporen

We zullen de shortener niet online plaatsen, maar achteraf zou je bijvoorbeeld naar localhost:5000/abcde moeten kunnen surfen en omgeleid worden naar bijvoorbeeld https://www.ap.be/sites/default/files/reglementen/AP/2022-2023/OER_22-23_Dep_def_21.12.2022.pdf.

