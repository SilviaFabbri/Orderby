# Orderby
Come ordinare il DateTime di un Array di stringhe

Avevo bisogno di ordinare un file in base al DateTime contenuto nelle stringhe, si tratta di un gestionale "casalingo" volto a mantenere il tracciamento delle scadenze della dispensa di prodotti confezionati e deperibili.
Ho trovato informazioni utili nella documentazione microsoft, ho impiegato alcune ore a risolvere il rompicapo in quanto IEnumerable proposto mi ordinava
le date in base ai primi 2 numeri della data.
ho composto il riordino del DateTime in tre tempi, prima il giorno, poi il mese e infine l'anno.
Ora il mio applicativo desktop funziona come desideravo. Spero possa essere utile a qualcuno.
