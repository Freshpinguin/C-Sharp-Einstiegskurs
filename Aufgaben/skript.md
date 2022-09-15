C# Brückenkurs

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