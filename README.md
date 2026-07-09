# HR Analytics Dashboard: Employee Attrition and Workforce Insights
## Business Understanding
Seiring dengan pertumbuhan perusahaan, pengelolaan sumber daya manusia menjadi semakin kompleks, salah satunya ditandai dengan tingginya tingkat employee attrition. Berdasarkan data yang tersedia, perusahaan mencatat attrition rate sebesar 17%, melampaui ambang batas ideal sebesar 10%. Kondisi ini berpotensi meningkatkan biaya rekrutmen dan pelatihan, mengganggu produktivitas, serta memengaruhi stabilitas operasional perusahaan.
Untuk membantu perusahaan memahami penyebab tingginya attrition, dikembangkan sebuah HR Analytics Dashboard yang menyajikan analisis komprehensif mengenai karakteristik tenaga kerja, distribusi karyawan, dan pola attrition berdasarkan berbagai faktor, seperti jenis kelamin, status pernikahan, tingkat pendidikan, departemen, bidang studi, jabatan, tingkat gaji, level pekerjaan, dan status lembur (overtime). Dashboard ini diharapkan dapat mendukung pengambilan keputusan berbasis data dalam menyusun strategi retensi karyawan yang lebih efektif.

### Persiapan

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv

Setup environment:

```
pip install numpy pandas matplotlib seaborn squarify
```

## Business Dashboard

Business dashboard proyek ini dibuat menggunakan Google Data Studio dengan menambahkan fitur filter berdasarkan status karyawan yaitu aktif dan inaktif. Pada dashboard ditampilkan jumlah seluruh karyawan, jumlah karyawan yang aktif dan yang keluar, nilai rata-rata gaji karyawan, nilai rata-rata tahun bekerja karyawan di perusahaan, grafik pie chart perbandingan jumlah berdasarkan status dengan gender, status dengan status pernikahan, attrition rate, dan status dengan bekerja overtime. Selain itu terdapat grafik yang menunjukkan sebaran karyawan berdasarkan usia, departement kerja, bidang pekerjaan, level pekerjaan, jenjang pendidikan, bidang pendidikan yang ditempuh dan kategori gaji karyawan.


Link DASHBOARD:

https://datastudio.google.com/reporting/e6097218-26aa-4923-b213-27dd7aa18fb7

## Conclusion

- Secara total keseluruhan terdapat 1058 karyawan yang bekerja
- Terdapat 879 atau 83% karyawan yang masih aktif bekerja sedangkan 179 atau karyawan 17% memilih untuk keluar dari perusahann.
- Secara keseluruhan karyawan di dominasi oleh laki-laki, tetapi laki-laki juga yang paling banyak keluar dari perusahaan
- secara keseluruhan karyawan di dominasi oleh mereka yang sudah menikah, akan tetapi secara jumlah yang keluar lebih banyak mereka yang masih sigle
- secara keseluruhan karyawan di dominasi oleh lulusan sarjana dan lulusan sarjana juga yang paling banyak keluar dari perusahaan
- Secara keseluruhan departeman rnd yang paling banyak totak karyawan. akan tetapi, departemen rnd juga yang paling banyak keluar dari perusahaan.
- secara keseluruhan karyawan di dominasi oleh karyawan dengan bidang life science, akan tetapi bidang tersebut juga yang paling banyak karyawan yang keluar
- secara total karyawan palimg banyak pada jabatan sales executive, sedangkan yang paling banyak keluar pada bidang laboratory techincian
- secara keseluruhan gaji karyawan masih di bawah rata-rata atau di bawah USD5000 dan karyawan dengan gaji tersebut juga yang paling banyak keluar dari perusahaan.
- karyawan yang masih level 1 menyumbang karyawan yang paling banyak keluar dari perusahaan
- mereka yang bekerja secara overtime yang paling banyak keluar dari perusahaan.

### Rekomendasi Action Items

- Meningkatkan Kesejahteraan Karyawan dengan menaikan gaji karyawan yang masih di bawah rata-rata, Terutama Level dan Bergaji Rendah, Kesimpulan menunjukkan bahwa karyawan dengan gaji di bawah rata-rata (USD5000) dan level 1 memiliki tingkat attrition yang tinggi.
- Fokus pada Retensi Karyawan di Departemen R&D dan Bidang Life Science, Departemen R&D dan bidang Life Science memiliki jumlah karyawan terbanyak, namun juga memiliki attrition rate yang tinggi.
- Memberikan Perhatian Lebih kepada Karyawan Single, Meskipun didominasi oleh karyawan yang sudah menikah, karyawan single memiliki tingkat attrition yang lebih tinggi.
- Mengurangi kerjaan secara overtime kepada karyawan
