# MoKeep Android Native 📱

Aplikasi Pencatat Keuangan Pribadi (Android Native) yang dibangun dengan **Kotlin**, **Jetpack Compose (Material 3)**, dan **Room/SQLite Database** (100% Offline tanpa server).

---

## 🌟 Fitur Utama
- **100% Offline**: Data tersimpan langsung di memori HP (`mokeep_local.db`).
- **Multi-Akun / Dompet (Wallets & Pockets)**: Kas/Tunai, Bank, E-Wallet, Kartu Kredit, Investasi.
- **Fleksibel**: Nomor rekening bersifat opsional (tidak wajib).
- **Mutasi & Catat Transaksi**: Pemasukan, Pengeluaran, Transfer antar dompet secara atomik.
- **Anggaran Bulanan (Budget)**: Monitoring pengeluaran per kategori dengan progress bar.
- **Target Tabungan (Impian/Goals)**: Visualisasi target dan pencatatan kontribusi tabungan.
- **Laporan & Analisis Arus Kas**: Ringkasan pemasukan vs pengeluaran & persentase kategori.
- **Ekspor Data**: Simpan dan bagikan riwayat transaksi ke format CSV langsung dari HP.

---

## 🛠️ Tech Stack
- **Bahasa**: Kotlin (100% Native)
- **UI Framework**: Jetpack Compose + Material 3
- **Database**: Android SQLite Local Storage
- **Architecture**: Clean MVVM-ready Repository Pattern
- **Min SDK**: Android 7.0 (API 24)
- **Target SDK**: Android 15 / 16 (API 36)

---

## 📦 Build Project
Jalankan perintah berikut menggunakan terminal:
```bash
./gradlew assembleDebug
```
File APK akan berada di: `app/build/outputs/apk/debug/app-debug.apk`
