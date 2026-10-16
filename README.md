# pertemuan-07-fungsi-2225250002

Nama: Nasywaa Zaafarani Kurniawan 
NIM: 2225250002
Kelas: 3A 

## Tujuan
Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

## Cara Menjalankan
python3 utilitas_matematika.py

## Struktur Fungsi
- `salam(nama)`: Menerima parameter nama, lalu mencetak pesan sapaan ke layar.
- `luas_persegi_panjang(p, l)`: Menerima parameter panjang ($p$) dan lebar ($l$), lalu mengembalikan nilai luas $p \times l$.
- `jumlah_n(n)`: Menerima parameter $n$, lalu mengembalikan total penjumlahan beruntun dari 1 sampai $n$.
- `faktorial(n)`: Menerima parameter $n$, lalu mengembalikan nilai faktorial bilangan tersebut.
- `statistik(data)`: Menerima parameter list data angka, lalu mengembalikan nilai minimum, maksimum, dan rata-rata.

## Hasil Pengujian

| Operasi | Input | Hasil yang Diharapkan | Hasil Aktual | Status |
| :--- | :--- | :--- | :--- | :--- |
| Luas persegi panjang | p=8, l=5 | 40 | 40 | Sesuai |
| Luas segitiga | a=10, t=6 | 30.0 | 30.0 | Sesuai |
| Jumlah 1..n | n=10 | 55 | 55 | Sesuai |
| Faktorial | n=5 | 120 | 120 | Sesuai |
| Faktorial | n=0 | 1 | 1 | Sesuai |

## Refleksi
Bagian program yang menjadi lebih sederhana setelah dipisah menjadi fungsi adalah pengorganisasian rumus-rumus dan logika perhitungannya. Dengan memecah program ke dalam fungsi-fungsi modular, kode utama menjadi jauh lebih rapi, terstruktur, mudah diuji per bagiannya, serta dapat dipanggil kembali dengan mudah tanpa menulis ulang baris kode yang sama.
