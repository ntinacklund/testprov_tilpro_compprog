# Testprov i competitive programming

I detta repo finns det tre filer. Fyll i var och en för respetkive uppgift. När du pushar kommer det att köras ett flertal tester för att kontrollera din lösning. Se till att dina inputs och outputs är exakt som i varje uppgifts respektive exempel.

## Uppgift 1

### Uppgiftsbeskrivning

Skriv en Python-funktion som tar en textsträng som input och översätter den till rövarspråket enligt följande regler:

Lägg till "o" framför varje konsonant i strängen (utom "y").
Behåll vokalerna oförändrade.
Behåll mellanslag, siffror och specialtecken oförändrade.

### Testfall

- Testfall 1:
    - Input: "hej"
    - Output: "hohejoj"

- Testfall 2:
    - Input: "python"
    - Output: "popytotohon"

## Uppgift 2 - Parenteskontroll

### Uppgiftsbeskrivning

Skriv en Python-funktion som tar en textsträng som input och kontrollerar om parenteser i strängen är korrekt balanserade enligt följande regler:

Varje öppen parentes "(" måste ha en motsvarande stängd parentes ")".
Parenteserna måste vara korrekt inbäddade, t.ex., "(a(b)c)" är korrekt, men "((a)b)c)" är inte korrekt.
Funktionen ska returnera True om parenteserna är korrekt balanserade, annars False.

Skriv ut vad din funktion returnerar.

### Testfall

- Testfall 1:
    - Input: ((a+b)*(c-d))
    - Output: True

- Testfall 2:
    - Input: (({}[])
    - Output: False

## Uppgift 3 - Fibonaccisekvensen

### Uppgiftsbeskrivning

Skriv en Python-funktion som genererar de första n Fibonacci-numren och returnerar dem som en utskrift. Fibonacci-sekvensen börjar med 0 och 1, och varje efterföljande nummer är summan av de två tidigare.

Användaren matar in vad n är.

### Testfall

- Testfall 1:
    - Input: 5
    - Output: 0 1 1 2 3

- Testfall 2:
    - Input: 6
    - Output 0 1 1 2 3 5
