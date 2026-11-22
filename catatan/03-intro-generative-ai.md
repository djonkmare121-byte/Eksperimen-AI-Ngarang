Catatan 03: Introduction to Generative AI
Tanggal belajar: (22/11/2026)
Sumber: Google Cloud Skills Boost, Introduction to Generative AI
> Kerangka ini mengikuti 5 topik yang gue pelajari. Isi tiap bagian dengan kata-kata sendiri,
> jangan salin dari materi atau dari AI.
1. Generative AI sebagai turunan deep learning
Hubungannya dengan AI, ML, dan deep learning:
Analogi gue:Seperti olahraga bola, ada sepak bola dan futsal
2. Ini GenAI atau bukan?
Patokan cepat: lihat outputnya.
Output angka atau label (misalnya harga rumah, spam atau bukan) berarti machine learning biasa.
Output konten baru (teks, gambar, suara, kode, video) berarti GenAI.
Kasus	GenAI atau bukan	Alasan gue
Menebak harga rumah dari luas dan lokasi	bukan	karena dari angka atau label
Menulis puisi dari satu kata kunci	GenAI	belajar dari teks lalu menghasilkan teks yang baru
Menandai email spam atau bukan	bukan	cuma disuruh nebak jadi jenisnya termasuk klasifikasi
Mengubah deskripsi teks jadi gambar	GenAI	sudah jelas, dia merubah teks menjadi gambar 
Catatan: patokan ini cuma jalan pintas. Yang menentukan adalah jenis tugasnya (memprediksi atau
menciptakan), bukan sekadar bentuk outputnya.
3. Definisi generative AI (dalam kata-kata gue)
GenAI adalah jenis turunan dari deep learning yg dihasilkan dari neuron yang lebih kompleks sehingga dapat menghasilkan jenis baru dari perintah
4. Transformer, halusinasi, dan prompt
Transformer: Transformer adalah arsitektur di balik LLM modern
Halusinasi: Halusinasi adalah keluaran yang ngawur atau salah fakta, penyebabnya antara lain data latih yang kurang, berisik, atau bias, serta konteks yang kurang
Prompt: Prompt adalah perintah yang kita kasih ke model, semakin jelas perintahnya maka yg dihasilkan semakin bagus
Analogi gue untuk prompt:
5. Jenis-jenis model generative AI
Jenis	Input	Output	Contoh
Teks ke teks	sebuah kata	menghasilkan kata yang baru	buatkan puisi dari kata senja
Teks ke gambar	rangkain kata yang menerangkan keadaan	menghasilkan gambar tergantung kualitas perintahnya	buatkan gambar seoarang kakek sedang duduk di depan rumah, dan memandangi matahari terbenam
Teks ke video	rangkain kata yang menerangkan keadaan	menghasilkan video tergantung kualitas perintahnya	buatkan video seoarang kakek sedang duduk di depan rumah, dan memandangi matahari terbenam
Teks ke aksi/tugas	rangkain teks untuk memerintah AI utuk membuat dashboard	AI akan coding dan menghasilkan dashboard	buatkan dashboard penjualan
Yang masih belum gue paham
paham
Yang bisa gue coba dari ini
Eksperimen prompt jelas vs asal-asalan (lihat `eksperimen/prompt-jelas-vs-asal.md`).
