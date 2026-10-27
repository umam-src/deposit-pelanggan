# Panduan Kontribusi

## Prinsip

- Gunakan bahasa pemrograman Alur untuk implementasi aplikasi.
- Gunakan Bahasa Indonesia untuk nama dan dokumentasi sejauh wajar serta jelas.
- Jangan menambahkan fungsi runtime atau API pustaka sebelum keberadaannya dibuktikan oleh dokumentasi, contoh, atau manifes.
- Jaga integritas saldo dan jejak transaksi. Koreksi harus tercatat; jangan menghapus riwayat transaksi secara diam-diam.
- Jangan mengklaim uji atau kompilasi berhasil tanpa menjalankannya dan menyimpan bukti hasil.

## Alur perubahan

1. Periksa `TODO.md` dan isu terkait sebelum mengerjakan fase.
2. Buat perubahan sekecil mungkin yang memenuhi tujuan.
3. Jalankan pemeriksaan yang sesuai dengan compiler dan lingkungan yang tersedia.
4. Catat hasil pemeriksaan, termasuk yang belum dapat dijalankan.
5. Perbarui `CHANGELOG.md` pada bagian `[Unreleased]`.

## Versi

- Versi minor mengikuti fase roadmap.
- Versi patch untuk perbaikan, keamanan, atau perubahan yang memengaruhi penggunaan.
- Perubahan dokumentasi dan refaktor internal tanpa dampak pengguna tidak memerlukan kenaikan versi.

Aturan kerja agen disimpan di vault proyek, bukan di repositori kode.
