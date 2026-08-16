# ultah 🎂💖

Website statis interaktif yang dibuat khusus untuk memberikan kejutan ulang tahun (dan sedikit *prank*) kepada pacar tersayang. Menggunakan tema karakter **Bubu Dudu** yang menggemaskan!

Web ini dibangun menggunakan HTML, CSS, dan Vanilla JavaScript murni tanpa *framework*, sehingga sangat ringan dan mudah di-hosting secara gratis menggunakan **GitHub Pages**.

---

## ✨ Fitur Utama

- 🛡️ **Sistem Anti-Curang (Anti-Cheat):** Menggunakan `sessionStorage` untuk mencegah pengunjung melompati halaman (misal: langsung mengakses `end.html`). Jika ketahuan curang, akan muncul pop-up Bubu marah yang memaksa kembali ke halaman awal.
- 🏃‍♀️ **Interactive Buttons:** Tombol yang bisa menghindar, mengecil, atau menghilang (*fade out*) saat diklik, memaksa target untuk memilih jawaban yang kita inginkan.
- 💥 **Particle Animations:** Efek ledakan *confetti* (bintang dan hati) warna-warni yang dibuat menggunakan Vanilla JS dan Web Animations API.
- ⌨️ **Typewriter Effect:** Efek teks mengetik perlahan untuk memberikan kesan dramatis saat membaca pesan romantis.
- 📱 **WhatsApp Integration:** Pesan balasan di halaman terakhir akan langsung diformat dan dikirimkan ke nomor WhatsApp yang sudah ditentukan.
- 🎨 **Responsive Design:** Tampilan rapi dan mulus, baik dibuka melalui layar HP maupun Laptop (Flexbox).

---

## 🗺️ Alur Halaman (User Flow)

Website ini dirancang seperti sebuah permainan berurutan. Berikut adalah urutan halamannya:

1. **`index.html`** - Pertanyaan awal "Siapa yang ulang tahun?". Tombol "Bukan saya" akan terus mengecil jika ditekan.
2. **`next1.html`** - Pemilihan tanggal. Tanggal hari ini otomatis terdeteksi, namun tombolnya akan menghilang cantik jika ditekan, menyisakan tanggal ulang tahun yang asli.
3. **`next2.html`** - Mini game! Harus mengetuk icon kado sebanyak 10 kali yang akan memunculkan efek ledakan partikel sebelum bisa lanjut.
4. **`next3.html`** - *Prank* Zonk! Ledakan partikel besar tapi isinya ucapan "tidak ada hadiah disini" wkwk.
5. **`next4.html`** - *Prank* lanjutan "tapi boong" yang akan otomatis berpindah halaman dalam 4 detik.
6. **`next5.html`** - Pesan manis pertama (disertai efek mengetik).
7. **`next6.html`** - Pesan romantis utama (disertai efek mengetik yang lebih lambat agar baper maksimal).
8. **`end.html`** - Halaman terakhir untuk menagih ucapan terima kasih. Input teks terhubung langsung ke API WhatsApp. Lengkap dengan validasi *pop-up* jika pesan kosong.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** & **CSS3** (Styling, Animasi Keyframes)
- **Vanilla JavaScript** (DOM Manipulation, Timeout, SessionStorage, Animations API)
- **FontAwesome** (Icon kado, bintang, hati)
- **Google Fonts** (Font *Nunito*)
- **Tenor GIF Embed** (Stiker Bubu Dudu)

---

## 🚀 Cara Menjalankan secara Lokal

1. Lakukan *Clone* repositori ini:
   ```bash
   git clone [https://github.com/username-kamu/nama-repo-kamu.git](https://github.com/username-kamu/nama-repo-kamu.git)
