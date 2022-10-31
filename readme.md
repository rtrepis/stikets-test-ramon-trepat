Maquetació

	Traduir disseny de "design/design.png" a HTML+CSS amb JQuery (Tot el que no està present en el disseny -Icones, pop-ups, etc ...- es pot implementar d'una forma lliure).

Interacció

	Mitjançant JQuery com a llibreria principal:

		1 - Validar que el format de camp email sigui efectivament un correu electrònic i que a més sigui requerit, el camp password també és requerit. Si algun dels camps no passes les validacions ha de mostrar el missatge d'error en un tooltip (diseny lliure).

		2 - Al pressionar el botó "SIGN IN" s'ha de validar que l'usuari i contrasenya siguin vàlids, per a això s'ha de "llegir" amb javascript l'arxiu remote.JSON i permetre l'accés només a aquests usuaris, si l'usuari i contrasenya no són vàlids s'ha d'informar a l'usuari: "Les dades ingressades són incorrectes" a través d'un pop-up.

		3 - Si les dades ingressades a la finestra de login són correctes s'ha de mostrar un pop-up indicant el següent missatge: "Les dades són correctes, Benvingut" i redirigir petició a www.stikets.es passat 5 segons.
