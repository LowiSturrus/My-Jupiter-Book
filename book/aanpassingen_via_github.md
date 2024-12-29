# Mijn eerste aanpassingen via gitHub

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Visuele middelen toevoegen

Onder visuele middelen wordt verstaan afbeeldingen en video's. Hoe deze kunnen worden ingevoegd wordt hieronder getoond.

### Aanmaken van een afbeelding

``` {figure} /figures/FotoCrezeepolder.JPG
---
width: 75%
height: 50%
name: fig_Crezeepolder
---
Crezeepolder Ridderkerk
``` 

### Invoegen van een YouTube-video

<div style="display: flex; justify-content: center;">
    <div style="position: relative; width: 75%; height: 0; padding-bottom: 56.25%;">
        <iframe
            src="https://www.youtube.com/embed/YDBr1Lof_mI?si=RhTC31XHv-6gL4Kl"
            style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
        ></iframe>
    </div>
</div>

## Vergelijking toevoegen

Voor de betavakken zijn wiskundige vergelijkingen essentieel. In het volgende staat een voorbeeld hoe een vergelijking kan worden ingevoegd'

$$F_{res} = m.a$$ (eq:Newton)

Waarbij naar gelabelde vergelijkingen, zoals vergelijking {eq}`eq:Newton` naar verwezen kan worden. Maar je kunt ook inline vergelijkingen opnemen zoals deze: $s=v_{gem}.t$

## Een tabel invoegen

Er zijn twee methoden om een tabel in te voegen. Die worden hieronder getoond.

### Methode 1

|Kop 1|Kop 2|Kop3|
|---|---|---|
|tekst 1|tekst 2|tekst 3|
|tekst 4|tekst 5|tekst 6|

### Methode 2

```{list-table} Overzicht van sancties bij bepaald gedrag
:header-rows: 1
:name: sancties
* - Gedrag
  - Sanctie bij 1e keer
  - Sanctie bij 2e keer
  - Sanctie bij 3e keer
* - Niet tijdig afgemeld 
  - Een penalty                                       
  - uitsluiting
  - schorsing
* - Niet of niet met een geldige reden afgemeld                                       
  - uitsluiting
  - schorsing
  - geroyeerd              
``` 

In {numref}`Tabel {number} <wiskundigebewerkingen>` zijn de notaties voor wiskunde bewerkingen opgenomen.

```{list-table} Overzicht van notaties voor wiskunde bewerkingen
:header-rows: 1
:name: wiskundigebewerkingen
* - Naam
  - Script                                      
  - Symbolen
* - wortel                                      
  - `\sqrt{4}`
  - $\sqrt{4}$
* - macht
  - `^{2x}`                                      
  - $^{2x}$
* - breuk
  - `\frac{2}{3}`                                      
  - $\frac{2}{3}$
* - subscript
  - `_{gem}`
  - $_{gem}$
* - superscript
  - `^{N}`
  - $^{N}$
* - vermenigvuldiging
  - `\cdot`
  - $\cdot$
* - afgeleide
  - `\frac{\Delta f}{\Delta t}`
  - $\frac{\Delta f}{\Delta t}$
* - integraal
  - `\int_a^b dx`
  - $\int_a^b dx$
* - sinus
  - `sin(x)`
  - $sin(x)$                         
``` 

## Referenties

De link naar een website wordt gemaakt met:
[startpage](https://www.startpage.com)

De verwijzing naar vergelijking {eq}`1.1`

De verwijzing naar {numref}`Tabel {number} <sancties>`

De verwijzing naar {numref}`Figuur {number} <fig_Crezeepolder>`



## Admolitions

Er zijn een paar voorgeprogrammeerde blokken. Dit zijn:

warning
tip
danger
note
admonition
important
Dit is een waarschuwing!

Of:

    ```{tip}
    :class: dropdown
    Je kunt een dropdown class toevoegen `:class: dropdown`. 
    ```
resulterend in:

:class: dropdown
Je kunt een dropdown class toevoegen `:class: dropdown`. 
Exercise Een speciale admonition is de exercise, deze nummert automatisch. Als je een label toevoegt kun je ook een solution maken die daaraan koppelt:

    ```{exercise} Vermenigvuldiging
    :label: ex_kleine_opdracht
    Wat is 4x2?
    ```
resulterend in:

:label: ex_kleine_opdracht
Wat is 4x2?
en het antwoord:

    ```{solution} ex_kleine_opdracht
    :class: dropdown
    4x2 = 8
    ```
resulterend in:

:class: dropdown
4x2 = 8
Om gebruik te maken van exercise moet:
- In je requirement.txt file staan: sphinx-exercise
- In je _config file staan:\
    extra_extensions:\
        - sphinx_exercise
