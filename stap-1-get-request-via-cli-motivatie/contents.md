Als eerste stap zullen we gewoonweg de HTML van een webpagina naar keuze opvragen. Dit vereist twee zaken:

- De capaciteit om webpagina's van uit Python op te vragen. Dit kan met Requests.
- Een command line interface. Dit kan je in principe met `sys.argv`, maar het is erg arbeidsintensief om dat goed te doen. Daarom zullen we Click gebruiken, een library die hierin gespecialiseerd is.
