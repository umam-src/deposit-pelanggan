# Ruang Lingkup Awal

## Tujuan

Mencatat deposit pelanggan dengan saldo yang dapat ditelusuri kembali ke transaksi pembentuknya.

## Fitur yang direncanakan

1. Pencatatan pelanggan.
2. Penambahan deposit.
3. Pencatatan pemakaian deposit.
4. Perhitungan dan penampilan saldo.
5. Riwayat transaksi.
6. Koreksi yang tercatat sebagai tindakan tersendiri.
7. Pencarian dan laporan dasar.

## Aturan integritas yang perlu dirancang

- Saldo harus dapat ditelusuri dari transaksi.
- Transaksi lama tidak boleh diubah atau dihapus diam-diam.
- Koreksi harus menyimpan alasan dan hubungan ke transaksi yang dikoreksi bila sesuai.
- Perhitungan nilai harus menghindari ketidakakuratan numerik.
- Perilaku saat saldo tidak mencukupi harus ditetapkan sebelum fitur pemakaian dibuat.

## Hal yang belum diputuskan

- Aplikasi terminal, GUI, atau web.
- Format dan lokasi penyimpanan.
- Peran pengguna dan autentikasi.
- Aturan saldo negatif, pembatalan, dan koreksi.
- Format ekspor atau cetak.

Keputusan tersebut tidak diasumsikan pada fase kerangka.
