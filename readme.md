# COMPRARE QUALCOSA SU AMAZON
//scegliere un libro in base al budget, consegna prime

dichiaro il budget

dichiaro regalo di Silvia

accendo il pc

vado sulla pagina web di Amazon

apro la catogoria libri

?SE RICORDO IL GENERE DI LIBRO CHE PIACE A SILVIA
    - dichiaro la categoria che piace a Silvia

    - Vado nella categoria genere libro =  categoria che piace a Silvia

    - guardo le recensioni


    RIPETI FINO A CHE LIBRO NON è NEL CARRELLO
        ?SE  RECENSIONE > 4.5 STELLE
            - apro il dettaglio del libro
            - leggo la sinossi
            ?SE MI PIACE 
                - controllo il budget 
                ?SE (budget < or = prezzo libro) and (il libro ha la consegna Prime)
                    - metto il libro nel carrello
                    - libro = regalo di silvia
                    - apro il carrello per comprare
                    - scelgo indirizzo
                    - scelgo metodo di pagamento
                    - compro il libro.


                
                ALTRIMENTI 
                    - continuo a cercare
            
            ALTRIMENTI 
                - continuo a cercare

        ALTRIMENTI 
            - continuo a cercare
        
    FINE RIPETI


ALTRIMENTI

    - dichiaro la catogoria che piace a me

    - Vado nella categoria genere libro =  categoria che piace a Silvia

    - scelgo tra i libri che sono piaciuti tanto a me

    - dichiaro lista di libri piaciuti a me

    scorro la lista FINCHE' regalo silvia è nel carrello
       
        - controllo il budget 
        ?SE (budget < or = prezzo libro) and (il libro ha la consegna Prime)
            - metto il libro nel carrello
            - libro = regalo di silvia
            - apro il carrello per comprare
            - scelgo indirizzo
            - scelgo metodo di pagamento
            - compro il libro.


        
        ALTRIMENTI 
            - continuo a cercare

   

       
    