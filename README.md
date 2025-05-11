# 📊 Sentiment Analysis using SVM

**Sumber Belajar:**  
https://medium.com/scrapehero/sentiment-analysis-using-svm-338d418e3ff1

---

## 🧠 Deskripsi 

Sentiment Analysis merupakan sebuah teknik dalam Natural Language Processing (NLP) yang digunakan untuk mengidentifikasi emosi atau opini seseorang terhadap suatu topik dalam bentuk teks apakah bersifat positif, negatif, atau netral. NLP sendiri merupakan cabang dari kecerdasan buatan yang memungkinkan mesin memahami bahasa manusia. Pada kali dilakukan sebuah percobaan untuk membuat sebuah model SVM yang berasal dari sumber berikut :
https://raw.githubusercontent.com/Vasistareddy/sentiment_analysis/master/data/test.csv
dengan struktur dataset Kolom Content berisi teks ulasan dan kolom label Berisi label sentimen (pos untuk positif dan neg untuk negatif).

---

## ⚙️ Model dan Proses

Model yang digunakan yaitu Support Vector Machine (SVM) merupakan salah satu algoritma yang sangat efektif dalam menangani masalah klasifikasi teks. 
proses yang dilukan oleh model svm memakan waktu sebanyak **15.67** detik

---

## 📈 Hasil 

Bedasarkan hasil uji coba yng dilakukan didapat hasil :

### ✅ Kelas Positif (`pos`)
- Precision: 0.9519 menunjukkan bahwa prediksi yang diklasifikasikan sebagai positif benar-benar positif.
- Recall: 0.981 menunjukkan bahwa dari ulasan positif berhasil dikenali oleh model.
- F1-Score: 0.9662  menunjukkan keseimbangan yang sangat baik antara precision dan recall.
- Support: 100 data

### ❌ Kelas Negatif (`neg`)
- Precision: 0.9890 menunjukkan bahwa hampir semua prediksi negatif adalah benar.
- Recall: 0.82  artinya ada ulasan negatif yang gagal dikenali oleh model (terklasifikasi sebagai positif).
- F1-Score: 0.8974 menunjukkan bahwa kinerja pada kelas negatif sedikit lebih rendah dibanding kelas positif.
- Support: 100 data

---

## 📝 Kesimpulan

Bahwa hasil yang telah didapat disimpulkan bahwa model SVM berhasil dan akurat melakukan klasifikasi sentimen. Model menemukan ulasan positif dengan sangat baik dan ulasan negatif dengan cukup baik; namun, kelas negatif memiliki kinerja yang kurag baik sehingga, beberapa menunjukkan ulasan negatif tidak dikenali dengan baik.

---



