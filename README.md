# Codeigniter-4-master
Kerangka CodeIgniter 4 Apa itu CodeIgniter? CodeIgniter adalah framework web full-stack PHP yang ringan, cepat, fleksibel dan aman. Informasi lebih lanjut dapat ditemukan di situs resmi .  Repositori ini menyimpan versi kerangka kerja yang dapat didistribusikan, termasuk panduan pengguna. Ini telah dibangun dari repositori pengembangan .  Informasi lebih lanjut tentang rencana untuk versi 4 dapat ditemukan di pengumuman di forum.  Panduan pengguna yang sesuai dengan versi kerangka kerja ini dapat ditemukan di sini .  Perubahan Penting dengan index.php index.phptidak lagi berada di akar proyek! Itu telah dipindahkan ke dalam folder publik , untuk keamanan dan pemisahan komponen yang lebih baik.  Ini berarti Anda harus mengonfigurasi server web Anda untuk "menunjuk" ke folder publik proyek Anda , dan bukan ke root proyek. Praktik yang lebih baik adalah mengonfigurasi host virtual untuk menunjuk ke sana. Praktik yang buruk adalah mengarahkan server web Anda ke root proyek dan berharap untuk masuk ke public/... , karena sisa logika dan kerangka kerja Anda terbuka.  Silakan baca panduan pengguna untuk penjelasan yang lebih baik tentang cara kerja CI4!  Manajemen Repositori Kami menggunakan masalah Github, di repositori utama kami, untuk melacak BUGS dan untuk melacak paket kerja DEVELOPMENT yang disetujui . Kami menggunakan forum kami untuk memberikan DUKUNGAN dan mendiskusikan PERMINTAAN FITUR.  Repositori ini adalah repositori "distribusi", dibangun oleh skrip persiapan rilis kami. Masalah dengan itu dapat diangkat di forum kami, atau sebagai masalah di repositori utama.  Berkontribusi Kami menyambut baik kontribusi dari komunitas.  Silakan baca bagian Berkontribusi ke CodeIgniter di repositori pengembangan.  Persyaratan Server PHP versi 7.3 atau lebih tinggi diperlukan, dengan ekstensi berikut diinstal:  termasuk libcurl jika Anda berencana untuk menggunakan perpustakaan HTTP\CURLRequest Selain itu, pastikan ekstensi berikut diaktifkan di PHP Anda:  json (diaktifkan secara default - jangan matikan) mbstring mysqlnd xml (diaktifkan secara default - jangan matikan)
