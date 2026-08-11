# Pure Math — V1
## Matematik nivå 1c — fundament: aritmetik och algebra
**Period:** måndag 10 augusti 2026 – söndag 16 augusti 2026  
**Vardagar:** 17:00–19:00  
**Lördag–söndag:** 18:00–20:00  
**Styrnivå:** Gy25, Matematik nivå 1c  
**Arbetsform:** tät teori → genomräknade exempel → egen praktik → kontrollfrågor → facit → veckogate.

---

# 0. Varför veckan ser ut så här

Matematik nivå 1c innehåller aritmetik, algebra och funktioner som centrala byggstenar. Den här första veckan går medvetet djupare i fundamenten än en vanlig snabb repetition. Syftet är att göra senare algebra, funktioner, trigonometri, analys och slutligen bevisbaserad matematik stabila.

Vi börjar därför inte med att memorera metoder. Varje moment behandlas i fyra lager:

1. **Definition:** Vad betyder objektet eller symbolen?
2. **Struktur:** Vilka regler gäller, och under vilka villkor?
3. **Exempel:** Hur används reglerna korrekt?
4. **Falsifiering:** Vilka vanliga regler ser nästan rätt ut men är fel?

## Veckans gate

Efter söndagens pass ska du utan stöd kunna:

- klassificera tal i \(\mathbb N,\mathbb Z,\mathbb Q,\mathbb R\),
- använda räkneordningen säkert,
- räkna med negativa tal och bråk,
- skilja täljare från nämnare,
- förlänga och förkorta bråk,
- använda potenslagarna med korrekta villkor,
- arbeta med kvadratrötter,
- skriva tal i grundpotensform,
- förstå variabel, konstant, term, faktor och koefficient,
- använda distributiva lagen,
- förenkla algebraiska uttryck,
- lösa linjära ekvationer med balansprincipen,
- kontrollera en lösning genom insättning,
- förklara *varför* varje steg är tillåtet.

**Gate-regel:** minst 80 % på veckotestet och inga systematiska fel på bråk, tecken eller ekvationsbalans. Vid systematiska fel repeteras just den noden innan V2.

---

# Måndag 10/8 — Talmängder, räkneordning och negativa tal
**Tid:** 17:00–19:00  
**Dagens mål:** förstå vad ett tal är i relation till en talmängd och kunna beräkna sammansatta uttryck utan teckenfel.

## 17:00–17:10 — Startdiagnostik

Räkna utan miniräknare:

1. \(7-12\)
2. \(-4+9\)
3. \(3+4\cdot5\)
4. \((3+4)\cdot5\)
5. \(18/3\cdot2\)
6. \(2^3+4\)
7. \(-3^2\)
8. \((-3)^2\)

Spara svaren. Vi återkommer till dem efter teorin.

---

## 17:10–17:35 — Teori 1: talmängder

En **mängd** är en samling objekt. När objekten är tal talar vi om en **talmängd**.

### Naturliga tal

Vi använder konventionen

\[
\mathbb N=\{0,1,2,3,\ldots\}.
\]

Exempel:

- \(0\in\mathbb N\)
- \(17\in\mathbb N\)
- \(-2\notin\mathbb N\)

Symbolen \(\in\) betyder ”tillhör”.

### Heltal

\[
\mathbb Z=\{\ldots,-3,-2,-1,0,1,2,3,\ldots\}.
\]

Alla naturliga tal är heltal:

\[
\mathbb N\subseteq\mathbb Z.
\]

### Rationella tal

Ett rationellt tal kan skrivas

\[
\frac ab,
\]

där \(a,b\in\mathbb Z\) och \(b\neq0\).

Exempel:

\[
\frac34,\qquad -\frac72,\qquad 5=\frac51,\qquad 0,125=\frac18.
\]

Alltså:

\[
\mathbb Z\subseteq\mathbb Q.
\]

### Irrationella tal

Tal som **inte** kan skrivas som kvoten av två heltal är irrationella.

Exempel:

\[
\sqrt2,\qquad \pi.
\]

### Reella tal

De rationella och irrationella talen bildar tillsammans \(\mathbb R\):

\[
\mathbb Q\subseteq\mathbb R.
\]

Hela kedjan:

\[
\mathbb N\subseteq\mathbb Z\subseteq\mathbb Q\subseteq\mathbb R.
\]

### Exempel 1 — minsta naturliga mängd

Klassificera \(-7\).

- Inte naturligt.
- Heltal.
- Därmed också rationellt, eftersom \(-7=-7/1\).
- Därmed också reellt.

Den **minsta** av våra standardmängder som innehåller \(-7\) är alltså \(\mathbb Z\).

### Exempel 2

\[
0,75=\frac34.
\]

Talet är rationellt och därmed reellt.

### Exempel 3

\[
\sqrt9=3.
\]

Trots rottecknet är talet naturligt, eftersom värdet är exakt \(3\).

### Exempel 4

\[
\sqrt5
\]

är irrationellt och reellt.

---

## 17:35–17:55 — Teori 2: räkneordning

Vi använder följande prioritet:

1. parenteser,
2. potenser och rötter,
3. multiplikation och division, från vänster till höger,
4. addition och subtraktion, från vänster till höger.

### Exempel 5

\[
3+4\cdot5=3+20=23.
\]

Inte \(35\).

### Exempel 6

\[
(3+4)\cdot5=7\cdot5=35.
\]

### Exempel 7

\[
18/3\cdot2=6\cdot2=12.
\]

Multiplikation går **inte** före division. De har samma prioritet; vi arbetar från vänster till höger.

### Exempel 8 — den klassiska teckenfällan

\[
-3^2=-(3^2)=-9.
\]

men

\[
(-3)^2=9.
\]

Parentesen ändrar vilken storhet exponenten verkar på.

---

## 17:55–18:10 — Teori 3: negativa tal

På tallinjen betyder ett större tal att vi ligger längre åt höger.

\[
-8<-3<0<4.
\]

### Addition

\[
-5+8=3.
\]

### Subtraktion

Att subtrahera ett negativt tal motsvarar att addera dess motsatta tal:

\[
7-(-3)=7+3=10.
\]

### Multiplikation och division — tecken

\[
(+)(+)=+,\quad (+)(-)=-,\quad (-)(+)=-,\quad (-)(-)=+.
\]

Exempel:

\[
(-4)(-6)=24
\]

och

\[
\frac{-24}{6}=-4.
\]

---

## 18:10–18:20 — Läsning och film

### Läsning
- Matteboken — Talmängder:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/aritmetik/talmangder
- Matteboken — Räkneordning:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/aritmetik/rakneordning

### Film
- Mattecentrum — Skillnaden mellan rationella och irrationella tal:  
  https://www.youtube.com/watch?v=1cYrV_o2f_Y

**Läs-/filmfråga:** Varför är varje heltal rationellt?

---

## 18:20–18:50 — Praktik

Beräkna och skriv minst ett mellanled.

1. \(-12+7\)
2. \(14-(-9)\)
3. \((-3)\cdot7\)
4. \((-4)(-8)\)
5. \(4+3\cdot6\)
6. \((4+3)\cdot6\)
7. \(24/6\cdot3\)
8. \(2^4-3\cdot5\)
9. \(-2^4\)
10. \((-2)^4\)
11. \(18-(5+2\cdot4)\)
12. \(6+18/(3\cdot2)\)

Klassificera med minsta standardtalmängd:

13. \(8\)
14. \(-13\)
15. \(2/9\)
16. \(0,4\)
17. \(\sqrt{16}\)
18. \(\sqrt{7}\)

### Felsökning

Förklara exakt vad som är fel:

A. \(3+4\cdot5=7\cdot5=35\)  
B. \(-4^2=16\)  
C. \(\frac10=0\)

---

## 18:50–19:00 — Exit ticket

Utan anteckningar:

1. Skriv inklusionskedjan för \(\mathbb N,\mathbb Z,\mathbb Q,\mathbb R\).
2. Förklara skillnaden mellan \(-5^2\) och \((-5)^2\).
3. Varför är division med noll inte tillåten?

### Facit

Diagnostik: \(-5,5,23,35,12,12,-9,9\).

Praktik:  
1 \(-5\), 2 \(23\), 3 \(-21\), 4 \(32\), 5 \(22\), 6 \(42\), 7 \(12\), 8 \(1\), 9 \(-16\), 10 \(16\), 11 \(5\), 12 \(9\).  
13 \(\mathbb N\), 14 \(\mathbb Z\), 15 \(\mathbb Q\), 16 \(\mathbb Q\), 17 \(\mathbb N\), 18 irrationellt/reellt.

---

# Tisdag 11/8 — Bråk, förhållanden och proportionalitet
**Tid:** 17:00–19:00  
**Dagens mål:** göra bråkräkning mekaniskt säker och förstå varför reglerna fungerar.

## 17:00–17:10 — Retrieval

1. Vad betyder \(\mathbb Q\)?
2. Varför får nämnaren inte vara noll?
3. Beräkna \(1/2+1/3\) utan miniräknare.

---

## 17:10–17:35 — Teori 1: bråkets struktur

Ett bråk

\[
\frac ab
\]

har **täljare** \(a\) och **nämnare** \(b\).

Bråkstrecket betyder division:

\[
\frac ab=a/b.
\]

### Ekvivalenta bråk

\[
\frac12=\frac24=\frac{50}{100}.
\]

Vi får multiplicera täljare och nämnare med samma icke-nolltal:

\[
\frac ab=\frac{ak}{bk},\qquad k\neq0.
\]

Detta kallas **förlängning**.

Motsatt operation är **förkortning**.

### Exempel 1

\[
\frac{18}{24}
=
\frac{18/6}{24/6}
=
\frac34.
\]

### Addition och subtraktion

Bråk måste ha gemensam nämnare.

\[
\frac13+\frac14
=
\frac4{12}+\frac3{12}
=
\frac7{12}.
\]

Varför? Vi kan bara addera lika stora delar direkt.

### Exempel 2

\[
\frac56-\frac14
=
\frac{10}{12}-\frac3{12}
=
\frac7{12}.
\]

---

## 17:35–17:55 — Teori 2: multiplikation och division av bråk

### Multiplikation

\[
\frac ab\cdot\frac cd
=
\frac{ac}{bd}.
\]

Exempel:

\[
\frac23\cdot\frac58=\frac{10}{24}=\frac5{12}.
\]

### Division

Division med ett icke-nolltal motsvarar multiplikation med dess **reciproka tal**:

\[
\frac ab\div\frac cd
=
\frac ab\cdot\frac dc.
\]

Exempel:

\[
\frac34\div\frac25
=
\frac34\cdot\frac52
=
\frac{15}{8}.
\]

---

## 17:55–18:10 — Teori 3: förhållande och proportionalitet

Ett **förhållande** jämför två storheter.

\[
3:5
\]

kan läsas ”tre till fem” och kan skrivas \(3/5\).

Två kvoter bildar en **proportion** om

\[
\frac ab=\frac cd.
\]

Då, för icke-nollnämnare,

\[
ad=bc.
\]

### Exempel 3

Om 4 kg kostar 120 kr är enhetspriset

\[
120/4=30\text{ kr/kg}.
\]

7 kg kostar då

\[
7\cdot30=210\text{ kr}.
\]

### Exempel 4 — skala

Skala \(1:50\) betyder att 1 längdenhet på ritningen motsvarar 50 av samma längdenhet i verkligheten.

8 cm på ritningen:

\[
8\cdot50=400\text{ cm}=4\text{ m}.
\]

---

## 18:10–18:20 — Läsning och film

### Läsning
- Tal i bråkform:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/aritmetik/tal-i-brakform
- Aritmetiköversikt och övningar:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/aritmetik

### Film
- Rationella tal — förlänga och förkorta:  
  https://www.youtube.com/watch?v=8sjpWTkDlJY
- Proportionalitet:  
  https://www.youtube.com/watch?v=gf1QjzUv4ng

---

## 18:20–18:50 — Praktik

1. Förkorta \(24/36\).
2. Förläng \(3/7\) till nämnaren 35.
3. \(2/5+1/10\)
4. \(7/8-1/6\)
5. \(3/4\cdot8/9\)
6. \(5/12\div10/9\)
7. \(2-\frac35\)
8. \(\frac12+\frac13+\frac16\)
9. Vilket är störst: \(5/8\) eller \(7/12\)?
10. 5 kg kostar 145 kr. Bestäm kr/kg.
11. Vad kostar 8 kg vid samma proportionella pris?
12. Skala \(1:200\): 7,5 cm på ritningen. Verklig längd?
13. En blandning har förhållandet koncentrat:vattnen \(1:4\). Hur mycket koncentrat behövs till totalt 15 liter?
14. Förklara varför \(\frac{a+b}{a}\neq b\) i allmänhet.
15. Ge ett motexempel till \(\frac ab+\frac cd=\frac{a+c}{b+d}\).

### Facit

1 \(2/3\)  
2 \(15/35\)  
3 \(1/2\)  
4 \(17/24\)  
5 \(2/3\)  
6 \(3/8\)  
7 \(7/5\)  
8 \(1\)  
9 \(5/8\)  
10 \(29\) kr/kg  
11 \(232\) kr  
12 \(1500\) cm \(=15\) m  
13 \(3\) liter koncentrat  
14 och 15 kräver förklaring/motexempel, inte bara numeriskt svar.

---

# Onsdag 12/8 — Potenser, rötter och grundpotensform
**Tid:** 17:00–19:00  
**Dagens mål:** förstå potensnotation och kunna härleda potenslagarna från upprepad multiplikation.

## 17:00–17:10 — Retrieval

Förenkla:

1. \(2\cdot2\cdot2\cdot2\)
2. \(3^2\cdot3^4\)
3. \(\sqrt{49}\)

---

## 17:10–17:35 — Teori 1: potensbegreppet

\[
a^n
\]

har **bas** \(a\) och **exponent** \(n\).

För positivt heltal \(n\):

\[
a^n=\underbrace{a\cdot a\cdots a}_{n\text{ faktorer}}.
\]

Exempel:

\[
2^5=2\cdot2\cdot2\cdot2\cdot2=32.
\]

### Potenslag 1 — samma bas, multiplikation

\[
a^m a^n=a^{m+n}.
\]

Härledning:

\[
a^m a^n
\]

innehåller totalt \(m+n\) faktorer \(a\).

### Potenslag 2 — samma bas, division

För \(a\neq0\):

\[
\frac{a^m}{a^n}=a^{m-n}.
\]

### Potenslag 3 — potens av potens

\[
(a^m)^n=a^{mn}.
\]

### Potens av produkt

\[
(ab)^n=a^n b^n.
\]

### Nollte exponenten

För \(a\neq0\):

\[
a^0=1.
\]

Det följer av

\[
\frac{a^m}{a^m}=1=a^{m-m}=a^0.
\]

---

## 17:35–17:55 — Negativa exponenter och rötter

För \(a\neq0\):

\[
a^{-n}=\frac1{a^n}.
\]

Exempel:

\[
2^{-3}=\frac1{2^3}=\frac18.
\]

### Kvadratrot

\[
\sqrt a
\]

betecknar den icke-negativa kvadratrot vars kvadrat är \(a\), för \(a\ge0\) i de reella talen.

Exempel:

\[
\sqrt{36}=6.
\]

Observera:

\[
x^2=36
\]

har två lösningar,

\[
x=6\quad\text{eller}\quad x=-6,
\]

men själva symbolen \(\sqrt{36}\) betyder \(6\).

### Exempel 1

\[
\sqrt{\frac{25}{64}}=\frac58.
\]

### Exempel 2

\[
\sqrt{2^6}=\sqrt{64}=8.
\]

---

## 17:55–18:10 — Grundpotensform

Ett tal i grundpotensform skrivs

\[
a\cdot10^n
\]

där

\[
1\le |a|<10.
\]

Exempel:

\[
4500000=4,5\cdot10^6.
\]

\[
0,00072=7,2\cdot10^{-4}.
\]

### Multiplikation

\[
(3\cdot10^4)(2\cdot10^5)
=
6\cdot10^9.
\]

---

## 18:10–18:20 — Läsning och film

### Läsning
- Potenser:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/aritmetik/potenser
- Kvadratrötter och andra rötter:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/aritmetik/kvadratrotter-och-andra-rotter
- Grundpotensform:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/aritmetik/grundpotensform

### Film
- Potenser och potenslagar:  
  https://www.youtube.com/watch?v=UsNjDFnH2IU
- Introduktion till kvadratrötter:  
  https://www.youtube.com/watch?v=3wzylO0IHMk

---

## 18:20–18:50 — Praktik

Förenkla utan miniräknare när det är rimligt:

1. \(2^3\cdot2^5\)
2. \(7^9/7^4\)
3. \((3^2)^4\)
4. \((2x)^3\)
5. \(5^0\)
6. \(10^{-3}\)
7. \(3^{-2}\)
8. \(\sqrt{81}\)
9. \(\sqrt{121/144}\)
10. Skriv \(62000000\) i grundpotensform.
11. Skriv \(0,0000054\) i grundpotensform.
12. \((4\cdot10^6)(3\cdot10^{-2})\)
13. Förklara varför \(2^3+2^4\neq2^7\).
14. Är \(\sqrt{a+b}=\sqrt a+\sqrt b\) en lag? Testa \(a=9,b=16\).
15. Förklara skillnaden mellan \((-2)^4\) och \(-2^4\).

### Facit

1 \(2^8=256\)  
2 \(7^5\)  
3 \(3^8\)  
4 \(8x^3\)  
5 \(1\)  
6 \(0,001\)  
7 \(1/9\)  
8 \(9\)  
9 \(11/12\)  
10 \(6,2\cdot10^7\)  
11 \(5,4\cdot10^{-6}\)  
12 \(1,2\cdot10^5\)  
13 exponentlagen gäller multiplikation, inte addition  
14 nej; \(5\neq3+4\)  
15 \(16\) respektive \(-16\).

---

# Torsdag 13/8 — Algebraiska uttryck och distributiva lagen
**Tid:** 17:00–19:00  
**Dagens mål:** läsa algebra som ett språk och förenkla uttryck utan att göra otillåtna operationer.

## 17:00–17:10 — Retrieval

1. Vad är skillnaden mellan \(2^3+2^4\) och \(2^3\cdot2^4\)?
2. Vad betyder en faktor?
3. Vad är värdet av \(3x+2\) om \(x=5\)?

---

## 17:10–17:35 — Teori 1: uttryckets byggstenar

Ett **algebraiskt uttryck** innehåller tal, variabler och operationer men inget krav på att två sidor ska vara lika.

Exempel:

\[
3x+5.
\]

Här är:

- \(x\): variabel,
- \(3\): koefficient till \(x\),
- \(3x\) och \(5\): termer,
- \(5\): konstant term.

### Term kontra faktor

I

\[
3x+5
\]

är \(3x\) en term.

I termen \(3x\) är \(3\) och \(x\) faktorer.

### Lika termer

\[
3x+5x=8x.
\]

Men

\[
3x+5x^2
\]

kan inte slås ihop till en enda term, eftersom variabeldelarna skiljer sig.

### Exempel 1

\[
4a+3-2a+7
=
2a+10.
\]

### Exempel 2

\[
5x^2+2x-3x^2+x
=
2x^2+3x.
\]

---

## 17:35–18:00 — Distributiva lagen

\[
a(b+c)=ab+ac.
\]

Detta är en av algebrans centrala strukturlagar.

### Exempel 3

\[
3(x+4)=3x+12.
\]

### Exempel 4

\[
-2(3x-5)=-6x+10.
\]

Det negativa tecknet följer med multipliceringen av **båda** termerna.

### Exempel 5 — två parenteser i följd

\[
4(x+2)-3(x-1)
=
4x+8-3x+3
=
x+11.
\]

### Faktorisering som omvänd distribution

\[
6x+12=6(x+2).
\]

Vi bryter ut den gemensamma faktorn \(6\).

### Varför man inte får ”stryka termer”

I

\[
\frac{x+2}{x}
\]

kan \(x\) inte förkortas bort, eftersom täljaren är en **summa**. Förkortning gäller gemensamma faktorer:

\[
\frac{x(x+2)}{x}=x+2,\qquad x\neq0.
\]

---

## 18:00–18:15 — Läsning och film

### Läsning
- Uttryck och variabler:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/uttryck-och-variabler
- Distributiva lagen:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/distributiva-lagen
- Förenkla uttryck:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/forenkla-uttryck

### Film
- Algebra och algebraiska uttryck:  
  https://www.youtube.com/watch?v=Eb_pEDdbwfs
- Förenkla uttryck:  
  https://www.youtube.com/watch?v=7QuOz6i_kSA

---

## 18:15–18:50 — Praktik

Förenkla:

1. \(3x+7x\)
2. \(5a+4-2a+8\)
3. \(6x^2+3x-2x^2+x\)
4. \(4(x+3)\)
5. \(-3(x-5)\)
6. \(2(3x+1)+4x\)
7. \(5(x-2)-2(x+3)\)
8. \(3(2a-4)-2(a+5)\)
9. Faktorisera \(8x+16\).
10. Faktorisera \(15a-10\).
11. Beräkna \(2x^2-3x+4\) för \(x=-2\).
12. Förklara felet: \(3(x+4)=3x+4\).
13. Förklara felet: \(2x+3x^2=5x^3\).
14. Förklara varför \((a+b)^2\neq a^2+b^2\) i allmänhet genom att testa \(a=b=1\).

### Facit

1 \(10x\)  
2 \(3a+12\)  
3 \(4x^2+4x\)  
4 \(4x+12\)  
5 \(-3x+15\)  
6 \(10x+2\)  
7 \(3x-16\)  
8 \(4a-22\)  
9 \(8(x+2)\)  
10 \(5(3a-2)\)  
11 \(18\)  
12–14: kräver full förklaring.

---

# Fredag 14/8 — Linjära ekvationer och balansprincipen
**Tid:** 17:00–19:00  
**Dagens mål:** förstå en ekvation som ett sanningsvillkor och lösa den genom ekvivalenta transformationer.

## 17:00–17:10 — Retrieval

Förenkla:

1. \(3(x+2)-x\)
2. \(5a-2(a-4)\)

---

## 17:10–17:35 — Teori 1: uttryck är inte ekvation

Ett uttryck:

\[
3x+5
\]

har inget sanningsvärde i sig.

En ekvation:

\[
3x+5=20
\]

påstår att två uttryck är lika.

En **lösning** är ett värde på variabeln som gör påståendet sant.

### Vänsterled och högerled

I

\[
3x+5=20
\]

är \(3x+5\) vänsterled och \(20\) högerled.

### Balansprincipen

Om

\[
A=B
\]

får vi utföra samma tillåtna operation på båda leden.

Exempel:

\[
3x+5=20
\]

subtrahera 5:

\[
3x=15
\]

dividera med 3:

\[
x=5.
\]

Kontroll:

\[
3\cdot5+5=20.
\]

---

## 17:35–18:00 — Flera steg och parenteser

### Exempel 1

\[
5x-7=2x+8.
\]

Subtrahera \(2x\):

\[
3x-7=8.
\]

Addera 7:

\[
3x=15.
\]

Dividera med 3:

\[
x=5.
\]

### Exempel 2

\[
2(x+3)=14.
\]

Antingen dividera med 2 först:

\[
x+3=7
\]

så att

\[
x=4,
\]

eller distribuera:

\[
2x+6=14,
\]

vilket ger samma lösning.

### Exempel 3 — bråk

\[
\frac{x}{3}+2=7.
\]

Subtrahera 2:

\[
\frac{x}{3}=5.
\]

Multiplicera båda led med 3:

\[
x=15.
\]

### Exempel 4 — identitet eller motsägelse

\[
2(x+1)=2x+2
\]

blir efter förenkling

\[
2x+2=2x+2.
\]

Alla reella \(x\) fungerar.

Men

\[
2(x+1)=2x+5
\]

ger

\[
2=5,
\]

vilket är falskt. Ingen lösning finns.

---

## 18:00–18:15 — Läsning och film

### Läsning
- Ekvationslösning:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/ekvationslosning
- Algebraöversikt:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra

### Film
- Ekvationslösning — steg för steg:  
  https://www.youtube.com/watch?v=54Gn9o-SAS0

---

## 18:15–18:50 — Praktik

Lös och kontrollera:

1. \(x+7=19\)
2. \(4x=28\)
3. \(3x-5=16\)
4. \(7-2x=15\)
5. \(5x+3=2x+18\)
6. \(4(x+2)=24\)
7. \(3(x-5)+2=11\)
8. \(x/5+7=10\)
9. \(2x/3=8\)
10. \(2(x+3)=2x+6\)
11. \(5(x-1)=5x+3\)
12. Skriv en ekvation: ”Tre gånger ett tal plus 4 är 25.”
13. Lös din ekvation i 12.
14. Ett abonnemang kostar 99 kr fast plus 25 kr per GB. En faktura är 224 kr. Hur många GB användes?

### Facit

1 \(12\)  
2 \(7\)  
3 \(7\)  
4 \(-4\)  
5 \(5\)  
6 \(4\)  
7 \(8\)  
8 \(15\)  
9 \(12\)  
10 alla reella tal  
11 ingen lösning  
12 \(3x+4=25\)  
13 \(x=7\)  
14 \(5\) GB.

---

# Lördag 15/8 — Konsolidering, felanalys och mixed practice
**Tid:** 18:00–20:00  
**Dagens mål:** koppla ihop veckans områden och upptäcka felmönster.

## 18:00–18:20 — Verifierad läsning

Läs sammanhängande:

- Aritmetiköversikt:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/aritmetik
- Algebraöversikt:  
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra

Markera ord du inte själv kan definiera utan att titta. Slå upp dem i `PureMath_V1_Forklaringar_Begrepp_Symboler.md`.

## 18:20–18:40 — Film

Välj relevanta delar av:

- Matematik 1b/1c — Aritmetik, spellista:  
  https://www.youtube.com/playlist?list=PLP4eRIdf14WRafOqXK1Rq7VJcnaTPHcV1
- Algebra — Matematik 1, spellista:  
  https://www.youtube.com/playlist?list=PLshJtXCW6HtX1avg3e6UgSrog8UHtxxCK

**Aktiv filmregel:** pausa före varje färdig uträkning och gör nästa steg själv.

---

## 18:40–19:20 — Mixed practice

1. \(-3^2+(-3)^2\)
2. \(2+3(4-7)\)
3. \(5/6-2/9\)
4. \(3/5\div9/10\)
5. \(2^7/2^3\)
6. \((5^2)^3\)
7. \(4^{-2}\)
8. \(\sqrt{196}\)
9. Skriv \(0,000081\) i grundpotensform.
10. Förenkla \(4x+3-2x+8\).
11. Förenkla \(3(2x-5)-2(x+4)\).
12. Faktorisera \(12x+18\).
13. Lös \(4x-9=19\).
14. Lös \(3(x+2)=2x+11\).
15. Lös \(5(x-2)=5x-10\).
16. Lös \(2(x+1)=2x+7\).
17. Klassificera \(-11/4\).
18. Klassificera \(\sqrt{25}\).
19. Förklara varför \(a^m+a^n\) inte normalt kan ersättas med \(a^{m+n}\).
20. Förklara varför balansprincipen bevarar lösningsmängden när samma tal adderas i båda leden.

---

## 19:20–19:45 — Felanalys

För varje påstående: **rätt/fel, motivering, korrigerad version.**

A.

\[
\frac12+\frac13=\frac25
\]

B.

\[
(-2)^3=8
\]

C.

\[
(2x)^3=2x^3
\]

D.

\[
3(x-4)=3x-4
\]

E.

\[
5x+2=17\Rightarrow5x=15\Rightarrow x=3
\]

F.

\[
x/0=0.
\]

G.

\[
\sqrt{49}=\pm7.
\]

H.

\[
x^2=49\Rightarrow x=\pm7.
\]

Observera särskilt skillnaden mellan G och H.

---

## 19:45–20:00 — Facit och egen felprofil

Mixed practice:  
1 \(0\)  
2 \(-7\)  
3 \(11/18\)  
4 \(2/3\)  
5 \(16\)  
6 \(5^6\)  
7 \(1/16\)  
8 \(14\)  
9 \(8,1\cdot10^{-5}\)  
10 \(2x+11\)  
11 \(4x-23\)  
12 \(6(2x+3)\)  
13 \(7\)  
14 \(5\)  
15 alla reella tal  
16 ingen lösning  
17 \(\mathbb Q\)  
18 \(\mathbb N\)

Skriv därefter tre rubriker:

- **Säkert**
- **Osäkert**
- **Fel jag upprepar**

Minst ett konkret exempel under varje rubrik.

---

# Söndag 16/8 — Veckogate 1
**Tid:** 18:00–20:00  
**Dagens mål:** testa om fundamentet håller utan stöd.

## 18:00–18:15 — Kort repetition

Läs endast dina egna fel från lördagen. Ingen ny teori.

## 18:15–19:15 — Gate-test
**Ingen bok, ingen webbsökning, ingen miniräknare om den inte uttryckligen behövs.**

### Del A — Begrepp, 10 p

1. Definiera rationellt tal.  
2. Vad betyder \(\in\)?  
3. Vad betyder \(\subseteq\)?  
4. Förklara täljare och nämnare.  
5. Vad är en exponent?  
6. Vad är en koefficient?  
7. Vad är skillnaden mellan term och faktor?  
8. Skriv distributiva lagen symboliskt.  
9. Vad är en lösning till en ekvation?  
10. Vad innebär balansprincipen?

### Del B — Beräkning, 12 p

11. \(5-3(2-7)\)  
12. \(-4^2+(-4)^2\)  
13. \(7/12+5/18\)  
14. \(5/6\div15/8\)  
15. \(3^4\cdot3^2/3^3\)  
16. \(2^{-4}\)  
17. \(\sqrt{225}\)  
18. Skriv \(0,000034\) i grundpotensform.  
19. Förenkla \(7x+3-4x+9\).  
20. Förenkla \(4(2x-3)-3(x+5)\).  
21. Lös \(5x-7=3x+11\).  
22. Lös \(3(x+4)=3x+12\).

### Del C — Resonemang, 8 p

23. Varför är \(0,125\) rationellt?  
24. Ge ett motexempel till \(\sqrt{a+b}=\sqrt a+\sqrt b\).  
25. Varför är \((-3)^2\neq-3^2\)?  
26. Varför får man inte förkorta \(x\) i \((x+5)/x\)?  
27. Förklara varför \(a^m a^n=a^{m+n}\) för positiva heltalsexponenter.  
28. Avgör om \(2(x+1)=2x+2\) har noll, en eller oändligt många lösningar. Motivera.  
29. Avgör om \(2(x+1)=2x+5\) har noll, en eller oändligt många lösningar. Motivera.  
30. Skriv ett eget felaktigt algebraiskt påstående och falsifiera det med ett numeriskt motexempel.

---

## 19:15–19:35 — Facit och bedömning

Del B:

11 \(20\)  
12 \(0\)  
13 \(31/36\)  
14 \(4/9\)  
15 \(3^3=27\)  
16 \(1/16\)  
17 \(15\)  
18 \(3,4\cdot10^{-5}\)  
19 \(3x+12\)  
20 \(5x-27\)  
21 \(x=9\)  
22 alla reella \(x\)

### Poänggräns

- **24–30 p:** Gate godkänd, förutsatt att inga systematiska grundfel finns.
- **20–23 p:** nästan; gör riktad repetition och nytt mini-test.
- **0–19 p:** fundamentet är inte stabilt ännu; repetera berörda noder.

**Viktigare än totalpoängen:** ett återkommande fel på exempelvis nämnare, tecken eller distributiva lagen blockerar progression även om totalpoängen råkar vara hög.

---

## 19:35–19:50 — Film/repetition

Se endast den film som matchar största felområdet:

- Potenser: https://www.youtube.com/watch?v=UsNjDFnH2IU
- Algebraiska uttryck: https://www.youtube.com/watch?v=Eb_pEDdbwfs
- Ekvationer: https://www.youtube.com/watch?v=54Gn9o-SAS0

Skriv tre egna exempel direkt efter filmen.

---

## 19:50–20:00 — Veckologg

Skriv:

1. Vilket begrepp kan jag nu förklara bättre än i måndags?
2. Vilken symbol kan jag fortfarande misstolka?
3. Vilket fel gjorde jag mer än en gång?
4. Kan jag härleda potenslagen för multiplikation?
5. Kan jag förklara balansprincipen utan att säga ”flytta över och byt tecken”?

**Viktig språkregel:** ”flytta över och byt tecken” används inte som grundförklaring. Den säkra modellen är att samma tillåtna operation görs på båda leden.

---

# Reality check — V1

V1 är korrekt genomförd endast om du faktiskt kan göra följande från tomt papper:

- skriva \(\mathbb N\subseteq\mathbb Z\subseteq\mathbb Q\subseteq\mathbb R\),
- förklara varför \(b\neq0\) i \(a/b\),
- visa ett korrekt bråkexempel med gemensam nämnare,
- härleda minst en potenslag,
- ge ett motexempel till en falsk rotregel,
- skilja term från faktor,
- distribuera ett negativt tal över en parentes,
- lösa en linjär ekvation med explicita balanssteg,
- kontrollera lösningen genom insättning.

Om något av detta inte går utan att titta är det fortfarande ett aktivt repetitionsområde.

---

# Källor och verifierad extern läsning

## Styrkälla
Skolverket, Gy25, Matematik (MATE), nivå 1c:
https://syllabus-web.skolverket.se/programs/BF25/MATE

Skolverket, söksida för Matematik MATE:
https://www.skolverket.se/undervisning/gymnasieskolan/program-och-amnen-i-gymnasieskolan/gymnasieprogrammen-gy25/nationella-program/programs/VF25/MATE

## Läromedelskälla
Matteboken/Mattecentrum, Matematik nivå 1:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1

Aritmetik:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/aritmetik

Algebra:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra

## Källstatus
- Kursens placering och nivåstruktur är verifierad mot Skolverkets aktuella Gy25-material.
- Matematikens definitioner och regler i veckan är standardresultat på elementär algebraisk nivå och har korsats mot Mattebokens aktuella Matematik-nivå-1-material.
- Videolänkar är verifierade som tillgängliga sökresultat inför skapandet av V1 den 11 augusti 2026.
- Exempel, övningar, gate-test och formuleringar i detta dokument är nyskrivna för kursen.

# Pre-mortem

1. Matteboken samlar material för 1a/1b/1c på gemensamma sidor; därför används Skolverket som normerande styrkälla för själva nivån.
2. Videoplattformars URL:er och tillgänglighet kan förändras över tid.
3. Konventionen \(0\in\mathbb N\) används här och i den länkade Matteboken; andra matematiska texter kan använda \(\mathbb N=\{1,2,\ldots\}\). Kontrollera alltid författarens konvention.
4. En veckogate mäter inte full behärskning av Matematik nivå 1c; den mäter endast V1:s fundament.
