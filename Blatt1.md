# Blatt 1

## Console


```cs
Console.WriteLine("Dies ist mein erstes C# Project!");
```

### Hello World

Führe ein Programm aus, welches den Text "Hello World!" ausgibt.

### Ausgabe ändern

Ändere den Ausgabetext. Schreibe "Hallo, mein Name ist ..." in die Konsole.

### Ausgabe mit mehreren Zeilen

Gebe ein Ausgabetext aus, der aus mehrere Zeilen besteht. Schreibe ein Smiley pro Zeile: (^\_^) [o_O] (°.°) (+\_+) {$.$}

Verwende dafür mehrere Console.WriteLine().

## String Variable 

```cs
string var = "Meine erste Variable!";

Console.WriteLine(var);
```

Deklariere eine String Variable mit dem Text: "Dies ist eine String Variable!".

Geben den Inhalt dieser Varible im Terminal aus.

### Den Wert der Variable ändern

Deklariere eine String Variable mit dem Text: "Zuerst ist dies der Text."

Gebe den Inhalt dieser Variable im Terminal aus.

Ändere den Wert der Variable zu: "Geänderter Text."

Gebe den Inhalt dieser Variable erneut im Terminal aus.

### Konkatenieren einer Variable mit einem Text

Deklariere eine String Variable mit deinem Namen als Text.

Schreibe "Hallo, mein Name ist ____" ins Terminal.

### Konkatinieren von beiden Seiten

Deklariere eine String Variable mit deinem Namen als Text.

Schreibe "===> ___ <===" ins Terminal.

### Konkatinieren von mehreren Variablen zu einer Variablen

Deklariere zwei String Variablen mit dem Text "Dies ist der erste Text" und "dies ist der zweite Text".
Deklariere eine String Variable und weiße ihr die Konkatination der beiden Variablen als Wert zu.

Schreibe den Wert der Variablen ins Terminal.

## Konsolen Eingabe

```cs
Console.WriteLine("Gebe eine Eingabe ein und bestätige mit Enter!");

string input = Console.ReadLine();

Console.WriteLine(Eingabe);
```

## Konsole Ausgabe

### Einlesen des Namens

Das Program soll folgendes tun. Das Program soll den Nutzer nach seinen Namen fragen und warten bis der Nutzer seinen Namen eingeben hat.
Nach der Eingabe soll das Program den Nutzer mit seinen Namen begrüßen.


## Integer Variablen

### Rechenoperationen

Gebe das Ergebnis der Rechnungen 4+2, 4-2, 4*2, 4/2 ins Terminal.

### Teilen von Integers

Gebe das Ergebniss der Rechnung 5/2 im Terminal aus. Wie erklärst du dir das Ergebnis?

### Variablen

Deklariere zwei Integer Variable a und b mit den Werten 3 und 7. 
Speichere den Wert von a + b in einer neuen Variablen c.
Speichere den Werte c*3 - b in einer neuen Variablen d.
Geben den Wert von d im Terminal aus.


### Variablen Tauschen

Deklariere zwei Integer Variable num3 und num7 mit den Werten 3 und 7. 
Gebe die Werte jeweils im Terminal aus.
Tausche den Wert der beiden Variablen.
Gebe die Werte jeweils im Terminal aus.

### Rechenaufgabe

Deklariere die Integer Variable x mit dem Wert 13.

Deklariere die Integer Variable y mit einem Wert, so dass der Ausdruck (2*x + y)/3 den Wert 10 annimmt.


### Rechenaufgabe

Deklariere vier Integer Variablen num2, num3, num5, num7 mit den Werten 2,3,5 und 7.

Verbinde die Variablen mit genau drei Rechenoperationen, so dass der Ausdruck num2 _ num3 _ num5 _ num7 den Wert 0 annimmt und gebe diesen im Terminal aus.

### Rechnen mit Rest


```Csharp 

Console.WriteLine(13%10);

Console.WriteLine(7%2);

Console.WriteLine(5%5);

```

Versuche anhand der Consolen Ausgabe zu verstehen, was der %-Rechenoperator bewirkt.

## Konvertieren von Integer zu String 

### Beispiel

```Csharp 
int zahl = 13;

string dreizehn = zahl.ToString();

string sieben = "7";

string hundertsiebenundreissig = dreizehn + sieben;

int ergebniss = Convert.ToInt32(hundertsiebenundreissig);

Console.WriteLine(ergebniss);

```

### Konvertieren

Deklariere eine String Variable mit dem Wert "239". Konvertiere den Wert der Variable zu einem Integer und speichere ihn in einer Variable.
Multipliziere das Ergebnis mit 3, ziehe dann 3 ab und teile das Ergebniss durch 17. Konvertiere diese Zahl dann wieder in einen String und gebe das Ergebniss in der Konsole aus.

### Beispiel

```Csharp 
string eingabe = Console.ReadLine();

int zahl = Convert.ToInt32(eingabe);

Console.WriteLine(zahl - 5);

```

### Eingabe des Alters.

Das Program soll nun folgendes tun. Der Nutzer wird nach seinem Alter gefragt. Nach dem der Nutzer sein Alter eingeben hat, soll das Program dem Nutzer sein Alter plus 10 ausgeben.

### Taschenrechner I

Lese zwei Zahlen vom User ein. Berechne die Summe und die Differenz der beiden Zahlen und gebe jeweils das Ergebniss in der Konsole aus.

