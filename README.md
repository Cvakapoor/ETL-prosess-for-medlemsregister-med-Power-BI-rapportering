### 🧾 Analyse av medlemsbetalinger

Dette prosjektet utfører datarensing og validering av medlems-, betalings- og kontingentdata for å sikre konsistens og identifisere avvik i en medlemsdatabase.

## 📊 Prosjektmål

  ## Forstå og rense data
    
  Laste inn og analysere data fra tre Excel-ark: Medlemmer, Kontingent og Betalinger.
    
  Håndtere manglende verdier og oppdage duplikater.
    
  Beregne medlemmers alder basert på fødselsdato og kontrollere medlemstype.

  ## Transformasjon og validering
    
  Tildele korrekt medlemstype (Junior, Senior, Veteran) basert på aldersregler.
    
  Matche hvert medlem med deres betaling og forventet kontingent basert på medlemstype og år.
    
  Identifisere:
    
  Medlemmer med feil eller manglende medlemstype
      
  Dupliserte medlemmer eller betalinger
      
  Manglende betalinger
      
  Avvik i betalingsbeløp

  ## Rapportering og visualisering
    
  Samlet og renset datasett eksporteres som en endelig rapport.
    
  Interaktivt dashboard laget i Power BI, som visualiserer:
    
  Betalingsstatus
      
  Fordeling av medlemstyper
      
  Avvik og feilkilder

## 📁 Datakilder

  Medlemmer: Informasjon om medlemmer (navn, fødselsdato, kjønn, osv.)
  
  Kontingent: Satser for medlemskontingent etter type og år
  
  Betalinger: Registrerte betalinger

## 🛠️ Verktøy brukt

  Python – til datarensing og transformasjon
  
  pandas – for datamanipulasjon
  
  Power BI – for visualisering og rapportering

## 📈 Hvordan det fungerer
  
  Hent data:
  
  Laste inn Excel-filer med pandas.read_excel.
  
  Transformer:
  
  Rense for manglende verdier og ugyldige datoer.
    
  Beregne alder (basert på året 2017).
    
  Tilordne riktig medlemstype.
    
  Identifisere og håndtere duplikater og mangler.
  
  Last / Visualiser:
  
  Slå sammen datasett og flagge uoverensstemmelser.
    
  Eksportere endelig datasett til Power BI for interaktiv visualisering.

✅ Status
  
  ✔️ Datarensing fullført
  
  ✔️ Betalingsmatching gjennomført
  
  ✔️ Validering mot kontingentregler fullført
  
  ✔️ Rapport eksportert
  
  ✔️ Visualisering fullført i Power BI
