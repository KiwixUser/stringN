# stringN

Ziel ist eine performante String-Klasse zum Erzeugen einfacher String fester Maximalgröße.

Hauptaugenmerk ist hierbei: 
* sehr wenig Zeit zu benötigen
* Einfache Konstruktion von typischer rudimentärer "innerbetrieblichen" Stringverarbeitung.

Weniger: 
* komplexe String-Operationen durchzuführen, auch wenn ich das jetzt noch nicht prinzipiell ausschließen möchte.

Haupteinschränkung:
* Speicher wird im Objekt selbst angelegt, d.h.
* die maximale Größe muss zur Compilezeit bekannt sein. 
