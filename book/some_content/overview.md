# Inleiding

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Visuele middelen toevoegen

Onder visuele middelen wordt verstaan afbeeldingen en video's. Hoe deze kunnen worden ingevoegd wordt hieronder getoond.

### Aanmaken van een afbeelding

``` {figure} /figures/FotoCrezeepolder.JPG
---
width: 75%
height: 50%
name: fig_Crezeepolder Ridderkerk
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

$$F_{res} = m.a$$                                                                    (1.1)#

Maar je kunt ook inline vergelijkingen opnemen zoals deze: $s=v_{gem}.t$
. 
## Invoegen tabel

Er zijn twee methoden om een tabel in te voegen. Die worden hieronder getoond

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
* - Niet (tijdig of met een geldige reden) afgemeld 
- Een penalty                                       
- uitsluiting              
``` 
