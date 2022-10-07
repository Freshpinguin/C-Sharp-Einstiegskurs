# Aufgabe 4

## 1. Arrays

Siehe Beispiel fuer die Erstellung eines Arrays und seine Nutzung.
```csharp
int[] number = new int[5];
number[0] = 1;
number[1] = 50;
number[2] = 2;
number[3] = 7;
number[4] = 9;

Console.WriteLine("Length: " + number.Length);
for (int i = 0; i < number.Length; i++)
{
    Console.WriteLine("Number: " + number[i]);
}
```


Kopiere und fuehre den oberen Code aus. Spiel ein bisschen damit rum. Ändere oberen Code so ab, das folgeendende Ausgabe erzeugt wird.

```csharp
0
1 
2
3
4
```

## 2. Ausgabe von Array

Folgendes Array aus auf der Konsole.
```csharp
string[] names = new string [4];
names[0] = "Mario";
names[1] = "Luigi";
names[2] = "Peach";
names[3] = "Bowser";
```

Schreibe ein Program welches den Inhalt des Arrays ausgibt.

## 3. Beheben von einem Bug

Bug: Ein Fehler in der Software.

Folgender Code ist gegeben:

```csharp
int[] number = new int[3];
number[0] = 1;
number[1] = 2;
number[3] = 3;
```

Dieser Code wird crashen. Ändere den Code so ab, das der Inhalt des Arrays ausgeben wird und folgende Ausgabe kommt. 

```charp
1
2
3
```
## 4. Zaehlen eines Wort im Array.

Folgender Code ist gegeben.

```csharp
var array = new string[] {
    "Mario",
    "Mario",
    "Hello",
    "Array",
    "Mario",
    "C",
    "Hello",
    "World",
    "C",
    "Array",
    "World",
    "Mario",
    "C++",
    "Array",
    "World",
    "CSharp",
    "C",
    "Array",
    "CSharp",
    "CSharp",
    "Mario",
    "C++",
    "Mario",
    "World",
    "C"
};
```

Nun schreibe ein Program welches die Anzahl von dem Wort Mario im Array ausgibt.

## 4. Berechne das eines Arrays.

Deklariere ein Array mit folgenden Werten 789, 23, -34, 2134, -78 in genau dieser
Reihenfolge. Nun schreibe noch ein Program welches den kleinsten Wert dieser Zahlen 
ausgibt.

## 5. Berechne das Maximum eines Arrays.

Deklariere ein Array mit folgenden Werten 1000, 451, -378, -2134, -78, 78 in genau dieser
Reihenfolge. Nun schreibe noch ein Program welches den größten Wert dieser Zahlen 
ausgibt.

## 6. Berechne den Durchschnitt eines Arrays.

Deklariere ein Array mit folgenden Werten 1000, 234, 9793, 1789, 78, 728 in genau dieser
Reihenfolge. Nun schreibe noch ein Program welches den Durchschnitt dieser Zahlen 
ausgibt.

