# Java Tutorial
## Java Home/Intro/Get Started 
Diese Kaptiel die eine Einleitung darstellen habe ich mir durchgelesen
## Java Syntax
Ich wusste bereits das jeder Quellcode in Java mit einer class verbunden ist. Den Befehl ```System.out.println("Hello World")```kannte ich ebenfalls schon. Der sagt eigentlich nur aus das dieses Hello World ausgegeben werden soll. Trotzdem habe ich die Übung dazu nochmal wiederholt.
## Java Comments
Ich wusste das man eine Zeile mit dem Befehl ```//Beliebiger Text``` auskommentiert. Allerdings kannte ich nicht die Funktion ```/*Beliebiger Text*/``` um mehrere Zeilen auszukommentiern. Die Übungen habe ich dazu ebenfalls wiederholt
## Java Variables/Data Types
Variablen an sich kannte ich schon aus anderen Programmiersprachen, da die so gut wie immer benötigt werden um eine Variable Zahl,Buchstaben oder auch einen Satz auszugeben.Einige davon kannte ich von meiner alten Schule aus dem Programmierunterricht wo wir mit VB6 programmiert haben. 
* Bekannt war mir deshalb:
  * ```String``` - Um einen Text auszugeben
  * ```int``` - Was ganze Zahlen umfasst(-2147483648 bis 2147483647)
  * ```long``` - Welche sehr große Zahlen darstellen lässt(-9223372036854775808 bis 9223372036854775807)
  * ```float``` - Welche Kommazahlen darstellen
  * ```double``` - Welche Kommazahlen darstellen(größere Zahlen)
* Diese kannte ich nicht
  * ```byte``` - Für ganz kleine Zahlen(-128 bis 127)
  * ```short``` - Für kleine Zahlen(-32,768 bis 32,767)
  * ```boolean``` - Für **true** or **false** Abfragen
  * ```char``` - Für Buchstaben oder Symbole
## Java Type Casting
Java Type Casting ist eine Methode um eine bestimmte Variable in eine anderen Variable zu ändern. Zum Beispiel eine Zahl wie Int(5) in Double(5,0) umzuwandeln. Für diese Funktion gibt es 2 Varianten.
* **Widening Casting** geschieht automatisch. Dies konvertiert eine kleine Variable zu einer größeren.
```byte``` -> ```short``` -> ```char``` -> ```int``` -> ```long``` -> ```float``` -> ```double```
Beipsiel: ```public class MyClass {
  public static void main(String[] args) {
    int myInt = 9;
    double myDouble = myInt; // Automatic casting: int to double

    System.out.println(myInt);      // Outputs 9
    System.out.println(myDouble);   // Outputs 9.0
  }
}```
