<div align="center">

```
██████╗  ██████╗ ██╗   ██╗██╗  ██╗
██╔══██╗██╔════╝ ██║   ██║██║ ██╔╝
██████╔╝██║      ██║   ██║█████╔╝ 
██╔═══╝ ██║      ╚██╗ ██╔╝██╔═██╗ 
██║     ╚██████╗  ╚████╔╝ ██║  ██╗
╚═╝      ╚═════╝   ╚═══╝  ╚═╝  ╚═╝
```

# Pengolahan Citra dan Visi Komputer

### *Digital Image Processing & Computer Vision — Course Repository*

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

<br/>

> *"Computer vision is the enterprise of automating and integrating a wide range of processes and representations for vision perception."* — David Marr

<br/>

[![GitHub commits](https://img.shields.io/github/commit-activity/m/athfizh/PCVK26_05_Hafizh?style=flat-square&color=4ade80&label=Commits)](https://github.com/athfizh/PCVK26_05_Hafizh/commits)
[![GitHub repo size](https://img.shields.io/github/repo-size/athfizh/PCVK26_05_Hafizh?style=flat-square&color=60a5fa&label=Repo%20Size)](https://github.com/athfizh/PCVK26_05_Hafizh)
[![GitHub last commit](https://img.shields.io/github/last-commit/athfizh/PCVK26_05_Hafizh?style=flat-square&color=f472b6&label=Last%20Update)](https://github.com/athfizh/PCVK26_05_Hafizh)

</div>

---

## 👤 Identitas Mahasiswa

<table>
  <tr>
    <td><b>Nama</b></td>
    <td>Athaulla Hafizh</td>
  </tr>
  <tr>
    <td><b>Presensi / NIM</b></td>
    <td>05 / 244107020030</td>
  </tr>
  <tr>
    <td><b>Kelas</b></td>
    <td><a>TI-3F</a></td>
  </tr>
  <tr>
    <td><b>Mata Kuliah</b></td>
    <td>Pengolahan Citra dan Visi Komputer (PCVK)</td>
  </tr>
  <tr>
    <td><b>Program Studi</b></td>
    <td>D-IV Teknik Informatika</td>
  </tr>
  <tr>
    <td><b>Jurusan</b></td>
    <td>Teknologi Informasi — Politeknik Negeri Malang</td>
  </tr>
</table>

---

## 📂 Struktur Repository

```text
PCVK26_05_Hafizh/
│
├── 📁 Modul 1/                        
├── 📁 Modul 2/
│   └── P2_TugasPraktikum_05.ipynb                        
├── 📁 Modul 3/
│   └── P3_TugasPraktikum_05.ipynb                         
├── 📁 Modul 5/
│   └── P5_TugasPraktikum_05.ipynb                         
├── 📁 Modul 6/
│   └── P6_TugasPraktikum_05.ipynb                         
├── 📁 Modul 7/
│   └── P7_TugasPraktikum_05.ipynb                         
├── 📁 Modul 9/
│   └── P9_TugasPraktikum_05.ipynb                         
│
└── README.md

```

> Catatan: Modul 4 dan Modul 8 tidak berisi tugas praktikum (tidak ada direktori), sehingga tidak dicantumkan.

---

## 📋 Daftar Modul Praktikum

| No | Topik Praktikum | Direktori | Status |
|:--:|----------------|:---------:|:------:|
| 1 | Pengantar Citra Digital: Representasi & Library Dasar | [📁 Modul 1](./Modul%201) | ✅ Selesai |
| 2 | Representasi dan Karakteristik Citra Digital | [📁 Modul 2](./Modul%202) | ✅ Selesai |
| 3 | Operasi Citra Sederhana | [📁 Modul 3](./Modul%203) | ✅ Selesai |
| 4 | *Tidak ada tugas praktikum* | — | — |
| 5 | Histogram, Histogram Equalization, dan Dithering | [📁 Modul 5](./Modul%205) | ✅ Selesai |
| 6 | Spasial Filter (Smoothing & Sharpening) | [📁 Modul 6](./Modul%206) | ✅ Selesai |
| 7 | Segmentasi Citra | [📁 Modul 7](./Modul%207) | ✅ Selesai |
| 8 | *Tidak ada tugas praktikum* | — | — |
| 9 | Morfologi Citra (Erosi, Dilasi, Opening, Closing, Top-Hat, Black-Hat, Skeleton, Thinning) | [📁 Modul 9](./Modul%209) | ✅ Selesai |

---

## 🧪 Ringkasan Modul 9 — Morfologi

Praktikum terakhir menguji operasi morfologi secara manual (tanpa library) dan membandingkannya dengan OpenCV:

| Langkah | Materi | Pembanding |
|:--:|--------|-----------|
| 3 | Dilasi manual SED square 5×5 | Hasil = `cv2.dilate` (selisih 0 di bagian dalam) |
| 4 | Dilasi `cv2.dilate` square 3×3 | — |
| 5 | Erosi manual SE square 5×5 | Hasil = `cv2.erode` (selisih 0 di bagian dalam) |
| 6 | Erosi `cv2.erode` square 5×5 | — |
| 7 | Opening manual & `cv2.morphologyEx` square 3×3 | Manual vs Library |
| 8 | Closing manual & `cv2.morphologyEx` square 3×3 | Manual vs Library |
| 9 | Dilasi SED cross 3×3 dan 5×5 | — |
| 10 | Dilasi SED circular 3×3 dan 5×5 | — |
| 11 | Erosi SE rectangle 3×5 dan 5×7 | — |
| 12 | Erosi SE line vertikal 3 dan 5 | — |
| 13 | Transformasi Top-Hat SE 3×3 | Citra kitten + Plat Nomor |
| 14 | Transformasi Black-Hat | Citra kitten + Plat Nomor |
| 15 | Skeleton citra biner (`threshold_triangle`) | Citra lily + Plat Nomor |
| 16 | Skeleton citra inversi (`img < threshold`) | Dibandingkan Langkah 15 |
| 17 | Thinning (`morphology.thin`) | Dibandingkan `skeletonize` |

---

## 🛠️ Tech Stack & Library

<div align="center">

| Kategori | Teknologi / Pustaka |
|---|---|
| **Programming Language** | Python 3.x |
| **Computer Vision** | OpenCV (`cv2`), Scikit-Image (`skimage`), Pillow (`PIL`) |
| **Numerical & Matrix** | NumPy |
| **Data Visualization** | Matplotlib (`pyplot`), Seaborn |
| **Environment** | Google Colaboratory, Git & GitHub |

</div>

---

## 🚀 Cara Menjalankan Notebook

Praktikum pada repositori ini dirancang agar dapat dieksekusi langsung di cloud menggunakan **Google Colaboratory**:

1. Buka file `.ipynb` yang ingin dipelajari pada direktori modul di atas.
2. Klik tombol badge **Open in Colab** di bagian atas file notebook (atau buka melalui Google Colab dengan memasukkan URL repo ini).
3. Pastikan runtime Colab terhubung (*Connected*).
4. Jalankan sel kode secara berurutan dengan menekan `Shift + Enter` atau tombol **Run Cell**.
5. Untuk notebook yang membaca citra dari Drive, mount folder `MyDrive` lalu sesuaikan variabel `BASE` dengan lokasi folder citra.

---

## 🎯 Capaian Pembelajaran

Melalui mata kuliah ini, mahasiswa diharapkan mampu:

- [x] Memahami representasi digital citra, sistem koordinat, matriks piksel, dan ruang warna (RGB, BGR, HSV, Grayscale).
- [x] Menggunakan library visi komputer standar industri seperti **OpenCV** dan **NumPy** untuk manipulasi matriks citra.
- [x] Menerapkan teknik perbaikan citra, penajaman, perataan histogram, dan reduksi derau (*noise filtering*).
- [x] Mengimplementasikan transformasi geometri dan morfologi matematis.
- [x] Menganalisis dan mengekstraksi fitur visual untuk segmentasi serta deteksi objek otomatis.

---

## 📬 Kontak

<div align="center">

**Athaulla Hafizh**

[![GitHub](https://img.shields.io/badge/GitHub-athfizh-181717?style=for-the-badge&logo=github)](https://github.com/athfizh)

</div>

---

<div align="center">

<sub>⭐ Repository ini disusun untuk memenuhi tugas perkuliahan Pengolahan Citra dan Visi Komputer</sub>

<br/>

</div>
