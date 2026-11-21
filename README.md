# Eksperimen: Seberapa Sering AI Ngarang?

Proyek belajar AI dari nol. Di sini gue (Regal) mencatat apa yang gue pelajari dan menguji sendiri
bagaimana chatbot AI menjawab pertanyaan, terutama kapan jawabannya benar dan kapan jawabannya ngarang
(*hallucination*).

## Masalah yang mau dijawab
AI seperti ChatGPT dan Claude sering menjawab dengan nada yakin, padahal isinya kadang salah.
Pertanyaan gue: **jenis pertanyaan apa yang paling sering bikin AI salah, dan bagaimana cara mengeceknya?**

## Cara kerja eksperimen
1. Gue menyiapkan 15 pertanyaan dalam 5 kelompok (angka dan fakta, hal lokal, sumber dan kutipan, hal yang tidak ada, hitungan).
2. Pertanyaan yang sama gue ajukan ke AI.
3. Jawaban AI gue cek ke sumber asli (BPS, Wikipedia, kalkulator, dan sebagainya).
4. Tiap jawaban gue nilai: **Benar**, **Sebagian benar**, **Salah/ngarang**, atau **Jujur bilang tidak tahu**.
5. Di akhir gue tulis pola yang gue temukan.

Detail dan hasilnya ada di [`eksperimen/hasil.md`](eksperimen/hasil.md).

## Hasil singkat
*(Isi setelah eksperimen selesai: berapa yang benar, berapa yang ngarang, dan kelompok pertanyaan mana yang paling bermasalah.)*

## Isi repo
```
README.md              ringkasan proyek (file ini)
eksperimen/hasil.md    daftar pertanyaan, tabel hasil, dan kesimpulan
catatan/               catatan belajar gue per topik, dengan bahasa sendiri
```

## Keterbatasan
- Sampel kecil (15 pertanyaan), jadi ini bukan penelitian ilmiah, cuma eksperimen belajar.
- Hasil bisa beda tergantung model dan versinya, serta apakah fitur pencarian web aktif.
- Jawaban AI bisa berubah kalau pertanyaan yang sama diulang.

## Yang gue pelajari
*(Isi dengan 2-3 kalimat dalam kata-kata sendiri setelah selesai.)*
