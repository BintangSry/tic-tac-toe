
# Tic‑Tac‑Toe

Game **Tic‑Tac‑Toe** sederhana berbasis web, menggunakan **HTML**, **CSS**, dan **JavaScript**. Kamu bisa bermain dengan teman via browser — lengkap dengan deteksi giliran pemain, cek kemenangan atau seri, dan tombol *reset*.

---

## 🎲 Fitur

- Papan 3×3 interaktif
- Pertukaran giliran otomatis antara **X** dan **O**
- Pendeteksian menang (baris, kolom, diagonal) dan seri
- Tombol **Reset/New Game** untuk mulai ulang permainan

---

## 📂 Struktur Proyek

```
tic-tac-toe/
├─ index.html         # Struktur tampilan game
├─ style.css          # Gaya visual untuk papan & tombol
└─ script.js          # Logika permainan (giliran, cek kemenangan, reset)
```

---

## 🚀 Cara Menjalankan

1. **Clone** repositori:
   ```bash
   git clone https://github.com/BintangSry/tic-tac-toe.git
   ```
2. Masuk ke folder:
   ```bash
   cd tic-tac-toe
   ```
3. Buka file `index.html` di browser:
   - Klik dua kali filenya, **atau**
   - Jalankan live server (VSCode / ekstensi serupa)

---

## 🧩 Cara Kerja Logika

- Semua kotak dihubungkan dengan event listener `click` di `script.js`.
- Setiap klik menempatkan tanda (X/O) berdasarkan giliran saat ini.
- Setelah tiap langkah, dicek kondisi kemenangan atau papan penuh (seri).
- Jika game selesai, tampilkan pesan pemenang/seri dan nonaktifkan papan hingga *Reset* diklik.

---

## 🧪 Contoh Pemakaian

1. Pemain X klik kotak → tanda “X” muncul.
2. Otomatis giliran O, dan seterusnya.
3. Setelah ada 3 tanda sejajar (baris/kolom/diagonal), muncullah pesan “X menang!” atau “O menang!”
4. Jika papan penuh tanpa pemenang → “Draw!”
5. Klik “New Game” → mulai ulang papan kosong.

---

## 🛠️ Kontribusi

Ingin tambahkan fitur seperti:
- AI / komputer lawan
- Mode 2, 3 pemain atau skor harian
- Responsif untuk mobile
- Animasi / tema grafis

Silakan:
1. Fork repositori ini
2. Buat branch: `git checkout -b fitur-baru`
3. Commit dengan jelas terkait perubahan
4. Push dan bikin pull request

---

## 📄 Lisensi

dibuat oleh **BintangSry**

---

## 📌 Kontak

Ada ide, saran, atau bug? Feel free untuk hubungi:
- GitHub Issues di repo ini
- [bintangsry31@gmail.com]

---

**Selamat bermain & semangat coding! 🧑‍💻**
