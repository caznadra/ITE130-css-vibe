# **C**ascading **S**tyle **S**heet - CSS
---
### Syfte
Syftet med CSS är att påverka browser defult style med hjälp av ge olika taggar, id eller klasser *egenskaper*.

För att anpassa ett element med en (eller flera) egenskaper skriver du din tagg, id´t eller klassen du vill påverka, följt av klammerparenteser (måsvingar). Egenskaper skrivs mellan dina klammerparenteser. 

Notera: "." skrivs innan om det är en klass du vill påverka. 

Avsluta med ";" efter varje egenskap

Exempel på hur detta kan se ut

![Exempel på hur CSS kan skrivas](<Skärmavbild 2026-11-18 kl. 15.33.58.png>)

---
Olika sätt att styla
- Inline
- Embedded
- Linked

Inline, stilen skrivs rakt i HTML-Taggen
ex.

```
<p style="color: yellow; font-size: 10px">Ät inte gul snö!</p> 

```

##

Embedded, stilen samlas överst i HTML-dokumentet

```
<html>
<head>
 <style>
    p{
        color:blue;
        font-size: 10px;
    }
 </style>
</head>
    <body>
        <p> Alla stycken blir nu blå. </p>
    </body>
</html>

```
##

Linked, CSS är en separat fil vid sidan av din HTML fil. Länkas i din "head" del av HTML

```
<link rel="stylesheet" href="länk till mapp/fil">
````

