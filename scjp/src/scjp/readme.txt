Top level classes, outer classes - unverschachtelte, �u�ere Klassen - sind nich verschachtelt.

Nested classes - verschachtelte Klassen - werden gebrauch um Informationen zu verstecken und um die Kommunikation zwischen Objekten zu optimieren:
Zwei Varianten; statische verschachtelte Klassen (static nested classes) und innere Klassen (inner classes).
Haben keine Verbindung zu einer Instanz der �u�eren Klasse.
Werden nur dort verwendet, wo die Funktionalit�t nur in der �u�eren/besitzenden Klasse ben�tigt wird.
Wegen �bersichtlichkeit sollen nicht gr��er werden.
Wird wie ein sonstiges Member innerhalb der �u�eren Klasse definiert.
Kann selbst statische oder dynamische Membervariablen haben.
Die Methoden k�nnen statisch oder dynamisch sein, von der statischen Methode kann nicht auf dynamische Member der �usseren Klassen zugegriffen werden.
Von der �u�ere Klasse kann auf Member der verschachtelten Klasse per Punktnotation zuegriffen werden.




Innere Klassen - Zugriff auf Membervariablen der umschlie�enden Klasse. K�nnen nicht ohne Instanz der �u�eren Klasse instanziiert werden und dies nur in einem nicht-statischen Kontext.
Zwei Varianten: benannt oder anonym.
Die Kompilierung - AeussereKlasse$InnereKlasse.class.

Staische innere Klassen gibt es nicht.