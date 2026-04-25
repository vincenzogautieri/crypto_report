# Crypto Report

Script Python per il recupero automatico e l'analisi
dei dati delle top 100 criptovalute tramite API CoinMarketCap.
Il report viene generato e salvato ogni 24 ore in formato JSON.

## Funzionalità
- Connessione all'API CoinMarketCap (dati in tempo reale)
- Identificazione della crypto con volume maggiore nelle 24h
- Classifica delle top 10 migliori e peggiori per variazione %
- Calcolo del costo per acquistare una unità delle prime 20 crypto
- Simulazione della percentuale di guadagno/perdita giornaliera
- Salvataggio automatico del report in formato JSON con data

## Tecnologie utilizzate
- Python 3
- `requests` – chiamate API REST
- `json` – generazione e salvataggio report
- `datetime` – gestione date e naming automatico dei file
- CoinMarketCap Pro API

## Output
Il report viene salvato come file JSON giornaliero

## Scopo
Progetto personale per approfondire l'uso di API finanziarie
in Python e l'analisi automatizzata di dati di mercato.
