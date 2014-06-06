Top level classes, outer classes - unverschachtelte, äußere Klassen - sind nich verschachtelt.

Nested classes - verschachtelte Klassen - werden gebrauch um Informationen zu verstecken und um die Kommunikation zwischen Objekten zu optimieren:
Zwei Varianten; statische verschachtelte Klassen (static nested classes) und innere Klassen (inner classes).
Haben keine Verbindung zu einer Instanz der äußeren Klasse.
Werden nur dort verwendet, wo die Funktionalität nur in der äußeren/besitzenden Klasse benötigt wird.
Wegen Übersichtlichkeit sollen nicht größer werden.
Wird wie ein sonstiges Member innerhalb der äußeren Klasse definiert.
Kann selbst statische oder dynamische Membervariablen haben.
Die Methoden können statisch oder dynamisch sein, von der statischen Methode kann nicht auf dynamische Member der äusseren Klassen zugegriffen werden.
Von der äußere Klasse kann auf Member der verschachtelten Klasse per Punktnotation zuegriffen werden.




Innere Klassen - Zugriff auf Membervariablen der umschließenden Klasse. Können nicht ohne Instanz der äußeren Klasse instanziiert werden und dies nur in einem nicht-statischen Kontext.
Zwei Varianten: benannt oder anonym.
Die Kompilierung - AeussereKlasse$InnereKlasse.class.

Staische innere Klassen gibt es nicht.