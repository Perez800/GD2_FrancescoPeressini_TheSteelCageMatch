# GD2_FrancescoPeressini_TheSteelCageMatch
 Modulo Unreal Enginge GD2 Francesco Peressini
Nel gioco due player si affrontano tentando di colpirsi a vicenda. Quando si colpiscono, quello che si trova più in alto tra i due segna un punto. A 3 punti si vince la partita.
Bug presenti:
La variabile isGrounded del player 2 non funziona correttamente e viene visualizzata come vera e falsa allo stesso tempo: Il player 2 è quindi in grado di saltare senza trovarsi a terra;
Ogni tanto il secondo player viene creato sul primo PlayerStart assegnando subito un punto al Player 2
