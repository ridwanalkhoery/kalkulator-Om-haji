KALKULATOR SHOPEE - PROYEK APK ANDROID

Ini adalah proyek aplikasi Android native berbasis WebView (bukan sekadar shortcut browser).
File APK belum dapat dikompilasi di lingkungan pembuatan ini karena Android SDK dan Gradle tidak tersedia. Proyek ini disiapkan agar dapat dibuka dan dibangun melalui Android Studio.

CARA MEMBUAT APK:
1. Unduh dan pasang Android Studio di komputer/laptop.
2. Ekstrak ZIP proyek ini.
3. Android Studio > Open > pilih folder KalkulatorOmHajiAndroid.
4. Tunggu Gradle Sync dan unduh Android SDK Platform 35 jika diminta.
5. Pilih Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Setelah selesai, klik "locate" pada notifikasi build. APK ada di app/build/outputs/apk/debug/app-debug.apk.
7. Pindahkan APK ke HP Android dan izinkan instalasi dari sumber tersebut jika diminta.

Untuk APK rilis yang ditandatangani:
Build > Generate Signed Bundle / APK > APK, lalu buat/ pilih keystore milik sendiri.

Aplikasi memuat kalkulator dari app/src/main/assets/index.html.
Semua kalkulasi berjalan di perangkat. Pengaturan disimpan secara lokal melalui localStorage WebView.

Catatan:
- applicationId: id.kalkulatoromhaji.app
- Minimum Android: Android 6.0 (API 23)
- Versi awal: 1.0
- Tarif biaya adalah input/estimasi yang dapat diubah; bukan tarif resmi yang diverifikasi Shopee.
