# FCD Studio Legale Agenda

Applicazione Android di prova (v1.1) per l'organizzazione dello Studio Legale FCD.

Il codice incluso usa esclusivamente dati fittizi di esempio. Non caricare nel repository dati personali dei clienti, documenti processuali, backup o password.

## APK Android

Apri la scheda [Actions](https://github.com/carlodragoni/FCD-STUDIO-LEGALE/actions) e il workflow **Compila FCD Agenda APK**. Al termine, l'APK di debug è reperibile negli artifact del workflow. È una build di prova, non un'app pubblicata sul Play Store.

## Sorgente

`android-source.tar.xz.b64` contiene un progetto Android Studio compresso, incorporato in base64; il workflow lo espande, compila e pubblica un APK. Il file è utile anche per ricostruire il progetto offline.

**Limiti:** alert nell'app/esportazione calendario, niente sincronizzazione automatica PolisWeb/Giustizia Civile e niente notifiche in background. Il calcolo dei termini processuali va verificato manualmente, e non usare dati riservati fino alla validazione del prototipo.
