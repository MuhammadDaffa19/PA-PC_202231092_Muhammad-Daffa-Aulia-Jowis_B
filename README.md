Teori yang Mendukung

Proyek ini berkaitan dengan pengolahan citra digital yang melibatkan transformasi geometris dasar seperti rotasi, perubahan ukuran (resizing), pemotongan (cropping), flipping, dan translasi. Berikut adalah penjelasan teoritis yang mendukung proyek ini:

Pengolahan Citra Digital:
Pengolahan citra digital adalah bidang yang mencakup berbagai teknik untuk memanipulasi gambar dalam bentuk digital. Pengolahan citra digunakan dalam berbagai aplikasi, termasuk pengenalan pola, pengawasan, medis, dan hiburan.

Transformasi Geometris:
- Rotasi: Mengubah orientasi gambar dengan memutarnya sebesar sudut tertentu di sekitar titik pusat. Matriks rotasi digunakan untuk melakukan operasi ini.

- Perubahan Ukuran (Resizing): Mengubah ukuran gambar, baik memperbesar atau memperkecil, dengan mempertahankan aspek rasio atau tidak.

- Pemotongan (Cropping): Mengambil bagian dari gambar yang diinginkan dan membuang sisanya. Berguna untuk fokus pada area tertentu dari gambar.

- Flipping: Membalik gambar secara horizontal atau vertikal, menciptakan cermin dari gambar asli.

- Translasi: Menggeser seluruh gambar dalam arah tertentu tanpa merubah ukuran atau orientasi gambar.

OpenCV: 
- OpenCV (Open Source Computer Vision Library) adalah pustaka perangkat lunak untuk visi komputer dan pengolahan citra digital. Pustaka ini menyediakan berbagai fungsi untuk melakukan operasi transformasi citra seperti rotasi, resizing, cropping, flipping, dan translasi.

Tahapan Cara Menyelesaikan Projek Secara Rinci:

1. Persiapan Lingkungan Kerja:
 - Pastikan kita memiliki Python dan Jupyter Notebook terinstal di sistem.
 - Instal pustaka OpenCV dengan menjalankan pip install opencv-python-headless.
 - Pastikan juga pustaka Matplotlib terinstal dengan menjalankan pip install matplotlib.

2. Memuat dan Menampilkan Gambar Asli:
 - Gunakan fungsi cv2.imread() untuk memuat gambar dari sistem.
 - Gunakan Matplotlib untuk menampilkan gambar asli.

3. Melakukan Transformasi Geometris:
- Rotasi:
   - Hitung titik pusat gambar.
   - Buat matriks rotasi menggunakan cv2 getRotationMatrix2D(). 
   - Terapkan rotasi dengan cv2.warpAffine().

- Perubahan Ukuran (Resizing): 
   - Gunakan cv2.resize() untuk mengubah ukuran gambar.
   - Pemotongan (Cropping):
   - Tentukan koordinat awal dan akhir dari area yang akan dipotong.
   - Potong gambar menggunakan slicing array.

- Flipping:
   - Gunakan cv2.flip() untuk membalik gambar secara horizontal atau vertikal.
   - Translasi:
   - Buat matriks translasi.
   - Terapkan translasi dengan cv2.warpAffine().

4. Menampilkan Hasil Transformasi:
- Gunakan Matplotlib untuk menampilkan gambar asli dan hasil transformasi dalam satu baris gambar.

5. Menjalankan dan Memverifikasi Kode:
- Pastikan semua langkah sudah berjalan dengan benar dengan menjalankan sel di Jupyter Notebook.
- Verifikasi hasil transformasi dengan memeriksa tampilan gambar yang dihasilkan.

Tambahan Jurnal Terkait (Opsional)
Digital Image Processing:

   - Rafael C. Gonzalez dan Richard E. Woods, "Digital Image Processing," Pearson Education, 2018.

   - OpenCV Documentation: OpenCV documentation provides comprehensive details on how to use various functions available in the library         Accessible at OpenCV Documentation.

   - Image Processing and Analysis: J. S. Lim, "Two-Dimensional Signal and Image Processing," Prentice Hall, 1990.