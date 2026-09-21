# BoundingBox Project — Stapler Detection Dataset

Dataset latihan object detection untuk deteksi **stapler** menggunakan Label Studio.

## Deskripsi
- **Jumlah gambar**: 12
- **Kelas**: 1 (`Stapler`)
- **Tipe annotasi**: Bounding Box
- **Variasi**: berbagai sudut, kondisi, dan background

## Struktur
- `Stapler_XX.jpg` — foto mentah
- `export.json` — hasil export Label Studio (JSON)
- `label-studio-config/labeling-config.xml` — config Label Studio

## Cara Reproduksi
1. Install Label Studio: `pip install label-studio`
2. Jalankan: `label-studio start`
3. Buat project baru, import `label-studio-config/labeling-config.xml`
4. Import foto `Stapler_XX.jpg`
5. Import `export.json` untuk lihat annotation

## Tools
- [Label Studio](https://labelstud.io/) — annotation tool
