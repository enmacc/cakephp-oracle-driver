Changelog
=========

* 1.0.5 Porting Cake 3.7
        
        Dopo l'aggiornamento di cake il driver modificato per i deprecated
        Errore nel parser? MethodStatementDecorator. Il fetch in  
        /src/Database/Statement/OracleBufferedStatement.php lo lascio.. test

* 1.0.4
    
        Errore nel model generation di cake, cambiato OracleSchema issue 4 su gitlab
        dovuto alla colonna indice che e una variabile a cui corrisponde una funzione
        ovvero type FUNCTION-BASED NORMAL

* 1.0.3 

        Altro bugfix, sempre nella generazione dello script create, Default veniva messo 2 volte nel 
        caso era null e c'era default. Poi i  valori di tipo string  di default  come  venivano scritti con
        3 apici

* 1.0.2
    
        bugfix in oracleschema, per il create script errato

* 1.0.1

        Modifiche base di Rugg e mie per composer

* 1.0.0

        Initial version of the CakePHP Driver for Oracle Database
