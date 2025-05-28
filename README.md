# Standarisasi Dokumentasi Riset (SDR)

**Tujuan Dokumen:**  
Dokumen ini bertujuan untuk menyusun dan mengarsipkan proses riset secara sistematis. Format ini dirancang untuk menjaga konsistensi dokumentasi di seluruh proyek riset di Workshop Robotika, agar memudahkan pemahaman lintas tim, evaluasi hasil, serta publikasi.

---

## 📂 Ringkasan Riset

- **Tim/Divisi:** [Nama tim, misal: KRSTI / NAWASENA]
- **Tipe Perangkat:** [Misal: ESP32, STM32, Raspberry Pi, dsb]
- **Tanggal Mulai - Selesai:** [dd/mm/yyyy - dd/mm/yyyy]
- **Status:** 🚧 _Dalam Pengembangan_ / ✅ _Selesai_ / 🧪 _Eksperimen_

---

## 1. 📚 Latar Belakang

Jelaskan alasan mengapa riset ini dilakukan. Sertakan:
- Masalah teknis atau ilmiah yang hendak diselesaikan.
- Signifikansi atau manfaat dari hasil riset.
- Keterkaitan riset ini dengan perkembangan teknologi atau kebutuhan praktis.

---

## 2. 🎯 Tujuan

Rinci tujuan riset secara umum dan khusus, seperti:
- Tujuan utama yang ingin dicapai.
- Sub-tujuan atau milestone penting dalam proses riset.
- Sasaran fungsional maupun eksperimental.

---

## 3. 🔬 Metodologi

Tabel berikut merinci tools dan teknologi utama yang digunakan dalam riset ini:

| Komponen           | Deskripsi                                                |
|--------------------|----------------------------------------------------------|
| Platform           | [ESP32, STM32, Arduino, dsb.]                           |
| Bahasa Pemrograman  | [C/C++, MicroPython, dsb.]                               |
| IDE                | [Arduino IDE, STM32CubeIDE, dsb.]                        |
| Komunikasi         | [UART, I2C, Bluetooth, WiFi, dsb.]                       |
| Dependensi         | [Library eksternal atau modul tambahan]                  |
| Framework          | [Kerangka kerja yang digunakan, misalnya: SPL, STM32 HAL, PlatformIO] |

- Jelaskan algoritma atau teori yang diterapkan.
- Jelaskan platform atau perangkat keras yang relevan.

---

## 4. ⚙️ Perancangan Sistem

Deskripsikan rancangan sistem secara keseluruhan:
- Diagram arsitektur atau diagram blok sistem (sertakan gambar/link).
- Penjabaran tiap komponen utama dan perannya dalam sistem.
- Relasi antar modul (komunikasi, alur data, kendali, dll).

---

## 5. 🧪 Eksperimen & Evaluasi

Dokumentasikan proses dan hasil pengujian:
- Metode eksperimen: prosedur, skenario uji, setup perangkat.
- Parameter yang diukur dan bagaimana pengukurannya.
- Hasil eksperimen (dapat disertai tabel, grafik, atau referensi file di `/results`).
- Dataset atau input uji yang digunakan.

---

## 6. 📊 Analisis & Pembahasan

Bahas hasil eksperimen secara kritis:
- Interpretasi hasil dan kaitannya dengan tujuan riset.
- Identifikasi kelemahan sistem atau anomali hasil.
- Komparasi dengan metode lain (jika ada).
- Insight teknis yang didapat selama proses riset.

---

## 7. ✅ Kesimpulan & Rencana Lanjut

Tuliskan ringkasan hasil riset:
- Apakah tujuan riset telah tercapai?
- Kontribusi utama dari riset ini.
- Rekomendasi pengembangan lebih lanjut, baik secara teknis maupun arah riset.

---

## 8. 🕒 Riwayat Revisi

Catat setiap perubahan besar pada dokumen ini:

| Versi | Tanggal     | Deskripsi Perubahan       | Penulis       |
|-------|-------------|--------------------------|---------------|
| 1.0   | YYYY-MM-DD  | Deskripsi awal           | Nama          |
| 1.1   | YYYY-MM-DD  | Perubahan besar berikutnya| Nama          |

---

## 9. 📁 Struktur Folder (Opsional)

Jelaskan struktur direktori proyek untuk memudahkan navigasi:

```

/src          → Source code utama
/include      → Header file
/results      → Data eksperimen dan grafik
/docs         → Dokumen pendukung dan SDR
/scripts      → Tool bantu, script analisis, dsb.

```

---

📌 **Catatan:**  
Dokumen SDR ini wajib diperbarui secara berkala, minimal setiap akhir sprint atau fase utama proyek. Gunakan format ini sebagai dasar yang konsisten untuk seluruh tim dalam organisasi riset Workshop Robotika.

---

**Contoh Riset:**  
- https://github.com/NawasenaKRSTI/Connect_PS3_KWSuper  
- https://github.com/NawasenaKRSTI/esp32_nvs
