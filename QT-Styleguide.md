Im Styleguide wird festgelegt, wie gewisse Widgets zu heißen haben und welche Programmierregeln generell einzuhalten sind.

- Variablen sind immer sinnvoll zu benennen, bei mehreren Wörtern als ein Wort durch Großuchstaben getrennt, z.B. int nennerErsterBruch
- Arrays sind in der Einzahl zu benennen, z.B. QString Farbe [4] = {"Rot", "Blau", "Gelb", "Grün"}
- Es wird kein goto verwendet.
- Es wird soweit möglich dem EVA-Prinzip gefolgt.
- Hinter einer schließenden Klammer folgt ein Kommentar z.B. }//for
- Es werden keine globalen Variablen benötigt.
- Es erfolgt nur ein Return pro Funktion.
- Wir verwenden nur bei einzeiligen Anweisungen Klammern z.B. if (b>0){b--,}
- Der Code wird immer passend eingerückt (ctrl+a -> ctrl+i)
- Wir verwenden kein else if(){, wir machen else{if()};
- Code wird soweit möglich von Widget-Methoden in andere Methoden oder Funktionen ausgelagert.

Widgets(Auswahl)

- PushButton -> btnName
- CheckBox -> chkbxName
- LineEdit -> edtName
- TextEdit -> txtedtName
- Label -> lblName
- TextBrowser -> txtName
