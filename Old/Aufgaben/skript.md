# C# Brückenkurs

Vorwort
Was ist ein Programm?
Ein Programm ist eine in Befehlen verfasste Anweisung, die du deinem Computer aufträgst.
Normale deutsche Sprache versteht der aber erst mal nicht. Von wegen hochdeutsches Vokabular, Genitiv, 2.Person Präsenz!
Das ist erst mal nicht drin. Normale Sprachen sind, wenn man es genau nimmt, viel zu komplex.
Sicher kannst du gutes Deutsch sprechen. Denk aber auch daran, dass du etwa sechs Jahre deiner Kindheit gebraucht hast, um es zu lernen.
Diese Eingewöhnungszeit wirst du in der Uni nicht bekommen. Die wirst du aber auch nicht brauchen. 
Dein Computer versteht also kein deutsch, japanisch oder englisch, sondern eben Sätze aus PROGRAMMIERSPRACHEN.
Diese haben ein sehr kleines Vokabular, jedoch eine große Anzahl an Regeln auch Syntax genannt.
Die Syntax ist, kann man sagen, die Grammatik der Programmiersprache. 
Aber auch hier gilt "weniger ist mehr" und du wirst in Uni-Kursen die wichtigsten dieser Regeln kennenlernen.
Sätze, die du deinem Computer nach Abschluss dieser Kurse vermitteln kannst, sind (ins deutsche übersetzt):
"Gib mir die Einkaufsliste aus der Datei und sortiere diese nach den Preißen, die ich dahinter notiert habe."
"sag mir welchen Wochentag wir vor vier Jahren, fünf Monaten und vier Tagen hatten."
Wie diese Sätze vermuten lassen, geht es also um die basics der Programmierung. 


Programme in c#



1.Daten
Daten enthalten informationen die unser Programm auswertet

1.1 Datentypen
Die zwei grundlegendsten Typen für Daten sind Zahlen und Zeichenketten(Strings)

1.1.1 Zahlen
Ziffern von 0-9
Zahl = Aneinanderreihung von Ziffern

als ganze Zahl:
 918, 182, 1, 2, 3
als Kommazahl:
 1.0283, 209983.29823

1.1.2 Zeichenketten(Strings)
Ein Zeichen kann alles sein, was du auf deiner Tastatur findest und noch mehr. 
'a','b','c','.','_','1','%','&',
Zeichenkette = Aneinaderreihung von Zeichen, also ein Text.
"Peter", "1&1", "40% auf alles außer Tiernahrung", "$t&jjghfr?halloundtschüss"

2.Variablen
Variablen werden von dir selbst erstellt. Sie sind wie Kisten in welche du Daten reinlegen und rausnehmen kannst.
Die Variablen müssen immer von dir benannt werden, außerdem muss der Variablentyp angegeben werden.
c# lässt dich aus verschiedenen Typen wählen:
char(Zeichen), String(Zeichenkette), Int(Ganzzahl), double(Kommazahl)
Bsp. 
```cs
String meineVariable = "Hallo";
``` 
Variable mit der Bezeichnung meineVariable vom Typ Zeichenkette, das den Text "Hallo" speichert


Aufgaben zu Variablen:
1.
a)Deklariere eine String Variable mit dem Text: "Dies ist eine String Variable!".

Was passiert bei Eingabe dieses Codes?

string name = "Pete";
if (name == Pete)
{
    Console.WriteLine("Hallo Pete!");
}
Was müsste ich stattdessen schreiben?


Was ergibt folgender Code:

string name = "Max";
if (name == "Pete")
{
    Console.WriteLine("Hallo Pete!");
}
else
{
    Console.WriteLine("Wo ist Pete?");
    name = "Peter";
    Console.WriteLine("Pete kommt zurück");
}
Console.WriteLine($"{name}: Sucht ihr jemanden?");


## Nested Loops

In manchen Situationen braucht mehr als nur einen For Loop. Man kann auch einen For Loop in einen anderen packen.
Das nennt man auch nested Loop

Beispiel:

```csharp
for (int i = 0; i < 10; i++)
{
    for (int j = 0; j < 10; j++)
    {
        Console.WriteLine(i + " " + j);
    }
}

```

Folgende Ausgabe wird kommen:

```
0 0
0 1
0 2
0 3
0 4
0 5
0 6
0 7
0 8
0 9
1 0
1 1
1 2
1 3
1 4
1 5
1 6
1 7
1 8
1 9
2 0
2 1
2 2
2 3
2 4
2 5
2 6
2 7
2 8
2 9
3 0
3 1
3 2
3 3
3 4
3 5
3 6
3 7
3 8
3 9
4 0
4 1
4 2
4 3
4 4
4 5
4 6
4 7
4 8
4 9
5 0
5 1
5 2
5 3
5 4
5 5
5 6
5 7
5 8
5 9
6 0
6 1
6 2
6 3
6 4
6 5
6 6
6 7
6 8
6 9
7 0
7 1
7 2
7 3
7 4
7 5
7 6
7 7
7 8
7 9
8 0
8 1
8 2
8 3
8 4
8 5
8 6
8 7
8 8
8 9
9 0
9 1
9 2
9 3
9 4
9 5
9 6
9 7
9 8
9 9
```

### Notes zu Nested Loops

Bei verschachteln For Loops ist es wichtig das die Loop variablen einen unterschiedlichen Namen haben. In diesem Beispiel (i, j).

So etwas wie

```csharp
for (int i = 0; i < 10; i++)
{
    // i ist schon in der oberen for Schleife deklariert.
    for (int i = 0; i < 10; i++)
    {
        Console.WriteLine(i + " " + j);
    }
}
```

Um die Technik von verschachteln For Schleifen besser zu verstehen, ist zu empfehlen, dass man bei untern Beispiel die Zahlen für die Grenzen anpasst, Variable a und b, und schaut wie sich die Ausgabe ändert.

```csharp
int a = 5;
int b = 10;
for (int i = 0; i < a; i++)
{
    // i ist schon in der oberen for Schleife deklariert.
    for (int j = 0; j < b; j++)
    {
        Console.WriteLine(i + " " + j);
    }
}
```