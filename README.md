# 📱 Aplikasi Kartu Nama Digital (Kartu-Nama)

Sebuah aplikasi Android sederhana yang dibuat menggunakan Kotlin dan berfungsi sebagai kartu nama digital untuk menampilkan informasi kontak dan profesional. Proyek ini dibuat untuk mendemonstrasikan dasar-dasar pengembangan Android modern.



#✨ Fitur Utama
* Informasi Lengkap: Menampilkan informasi penting seperti nama, jabatan, dan detail kontak.
* Akses Cepat: Menyediakan tautan interaktif untuk email, nomor telepon, dan media sosial.
* Antarmuka Modern: Didesain dengan antarmuka yang bersih dan minimalis menggunakan komponen Material Design.
* Struktur Modern: Dibangun dengan arsitektur dan komponen Android terbaru.


#🛠️ Teknologi yang Digunakan
* Bahasa: [Kotlin](https://kotlinlang.org/)
* IDE: [Android Studio](https://developer.android.com/studio)
* Build System: [Gradle](https://gradle.org/)
* UI/UX: Material Components for Android, XML Layouts

## 📂 Struktur Proyek
Berikut adalah struktur direktori standar yang digunakan dalam proyek ini.

```
Kartu-Nama/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/
│   │   │   │       └── example/
│   │   │   │           └── kartunama/
│   │   │   │               ├── MainActivity.kt      # <-- File kode Kotlin utama
│   │   │   │               └── (file-file lainnya...)
│   │   │   ├── res/
│   │   │   │   ├── drawable/                      # <-- Gambar, ikon, bentuk XML
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml        # <-- File layout UI (XML)
│   │   │   │   ├── mipmap/                        # <-- Ikon aplikasi (ic_launcher)
│   │   │   │   └── values/
│   │   │   │       ├── colors.xml
│   │   │   │       ├── strings.xml
│   │   │   │       └── themes.xml
│   │   │   └── AndroidManifest.xml              # <-- Manifest aplikasi (izin, komponen)
│   ├── build.gradle.kts                         # <-- Konfigurasi build khusus untuk modul 'app'
│   └── proguard-rules.pro                     # <-- Aturan ProGuard untuk optimasi kode
│
├── .gitignore
├── build.gradle.kts                             # <-- Konfigurasi build untuk SELURUH proyek
├── gradle.properties
├── gradlew                                      # <-- Gradle wrapper script untuk Mac/Linux
├── gradlew.bat                                  # <-- Gradle wrapper script untuk Windows
└── settings.gradle.kts                          # <-- Pengaturan modul dalam proyek
```

# 🚀 Cara Menjalankan Proyek
Untuk menjalankan proyek ini di komputer Anda, ikuti langkah-langkah berikut:

1.  Clone repositori ini
    ```bash
    git clone [https://github.com/Achmadtegar23/Kartu-Nama.git](https://github.com/Achmadtegar23/Kartu-Nama.git)
    ```
2.  Buka proyek menggunakan Android Studio.
3.  Tunggu hingga Gradle Sync selesai mengunduh semua dependensi yang diperlukan.
4.  Jalankan aplikasipada Emulator atau perangkat Android fisik. (Jika bermasalah silahkan berdiskusi dengan AI)

## 📄 Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

_Jangan ragu untuk memberikan bintang ⭐ pada repositori ini jika Anda merasa terbantu!_
