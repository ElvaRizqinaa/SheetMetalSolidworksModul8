# SheetMetalSolidworksModul8
### **Deskripsi Proyek**
Proyek ini berisi kumpulan model 3D dan analisis teknis yang difokuskan pada pemodelan Sheet Metal menggunakan SolidWorks. Dimana hal ini didasarkan pada materi modul ke 8 yaitu sheet metal untuk menguji kemahiran dalam merancang komponen berbasis pelat logam.

Berbeda dengan pemodelan *part* standar, proyek ini menekankan pada penggunaan fitur-fitur fabrikasi seperti:
* Pengaturan ketebalan seragam sebesar 1.20 mm pada seluruh bagian model.
* Penerapan nilai K-Factor yang spesifik (0.32 dan 0.40) untuk memastikan akurasi dimensi saat model diratakan (*flattened*).
* Implementasi *Edge Flange*, *Hem* (lipatan tepi), serta penggunaan opsi *Trim Side Bends* untuk merapikan geometri tekukan.

### **Spesifikasi Model**
Seluruh komponen dalam proyek ini dirancang dengan parameter berikut:
* **Unit System**: MMGS (Millimeter, Gram, Second).
* **Material**: Aluminum, 1060 Alloy.
* **Densitas**: $0.0027~g/mm^3
* **Inner Bend Radius**: 1.00 mm.

### **Target Capaian**
1.  **Akurasi Geometri**: Memastikan dimensi variabel (A, B, C, D) sesuai dengan instruksi desain yang dinamis.
2.  **Analisis Massa**: Menghitung massa akhir komponen dengan toleransi akurasi +/- 0.50 gram.
3.  **Flat Pattern Analysis**: Mengukur dimensi bentangan pelat (X) dan luas area kotak pembungkus (*Bounding Box Area*) setelah model diratakan.
