# Dokumentasi Penyusunan Dashboard Visualisasi pada Statistik Sistem Uang Elektronik

## Penjelasan Data dan Metadata
Sumber data yang digunakan pada visualisasi ini adalah data statistik sistem pembayaran/uang elektronik dari Bank Indonesia. Data ini menyediakan data dari tahun 2009 hingga tahun 2022, meskipun pada tahun 2022 data terakhir kali dicatat pada Bulan Maret dan masih bersifat sementara. Variabel dan Sub-variabel yang digunakan antara lain:
- Jumlah Instrumen: jumlah uang elektronik yang beredar di masyarakat pada periode tertentu.
  - Berdasarkan media penyimpan
    - *Chip Based*
    - *Server Based*
  - Berdasarkan pencatatan data
    - *Registered*
    - *Unregistered*
  - Jumlah Kartu dalam Rangka LKD
- Volume Transaksi: jumlah transaksi pembelanjaan yang dilakukan dengan menggunakan uang elektronik pada periode tertentu.
  - Volume Transaksi Belanja
  - Volume Transaksi Transfer antar Uang Elektronik
  - Volume Transaksi *Initial* (isi pertama kali)
  - Volume Transaksi *Reload/Top Up*
  - Volume Transaksi Tarik Tunai Uang Elektronik
  - Volume Transaksi *Redeem*
- Nilai Transaksi: nilai/nominal dari transaksi pembelanjaan yang dilakukan dengan menggunakan uang elektronik pada periode tertentu.
  - Nilai Transaksi Belanja
  - Nilai Transaksi Transfer antar Uang Elektronik
  - Nilai Transaksi *Initial* (isi pertama kali)
  - Nilai Transaksi *Reload/Top Up*
  - Nilai Transaksi Tarik Tunai Uang Elektronik
  - Nilai Transaksi *Redeem*
- Penyelenggara Uang Elektronik
  - Penerbit:  adalah Bank atau Lembaga Selain Bank yang menerbitkan uang elektronik
    - Bank Umum
    - Lembaga Selain Bank/LSB

## Preprocessing
Agar Tableau dapat memproses data sesuai dengan yang diinginkan, maka harus ada perubahan struktur tabel terlebih dahulu.
Data awal berbentuk seperti ini
ggggggggg
Lalu dilakukan transformasi tabel menjadi seperti ini
ggggggggg
Setelah tabel berhasil di transformasi, maka data di export ke Tableau. Namun ketika pertama kali di export ternyata tipe data yag terdetekti oleh Tableau tidak sesuai yang diinginkan, yang seharusnya tipe data numerik justru terbaca menjadi tipe data kategori. Oleh karena itu dilakukan perubahan tipe data di Tableau, dan data yang sudah diubah tipe datanya di drag-and-drop ke bagian numerik.
Awalnya seperti ini
ggggggggg
menjadi seperti ini
ggggggggg

## Proses Visualisasi
Proses visualisasi akan dijelaskan per-variabel

### Jumlah Instrumen
#### Jumlah Instrumen Berdasarkan Media Penyimpan dan Pencatatan Data
### Penerbit
### Volume Transaksi
### Nilai Transaksi

## Penyusunan Dashboard
Penyusunan dashboard ini ada beberapa visualisasi yang dijadikan ke satu container dan dibuat suatu parameter untuk memilih visualisasi apa yang perlu ditampilkan

### Jumlah Instrumen dan Penerbit
#### Jumlah Instrumen Berdasarkan Media Penyimpan dan Pencatatan Data
### Volume dan Nilai Transaksi Treemap
#### Volume dan Nilai Transaksi *Area Chart* dan *Line Chart*

## Implementasi Penggunaan Dashboard Visualisasi
Hasil dari penyusunan dashboard visualisasi yang sudah diterangkan sebelumnya menjadi seperti ini
ggggggg
