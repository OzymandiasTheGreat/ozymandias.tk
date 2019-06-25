# [macpy](https://github.com/OzymandiasTheGreat/macpy)

![stars](https://img.shields.io/github/stars/OzymandiasTheGreat/macpy.svg?style=social)
![downloads](https://img.shields.io/github/downloads/OzymandiasTheGreat/macpy/total.svg?style=social)
![installs](https://img.shields.io/pypi/dm/macpy.svg?label=Installs&style=social)

> Palaikomos platformos: <span class="platform">Linux</span>, <span class="platform">Windows</span>

[mac]ro (makro) + [py]thon, tariama kaip magpie (šarka Angliškai).

Šis paketas leidžia lengvai valdyti klaviatūra, pelę ir programų langus, kurti makro ir automatizuoti grafines sąsajas (GUI). Veikia su python versijom 2.7 ir 3.4+.
Šiuo metu macpy veikia Window ir Linux (su X ir ribotai su Wayland) operacinėse sistemose.

macpy galima rasti pypi:
```pip install macpy```

Keletas iš macpy funkcijų:
- Žemo lygio kabliai klaviatūros ir pelės įvykiam (events)
- Kablys programų langų kūrimui, uždarymui ir dėmesio (focus) pasikeitimui
- Galimybė registruoti trumpinius (hotkeys ir hotstrings)
- Klaviatūros ir pelės įvylių simuliacija
- Nuo platformos nepriklausomas klavišų ir mygtukų apibrėžimas (definition ir mapping)
- Atvirų langų surašymas
- Atvirų langų tvarkymas
- Ir dar daugiau!

<div class="warning">

> Įspėjimas:
>
> Langų tvarkymas negalimas Wayland aplinkoje.
> Taip yra dėl to, jog Wayland neturi jokio API šiom
> funkcijom ir neplanuojo jo turėti dėl saugumo sumetimų.
>
> Dar: klaviatūros ir pelės funkcijoms reikia root privielgijų Wayland aplinkoje, dėl tų pačių priežasčių.

</div>


<div class="more">

Daugiau [github puslapyje](https://github.com/OzymandiasTheGreat/macpy) arba [skaitykite dokumentacija](https://macpy.readthedocs.io/)

</div>