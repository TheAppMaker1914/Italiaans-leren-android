ITALIAANS LEREN – ANDROID APP

Dit project verpakt de bestaande cursus als een Android-app.
De cursus wordt lokaal in de app geopend; JavaScript en localStorage zijn ingeschakeld,
zodat de bestaande voortgangsopslag in de WebView kan werken.

ZO KRIJG JE DE APK VIA GITHUB:

1. Maak op GitHub een NIEUWE repository aan, bijvoorbeeld 'italiaans-leren-android'.
2. Pak dit ZIP-bestand uit op je computer.
3. Upload alle bestanden en mappen uit deze map naar de hoofdmap van die nieuwe repository.
   Upload dus ook de verborgen map '.github'.
4. Ga in GitHub naar het tabblad 'Actions'.
5. Open de workflow 'Bouw Android APK'. Als die niet vanzelf gestart is:
   kies 'Run workflow'.
6. Wacht tot de workflow groen is.
7. Open de geslaagde workflow-run en download onder 'Artifacts' het bestand
   'ItaliaansLeren-APK'.
8. Pak de download uit. Daarin staat 'app-debug.apk'.
9. Zet de APK op je Android-telefoon en open hem om te installeren.
   Mogelijk moet Android toestemming vragen om apps uit deze bron te installeren.

LET OP:
- Dit ZIP-bestand is het Android-project, nog niet de kant-en-klare APK.
- De APK wordt door GitHub Actions gebouwd.
- Dit is een debug-APK voor persoonlijk gebruik, geen Play Store-release.
- De cursusinhoud is dezelfde HTML-versie die bij dit project is meegeleverd.
