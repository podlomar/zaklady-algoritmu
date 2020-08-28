Vítejte na začátku kurzu, který vás postupně krok po kroku seznámí se světem algoritmů. Algoritmy jsou důležitou součástí programování každý programátor na ně někdy narazí. Téměř každý program nebo aplikace obsahuje nějaký algoritmus i když třeba jen velmi jednoduchý. 

## Co je to algoritmus

Algoritmus je ve své podstatě postup řešení nějakého problému rozdělený do jednotlivých kroků. Nemusíme hned chodit do světa IT, abychom potkali nějaký zajímavý algoritmus. Algoritmy jsou běžnou součástí našeho každodenního života. Příkladem může být například tak jednoduchá věc, jak je vaření čaje. 

### Jak uvařit čaj za sáčku

Vaření čaje se může zdát jako banální problém. To však pouze do té doby, než se pokusíme skutečně přesně popsat, jaké kroky je třeba provést.

![Vaření čaje](assets/tea.jpg)

1. Nejprve zvolíme, jaký typ čaje chceme vařit - zelený, černý, ovocný apod.
1. Podle počtu osob odhadneme, kolik sáčků čaje potřebujeme.
1. Podle množství čaje odhadneme jaký objem vody budeme potřebovat.
1. Vodu nalejeme do varné konvice.
1. Varnou konvici nastavíme na teplotu podle typu čaje a zapneme.
1. Vybereme správnou konvici podle objemu vody.
1. Do konvice vložíme čajové sáčky.
1. Vybereme správný počet hrnků podle počtu osob
1. Jakmile konvice dovaří, zalejeme sáčky v konvici vodou
1. Počkáme stanovenou dobu podle typu čaje, aby se čaj vylouhoval.
1. Vylouhovaný čaj rozlejeme do připravených hrnků.

Už u takto jednoduchého algoritmu si můžeme všimnout několika důležitých věcí:

1. Některé kroky musíme provést ve stanoveném pořadí. Například je třeba vodu nejdříve přivést na správnou teplotu, než jí zalejeme čaj.
1. Nekteré kroky naopak můžeme provést v různém pořadí. Kdy přesně vytáhneme hrníčky ze skříně výsledek algoritmu nijak neovlivní.
1. To, kdy hrníčky ze skříně vybíráme, však ovlivní rychlost algoritmu. Pokud hrníčky ve skříni hledáme dřív, než vůbec zapneme konvici, zbytečně si tím prodlužujeme čas. 

### Algoritmy vs mozek

Náš mozek je perfektně uzpůsoben tomu vykonávat různé algoritmy. Už jako malí se učíme

1. jak si vyčistit zuby,
1. jak si zavávat boty,
1. jak si ošetřit drobné zranění,
1. jak si uvařit jídlo.

Takto jednoduché algoritmy bychom jistně dokázali snadno rozepsat do jednotlivých kroků. Našli bychom však také algoritmy, jsou tak složité, že rozepsání do jednotlivých kroků je obrovská výzva. Jedním z takových algoritmů je napříkld problém zdravení.

### Kdy zdravit a nezdravit?

## Algoritmy pro počítač

Výše uvedené příklady jsme použili jako ilustraci toho, že náš mozek vykonává spoustu algoritmů, často zcela automaticky a nevědomky. My se však nadále chceme zabývat algoritmy, které bude vykonávat počítač a které později můžeme zapsat pomocí nějakého programovacího jazyka. Ještě než se pustíme do opravdu technických detailů, pojďme si vyzkoušet sestavit algoritmy pro dva praktické problémy.

### Problém spolubydlení

Mějme následujících šest studentů, kteří společně bydlí v jednom bytě.

![Studenti](assets/roommates.jpg)

Jak často bývá zvykem, tito spolubydlící se dohodli, že některé spotřební věci budou nakupovat vždy pro všechny, aby si každý nemusal kupovat vlastní mouku, vlastní toaleťák a podobně. Po čase tedy vznikne tabulka nákupů podobné této.

<table>
  <thead>
    <tr><th>Jméno</th><th>Věc</th><th>Částka</th></tr>
  </thead>
  <tbody>
    <tr><td>Petr</td><td>Prací prášek</td><td>240 kč</td></tr>
    <tr><td>Ondra</td><td>Savo</td><td>80 kč</td></tr>
    <tr><td>Pavla</td><td>Toaleťák</td><td>65 kč</td></tr>
    <tr><td>Zuzka</td><td>Mýdlo</td><td>50 kč</td></tr>
    <tr><td>Pavla</td><td>Závěs do koupelny</td><td>350 kč</td></tr>
    <tr><td>Libor</td><td>Pivka na kolaudačku</td><td>124 kč</td></tr>
    <tr><td>Petr</td><td>Pytle na odpadky</td><td>75 kč</td></tr>
    <tr><td>Míša</td><td>Utěrky na nádobí</td><td>130 kč</td></tr>
    <tr><td>Ondra</td><td>Toaleťák</td><td>120 kč</td></tr>
    <tr><td>Míša</td><td>Pečící papír</td><td>30 kč</td></tr>
    <tr><td>Zuzka</td><td>Savo</td><td>80 kč</td></tr>
    <tr><td>Petr</td><td>Tapeta na záchod</td><td>315 kč</td></tr>
    <tr><td>Ondra</td><td>Toaleťák</td><td>64 kč</td></tr>
  </tbody>
</table>

Představme si, že naši studenti se chtějí rozestěhovat a potřebují se finančně vyrovnat. Někteří totiž přirozaně utratili za společné věci o něco víc než jiní. Váš úkol je zamyslet se nad tím, jakým postupem takového vyrovnání dosáhnout. Je zde však několik důležitých pravidel a omezení.

Samotné zpracování tabulky nebudete dělat vy, nýbrž člověk, o kterém bychom mohli říct, že je to pečlivý blbec. To znamená, že není vůbec schopen přemýšlet sám za sebe. Je pouze schopen do puntíku plnit vaše pokyny jsou-li dostatečně detailní a přímočaré. Tento náš úřednický blbec má navíc k dispozici pouze tužku, papír a kalkulačku. Kalkulačku k tomu, aby mohl spolehlivě provádět jednoduché výpočty a tužku a papír, aby si mohl poznamenávat mezivýsledky.

![Tužka, papír, kalkulačka a blbec](assets/dummy.jpg)

Počítač ve svojí nejzákladnější podstatě funguje přesně jako náš blbec. Nic za vás nevymyslí, pouze slepě vykonává postup řešení, který musíte do detailu popsat vy. Papír pak pro nás představuje pamět počítače a kalkulačka procesor.

@exercises[

- spolubydleni
  ]@

### Problém víkendového nákupu