# 📈 StockRadar AI — Pengamat Saham Cerdas

Aplikasi web pengamat saham Indonesia & global dengan analisis AI, sinyal beli, kalkulator saham terdiskon, dan portfolio tracker. Dilindungi password.

---

## 🔑 Password & Pengaturan Penting

Sebelum upload, buka file `index.html` dengan teks editor (Notepad, VS Code, dll) dan ubah baris ini di bagian atas `<script>`:

```javascript
// 🔑 GANTI PASSWORD DI SINI (default: stockradar2025)
const APP_PASSWORD = "stockradar2025";
```

Ganti `stockradar2025` dengan password pilihanmu, lalu simpan.

> ⚠️ **Catatan keamanan:** Password ini disimpan di sisi browser (client-side). Cocok untuk membatasi akses kasual agar tidak sembarang orang bisa masuk, tapi orang yang paham teknis bisa melihatnya lewat "view source". Untuk keamanan penuh, perlu server backend. Untuk penggunaan pribadi, ini sudah memadai.

---

## 🚀 Cara Upload ke GitHub Pages (Gratis)

### Langkah 1 — Buat Repository
1. Login ke [github.com](https://github.com)
2. Klik **+** (pojok kanan atas) → **New repository**
3. Beri nama, misal: `stockradar`
4. Pilih **Public** (wajib untuk GitHub Pages gratis)
5. Klik **Create repository**

### Langkah 2 — Upload File
1. Di halaman repo, klik **Add file** → **Upload files**
2. Seret file **`index.html`** ke area upload
3. Klik **Commit changes**

### Langkah 3 — Aktifkan GitHub Pages
1. Buka tab **Settings** di repo
2. Menu kiri → **Pages**
3. Bagian **Branch**, pilih **main** dan folder **/ (root)**
4. Klik **Save**
5. Tunggu 1–2 menit

### Langkah 4 — Akses Aplikasi
URL aplikasi kamu akan menjadi:
```
https://USERNAME.github.io/stockradar/
```
Ganti `USERNAME` dengan username GitHub-mu.

---

## 🤖 Mengaktifkan Fitur AI (Penting)

Aplikasi punya 2 mode:

| Mode | Yang Berfungsi |
|------|----------------|
| **Demo** (tanpa API key) | Tampilan & navigasi penuh, tapi data saham simulasi |
| **Penuh** (dengan API key) | Harga real-time, analisis AI, scanner diskon, semua tools |

### Cara menambahkan API Key:
1. Buka aplikasi, login dengan password
2. Klik tombol **⚙️** (pojok kanan atas)
3. Tempel **Anthropic API Key** kamu
4. Klik **Simpan**

Dapatkan API key di: [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)

> 🔒 API key disimpan **hanya di browser kamu** (localStorage), tidak dikirim ke server mana pun selain Anthropic langsung. Setiap pengguna memasukkan key-nya sendiri.

---

## ✨ Fitur Lengkap

**👁 Watchlist** — 41 saham IDX + Global, harga per lot, sinyal BUY/HOLD/SELL, 52-week high/low dengan tanggal, estimasi profit, tambah saham kustom otomatis.

**💼 Portofolio** — Lacak saham yang sudah dibeli, hitung P&L otomatis (untung/rugi real-time).

**🏷️ Diskon** — Scanner saham terdiskon, kalkulator nilai intrinsik (Graham/DCF/PEG), Fibonacci entry timing, strategi alokasi modal.

**🤖 AI Tools** — Smart Analyzer, Technical Scanner, Trading Plan Builder, Multi-Stock Comparison, Market Timing, Post-Trade Review.

---

## 📱 Tips
- Bisa diakses dari HP — buka URL di browser, lalu **"Add to Home Screen"** agar seperti app native.
- Data watchlist & portofolio kustom tersimpan otomatis di browser.
- Untuk logout, buka ⚙️ → Logout.

---

## ⚠️ Disclaimer
Aplikasi ini alat bantu analisis, **bukan saran investasi/finansial resmi**. Selalu lakukan riset mandiri dan pertimbangkan profil risiko sebelum berinvestasi.
