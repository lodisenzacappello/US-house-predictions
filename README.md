FORECASTING DEL NUMERO DI UNITA' ABITATIVE NEGLI STATI UNITI

Il progetto si basa sull'analisi della serie temporale del numero di  "Unità abitative a scopo residenziale autorizzate ma non ancora costruite negli US - Totale delle unita [migliaia di unità ] non corrette per la stagionalità".
La time series in analisi è stata redatta dall' "U.S. Census Bureau" ed è composta da 548 osservazioni.
La time series contiene le misurazioni mensili da gennaio 1980 fino ad agosto 2025.
Lo scopo dell'analisi è individuare il modello ARIMA alla base della time series e fare previsioni sul mercato immobiliare americano nei 12 mesi successivi all'agosto 2025.

I dati dell'ultimo trimestre del 2025 non erano ancora disponibili in data di analisi a causa dello shutdown governativo che ha colpito gli Stati Uniti dall'1 ottobre.

#------------------------------------------------------------------------------------------------------------------------------------------------

FASE 1: ANALISI ESPLORATIVA DELLA TIME SERIES

FASE 2: VALUTAZIONE DELLA NON STAZIONARIETA'

FASE 3: STIMA DEI MODELLI ARIMA

    ARIMA(2,1,2)x(2,1,1)
  
    ARIMA(3,1,2)x(1,1,1)
  
    ARIMA(2,1,2)x(1,1,1)
    

FASE 4: CONTROLLO DELL'IMPATTO DEI REGRESSORI ESTERNI

    ARIMA(2,1,2)x(1,1,1) + ["Mon" , "wd"]
  
    ARIMA(3,1,2)x(1,1,1) + ["Mon" , "wd"]
  
    ARIMA(2,1,2)x(1,1,1) + ["Mon" , "wd"]
    

FASE 5: VALUTAZIONE DELLE ANOMALIE

FASE 6: DIAGNOSTICHE FINALI SUI RESIDUI DEL MODELLO

FASE 7: PREVISIONI EX-ANTE

#------------------------------------------------------------------------------------------------------------------------------------------------
  
#------------------------------------------------------------------------------------------------------------------------------------------------
  
  
