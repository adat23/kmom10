---
Title: Hidden
Description: This is my hidden page.
Template: hidden
Hidden: true
---
Tema
==========================

## Primärtema
Efter att jag valt att köra projektet Art-ist så gick jag in på Unsplash.com för att hitta en bild som jag ville ha som "första bild" eller den bild man direkt möts av när man når hemsidan vilket då även blev min hero bild, jag trillade relativt snabbt över den bild som visas i svartvitt på första sidan.
<a href="%base_url%/image/artist/art-ist.jpg" target="_blank">
    <picture>
        <source media="(min-width: 101px)" srcset="%base_url%/image/artist/art-ist.jpg">
        <img src="%base_url%/image/artist/artist/art-ist.jpg&w=100" alt="artist">
    </picture>
</a>
När jag väl hade hittat den föll jag direkt för färgen på kepsen som är med på bilden och valde att ha utgå från den färgen då jag tror att Art-ist(som har kepsen på sig) gillar den färgen. Kepsen fick även bli logotypen för hemsidan. 
När väl det valet var gjort använde jag adobe color för att hitta en färgpalett som matchade färgen på kepsen. 
<a href="%base_url%/image/artist/color/backtground-light.png" target="_blank">
    <picture>
        <source media="(min-width: 101px)" srcset="%base_url%/image/artist/color/backtground-light.png">
        <img src="%base_url%/image/artist/artist/color/backtground-light.png&w=100" alt="Background light">
    </picture>
</a>

## Dark-mode
Jag valde att lägga till ett darkmode där bakgrunden skulle hållas till mörkare färger för ett behagligare läsande kvällstid, där körde jag på ett svart bakgrund med röda tillägg då jag tror att art-ist uppskattar den något dämpade färgerna men att det röda sticker ut något ändå som jag tror passar honom. 
<a href="%base_url%/image/artist/color/dark-red.png" target="_blank">
    <picture>
        <source media="(min-width: 101px)" srcset="%base_url%/image/artist/color/dark-red.png">
        <img src="%base_url%/image/artist/artist/color/dark-red.png&w=100" alt="Background red">
    </picture>
</a>
Uttöver de mer dämpade färgerna ligger det även ett filter över alla bilderna som sänker ljusstyrkan på dessa för att ytterligare göra det behagligare för åskådaren när det är mörkt. Uttöver färgvalen och mörkläggning av bilderna har jag även ändrat typsnittet på text, rubriker och länkar för att få ett något annorlunda utseende. I detta temat valde jag en något kantigare font som jag tror Art-ist uppskattar ihop med dom något "enklare" färgvalen i darkmode. 
<br>Man byter tema på den lilla gitarren i footern. 

## Känsla

Känslan som Art-ist vill framföra är ett varmt välkomnande med mycket energi likt hans framträdanden. 

## Sass

Sass anpassningen som jag har gjort är att jag har lagt allt som rör primär temat eller ljust temat har jag lagt i style.scss och allt som rör det mörkare temat har jag lagt i style-dark.scss, uttöver dessa har jag fortsatt med en technology.scss där jag lagt allt som är gemensammt för dessa båda bland annat ligger responsivitet delarna i denna scss. Alla färger är plockade från variables.scss för att även hålla dessa på ett ställe, dom är uppdelade i mörka och ljusa färgvariabler.
<a href="%base_url%/image/artist/color/variables.png" target="_blank">
    <picture>
        <source media="(min-width: 101px)" srcset="%base_url%/image/artist/color/variables.png">
        <img src="%base_url%/image/artist/artist/color/variables.png&w=100" alt="Background red">
    </picture>
</a>