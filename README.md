# LA1300_Beaver

# Kursanmeldung

## Aufgabenstellung und Ziele

Im Lernatelier durften wir in der Gruppe zusammen ein Programm in C# machen, in dem man sich in Kurse anmelden kann und danach in einem Kurs eingeteilt wird. Für dies brauchte es eine Mail-Adresse, also werde ich probieren, Ihnen zu erklären, wie man automatisch eine Mail austeilt.

**Ziele**:
1. Der Leser versteht, wie man dem User automatisch eine Email einteilt.
## Inhalt 1

Im Programm, dass wir machten, brauchte es die E-mail Adresse des Users, um sie in ein Kurs einzuteilen. Es hatte eine bestimmte Vorgabe für den E-mail, also konnten wir nicht dem User erlauben, die E-mail Adresse selber zu schreiben. Der Aufbau der Adresse musste "Vorname.Nachname@stud.bbbaden.ch" sein. Damit wir also kontrollieren konnten, dass die E-mail richtig aufgebaut ist, mussten wir nach der Vor- und Nachname des Users fragen. Der Rest war einfach, man musste nur noch eine "Formel" schreiben, damit das Programm automatisch die E-mail ausgibt. In dieser "Formel" war alles vorgegeben, und der Name des Users wurde automatisch eingeteilt und somit wurde eine ganze Mail-adresse ausgegeben, so wie sie vorgegeben wurde.

## Inhalt 2
Hier ist ein Code-Beispiel, wie wir es in unserem Programm ausgeübt haben:
```csharp
string vorname = ConsoleReadLine();
string nachname = Console.ReadLine();
Console.WriteLine(vorname + "." + nachname + "@stud.bbbaden.ch");
```

## Inhalt 3

Hier zeige ich, wie es mit dem automatischen E-mail aussieht:
[YouTube Video](https://www.youtube.com/watch?v=rdfIafQPElk)

## Verifikation + Reflektion 

**Reflektion**:
Ich hatte sehr viel übrige Zeit, während manche Teammitglieder sehr viel zu tun hatten, weil wir die Aufgaben nicht gut aufteilen konnten und wir konnten in der Gruppe nicht gut kommunizieren.
VBV: Das nächste Mal werden wir die Aufgaben so aufteilen, dass alle ungefähr gleich viel zu tun haben, damit niemand mehr als dem anderen arbeitet. 

**Verifikation**:
Ziel 1: Ich habe dieses Portfolio meinem Pultnachbar gezeigt, *Ziel erreicht, aber es hatte viele Rechtschreibfehler.*
