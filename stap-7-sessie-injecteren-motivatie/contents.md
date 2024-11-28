Je merkt vast dat het een karwei is om in elke handler dezelfde code te schrijven om een databasesessie te starten.
Eigenlijk is een databasesessie iets dat bijna elke handler gewoon nodig heeft, zoals zijn argumenten.
In dit soort situatie is "dependency injection" een heel handige techniek. 
FastAPI biedt hier ingebouwde ondersteuning voor.
