# Graphisoft-ITechChallenge
Online Round Repository

--Intervallumos: azt hiszem ennek kb tudom a megoldását, de azért agyaljatok rajta ti is kicsit :D 
Amúgy van olyan részbenrendezés+input amire fizikai képtelenség, hogy 10mp alatt kiszámítható legyen a helyes válasz a megadott korlátok mellett, szóval már eleve kicsit wtf a dolog, és azt is imádom, hogy semmi info a tesztadatokról (kézzel buherált példák, random példák, intervallumszám és lekérdezésszám aránya, semmi) - egyáltalán hogyan számolják itt a pontszámot? Mert pl simán lehet, ha szarok a tesztesetek, hogy egy olyan módszer, ami teljes rendezést feltételezve dolgozik és 0 pontot szerez a részbenrendezéseken, jobb eredményt ér el, mint egy részbenrendezéseken igazoltan helyes és kvázi optimális módszer, szóval ??  :(

--Tervrajzos: NP-nehéz, szóval lehet valami heurisztikus megközelítésen érdemes gondolkodni, esetleg egy jó kezdőelrendezés + javítgatások valamilyen backtrack jellegű algoritmussal.
Kérdés: az input összterülete 4000^2 -e, és ha igen, létezik-e teljes fedés, vagy ilyesmiket egyáltalán ne tételezzünk fel, hanem bármi lehet az input?
Egyébként a feladatra "rectangle packing" kulcsszóval lehet rákeresgélni, de jó sok változata ismert és kismillió közelítő (heurisztikus) algoritmus, valamit összekalapálunk :)

-- Autópálya: NP nehéz, szóval itt is heurisztika kell -.- A célfüggvény leginkább olyan, mint egy tagonként négyzetreemelt 1-es norma, csakhogy így sokkal erősebben bünteti a nagy távolságot egy-egy koordinátapáron (a négyzetreemelés miatt); szóval én affelé gondolkodnék pl, hogy kb (vagy minimum?) K darab, egymáshoz páronként közeli várost keresni aztán behúzni közéjük az utat valahogy. De más ötletek is jöhetnek.
Itt is jó lenne tudni, hogy a városok helyzete random vagy kézzel buherált, de ezt úgysem tudjuk meg. 

-- Világításos: --
