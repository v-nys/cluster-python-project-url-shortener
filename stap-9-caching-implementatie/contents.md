Schrijf nu een decoratorfunctie, `remember_recent_calls`, die je kan gebruiken om caching toe te voegen aan een functie waarbij je voor dezelfde input (1 argument) altijd dezelfde output zou moeten krijgen.

We wensen echter niet de volledige database in cache te bewaren, dus we zullen enkel de 5 recentst geraadpleegde aliassen cachen.
Je kan dit doen door middel van een `OrderedDict`.
Dit is bijna hetzelfde als een gewoon dictionary.
In een gewoon dictionary zijn de entries al enige tijd ook geordend, maar `OrderedDict` beschikt over de methode `popitem` waarmee je het nieuwste of laatste item kan verwijderen.

**Je decorator moet alleen werken voor functies met één argument.**

**In Flask zet je eerst je eigen decorator(s) boven een route en dan pas die voor de routering.**
