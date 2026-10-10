# Aris Toyota — website statis siap deploy ke Vercel

Website landing page responsif untuk Aris Toyota dengan tombol WhatsApp ke 0812 9013 4203.

## Isi folder
- `index.html` — website lengkap (CSS dan JavaScript sudah ada di dalamnya).
- `vercel.json` — konfigurasi sederhana untuk deployment statis.

## Cara memasang ke GitHub
1. Buka GitHub dan masuk ke akun Anda.
2. Buat repository baru, misalnya `aris-toyota-site` (atau gunakan repository yang sudah Anda miliki setelah mencadangkan file yang ada).
3. Unggah `index.html` dan `vercel.json` ke root repository.
4. Commit perubahan.

## Cara deploy ke Vercel
1. Buka https://vercel.com/dashboard
2. Pilih **Add New → Project**, lalu impor repository GitHub tadi.
3. Untuk website ini, pilih framework **Other** jika diminta.
4. Biarkan Build Command kosong dan Output Directory kosong/default untuk proyek statis; Vercel akan menyajikan `index.html`.
5. Tekan **Deploy**.
6. Jika proyek `toyota-99d2` sudah tersambung ke repository lain, jangan menimpa repository itu sebelum membuat backup. Anda bisa mengimpor repo ini sebagai proyek baru atau mengganti repository proyek yang ada melalui Settings.

## Hubungkan domain www.aristoyota.my.id
1. Di Vercel, buka proyek yang benar → **Settings → Domains**.
2. Tambahkan `aristoyota.my.id` dan `www.aristoyota.my.id`.
3. Ikuti instruksi DNS yang ditampilkan Vercel untuk domain Anda. Nilai DNS harus mengikuti instruksi di dashboard; jangan menebak nilai.
4. Setelah status domain valid, pilih domain utama yang diinginkan.

## Sebelum dipublikasikan
- Harga dan promo tidak dicantumkan sebagai angka tetap; konfirmasikan harga, tipe, ketersediaan, dan program terbaru ke sales.
- Visual mobil pada kartu adalah ilustrasi, bukan foto produk resmi.
- Pastikan Anda berhak menggunakan nama, logo, foto, dan materi promosi yang ditambahkan.
- Halaman ini merupakan situs konsultasi sales independen, bukan situs resmi Toyota Indonesia.
