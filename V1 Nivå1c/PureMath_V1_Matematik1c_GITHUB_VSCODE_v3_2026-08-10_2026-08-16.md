# Pure Math — Matematik nivå 1c
# V1 — Algebraiska uttryck och formler
## GitHub/VS Code-kompatibel v3

**Period:** måndag 10 augusti 2026 – söndag 16 augusti 2026  
**Vardagar:** 17:00–19:00  
**Lördag–söndag:** 18:00–20:00  
**Schemalagd tid:** 14 timmar  
**Styrpunkt från Gy25:** Hantering av formler och algebraiska uttryck, inklusive faktorisering och multiplicering av uttryck.

> **Markdown-standard:** Inline-matematik använder `$...$`; blockmatematik använder `$$...$$`. Detta är kursens standard för GitHub och VS Code Markdown Preview.

---

# Veckans idé

Den här veckan handlar inte om att "hinna algebra".

Den handlar om att göra algebrans språk stabilt.

Du ska efter veckan kunna se

$$
3x(2x-5)+7
$$

och omedelbart kunna skilja:

- termer,
- faktorer,
- koefficienter,
- variabler,
- konstanttermer,
- operationer,
- vilka delar som får förenklas,
- vilka delar som **inte** får förenklas.

Du ska även kunna motivera varför

$$
3(x+4)=3x+12
$$

och varför

$$
3(x+4)\neq 3x+4.
$$

---

# Veckans slutgate

Du ska kunna:

1. definiera numeriskt uttryck,
2. definiera algebraiskt uttryck,
3. skilja variabel från konstant,
4. identifiera term, faktor och koefficient,
5. beräkna ett uttrycks värde genom insättning,
6. förenkla lika termer,
7. använda kommutativa och associativa lagen där de gäller,
8. använda distributiva lagen,
9. multiplicera monom med parentes,
10. multiplicera två enklare binom,
11. faktorisera med gemensam faktor,
12. förstå faktorisering som omvänd distributiv lag,
13. tolka en formel som ett samband,
14. använda en formel med korrekta enheter,
15. skriva om enklare formler,
16. upptäcka och förklara falska algebrasteg.

---

# Måndag 10/8 — Algebra är ett språk
**Tid:** 17:00–19:00

## 17:00–17:15 — Förkunskapsdiagnostik

Räkna utan hjälpmedel.

1. $7+3\cdot4$
2. $5(2+3)$
3. $-4+9$
4. $\frac12+\frac14$
5. $3^2$
6. $(-3)^2$
7. $18/6$
8. $2(5-8)$

Syftet är inte betyg. Fel här markeras som **reparationsnoder**.

---

## 17:15–17:35 — Teori: numeriska och algebraiska uttryck

### Numeriskt uttryck

Ett numeriskt uttryck innehåller endast tal och operationer.

Exempel:

$$
7+3\cdot4.
$$

Det har ett bestämt numeriskt värde:

$$
7+3\cdot4=7+12=19.
$$

### Algebraiskt uttryck

Ett algebraiskt uttryck innehåller minst en variabel.

Exempel:

$$
3x+5.
$$

Det har inte ett enda numeriskt värde förrän $x$ har fått ett värde.

Om

$$
x=4
$$

får vi

$$
3x+5=3\cdot4+5=17.
$$

### Exempel 1

Uttrycket

$$
5a-2
$$

är algebraiskt eftersom $a$ är en variabel.

### Exempel 2

$$
5\cdot7-2
$$

är numeriskt.

### Exempel 3 — samma struktur

$$
5a-2
$$

och

$$
5\cdot7-2
$$

har samma operationsstruktur. Skillnaden är att $a$ kan variera.

---

## 17:35–17:55 — Teori: variabel, konstant, term, faktor och koefficient

Studera

$$
4x^2-3x+7.
$$

### Termer

Termerna är:

$$
4x^2,\qquad -3x,\qquad 7.
$$

Addition och subtraktion skiljer termerna på den aktuella nivån.

### Faktorer

I termen

$$
4x^2
$$

är $4$ och $x^2$ faktorer.

### Koefficient

I

$$
-3x
$$

är koefficienten $-3$.

### Konstantterm

I

$$
4x^2-3x+7
$$

är $7$ konstantterm.

### Viktig skillnad

I

$$
3(x+5)
$$

är $3$ en faktor till **hela parentesen**.

Inuti parentesen är $x$ och $5$ termer.

---

## 17:55–18:10 — Genomräknade exempel

### Exempel 4

Identifiera delarna i

$$
8y-11.
$$

- variabel: $y$
- koefficient: $8$
- variabelterm: $8y$
- konstantterm: $-11$

### Exempel 5

Identifiera delarna i

$$
-2a^2+5a-9.
$$

Termer:

$$
-2a^2,\quad 5a,\quad -9.
$$

Koefficienter:

$$
-2,\quad 5.
$$

### Exempel 6 — implicit koefficient

$$
x
$$

betyder

$$
1x.
$$

Koefficienten är alltså $1$.

$$
-x
$$

betyder

$$
-1x.
$$

---

## 18:10–18:20 — Läsning och videolektion

Läs:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/uttryck-och-variabler

På samma sida: öppna **Videolektion**.

Fokusera på:
- algebraiskt uttryck,
- variabel,
- konstant,
- koefficient.

---

## 18:20–18:50 — Praktik

### A. Klassificera

Ange numeriskt eller algebraiskt.

1. $5+8$
2. $4x+7$
3. $3(2+5)$
4. $2a^2-1$
5. $9/3+4$
6. $7t$

### B. Identifiera delar

För varje uttryck: ange termer, variabler, koefficienter och konstantterm.

7. $3x+8$
8. $7y-4$
9. $-5a+2$
10. $2x^2+6x-1$
11. $-z+9$

### C. Beräkna värde

12. $3x+5$ för $x=4$
13. $2a^2-3$ för $a=5$
14. $4-2t$ för $t=-3$
15. $x^2+x+1$ för $x=-2$

### D. Förklara

16. Varför är $3x+5$ inte en ekvation?
17. Vad är skillnaden mellan en term och en faktor?
18. Vad är koefficienten i $-x$?

---

## 18:50–19:00 — Micro-gate

Utan anteckningar:

1. Definiera variabel.
2. Definiera koefficient.
3. Ange termerna i $5x^2-2x+9$.
4. Beräkna $2x^2+1$ för $x=3$.

### Facit

1 numeriskt  
2 algebraiskt  
3 numeriskt  
4 algebraiskt  
5 numeriskt  
6 algebraiskt  
12 $17$  
13 $47$  
14 $10$  
15 $3$  
Micro-gate 4: $19$

---

# Tisdag 11/8 — Ekvivalenta uttryck och lika termer
**Tid:** 17:00–19:00

## 17:00–17:10 — Retrieval

1. Vad är en term?
2. Vad är en faktor?
3. Vad är koefficienten i $-7x$?
4. Beräkna $3x-2$ för $x=-4$.

---

## 17:10–17:35 — Teori: när får termer slås ihop?

### Lika termer

$$
3x+5x=8x.
$$

Varför?

$$
3x+5x=(3+5)x=8x.
$$

Vi använder distributiva lagen baklänges.

### Inte lika termer

$$
3x+5x^2
$$

kan inte reduceras till en enda term.

Testa exempelvis $x=2$:

$$
3x+5x^2=6+20=26.
$$

Det falska förslaget

$$
8x^3
$$

ger

$$
8\cdot2^3=64.
$$

Alltså kan de inte vara ekvivalenta uttryck.

### Exempel 1

$$
4a+7a-3a=8a.
$$

### Exempel 2

$$
6x^2+2x-4x^2+5x
=
2x^2+7x.
$$

### Exempel 3

$$
3x+5+2x-9
=
5x-4.
$$

---

## 17:35–17:55 — Kommutativa och associativa lagen

### Kommutativ addition

$$
a+b=b+a.
$$

### Kommutativ multiplikation

$$
ab=ba.
$$

Men subtraktion är inte kommutativ:

$$
7-3\neq3-7.
$$

Division är inte heller kommutativ:

$$
8/2\neq2/8.
$$

### Associativ addition

$$
(a+b)+c=a+(b+c).
$$

### Associativ multiplikation

$$
(ab)c=a(bc).
$$

### Varför bry sig?

Lagarna förklarar varför vi får ordna om delar av uttryck vid förenkling.

Exempel:

$$
3x+7+5x-2
$$

kan ordnas som

$$
3x+5x+7-2
$$

och förenklas till

$$
8x+5.
$$

---

## 17:55–18:15 — Felsäker förenkling

### Exempel 4

$$
2x+3+5x+4
=
7x+7.
$$

### Exempel 5

$$
4a^2-3a+6+2a^2+a-10
=
6a^2-2a-4.
$$

### Exempel 6 — minustecken

$$
5x-3-2x-7
=
3x-10.
$$

### Falsk regel

$$
x+x^2=x^3
$$

är falsk.

För $x=2$:

vänsterled:

$$
2+4=6,
$$

högerled:

$$
8.
$$

---

## 18:15–18:25 — Läsning och videolektion

Läs:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/forenkla-uttryck

Använd sidans **Videolektion**.

---

## 18:25–18:50 — Praktik

Förenkla.

1. $3x+8x$
2. $9a-4a$
3. $2x+5+4x+7$
4. $8y-3-2y+10$
5. $5a^2+2a^2$
6. $7x^2+3x-2x^2+x$
7. $4t^2-5t+2+3t^2+2t-8$
8. $-3x+5+8x-12$
9. $x+x+x+x$
10. $2a^2+a+3a^2-4a+5$

Avgör rätt/fel och motivera:

11. $2x+3x=5x$
12. $2x+3x^2=5x^3$
13. $a+a=2a$
14. $a\cdot a=2a$
15. $a\cdot a=a^2$
16. $7-3=3-7$

### Facit

1 $11x$  
2 $5a$  
3 $6x+12$  
4 $6y+7$  
5 $7a^2$  
6 $5x^2+4x$  
7 $7t^2-3t-6$  
8 $5x-7$  
9 $4x$  
10 $5a^2-3a+5$  
11 rätt  
12 fel  
13 rätt  
14 fel  
15 rätt  
16 fel

---

## 18:50–19:00 — Reality check

Förklara högt:

> Varför får $3x$ och $5x$ adderas direkt, men inte $3x$ och $5x^2$?

Om svaret bara är "för att reglerna säger så", är momentet inte klart.

---

# Onsdag 12/8 — Distributiva lagen
**Tid:** 17:00–19:00

## 17:00–17:10 — Retrieval

1. Förenkla $3x+5x-2$.
2. Vad är en faktor?
3. Är $a(b+c)=ab+c$ rimligt? Testa $a=2,b=3,c=4$.

---

## 17:10–17:35 — Teori: distribution

Distributiva lagen:

$$
a(b+c)=ab+ac.
$$

Faktorn $a$ multiplicerar **varje term** i parentesen.

### Exempel 1

$$
3(x+4)=3x+12.
$$

### Exempel 2

$$
5(2x-7)=10x-35.
$$

### Exempel 3 — negativ faktor

$$
-2(x+5)=-2x-10.
$$

### Exempel 4

$$
-3(2x-4)=-6x+12.
$$

Det sista tecknet blir plus eftersom

$$
(-3)(-4)=12.
$$

---

## 17:35–17:55 — Monom gånger parentes

### Exempel 5

$$
4x(2x+3)=8x^2+12x.
$$

Varje term multipliceras med $4x$.

### Exempel 6

$$
-2a(3a-5)=-6a^2+10a.
$$

### Exempel 7

$$
3x^2(2x^3-x+4)
=
6x^5-3x^3+12x^2.
$$

Här används både distributiva lagen och potensregeln för multiplikation av samma bas.

---

## 17:55–18:15 — Två parenteser

Vi kan distribuera term för term.

### Exempel 8

$$
(x+2)(x+3)
$$

Först $x$:

$$
x(x+3)=x^2+3x.
$$

Sedan $2$:

$$
2(x+3)=2x+6.
$$

Tillsammans:

$$
(x+2)(x+3)=x^2+5x+6.
$$

### Exempel 9

$$
(2x+1)(x-4)
=
2x^2-8x+x-4
=
2x^2-7x-4.
$$

### Exempel 10

$$
(x-5)(x+5)
=
x^2-25.
$$

Vi memorerar ännu inte detta som en specialregel. Vi ser först strukturen genom distribution.

---

## 18:15–18:25 — Läsning och videolektion

Läs:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/distributiva-lagen

På samma sida: använd **Videolektion**.

Extra exempel:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/faktorisering-och-parenteser/exempel/distributiva-lagen

---

## 18:25–18:50 — Praktik

Utveckla och förenkla.

1. $3(x+5)$
2. $4(2x-3)$
3. $-2(x+7)$
4. $-5(3x-2)$
5. $2x(x+4)$
6. $3a(2a-5)$
7. $-4x(2x+3)$
8. $2x^2(3x-1)$
9. $(x+1)(x+4)$
10. $(x+3)(x-2)$
11. $(2x+5)(x+1)$
12. $(3x-2)(2x+4)$

Felsök:

13. $4(x+3)=4x+3$
14. $-2(x-5)=-2x-10$
15. $3x(2x+1)=6x+3x$
16. $(x+2)(x+3)=x^2+6$

### Facit

1 $3x+15$  
2 $8x-12$  
3 $-2x-14$  
4 $-15x+10$  
5 $2x^2+8x$  
6 $6a^2-15a$  
7 $-8x^2-12x$  
8 $6x^3-2x^2$  
9 $x^2+5x+4$  
10 $x^2+x-6$  
11 $2x^2+7x+5$  
12 $6x^2+8x-8$

---

## 18:50–19:00 — Micro-gate

Utveckla utan stöd:

$$
-3x(2x-5).
$$

Svar:

$$
-6x^2+15x.
$$

Förklara dessutom varför $+15x$ blir positiv.

---

# Torsdag 13/8 — Faktorisering
**Tid:** 17:00–19:00

## 17:00–17:10 — Retrieval

Utveckla:

1. $5(x+2)$
2. $-2x(3x-4)$
3. $(x+2)(x+1)$

---

## 17:10–17:35 — Faktorisering som omvänd distribution

Vi vet:

$$
a(b+c)=ab+ac.
$$

Samma likhet kan läsas åt andra hållet:

$$
ab+ac=a(b+c).
$$

Det är **faktorisering**.

### Exempel 1

$$
6x+12=6(x+2).
$$

### Kontroll

Utveckla igen:

$$
6(x+2)=6x+12.
$$

### Exempel 2

$$
8x^2+12x=4x(2x+3).
$$

Gemensam faktor är $4x$.

### Exempel 3

$$
15a^3-10a^2=5a^2(3a-2).
$$

---

## 17:35–17:55 — Största användbara gemensamma faktor

### Exempel 4

$$
12x+18.
$$

Både 12 och 18 är delbara med 6:

$$
12x+18=6(2x+3).
$$

### Exempel 5

$$
14x^2-21x.
$$

Gemensam numerisk faktor: 7.  
Gemensam variabelfaktor: $x$.

Alltså:

$$
14x^2-21x=7x(2x-3).
$$

### Exempel 6 — negativ faktor

$$
-6x+9.
$$

Man kan skriva

$$
3(-2x+3)
$$

eller

$$
-3(2x-3).
$$

Båda är korrekta. Valet beror på syftet.

---

## 17:55–18:15 — Faktorisering och struktur

### Exempel 7

$$
x^2+5x=x(x+5).
$$

### Exempel 8

$$
3x^2+12x+15
=
3(x^2+4x+5).
$$

Vi stannar där om ingen ytterligare gemensam faktor finns.

### Falsk förkortning

I

$$
\frac{x+5}{x}
$$

kan $x$ inte "stryka" $x$, eftersom täljaren $x+5$ är en summa.

Men i

$$
\frac{x(x+5)}{x}
$$

är $x$ en gemensam faktor och kan förkortas när $x\neq0$.

---

## 18:15–18:25 — Läsning och videolektion

Läs:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/faktorisering-och-parenteser

Använd sidans **Videolektion**.

---

## 18:25–18:50 — Praktik

Faktorisera så långt som möjligt.

1. $4x+8$
2. $6a+18$
3. $10x^2+15x$
4. $12y^2-8y$
5. $21a^3+14a^2$
6. $9x^2-27x$
7. $5x^3+10x^2+15x$
8. $-8x+12$
9. $x^2+7x$
10. $3a^2-12a$

Kontrollera genom att multiplicera tillbaka.

Felsök:

11. $6x+12=6(x+12)$
12. $8x^2+4x=4(2x^2+x)$
13. $8x^2+4x=4x(2x+1)$
14. $(x+3)/x=3$

### Facit

1 $4(x+2)$  
2 $6(a+3)$  
3 $5x(2x+3)$  
4 $4y(3y-2)$  
5 $7a^2(3a+2)$  
6 $9x(x-3)$  
7 $5x(x^2+2x+3)$  
8 exempelvis $-4(2x-3)$  
9 $x(x+7)$  
10 $3a(a-4)$  
11 fel  
12 korrekt men inte maximalt faktoriserat  
13 korrekt och längre faktoriserat  
14 fel

---

## 18:50–19:00 — Reality check

Svara utan att använda ordet "flytta":

> Hur vet du att $7x(2x-3)$ och $14x^2-21x$ representerar samma uttryck?

Förväntad kärna: utveckla den faktoriserade formen med distributiva lagen.

---

# Fredag 14/8 — Formler som matematiska samband
**Tid:** 17:00–19:00

## 17:00–17:10 — Retrieval

1. Faktorisera $12x+18$.
2. Utveckla $4x(2x-3)$.
3. Vad är skillnaden mellan ett uttryck och en formel?

Sista frågan är avsiktligt diagnostisk.

---

## 17:10–17:35 — Teori: vad är en formel?

En formel uttrycker ett matematiskt samband mellan storheter.

Exempel:

$$
v=\frac{s}{t}.
$$

Här kan:
- $v$ stå för hastighet,
- $s$ för sträcka,
- $t$ för tid.

Formeln säger inte att bokstäverna i sig är viktiga. De representerar storheter.

### Exempel 1

Om

$$
s=150\text{ km}
$$

och

$$
t=2\text{ h},
$$

så:

$$
v=\frac{150}{2}=75\text{ km/h}.
$$

### Exempel 2 — area

$$
A=bh.
$$

Om

$$
b=7\text{ cm}
$$

och

$$
h=4\text{ cm},
$$

så:

$$
A=7\cdot4=28\text{ cm}^2.
$$

Enheten kvadratcentimeter är en del av svaret.

---

## 17:35–17:55 — Insättning och parentesdisciplin

Antag:

$$
F=3x^2-2x+5.
$$

För $x=-2$:

$$
F=3(-2)^2-2(-2)+5.
$$

Nu:

$$
(-2)^2=4,
$$

så

$$
F=12+4+5=21.
$$

### Varför parentes?

Att skriva

$$
3\cdot -2^2
$$

kan ge fel tolkning. Vid insättning av ett negativt värde skriver vi det explicit i parentes.

---

## 17:55–18:15 — Skriva om enkla formler

Utgå från

$$
v=\frac{s}{t}.
$$

Multiplicera båda led med $t$:

$$
vt=s.
$$

Alltså:

$$
s=vt.
$$

Från samma samband kan vi också lösa ut $t$:

$$
t=\frac{s}{v},
$$

för $v\neq0$.

### Exempel 3

$$
A=bh.
$$

Lös ut $h$:

$$
h=\frac{A}{b},
$$

för $b\neq0$.

### Exempel 4

$$
C=2\pi r.
$$

Lös ut $r$:

$$
r=\frac{C}{2\pi}.
$$

---

## 18:15–18:25 — Läsning och videolektion

Läs:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/formler-och-ekvationer

och:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/skriva-om-formler

Använd **Videolektion** på respektive sida.

---

## 18:25–18:50 — Praktik

### Insättning

1. $y=3x+4$, $x=5$
2. $A=bh$, $b=8$, $h=3$
3. $s=vt$, $v=72\text{ km/h}$, $t=2.5\text{ h}$
4. $P=2a+2b$, $a=7$, $b=4$
5. $F=2x^2-3x+1$, $x=-2$

### Lös ut angiven variabel

6. $s=vt$, lös ut $v$
7. $s=vt$, lös ut $t$
8. $A=bh$, lös ut $b$
9. $C=2\pi r$, lös ut $r$
10. $y=kx+m$, lös ut $m$

### Tolkning

11. Varför måste $t\neq0$ i $v=s/t$?
12. Vad betyder enheten km/h?
13. Varför bör $-3$ sättas in som $(-3)$ när det kvadreras?

### Facit

1 $19$  
2 $24$  
3 $180$ km  
4 $22$  
5 $15$  
6 $v=s/t$  
7 $t=s/v$, $v\neq0$  
8 $b=A/h$, $h\neq0$  
9 $r=C/(2\pi)$  
10 $m=y-kx$

---

## 18:50–19:00 — Micro-gate

Lös ut $h$ ur:

$$
A=\frac{bh}{2}.
$$

Svar:

$$
h=\frac{2A}{b},
\qquad b\neq0.
$$

---

# Lördag 15/8 — Djupträning: struktur före metod
**Tid:** 18:00–20:00

## 18:00–18:20 — Läsning

Läs sammanhängande:

1. Uttryck och variabler  
   https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/uttryck-och-variabler

2. Distributiva lagen  
   https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/distributiva-lagen

3. Faktorisering och parenteser  
   https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/faktorisering-och-parenteser

Under läsningen: skriv ned varje begrepp som du inte kan definiera utan att läsa meningen igen.

---

## 18:20–18:40 — Film

Använd **Videolektion** på samma tre Matteboken-sidor.

Aktiv regel:

1. pausa innan ett exempel löses,
2. skriv nästa steg själv,
3. starta filmen,
4. jämför,
5. skriv orsaken till eventuell skillnad.

Passiv tittning räknas inte som praktik.

---

## 18:40–19:20 — Mixed practice

1. Identifiera termer i $4x^2-7x+3$.
2. Ange koefficienten till $x$ i samma uttryck.
3. Beräkna $2x^2-3x+1$ för $x=-3$.
4. Förenkla $5x+2+7x-9$.
5. Förenkla $4a^2-3a+2a^2+8a-5$.
6. Utveckla $5(x-4)$.
7. Utveckla $-3(2x+7)$.
8. Utveckla $2x(3x-5)$.
9. Utveckla $(x+4)(x+2)$.
10. Utveckla $(2x-3)(x+5)$.
11. Faktorisera $15x+20$.
12. Faktorisera $12x^2-18x$.
13. Faktorisera $9a^3+6a^2$.
14. Beräkna $v=s/t$ för $s=420$ km, $t=6$ h.
15. Lös ut $t$ ur $s=vt$.
16. Lös ut $b$ ur $A=bh/2$.
17. Förklara skillnaden mellan term och faktor i $3(x+5)$.
18. Falsifiera $a(b+c)=ab+c$ med ett numeriskt exempel.
19. Förklara varför $x+x^2$ inte kan förenklas till $x^3$.
20. Förklara faktorisering med egna ord.

### Facit, kort

3 $28$  
4 $12x-7$  
5 $6a^2+5a-5$  
6 $5x-20$  
7 $-6x-21$  
8 $6x^2-10x$  
9 $x^2+6x+8$  
10 $2x^2+7x-15$  
11 $5(3x+4)$  
12 $6x(2x-3)$  
13 $3a^2(3a+2)$  
14 $70$ km/h  
15 $t=s/v$  
16 $b=2A/h$, $h\neq0$

---

## 19:20–19:45 — Felanalys

Avgör **rätt eller fel**. Vid fel: skriv rätt version och förklara felet.

A.
$$
3x+4x=7x
$$

B.
$$
3x+4x^2=7x^3
$$

C.
$$
2(x+5)=2x+10
$$

D.
$$
2(x+5)=2x+5
$$

E.
$$
-3(x-4)=-3x-12
$$

F.
$$
4x(2x+1)=8x^2+4x
$$

G.
$$
12x+18=6(2x+3)
$$

H.
$$
\frac{x+4}{x}=4
$$

I.
$$
s=vt
$$

omskrivet till

$$
t=\frac{s}{v}.
$$

För I ska du även ange villkoret.

---

## 19:45–20:00 — Egen felprofil

Skapa tre rubriker:

### Säkert
Minst tre saker.

### Behöver fler repetitioner
Minst två saker.

### Typfel
Minst ett verkligt fel du gjort under veckan.

---

# Söndag 16/8 — Gate 1: Algebraiska uttryck och formler
**Tid:** 18:00–20:00

## 18:00–18:10 — Förberedelse

Endast:
- papper,
- penna,
- eventuellt enkel räknare när numeriken kräver det.

Ingen bok under själva testet.

---

## 18:10–19:10 — Gate-test

**30 poäng**

## Del A — Begrepp, 8 p

1. Vad är ett algebraiskt uttryck?
2. Vad är en variabel?
3. Vad är en konstantterm?
4. Vad är en koefficient?
5. Vad är en term?
6. Vad är en faktor?
7. Vad betyder att faktorisera?
8. Vad är en formel?

## Del B — Struktur och procedur, 12 p

9. Förenkla $3x+8x-5$.
10. Förenkla $4a^2+3a-2a^2+5a-7$.
11. Utveckla $5(x-3)$.
12. Utveckla $-4(2x+1)$.
13. Utveckla $3x(2x-5)$.
14. Utveckla $(x+3)(x+7)$.
15. Utveckla $(2x-1)(x+4)$.
16. Faktorisera $18x+24$.
17. Faktorisera $15x^2-10x$.
18. Faktorisera $12a^3+8a^2$.
19. Beräkna $F=3x^2-2x+4$ för $x=-2$.
20. Lös ut $t$ ur $s=vt$.

## Del C — Resonemang, 10 p

21. Förklara varför $3x+5x=8x$.
22. Förklara varför $3x+5x^2$ inte är $8x^3$.
23. Förklara distributiva lagen med egna ord.
24. Visa med ett numeriskt motexempel att $a(b+c)=ab+c$ är falskt.
25. Varför blir $-3(x-4)=-3x+12$?
26. Förklara faktorisering som omvänd operation till distribution.
27. Varför får $x$ inte förkortas i $(x+4)/x$?
28. När får $x$ förkortas i $x(x+4)/x$?
29. En elev skriver $F=2x^2$, $x=-3$, och får $F=-18$. Förklara felet.
30. Beskriv ett realistiskt samband som kan skrivas med en formel och definiera varje variabel.

---

## 19:10–19:30 — Facit

9.
$$
11x-5
$$

10.
$$
2a^2+8a-7
$$

11.
$$
5x-15
$$

12.
$$
-8x-4
$$

13.
$$
6x^2-15x
$$

14.
$$
x^2+10x+21
$$

15.
$$
2x^2+7x-4
$$

16.
$$
6(3x+4)
$$

17.
$$
5x(3x-2)
$$

18.
$$
4a^2(3a+2)
$$

19.
$$
20
$$

20.
$$
t=\frac{s}{v},\qquad v\neq0.
$$

Del C rättas på **resonemang**, inte nyckelord.

---

## 19:30–19:45 — Gate-bedömning

### Godkänd
Minst:

$$
24/30
$$

samt:

- inga upprepade distributionsfel,
- inga upprepade term/faktor-förväxlingar,
- minst 7/10 på resonemangsdelen.

### Villkorligt
20–23 poäng eller ett tydligt systematiskt fel.

Gör då riktat mini-test innan V2.

### Inte godkänd
Under 20 poäng eller flera fundamentala strukturfel.

Då repeteras V1-noden.

---

## 19:45–20:00 — Veckologg och film

Välj **endast** videolektionen för ditt svagaste område:

- Uttryck och variabler:
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/uttryck-och-variabler
- Distributiva lagen:
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/distributiva-lagen
- Faktorisering:
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/faktorisering-och-parenteser
- Formler:
  https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra/skriva-om-formler

Efter filmen: skapa tre egna exempel och lös dem.

---

# Veckans Reality check

V1 är inte klar förrän du från tomt papper kan:

1. förklara term kontra faktor,
2. förklara koefficient,
3. förenkla lika termer,
4. distribuera både positiv och negativ faktor,
5. multiplicera två enkla parenteser,
6. faktorisera med gemensam faktor,
7. kontrollera faktorisering genom att multiplicera tillbaka,
8. sätta in negativa värden korrekt,
9. använda en formel med enheter,
10. lösa ut en enkel variabel,
11. falsifiera minst två vanliga algebrafel med numeriska motexempel.

---

# Källor

## Normerande källa
Skolverket — Matematik, MATE, Gy25:
https://syllabuswebb.skolverket.se/subject/MATE/1/pdf

Den officiella punkten som V1 primärt täcker är:
**Hantering av formler och algebraiska uttryck, däribland faktorisering och multiplicering av uttryck.**

## Kommentarmaterial
Skolverket:
https://www.skolverket.se/download/18.680ec99c197a1c18f613fc/1750771589712/Kommentarmaterial%20till%20%C3%A4mnet%20matematik%20%28Gy25%29.pdf

## Teori, exempel, övningar och videolektioner
Matteboken / Mattecentrum:
https://www.matteboken.se/lektioner/gymnasiet/matte-niva-1/algebra

---

# Pre-mortem

1. V1 går djupare i algebraisk struktur än vad en snabb gymnasiegenomgång ofta gör; det är avsiktligt eftersom senare Pure Math kräver hög symbolisk säkerhet.
2. Tvåparentesmultiplikation används som naturlig fördjupning av Skolverkets formulering "multiplicering av uttryck".
3. Fullständig potenslära skjuts till V5, även om enstaka potenser förekommer som tidigare förkunskap.
4. Om grundläggande bråk eller teckenregler ger återkommande fel skapas en reparationsnod utan att göra om hela kursens ordning.
