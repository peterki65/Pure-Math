# Pure Math
# Förklaringar TOTAL — begrepp, symboler och notation
## Kumulativ referensfil

Denna fil är den **permanenta kumulativa förklaringsfilen** för hela Pure Math-spåret.

Den börjar med innehållet från **Matematik nivå 1c, V1 — Algebraiska uttryck och formler** och byggs därefter vidare genom:

- svensk gymnasiematematik,
- svensk universitetsmatematik,
- avancerad/forskarförberedande matematik,
- MIT Course 18,
- graduate mathematics och research-level notation.

## Kumulativ regel

1. Tidigare begrepp och symboler tas inte bort.
2. Nya begrepp, symboler, notationer, satser och viktiga felmönster läggs till.
3. En tidigare definition får förtydligas eller fördjupas när senare matematik kräver större stringens.
4. Om ett begrepp får en striktare betydelse senare ska grundförklaringen behållas och kompletteras med den formella versionen.
5. GitHub/VS Code-standarden är permanent:
   - inline-matematik: `$...$`
   - blockmatematik: `$$...$$`
6. LaTeX-kommandon får endast förekomma inne i matematikläge.
7. Om ett begrepp eller en symbol används i kursmaterial men saknas här är det ett materialfel som ska korrigeras.


> **Markdown-standard:** Inline-matematik använder `$...$`; blockmatematik använder `$$...$$`. Detta är kursens standard för GitHub och VS Code Markdown Preview.

---

# 1. Grundord

## matematik
Studiet av strukturer, mönster, storheter, relationer och logiska konsekvenser med hjälp av definierade begrepp och symboler.

## tal
Ett matematiskt objekt som kan representera exempelvis antal eller storlek.

## siffra
Ett skrivtecken som används för att skriva tal. I decimalsystemet är siffrorna 0–9.

Exempel:

Talet 507 består av siffrorna 5, 0 och 7.

## operation
En regel som kombinerar eller förändrar matematiska objekt.

Exempel:
- addition,
- subtraktion,
- multiplikation,
- division,
- potens.

## värde
Det numeriska resultat som ett uttryck representerar när alla variabler har fått angivna värden.

---

# 2. Uttryck

## uttryck
En matematisk konstruktion av tal, variabler och operationer.

Exempel:

$$
3x+5.
$$

## numeriskt uttryck
Ett uttryck som endast innehåller kända numeriska värden.

Exempel:

$$
3\cdot4+5.
$$

## algebraiskt uttryck
Ett uttryck som innehåller en eller flera variabler.

Exempel:

$$
3x+5.
$$

## ekvivalent uttryck
Två uttryck som ger samma värde för alla tillåtna värden på variablerna.

Exempel:

$$
3(x+4)
$$

och

$$
3x+12.
$$

---

# 3. Algebraiska byggstenar

## variabel
En symbol som representerar ett värde som kan variera eller ännu inte är bestämt.

Vanliga symboler:

$$
x,\ y,\ a,\ b,\ t.
$$

## konstant
Ett värde som hålls fast i det aktuella sammanhanget.

## term
En del av ett uttryck som på den aktuella nivån skiljs från andra delar med addition eller subtraktion.

I:

$$
4x^2-3x+7
$$

är termerna:

$$
4x^2,\quad -3x,\quad 7.
$$

## variabelterm
En term som innehåller variabel.

Exempel:

$$
5x.
$$

## konstantterm
En term som inte innehåller variabel.

Exempel:

$$
7
$$

i

$$
3x+7.
$$

## faktor
Ett matematiskt objekt som multipliceras med ett annat.

I:

$$
6x
$$

är 6 och $x$ faktorer.

I:

$$
3(x+5)
$$

är 3 och $(x+5)$ faktorer.

## koefficient
En numerisk faktor som multiplicerar en variabel eller variabeldel.

I:

$$
7x
$$

är 7 koefficient.

I:

$$
-x
$$

är koefficienten $-1$.

## monom
Ett algebraiskt uttryck som består av en enda term.

Exempel:

$$
5x^2.
$$

## binom
Ett algebraiskt uttryck med två termer.

Exempel:

$$
x+3.
$$

## polynom
Ett uttryck som byggs av termer med variabler upphöjda till icke-negativa heltalsexponenter.

Exempel:

$$
2x^2-3x+5.
$$

V1 använder ordet främst som strukturord. Full polynomteori kommer senare.

---

# 4. Lika termer

## lika termer
Termer med samma variabeldel och samma exponenter.

Exempel:

$$
3x,\quad 5x.
$$

De kan kombineras:

$$
3x+5x=8x.
$$

## termer som inte är lika

$$
3x
$$

och

$$
5x^2
$$

är inte lika termer.

De får därför inte slås ihop till exempelvis $8x^3$.

---

# 5. Räknesätt och resultatord

## addition
Operationen:

$$
a+b.
$$

Resultatet kallas summa.

## summa
Resultatet av addition eller ett uttryck vars översta struktur är addition.

## subtraktion
Operationen:

$$
a-b.
$$

Resultatet kallas differens.

## differens
Resultatet av subtraktion.

## multiplikation
Operationen:

$$
a\cdot b.
$$

Resultatet kallas produkt.

## produkt
Resultatet av multiplikation eller ett uttryck byggt som multiplikation av faktorer.

## division
Operationen:

$$
\frac ab
$$

eller i linjär text `a/b`, där $b\neq0$.

Resultatet kallas kvot.

## kvot
Resultatet av division.

---

# 6. Algebraiska lagar

## kommutativa lagen för addition

$$
a+b=b+a.
$$

Ordningen kan bytas.

## kommutativa lagen för multiplikation

$$
ab=ba.
$$

Ordningen kan bytas.

## inte kommutativ
En operation är inte kommutativ om ordningsbyte kan ändra värdet.

Exempel:

$$
7-3\neq3-7.
$$

## associativa lagen för addition

$$
(a+b)+c=a+(b+c).
$$

Grupperingen får ändras.

## associativa lagen för multiplikation

$$
(ab)c=a(bc).
$$

## distributiva lagen

$$
a(b+c)=ab+ac.
$$

Faktorn utanför parentesen multiplicerar varje term i parentesen.

Även:

$$
a(b-c)=ab-ac.
$$

## distribuera
Att använda distributiva lagen för att multiplicera in en faktor i en parentes.

Exempel:

$$
3(x+4)=3x+12.
$$

---

# 7. Förenkling och faktorisering

## förenkla
Att skriva ett uttryck i en enklare men ekvivalent form.

Exempel:

$$
3x+5x-2=8x-2.
$$

## utveckla
Att ta bort parentesstruktur genom korrekt multiplikation.

Exempel:

$$
2(x+3)=2x+6.
$$

## faktorisera
Att skriva en summa eller differens som en produkt.

Exempel:

$$
6x+12=6(x+2).
$$

## gemensam faktor
En faktor som finns i alla termer som ska faktoriseras.

Exempel:

I

$$
12x^2+18x
$$

är $6x$ en gemensam faktor.

## största användbara gemensamma faktor
Den gemensamma faktor som ger en naturligt fullständig faktorisering i det aktuella sammanhanget.

Exempel:

$$
12x^2+18x=6x(2x+3).
$$

---

# 8. Parenteser

## parentes

$$
(\ )
$$

grupperar ett uttryck.

Exempel:

$$
3(x+5)
$$

betyder att 3 multiplicerar hela uttrycket $x+5$.

## parentesdisciplin vid negativa värden
Om $x=-3$ och vi beräknar $x^2$, skriv:

$$
(-3)^2.
$$

Det visar tydligt att hela värdet $-3$ kvadreras.

---

# 9. Potensbegrepp som förekommer i V1

## potens

$$
a^n.
$$

## bas
$a$ i $a^n$.

## exponent
$n$ i $a^n$.

## kvadrat

$$
a^2.
$$

V1 använder potenser i algebraiska uttryck. Potensregler behandlas systematiskt senare i Matematik 1c.

---

# 10. Formelbegrepp

## formel
Ett matematiskt samband mellan storheter.

Exempel:

$$
v=\frac{s}{t}.
$$

## samband
En matematisk relation mellan storheter.

## storhet
Något som kan mätas eller uttryckas med ett numeriskt värde och ofta en enhet.

Exempel:
- sträcka,
- tid,
- hastighet,
- area.

## insättning
Att ersätta en variabel med ett angivet värde.

Exempel:

Om

$$
x=4
$$

i

$$
3x+2,
$$

så:

$$
3\cdot4+2=14.
$$

## lösa ut en variabel
Att skriva om en formel så att den önskade variabeln står ensam i ett led.

Exempel:

$$
s=vt
$$

kan skrivas:

$$
t=\frac{s}{v},
\qquad v\neq0.
$$

## enhet
En standardiserad storhetsangivelse.

Exempel:
- m,
- km,
- s,
- h,
- km/h,
- cm².

## härledd enhet
En enhet som byggs av andra enheter.

Exempel:

$$
\text{km/h}
$$

är sträcka per tid.

---

# 11. Ekvationsord som behövs för formelomskrivning

## ekvation
Ett matematiskt påstående att två uttryck är lika.

Exempel:

$$
3x+5=20.
$$

## vänsterled
Uttrycket till vänster om likhetstecknet.

## högerled
Uttrycket till höger om likhetstecknet.

## balansprincip
Om två led är lika får samma tillåtna operation utföras på båda leden.

Detta används när vi skriver om formler.

Full linjär ekvationslösning behandlas i V2.

---

# 12. Symboler

## $+$
Addition eller positivt tecken.

## $-$
Subtraktion eller negativt tecken.

## $\cdot$
Multiplikation.

Exempel:

$$
3\cdot x.
$$

I algebra skrivs detta ofta:

$$
3x.
$$

## $/$
Division i linjär text.

## bråkstreck

$$
\frac ab
$$

betyder $a$ dividerat med $b$.

## $=$
Lika med.

Två uttryck har samma värde.

## $\neq$
Inte lika med.

## $(\ )$
Parenteser. Grupperar matematiskt innehåll.

## $x,y,a,b,t$
Vanliga variabelsymboler. Bokstaven har ingen universell betydelse; betydelsen bestäms av sammanhanget.

## $x^2$
$x$ upphöjt till 2.

## $\pi$
Pi, förhållandet mellan en cirkels omkrets och diameter. V1 använder symbolen endast i formelexempel.

## $\text{ }$
I LaTeX används `\text{...}` för vanlig text eller enheter inne i en matematisk formel.

---

# 13. Villkor

## villkor
En begränsning som måste vara uppfylld för att ett uttryck eller en omskrivning ska vara definierad.

Exempel:

$$
t=\frac{s}{v}
$$

kräver:

$$
v\neq0.
$$

## division med noll
Division med noll är inte definierad i den vanliga reella aritmetiken.

Därför får en nämnare inte vara noll.

---

# 14. Motexempel

## motexempel
Ett enda konkret exempel som visar att ett allmänt påstående är falskt.

Falskt påstående:

$$
a(b+c)=ab+c.
$$

Välj:

$$
a=2,\quad b=3,\quad c=4.
$$

Vänster:

$$
2(3+4)=14.
$$

Höger:

$$
2\cdot3+4=10.
$$

Eftersom $14\neq10$ är påståendet falskt.

Motexempel blir mycket viktigt senare i Pure Math.

---

# 15. Vanliga fel — explicit förbjudna

## Fel A

$$
3(x+4)=3x+4.
$$

Korrekt:

$$
3(x+4)=3x+12.
$$

## Fel B

$$
2x+3x^2=5x^3.
$$

Fel eftersom termerna inte är lika.

## Fel C

$$
-3(x-4)=-3x-12.
$$

Korrekt:

$$
-3(x-4)=-3x+12.
$$

## Fel D

$$
\frac{x+4}{x}=4.
$$

Man får inte förkorta en term ur en summa.

## Fel E

Om $x=-3$:

$$
x^2=-9.
$$

Fel.

$$
x^2=(-3)^2=9.
$$

---

# 16. Källor

Skolverket:
https://syllabuswebb.skolverket.se/subject/MATE/1/pdf

Matteboken / Mattecentrum — Algebra:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra

Uttryck och variabler:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/uttryck-och-variabler

Distributiva lagen:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/distributiva-lagen

Förenkla uttryck:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/forenkla-uttryck

Faktorisering och parenteser:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/faktorisering-och-parenteser

Formler och ekvationer:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/formler-och-ekvationer

Skriva om formler:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/skriva-om-formler

---

# 17. Pre-mortem

- Begreppet "polynom" används endast orienterande i V1; formell polynomteori kommer senare.
- Potenser förekommer i uttryck innan full potenslära har behandlats. Om detta orsakar fel ska det markeras som reparationsnod.
- Likhetstecknet används här för algebraisk ekvivalens i konkreta omskrivningar; senare Pure Math kommer att skärpa logik och formell notation ytterligare.
- Om någon symbol används i huvudkursfilen men saknas här är det ett materialfel som ska korrigeras.
