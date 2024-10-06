Je hebt misschien gemerkt dat het een behoorlijk karwei is om aan allerlei methodes logging toe te voegen.
We zouden graag met één instructie kunnen zeggen dat inputs en eventuele fouten van een handlerfunctie gelogd worden.
Er is een mogelijkheid om dit via een decorator te doen die gewoonweg aangeeft dat een functie dit soort logs bijhoudt, maar we willen wel dat we hier een andere logger kunnen instellen dan de default.
Dat betekent dat we deze decorator zullen moeten kunnen parameteriseren.
Bijvoorbeeld: `@log_inputs_and_exceptions(app.logger)` om de logger van Flask te gebruiken.
In de volgende stappen bekijken we hoe we dit kunnen realiseren.

