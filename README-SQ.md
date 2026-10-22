# FilmAlb për Android

Ky është projekti fillestar i një aplikacioni Android që hap `https://filmalb.xyz/` brenda aplikacionit duke përdorur Android WebView. Kështu, menutë dhe kërkimi sipas kategorive vijnë nga vetë faqja dhe mund të ndryshojnë nëse faqja ndryshon.

## Si ta ndërtoni APK-në

1. Instaloni Android Studio në kompjuter.
2. Hapni Android Studio dhe zgjidhni **Open**, pastaj këtë dosje `FilmAlbAndroid`.
3. Prisni për Gradle Sync dhe instaloni SDK platform 35 nëse kërkohet.
4. Zgjidhni **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. APK-ja e debug-ut zakonisht krijohet te `app/build/outputs/apk/debug/app-debug.apk`.

## Kufizime të rëndësishme

- Projekti nuk shkarkon, kopjon apo anashkalon mbrojtje të filmave. Ai shfaq faqen e internetit brenda WebView.
- Funksionimi varet nga disponueshmëria dhe mënyra se si faqja lejon t'u qasen shfletuesve të integruar.
- Përdorni vetëm përmbajtje që keni të drejtë ta shikoni ose shpërndani.
- Për publikim në Google Play, do të duhen kontrolluar rregullat për përmbajtjen, privatësinë dhe markën.
