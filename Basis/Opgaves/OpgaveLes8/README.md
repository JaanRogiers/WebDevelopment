# Opgave

## HTML

- Download en pak bovenstaand zip bestand uit
- Voeg in het html bestand geen extra's, zoals een id of een class, toe. 
- Voeg in het html bestand enkel een link toe naar een extern css bestand. 
- Laat de afbeeldingen in een map images staan. 

[Download File](https://learn-eu-central-1-prod-fleet01-xythos.content.blackboardcdn.com/61d42c1e6231a/19100948?X-Blackboard-S3-Bucket=learn-eu-central-1-prod-fleet01-xythos&X-Blackboard-Expiration=1701097200000&X-Blackboard-Signature=vfvFvBoNPNTw4xNGcmcBvwG1IgY2P4m3gWM83DHW1d0%3D&X-Blackboard-Client-Id=174089&X-Blackboard-S3-Region=eu-central-1&response-cache-control=private%2C%20max-age%3D21600&response-content-disposition=attachment%3B%20filename%3D%22Opgave%20Les%208.zip%22%3B%20filename%2A%3DUTF-8%27%27Opgave%2520Les%25208.zip&response-content-type=application%2Fzip&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEsaDGV1LWNlbnRyYWwtMSJGMEQCIH9LKy5kkXRanpDct8AE8gUfwChgDIzJRVIj1EkZwuvtAiBIt800Fc8J7TvgozNi7PDte0RsZhR9Wr%2Fd2eA8DQ6NSSrHBQik%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAMaDDYzNTU2NzkyNDE4MyIMyLFe231RLobYSH1aKpsFIp8sXHtUC15Gn3UBsFNMy72YG76XLsUHmqZQG91wS9kp32OdxH7nUvZtfJnTpF9TyPA565acTmSL9y8mnGWDTdDrq%2BXLhP2OOiXZDoMrvq9zBJsI2HhQyTXbC6Dq4uTkhJdkowDJNrWdY9lcxdTnK2G%2Fy%2Bg%2F2chsPwDVlqr4Gy4C9G4dwyU0M9%2FfAlsDOLJm9VVXaApwBq%2BzFGRZUb4dXmydCX%2F%2BNkAoXskl5ErssQPZIo27MgfPCRpFCYsEkHV7CISAR0H8%2FelzUSw6Lpm3gFIJxjfjqXbdo103PCXnzELiG4qQW3%2F%2F2hSfHkEdUOiNs%2FmcWkyl1VjmN5edyGgXzSva0DvBAwYXP3B%2BbZbBdww2Mh5b3k4w8m%2FmNPko3fAToKgsW8UqHxBAL4uVZe40Z%2B7n0y78aNFxQWCAtW4g6nSAG7j46kNnOruUvRY%2BAtZzMBf%2B%2FJB3qZ2HEg7WaMRbTgwrxaPOQRuCSK5ojTmxCGOx0cuEXNYngBOTqOI2fgdtysWjnNVzbEcUgZTDdYNPe%2BykGAVv7JQwpO6twKQIJU7kHTw%2FROYWUasmN%2Bkggwm3bvNOmm1LRKtx7qyZaG9%2Bd7JAMmViXKYAyU6zoKN%2B%2FbP2lxJKRLzcDIB1oHAa9%2FdKvrL%2FdptfwnLxbK0jUH0hcVCZkCxIt7ZoAkcGYOqEID3adZ1MLm392RX%2BbPF9YFJeZ%2BZmYUBpLgUtDwKVimDqfbHB8IrDUtr%2Fg%2BrFuVrp56xLOyey767%2FqV7lEZuAdqyfPdiMMsPDf7zVsrjNwnR6Xv1VzdZlA0DQMbOU38eD32f9li5C0d%2BW%2BZeNVAaLwNCK5Z9a3ThJVel34jjj4vM2dgolvm8EwG0Dbcbg%2BscpMdJZhAXgwpamFJ1dmDCP6JGrBjqyAa2jWI%2FXALDtGFrERIx%2BnH%2F5rQWMwmX51KTQJCrZ2A%2FqJpSfAIyofyzbJIRl4RLqvUwRXKF09UDE5ePXWUTXn2oScVi4XC00z111y0LQJdJsORz6kggPXdUd7A5DJJURXOR9G1%2FgBScJ1XccVCkLD3RhuZ%2BdJHOnT%2BizqM6aykewNr%2B04rMi%2B%2BHoL68KYTQSHXruQzB4lcYC6yspcX8X8e9KWdlo5vkra0C4S6v5hFAnGiY%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231127T090000Z&X-Amz-SignedHeaders=host&X-Amz-Expires=21600&X-Amz-Credential=ASIAZH6WM4PL7LXXPNOO%2F20231127%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Signature=bc87908b023b9332f8848e686375f0359349c552aa3469ee72f53c6bb8d48d2e)

## CSS

![Screenshot_Oplossing_Les8](./README/Screenshot_Oplossing_Les8.png)

### CSS Template

Omdat we in dit bestand zelf alle margins en padding willen kunnen bepalen, vertrek je van volgende CSS template:

```css
*{

 margin: 0;

 padding: 0;

}

body {

 font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;

}

input{

 font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;

 font-size: 1em;

}
```

### De container

- De container heeft een totale breedte van 790 pixel en wordt gecentreerd op de pagina.
- Alle inhoud wordt op 10 pixel van de rand van de container getoond. (Let op! Door een padding te gebruiken, is width geen 790 pixel meer.)
- De container heeft een witte achtergrond kleur.
- Buiten de container wordt op de achtergrond de rgb-kleur 147, 162, 243 gebruikt.

### De header

- De header gebruikt de achtergrondafbeelding header.jpg en is daarom 770pixel breed en 215 pixel hoog.
- De inhoud van de header wordt op 20pixel van de rand getoond.  (Let weer op de totale breedte en de totale hoogte)
- De tekst in de header is wit.
- De hoofdtitel is 1,8 keer het standaard lettertype.
- De subtitel is 0,8 keer het standaard lettertype.

### De navigatie

- Zorg ervoor dat de navigatie boven- en onderaan 10 pixel krijgt, zodat deze niet tegen de header afbeelding of de content komt.
- De koppelingen gebruiken de rgb 147, 162, 243 achtergrondkleur. 
- De tekst is wit en vet gedrukt en vertoont geen onderlijning.
- De tekst van de koppelingen staat bovenaan en onderaan op 5 pixels van de rand en links en rechts op 10 pixels van de rand.
- Wanneer over een koppeling bewogen wordt, krijgt deze een donkerdere achtergrondkleur rgb 101, 135, 224.
- Maak de koppelingen transparant (opacity:0;}, maar wanneer over de navigatie bewogen wordt, worden de koppelingen in de navigatie terug zichtbaar (opacity:1;}.

![Screenshot_Navigatie_Les8](./README/Screenshot_Navigatie_Les8.png)

### De titel in de content

- De grootte van de titel is 1,2maal de standaard lettergrootte, ze is niet vet gedrukt, maar enkel schuin gedrukt.
- De titel is wit en krijgt een rgb 147, 162, 243 achtergrondkleur.
- De titel krijgt een 5 pixel dikke outset rgb 101, 135, 224 omlijning en er is een ruimte van 5 pixel voorzien tussen de tekst en de omlijning.
- Geef de kader rechts bovenaan een afgeronde hoek (20pixel)

### De paragrafen in de content

- Toon een 1 pixel dikke rgb 147, 162, 243 puntjeslijn onder de paragrafen.
- Voorzie boven en onder de paragrafen 10 pixel ruimte.
- Links en rechts komen de paragrafen en ook de lijn nog eens 5 pixel extra van de zijkant.

Tip: Gebruik in je browser "element inspecteren" om plaats van marges te bekijken. In de verticale richting worden marges niet opgeteld, maar wordt de grootste marge gebruikt.

### De tabel

- De tabel is 90% van de resterende breedte.
- De tabel wordt gecentreerd en staat op 20pixel van de paragrafen en van het formulier.
- De buitenrand van de tabel is een ridge 5pixel dikke rand.
- De andere lijnen van de tabel zijn 1px volle lijnen.
- De inhoud van de tabel staat op 5pixel van de randen.
- De tabel hoofdingen zijn NIET vet gedrukt, maar worden in drukletters getoond de grootte van het standaard lettertype (Tip: small-caps).
- Wanneer over een rij bewogen wordt, krijgen de cellen een grijze achtergrondkleur. Dit geldt niet voor de hoofdingen.

![Screenshot_Tabel_Les8](./README/Screenshot_Tabel_Les8.png)

### Het formulier

- De fieldset en de legend van de fieldset gebruiken een dubbele omlijning met afgeronde hoeken.
- De afstand tussen de fieldset en zijn inhoud is 10pixel.
- Voor de legend wordt enkel links en rechts een ruimte voorzien van 10pixel.
- De invoervelden en de submitknop krijgen een 3px dikke omlijning
- De tekst in de invoervelden en op de submit knop komt op 5px van de rand van het invoerveld of de knop.
- De invoervelden hebben afgeronde hoeken met een breedte van 10px en hoogte van 5px.
- De submit knop heeft afgeronde hoeken met een straal van 10px.
- De invoervelden staan op 5px van de labels en de submitknop.
- De tekst invoervelden krijgen een licht grijze achtergrondkleur.
- De submit knop krijgt een donkerdere achtergrond kleur.
- De tekst in de submit knop is vet gedrukt en begint met een hoofdletter.

### De footer

- De footer gebruikt dezelfde achtergrond afbeelding als de header, maar we krijgen enkel de onderkant van de afbeelding te zien.
- Tussen het formulier en de footer is een witruimte van 10pixel.
- De tekst wordt rechts in de footer geplaatst op 5 pixel van de rechter- en onderrand. Aan de bovenkant wordt geen ruimte voorzien. 
- De tekst is wit en vertoont geen onderlijning en heeft een lettergrootte van 0,6 keer de standaard lettergrootte.
- De tekst wordt niet schuin gedrukt.
- De koppeling rechtstreeks in de footer wordt vet gedrukt. 