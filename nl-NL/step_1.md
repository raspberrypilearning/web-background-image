Je kunt een achtergrondafbeelding toevoegen die achter andere elementen op jouw webpagina verschijnt.

![Een kleurrijke elektronische circuitachtergrond achter de hoofdinhoud op een webpagina.](images/background-image.png)

Zoek deze style-declaratie in 'style.css':

## --- code ---

language: CSS
filename: style.css
line_numbers: false
--------------------------------------------------------

/\* voeg een achtergrondafbeelding toe aan de hoofdtekst \*/

body {
/_background-image: url('name.jpg');_/ /\* Verwijder commentaar en wijzig de bestandsnaam om een achtergrondafbeelding toe te voegen _/
/_background-repeat: repeat;_/ /_ Laat de afbeelding herhalen _/
/_background-size: cover;_/ /_ Laat de afbeelding de hele container bedekken \*/
}

\--- /code ---

Verwijder de `/*` en `*/` commentaar-tekens en vervang `name.jpg` door de naam van je achtergrondafbeelding.

## --- code ---

language: CSS
filename: style.css
line_numbers: false
--------------------------------------------------------

/\* voeg een achtergrondafbeelding toe aan de hoofdtekst \*/

body {
background-image: url('mijnachtergrond.png'); /\* Verwijder commentaar en wijzig de bestandsnaam om een achtergrondafbeelding toe te voegen _/
/_background-repeat: repeat;_/ /_ Laat de afbeelding herhalen _/
/_background-size: cover;_/ /_ Laat de afbeelding de hele container bedekken \*/
}

\--- /code ---

Je kunt ook proberen de commentaar-tekens bij de andere eigenschappen te verwijderen.

**Tip:** Je hoeft de HTML niet bij te werken omdat deze stijl direct van toepassing is op de `<body>` tag. Je zou een klasse kunnen maken om een achtergrondafbeelding op specifieke elementen toe te passen.
