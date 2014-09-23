RatNum
======

Tillhör Lab2

Del 1.
TestRseEH programmet testar Rse programmet.

[solback@ed6225-04 46.lab2]$ javac TestRseEH.java
[solback@ed6225-04 46.lab2]$ java TestRseEH

1)  a=  correct (T) [ { 1 2 1 2 1 2 } { 4 0 0 2 2 1 } { 1 1 1 1 1 4 } ]
2)  b=  correct (F) [ { 1 2 3 4 } { 5 6 7 8 } { 1 1 1 1 } ]
3)  c=  correct (T) [ { 1 } { 2 -1 } { 3 -1 -1 } ]
4)  d=  correct (T) [ null ]
5)  e=  correct (T) [ null null null ]
6)  f=  correct (T) [ - ]
7)  g=  correct (T) [ { - } ]
8)  h=  correct (T) [ { 1 2 3 } ]
9)  i=  correct (F) [ { 1 } { 2 } { 3 } ]
10) j=  correct (T) [ { 0 } ]
11) k=  correct (F) [ { 1 2 3 } { 3 2 1 } { 4 4 4 } ]
12) l=  correct (F) [ { 1 2 3 } { 3 -2 -1 } { 4 4 4 } ]
13) m=  correct (T) [ { 0 0 0 0 } null { 5 5 -5 -5 } ]
14) n=  correct (T) [ { 0 0 0 0 } null { - } ]
15) o=  correct (F) [ { 0 0 3 0 } null { - } ]
16) p=  correct (F) [ { 1 2 3 } { 4 5 6 } { 7 8 9 } { 1 2 3 } ]
17) q=  correct (F) [ { 1 2 3 } { 4 5 6 } { 7 8 9 } { 7 8 9 } ]
Rse: All tests passed

Del 2.
Steg 1:

Talen Ã¤r 1 och 1.	Ditt resultat: 1.		RÃ¤tt resultat: 1.  ok
Talen Ã¤r 12 och 1.	Ditt resultat: 1.		RÃ¤tt resultat: 1.  ok
Talen Ã¤r 12 och 2.	Ditt resultat: 2.		RÃ¤tt resultat: 2.  ok
Talen Ã¤r 12 och 14.	Ditt resultat: 2.		RÃ¤tt resultat: 2.  ok
Talen Ã¤r 22 och 14.	Ditt resultat: 2.		RÃ¤tt resultat: 2.  ok
Talen Ã¤r 39 och 15.	Ditt resultat: 3.		RÃ¤tt resultat: 3.  ok
Talen Ã¤r 40 och 12.	Ditt resultat: 4.		RÃ¤tt resultat: 4.  ok
Talen Ã¤r 168 och 49.	Ditt resultat: 7.		RÃ¤tt resultat: 7.  ok
Talen Ã¤r 143 och 7.	Ditt resultat: 1.		RÃ¤tt resultat: 1.  ok
Talen Ã¤r 7 och 143.	Ditt resultat: 1.		RÃ¤tt resultat: 1.  ok
Talen Ã¤r 1260 och 36.	Ditt resultat: 36.		RÃ¤tt resultat: 36.  ok
Talen Ã¤r 36 och 1260.	Ditt resultat: 36.		RÃ¤tt resultat: 36.  ok
Talen Ã¤r 15775 och 100.	Ditt resultat: 25.	RÃ¤tt resultat: 25.  ok
Talen Ã¤r 100 och 15775.	Ditt resultat: 25.	RÃ¤tt resultat: 25.  ok
Talen Ã¤r 15776 och 100.	Ditt resultat: 4.	RÃ¤tt resultat: 4.  ok
Talen Ã¤r 15775 och 12.	Ditt resultat: 1.		RÃ¤tt resultat: 1.  ok
Talen Ã¤r 0 och 12.	Ditt resultat: 12.		RÃ¤tt resultat: 12.  ok
Talen Ã¤r 12 och 0.	Ditt resultat: 12.		RÃ¤tt resultat: 12.  ok
Talen Ã¤r 0 och 0.		Korrekt IllegalArgumentException genererad  ok
Talen Ã¤r -6 och 39.	Ditt resultat: 3.		RÃ¤tt resultat: 3.  ok
Talen Ã¤r 39 och -6.	Ditt resultat: 3.		RÃ¤tt resultat: 3.  ok
Talen Ã¤r -6 och -39.	Ditt resultat: 3.		RÃ¤tt resultat: 3.  ok


Steg 2:

[solback@ed6225-05 46.lab2]$ javac RatNumTest2.java
[solback@ed6225-05 46.lab2]$ java RatNumTest2
Inga fel!


Steg 3:

[solback@ed6225-15 46.lab2]$ java RatNumTest3 < indata.txt

>>>> Test av equals: Vi har inte gÃ¥tt igenom equals Ã¤nnu 
sÃ¥ du behÃ¶ver inte klara dessa tester Ã¤n
<<<< Slut pÃ¥ equals tester
Skriv uttryck pÃ¥ formen a/b ? c/d, dÃ¤r ? Ã¤r nÃ¥got av tecknen + - * / = <
> 1/3 + 1/4	--> 7/12
> 2/9 * -4/5	--> -8/45
> 2/6 - 7/9	--> -4/9
> 7/-2 / -2/5	--> 35/4
> -5/10 + -3/4	--> -5/4
> -5/3 * 4	--> -20/3
> 7/9 * 2	--> 14/9
> -5 * 1/3	--> -5/3
> 2 / -5	--> -2/5
> 2/5 = 40/100	--> true
> 6/18 = -1/3	--> false
> 2/9 < 1/5	--> false
> -5/9 < 1/2	--> true
> 1/2 +1/3	--> Felaktigt uttryck!
> 1/5	--> Felaktigt uttryck!
> /4 + 1/3	--> NumberFormatException: For input string /4
> 5/ + 1/3	--> NumberFormatException: For input string 5/
> 1//4 + 1/4	--> NumberFormatException: For input string 1//4
> 1/ - 2 + 1/3	--> Felaktigt uttryck!
> 1/3 a + 1/3	--> Felaktigt uttryck!
> -/3 + 1/3	--> NumberFormatException: For input string -/3
> 1/3 + 1/3 + 1/3	--> Felaktigt uttryck!
> 1/3 & 1/3	--> Felaktig operator!
> 1/0 + 1/3	--> NumberFormatException: Denominator = 0
> 1 / 0	--> NumberFormatException: Denominator = 0

//Kommentarer för för testprogrammet RatNumTest3.java // 

public static String ratNumToString(RatNum r)
	
Denna metod tar objektet RatNum från våran klass och returnerar det rationella talet till en sträng. den initierar värdet num till värdet av numerator. Samma sak händer med denom som får värdet av denominator.

private static void divTester()

Först skapar denna metod ett antal objekt som kommer att användas för att testa vår equals() metod. w.equals(v) ska vara sann eftersom de innehåller samma värde. w == v hade gett falsk eftersom "pilarna" pekar på olika lådor. Samma typ av test genomförs sedan på andra testfall. 

Efter det testar programmet vår metod toDouble. Den kontrolleras med hjälp av 2 for-loopar, som ändrar värdet på variblerna j och i. Efter att den har anropat vår metod med två värden görs sedan j och i korrekt om till ett flyttal. Dessa värden subtraheras, om resultatet är större än 1*10^-13 är toDouble inte korrekt.

testExpr().

I denna metod testas våra metoder add(), sub(), mul(), div(), equals() och lessThan(). Genom att användaren själv får skriva in värden i konsolen. Testet ser ut på följande sätt r1.add(r2). Där r1 blir det aktuella talet och r2 sätts till "ett annat rationellt tal". Testaren vet vilken metod den ska testa genom att du skriver in antingen +,-,*,/,=,<. Här finns dock inget referens värde som metoderna kontrollerar mot, utan den skriver bara ut svaret och sedan får man själv kontrollera. 

I testfilens main metod anropas bland annat divTester som testar equals() och toDouble().......
Sedan skapas en while-loop som kommer användas när man testar testExpr(). Som man märker i terminalen när man kör programmet är att den slutar aldrig att fråga efter nya tal, detta är för att while-loopen tar värdet sant. Detta gör att du själv behöver avbryta loopen för att komma ut.

Referenser:

http://stackoverflow.com/questions/13174031/how-to-run-java-class-file-from-another-class-file-java-newb
http://www.tutorialspoint.com/java/java_string_substring.htm
