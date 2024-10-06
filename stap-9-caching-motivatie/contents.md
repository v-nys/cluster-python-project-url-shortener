Voor een goede performantie is het vervelend dat we veel database calls uitvoeren.
Zeker met een service als de onze kan het veel efficiënter zijn te focussen op de veelgebruikte links.
We zouden een optimalisatie kunnen inbouwen in de route die aliassen omleidt naar de oorspronkelijke websites door de meest recente raadplegingen bij te houden in een soort cache.
Dit soort optimalisatie kan je echter in heel veel contexten toepassen, dus we zullen ze schrijven als decorator.
Dit zal er voor zorgen dat je ze ook kan toepassen op andere functies van één argument.
