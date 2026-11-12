# Kelompok 2 Kode 02 — Anotasi Deteksi Objek Citra Berasap

## 1. Deskripsi Proyek

Proyek ini merupakan tugas kelompok untuk melakukan anotasi deteksi objek pada citra yang memiliki kondisi tertutup kabut atau asap.

Anotasi dilakukan menggunakan metode **Bounding Box** dengan bantuan platform **Roboflow**. Dataset yang dikumpulkan digunakan untuk mengenali dan menandai objek yang terdapat pada citra berasap.

## 2. Informasi Dataset

| Keterangan | Detail |
|---|---|
| Nama Proyek | Deteksi Objek Citra Berasap |
| Kelompok | Kelompok 2 |
| Kode Kelompok | 02 |
| Jumlah Gambar | 100 gambar |
| Metode Anotasi | Bounding Box |
| Platform Anotasi | Roboflow |
| Format Anotasi | YOLO |
| Jenis Tugas | Object Detection |

## 3. Kelas Objek

Objek yang menjadi fokus anotasi dalam dataset ini meliputi:

1. Manusia
2. Kendaraan
3. Gedung
4. Vegetasi
5. Titik Api

## 4. Struktur Dataset

Dataset disusun menggunakan format YOLO dengan struktur sebagai berikut:

```text
dataset/
├── train/
│   ├── images/
│   └── labels/
├── valid/
│   ├── images/
│   └── labels/
├── test/
│   ├── images/
│   └── labels/
└── data.yaml
```

**Keterangan:**

- `train`: Data untuk pelatihan.
- `valid`: Data untuk validasi.
- `test`: Data untuk pengujian.
- `images`: Berisi gambar.
- `labels`: Berisi anotasi bounding box.
- `data.yaml`: Konfigurasi dataset dan kelas objek.

## 5. Tools yang Digunakan

- **Roboflow:** Mengelola dataset dan melakukan anotasi bounding box.
- **GitHub:** Menyimpan dataset, dokumentasi, dan hasil pengerjaan kelompok.
- **YOLO:** Format penyimpanan anotasi objek.

## 6. Cara Mengunduh Dataset

1. Buka halaman repository GitHub ini.
2. Klik tombol **Code**.
3. Pilih **Download ZIP**.
4. Ekstrak file ZIP yang telah diunduh.
5. Buka folder `dataset` untuk mengakses gambar dan label.

Dataset juga dapat diunduh melalui versi dataset Roboflow yang digunakan dalam proyek ini.

## 7. Pembagian Tugas Anggota

| No. | Nama Anggota | Tanggung Jawab |
|---|---|---|
| 1 | Desti Fatimatuzzahra | Pengelolaan project Roboflow, anotasi bounding box, pengelolaan dataset, repository GitHub, dan dokumentasi. |
| 2 | Suci Salwa Amalia | Pencarian dan pengumpulan gambar untuk dataset. |
| 3 | Miracle Yuanita M | Pencarian dan pengumpulan gambar untuk dataset. |
| 4 | Nayla Riskahana | Pencarian dan pengumpulan gambar untuk dataset. |

## 8. Bukti Kontribusi GitHub

Tautan commit masing-masing anggota akan dicantumkan sebagai bukti kontribusi pengerjaan proyek.

| Nama Anggota | Bukti Commit |
|---|---|
| [Nama Kamu] | [Link Commit] |
| [Nama Anggota 2] | [Link Commit] |
| [Nama Anggota 3] | [Link Commit] |
| [Nama Anggota 4] | [Link Commit] |

## 9. Dokumentasi

Dokumentasi proses pengerjaan, screenshot Roboflow, dan contoh hasil anotasi dapat dilihat pada folder `dokumentasi` di repository ini.

## 10. Lisensi

Repository ini menggunakan **MIT License** untuk materi yang memang menjadi hak kelompok untuk dilisensikan.

Hak penggunaan gambar pihak ketiga tetap mengikuti lisensi atau izin dari sumber masing-masing.

Lihat file `LICENSE` untuk informasi lebih lanjut.

---

**Kelompok 2 — Kode 02**  
*Anotasi Deteksi Objek Citra Berasap*