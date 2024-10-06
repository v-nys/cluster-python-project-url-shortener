Schrijf nu een decoratorfunctie, `log_inputs_and_exceptions`.
Deze kan je als volgt boven een functie plaatsen: `@log_inputs_and_exceptions(some_logger)`.
Dan zal `some_logger` gebruikt worden om volgende zaken van de gewrapte functie te loggen:

- de naam (kan je opvragen via `__name__`)
- alle inputs (positioneel of niet)
- eventuele fouten die niet opgevangen zijn binnen de functie zelf
