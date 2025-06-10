# PCA_Visualization

# Menelusuri ‘Sidik Jari’ Kimia Asap Cair  
### Heatmap Komposisi GC-MS dari 9 Jenis Tanaman

## 📌 Pendahuluan
Asap cair menjadi alternatif alami yang digunakan dalam pengawetan makanan dan bahan antibakteri. Namun, tidak semua asap cair diciptakan sama — komposisi kimianya bisa sangat bervariasi tergantung dari jenis tanaman yang digunakan.

Dengan menggunakan data hasil analisis GC-MS dari 9 jenis tanaman, saya melakukan visualisasi heatmap yang dilengkapi dendrogram untuk melihat pola kemiripan dan perbedaan antara tanaman secara visual dan numerik.

---

## 📊 Data & Tools
- **Sumber data**: Hasil GC-MS asap cair dari 9 jenis tanaman (format `.xlsx`)
- **Software**: R (RStudio)
- **Visualisasi**: Heatmap dengan Clustering Hierarki

**Tanaman yang dianalisis:**
1. *E. zwageri*
2. *S. leavis*
3. *S. leprosula*
4. *S. mahagoni*
5. *A. mangium*
6. *A. chinensiss*
7. *D. excelsa*
8. *M. speciosa*
9. *L. confertus*

---

## 🔍 Proses Analisis
1. Import data dari Excel menggunakan `readxl`
2. Membersihkan data (menghapus NA dan duplikat)
3. Mengatur komponen sebagai baris, tanaman sebagai kolom
4. Visualisasi heatmap menggunakan `pheatmap()`
5. Penambahan dendrogram dengan metode clustering hierarki (euclidean + complete linkage)

---

## 📈 Hasil & Insight

- **Clustering tanaman** menunjukkan bahwa *M. speciosa* dan *L. confertus* membentuk kelompok tersendiri, menandakan profil kimia yang unik.
- **Clustering senyawa** memperlihatkan bahwa senyawa seperti *Acetic acid* dan *2-Propanone, 1-hydroxy-* muncul dominan di berbagai tanaman.
- *A. chinensiss* memiliki kemiripan profil dengan *S. mahagoni* dan *D. excelsa*.

> Visualisasi heatmap memberikan gambaran cepat namun kaya informasi terhadap perbedaan komposisi kimia asap cair dari berbagai tanaman.

---

## 🧠 Kesimpulan

Visualisasi ini dapat digunakan untuk:
- Identifikasi tanaman dengan senyawa dominan tertentu
- Pengembangan produk berbasis tanaman spesifik
- Clustering tanaman berdasarkan kesamaan kimiawi

---

## 📬 Kontak
Jika ada pertanyaan atau kolaborasi, silakan hubungi saya melalui 
GitHub
email : dimas06fk@gmail.com
