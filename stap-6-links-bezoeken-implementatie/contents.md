Pas nu je code aan zodat de absolute links niet meer getoond worden. In plaats daarvan ga je ze recursief bezoeken. Je geeft in elke call je `Counter` mee om het totaal aantal voorkomens van woorden over alle pagina's te tellen.

Om te voorkomen dat het te lang duurt, stop je de recursie nadat een bepaald aantal links gevolgd is vanaf de oorspronkelijke pagina. Dit aantal mag je voorlopig hardcoderen. Zet het op 1 of 2, anders gaat het erg lang duren.

Let op: twee pagina's kunnen een link naar dezelfde derde pagina bevatten. Om te vermijden dat je die pagina meermaals bezoekt, kan je best een een verzameling bijhouden met alle reeds bezochte pagina's. Ook die geef je dan mee in elke call.
