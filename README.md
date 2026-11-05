<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Misi Bumi Lestari: Simulasi Mitigasi & Keberlanjutan</title>
    <!-- Menggunakan framework CSS Pico agar tampilan game rapi dan responsif di HP/Laptop -->
    <link rel="stylesheet" href="https://jsdelivr.net">
    <style>
        body { padding: 20px; max-width: 800px; margin: 0 auto; }
        hr { margin: 40px 0; }
        .card { padding: 20px; border-radius: 8px; border: 1px solid #e0e0e0; margin-bottom: 40px; }
        a[href^="#"] { display: block; padding: 10px; margin: 10px 0; background: #2c3e50; color: white; text-align: center; border-radius: 5px; text-decoration: none; font-weight: bold; }
        a[href^="#"]:hover { background: #34495e; }
    </style>
</head>
<body>

    <!-- BAGIAN 1: MULAI PERMAINAN -->
    <div id="-misi-bumi-lestari-simulasi-mitigasi--keberlanjutan" class="card">
        <h1>🌍 Misi Bumi Lestari: Simulasi Mitigasi & Keberlanjutan</h1>
        <p>Selamat datang di <strong>Misi Bumi Lestari</strong>! Di game berbasis teks ini, kamu berperan sebagai <strong>Kepala Mitigasi dan Pembangunan Berkelanjutan</strong> di Kota Pesisir Hijau.</p>
        <p>Tugasmu adalah mengambil keputusan krusial untuk melindungi warga dari ancaman <strong>banjir rob dan perubahan iklim</strong>, sekaligus menjaga ekosistem kota tetap berkelanjutan.</p>
        <hr>
        <h3>🛑 Mulai Permainan</h3>
        <p>Kota Pesisir Hijau baru saja menerima peringatan dini: <strong>Curah hujan ekstrem akan terjadi dalam 3 hari ke depan, bersamaan dengan pasang air laut tertinggi tahunan.</strong></p>
        <p>Sebagai pemimpin, anggaran kotamu saat ini terbatas. Apa kebijakan pertama yang akan kamu ambil?</p>
        <a href="#-pilihan-a-tanggul-beton">🧱 Pilihan A: Membangun tanggul laut beton besar di sepanjang pantai.</a>
        <a href="#-pilihan-b-restorasi-mangrove">🌱 Pilihan B: Merestorasi hutan mangrove dan membuat ruang terbuka hijau (taman spons).</a>
    </div>

    <!-- BAGIAN 2: PILIHAN A -->
    <div id="-pilihan-a-tanggul-beton" class="card">
        <h2>🧱 Pilihan A: Tanggul Beton</h2>
        <p>Kamu memutuskan untuk membangun tanggul beton raksasa. Proyek selesai tepat waktu sebelum badai datang. Saat air laut pasang ekstrem tiba, tanggul berhasil menahan air laut masuk ke pemukiman. Warga aman untuk sementara waktu.</p>
        <p>Namun, 6 bulan kemudian muncul dampak baru: nelayan lokal mengeluh karena ekosistem pantai rusak akibat beton, dan abrasi justru berpindah menghantam desa tetangga yang tidak memiliki tanggul.</p>
        <p>Sekarang, apa langkah keberlanjutan selanjutnya?</p>
        <a href="#-pilihan-a1-pompa-fosil">Membakar minyak/energi fosil: Menambahkan pompa air bertenaga fosil untuk menyedot genangan sisa di dalam kota.</a>
        <a href="#-pilihan-a2-kombinasi-hijau">Mulai mengombinasikan tanggul dengan penanaman vegetasi pantai di area yang abrasi.</a>
    </div>

    <!-- BAGIAN 3: PILIHAN B -->
    <div id="-pilihan-b-restorasi-mangrove" class="card">
        <h2>🌱 Pilihan B: Restorasi Mangrove</h2>
        <p>Kamu memilih pendekatan berbasis alam (<em>Nature-based Solutions</em>). Lahan pesisir dibebaskan untuk ditanami mangrove dan dibuat kolam retensi alami. Saat badai tiba, sebagian air laut tetap masuk ke area mangrove, namun kecepatannya terendam dan tidak merusak rumah warga.</p>
        <p>Satu tahun berlalu, area mangrove berkembang menjadi tempat wisata edukasi baru, meningkatkan ekonomi warga, dan menjadi rumah bagi keanekaragaman hayati. Kota menjadi lebih sejuk dan mampu menyerap karbon.</p>
        <p>Untuk meningkatkan ketahanan kota jangka panjang terhadap perubahan iklim, apa program berikutnya?</p>
        <a href="#-pilihan-b1-sumur-resapan">Membangun sistem pemanenan air hujan dan sumur resapan di setiap rumah warga.</a>
        <a href="#-pilihan-b2-pembangunan-hotel">Membuka izin pembangunan hotel megah di dekat kawasan hutan mangrove untuk menambah kas daerah.</a>
    </div>

    <!-- BAGIAN 4: AKHIR A1 -->
    <div id="-pilihan-a1-pompa-fosil" class="card" style="border-color: #e74c3c;">
        <h2>🏭 Pilihan A1: Pompa Fosil</h2>
        <h3><strong>AKHIR CERITA: Solusi Semu (Bad Ending) ❌</strong></h3>
        <p>Pompa menyedot air dengan cepat, tetapi emisinya memperburuk polusi udara kota. Dua tahun kemudian, permukaan tanah kota semakin turun karena penyedotan air tanah berlebih, dan tanggul beton mulai retak karena beban alam. Biaya perawatan tanggul membengkak hingga kota bangkrut. Kota gagal mencapai target keberlanjutan.</p>
        <a href="#-misi-bumi-lestari-simulasi-mitigasi--keberlanjutan">🔄 Coba Lagi dari Awal</a>
    </div>

    <!-- BAGIAN 5: AKHIR A2 -->
    <div id="-pilihan-a2-kombinasi-hijau" class="card" style="border-color: #f1c40f;">
        <h2>🤝 Pilihan A2: Kombinasi Hijau</h2>
        <h3><strong>AKHIR CERITA: Adaptasi Transisi (Neutral Ending) ⚖️</strong></h3>
        <p>Meskipun awalnya memilih beton, keputusanmu untuk beralih ke pendekatan alami berhasil mengerem dampak buruk abrasi sekunder. Nelayan mulai mendapatkan kembali mata pencaharian mereka secara perlahan. Kota aman, meskipun kamu harus mengeluarkan anggaran ganda karena kesalahan strategi di awal.</p>
        <a href="#-misi-bumi-lestari-simulasi-mitigasi--keberlanjutan">🔄 Coba Lagi dari Awal</a>
    </div>

    <!-- BAGIAN 6: AKHIR B1 -->
    <div id="-pilihan-b1-sumur-resapan" class="card" style="border-color: #2ecc71;">
        <h2>🏆 Pilihan B1: Sumur Resapan</h2>
        <h3><strong>AKHIR CERITA: Kota Tangguh & Berkelanjutan (Best Ending) 🎉</strong></h3>
        <p>Langkah luar biasa! Kota Pesisir Hijau kini memiliki sistem mitigasi yang berlapis. Mangrove menahan rob dari laut, sementara sumur resapan mencegah banjir dari darat sekaligus menjaga cadangan air bersih di dalam tanah. Kota memenangkan penghargaan dunia sebagai <em>Eco-City</em> telazan. Kamu berhasil!</p>
        <a href="#-misi-bumi-lestari-simulasi-mitigasi--keberlanjutan">🔄 Mainkan Lagi</a>
    </div>

    <!-- BAGIAN 7: AKHIR B2 -->
    <div id="-pilihan-b2-pembangunan-hotel" class="card" style="border-color: #e74c3c;">
        <h2>🏨 Pilihan B2: Pembangunan Hotel</h2>
        <h3><strong>AKHIR CERITA: Serakah Membawa Petaka (Bad Ending) 💀**</h3>
        <p>Pembangunan hotel merusak sebagian besar mangrove yang baru tumbuh. Aliran limbah hotel mencemari kolam retensi. Ketika badai besar berikutnya datang, pelindung alami telah sirna. Hotel mewah dan pemukiman warga tenggelam diterjang banjir rob besar. Keberlanjutan dikorbankan demi profit jangka pendek.</p>
        <a href="#-misi-bumi-lestari-simulasi-mitigasi--keberlanjutan">🔄 Coba Lagi dari Awal</a>
    </div>

</body>
</html>
