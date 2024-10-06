Je kan het URL shortener project verder uitbreiden.
Hier zijn enkele suggesties:

- pas security best practices toe met behulp van `flask-talisman` en `flask-seasurf` (momenteel doen we niet veel controle van de inputs)
- voeg een accountsysteem toe aan je applicatie, waarmee een user de eigen URL's kan beheren
  - er bestaan packages om een user login toe te voegen aan Flask
  - je kan ook je eigen oplossing implementeren met SQLite, waarbij je wachtwoorden hasht en saltet
- genereer naast de verkorte URL ook een QR-code
