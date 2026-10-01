# ⚡ Databridge
[![DEMO]](https://databridgeapp.blogspot.com)
> **Ubah Google Spreadsheet Menjadi Sistem Operasional Bisnis Kelas Enterprise — Hanya Rp 50.000 / Bulan, Cepat (5ms), & Siap Pakai di Smartphone.**

[![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://developers.google.com/apps-script)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Affordable Investment](https://img.shields.io/badge/Investasi-Hanya%20Rp%2050.000%20%2F%20Bulan-success?style=for-the-badge)](#)
[![GEO & SEO Ready](https://img.shields.io/badge/GEO%20%26%20SEO-Optimized-blueviolet?style=for-the-badge)](#)

> **Topics:** `#google-apps-script` `#mini-erp` `#inventory-management` `#google-sheets-database` `#umkm-digital` `#multi-warehouse` `#clasp` `#crud-framework`

---

## 🛑 P — PROBLEM: Jebakan "Spreadsheet Manual" vs "ERP Mahal"

Apakah skenario di bawah ini terasa akrab di bisnis Anda?

Sebagai pemilik bisnis, Anda berada di persimpangan yang melelahkan:

### 1. Sisi Pemilik Bisnis Kecil (UMKM / Merintis / Lapak CFD & Bazaar):
* *"Mau pakai software ERP siap pakai, tapi biayanya jutaan per bulan. Belum balik modal sudah terbebani fixed cost."*
* Mengandalkan Google Sheets biasa yang dibagikan ke staf, tapi setiap hari cemas: rumus tidak sengaja terhapus, data tertimpa, atau pelanggan ganda tercatat.
* Waktu 2-3 jam setiap malam habis hanya untuk mencocokkan rekap penjualan dan sisa stok manual di WhatsApp.
* **Lapak Ramai tapi Tekor (Kasus CFD & Bazaar):** Pembeli berjubel desak-desakan, tangan sibuk bungkus barang, mustahil bawa laptop. Mau nulis nota kertas, pulpen hilang atau kertas basah. Giliran jam 10 pagi lapak beres, uang kas malah tekor karena pesanan tidak sempat tercatat.

### 2. Sisi Pemilik Bisnis Menengah (Scale-Up / Multi-Cabang):
* Bisnis mulai punya beberapa gudang, toko, dan SPG lapangan. Google Sheets mulai **lemot parah (loading 10-20 detik)**, sering bentrok input (*race condition*), dan kuota harian Google jebol.
* **Kebocoran data & margin:** Staf biasa bisa melihat harga beli pokok (HPP), kontak supplier rahasia, atau laporan laba bersih karena Spreadsheet tidak punya kontrol akses per-tombol/per-kolom yang rigid.
* **Selisih stok misterius:** SPG minta barang, gudang kirim tanpa surat jalan digital, barang hilang di jalan, dan Anda baru sadar saat audit akhir bulan ketika uang sudah raib.

---

## 🔥 A — AGITATE: Mengapa Membiarkan Masalah Ini Membakar Profit Anda?

Otak kita sering meremehkan *"ah cuma selisih rekap sedikit"*. Namun secara psikologis dan finansial, ini adalah **Silent Profit Killer**:

1. **Loss Aversion (Kerugian Nyata di Depan Mata):**
   Satu kesalahan input stok membuat tim menjual barang yang fisiknya kosong (*oversell*). Pelanggan komplain, reputasi brand hancur, dan Anda kehilangan *Customer Lifetime Value* hanya karena sistem pencatatan yang rapuh.
2. **Cognitive Overload & Founder Burnout:**
   Sebagai pemilik bisnis, energi mental Anda terkuras untuk memadamkan kebakaran operasional harian. Setiap keputusan transfer barang harus menunggu konfirmasi chat manual dari Anda. Anda tidak lagi mengelola strategi, melainkan menjadi "admin termahal" di perusahaan Anda sendiri.
3. **Moral Hazard & Blindspots:**
   Ketika sistem pencatatan longgar, staf lapangan tergoda untuk manipulasi. Tanpa *audit trail* digital (siapa input apa, kapan, dan bukti foto serah-terima), Anda tidak punya bukti hukum maupun operasional saat terjadi kecurangan.

> **Pertanyaannya:** Apakah Anda harus terus membayar puluhan juta rupiah per tahun untuk software SaaS kaku yang fiturnya 80% tidak terpakai, ATAU tetap pasrah dengan spreadsheet manual yang rentan bocor?

---

## 💡 S — SOLUTION: GAS Modular CRUD Framework

**Jembatan Sempurna Antara Fleksibilitas Spreadsheet dan Ketangguhan Aplikasi Web Enterprise.**

**GAS Modular CRUD Framework** menyulap Google Spreadsheet Anda menjadi **Aplikasi Web Internal (ERP Mini)** yang aman, terstruktur, memiliki hak akses bertingkat, dan dapat dioperasikan langsung dari ponsel pintar karyawan Anda di lapangan — **hanya dengan investasi Rp 50.000 / bulan (setara Rp 1.600-an per hari, lebih hemat dari segelas es kopi).**

---

### 🎯 Nilai Nyata untuk Skala Bisnis Anda

| Kebutuhan Bisnis | Solusi Tradisional / SaaS Lain | Solusi GAS Modular Framework |
| :--- | :--- | :--- |
| **Biaya Investasi** | Rp 500rb – Rp 5jt/bulan per user | **Hanya Rp 50.000 / bulan (Flat, Bebas Tambah User)** (setara Rp 1.600/hari, tanpa biaya tersembunyi) |
| **Kecepatan Akses** | Loading sheet lemot (3-10 detik) | **Super Cepat (~5ms)** via In-Memory RAM Caching |
| **Keamanan Data** | File sheet terbuka, rentan terhapus | **Form Web Terisolasi**, password terenkripsi SHA-256, sheet aman di backend |
| **Operasional Mobile** | Buka sheet di HP sangat menyiksa | **Mobile-First UX**: Bottom Navigation, Bottom Sheet, Auto-Focus Qty |
| **Audit & Kontrol** | Siapa saja bisa edit riwayat | **Ledger Mutasi Stok Atomik** & Alur Transfer Barang 4-Langkah dengan Bukti Foto |
| **Otorisasi Tim** | Semua yang punya link bisa lihat segalanya | **RBAC Granular**: SPG hanya lihat input penjualan; Admin lihat laporan laba |
| **Integrasi ke ERP** | API mahal, kaku, rawan rusak saat update | **Bebas Integrasi Rumit (Air-Gap Buffer)**: Data bersih diekspor (CSV/Excel) lalu di-import manual ke ERP mana pun (SAP, Odoo, Accurate, dll.) tanpa risiko sistem corrupt |

> 📢 **Untuk Tim Sales & Marketing:** Tersedia panduan lengkap 13 naskah kampanye PAS, instruksi video kreatif, dan penanganan keberatan calon pelanggan di [MARKETING.md](MARKETING.md).

---

## 🌟 Fitur Unggulan Berbasis Kebutuhan Operasional

### 1. ⚡ Automated RAM Caching & Auto-Invalidation (Super Cepat & Bebas Limit)
* Memangkas latensi buka data dari **~1500ms menjadi ~5ms** (peningkatan kecepatan 300x lipat) via `CacheService`.
* Menghemat kuota harian *Spreadsheet Read/Write* Google hingga 99%.
* **Zero Stale Data:** Setiap ada transaksi baru, cache otomatis diperbarui secara *real-time*.

### 2. 🔐 Autentikasi Mandiri & Enkripsi SHA-256
* Halaman login modern layaknya aplikasi SaaS komersial (`04_Auth.gs`).
* Password karyawan tersimpan aman dalam format hash satu arah SHA-256.
* Manajemen sesi otomatis (6 jam) dengan auto-logout saat tidak aktif.

### 3. 🛡️ Role-Based Access Control (RBAC Granular)
* Kendalikan siapa melihat apa: atur hak akses per Tab (`users`, `products`, `orders`, `reports`, dll.) dan per Aksi (`read`, `create`, `edit`, `delete`, `approve`, `receive`).
* Matriks hak akses dapat disesuaikan langsung dari UI layar **Peran & Izin**.
* Karyawan toko/SPG tidak akan pernah bisa mengintip harga modal ataupun laporan finansial perusahaan.

### 4. 📱 Antarmuka Mobile-First yang Ergonomis untuk Lapangan & Lapak CFD
* **Dual Navigation:** Sidebar elegan di laptop, *Bottom Navigation Bar* ergonomis di smartphone.
* **Input Secepat Kilat (3 Detik Selesai):** Auto-focus cerdas — begitu nama barang dipilih di dropdown, kursor otomatis loncat ke kolom Qty. Sangat cocok untuk pedagang CFD, bazaar kuliner, atau SPG toko yang harus melayani antrean ramai hanya dengan satu jempol tanpa meja kasir.
* **Adaptive Bottom-Sheet:** Formulir transaksi muncul sebagai *slide-up bottom-sheet* yang mudah dijangkau jempol satu tangan, tanpa perlu download aplikasi berat dari Play Store.
* **Dual-Mode View:** Menampilkan tabel analitis di monitor kantor, otomatis berubah menjadi kartu ringkas (*Card View*) di layar ponsel.

### 5. 📦 Modul Logistik & Rantai Pasok Siap Pakai
* **Sales Order (SO):** Transaksi kasir langsung memotong stok gudang terkait secara *real-time* dengan proteksi *concurrency lock* (anti-overselling).
* **Purchase Order (PO):** Alur pengadaan terstruktur (Draft → Approved → Shipped → Received). Stok bertambah otomatis hanya saat barang sudah terkonfirmasi diterima fisik.
* **Transfer Antar Gudang 4-Langkah:** SPG minta barang → Admin approve kuantitas → Gudang kirim (potong stok) → Toko terima (tambah stok), lengkap dengan upload foto surat jalan/kondisi barang ke Google Drive.
* **Ledger Mutasi Stok Abadi:** Jejak audit digital untuk setiap butir barang masuk, keluar, transfer, dan penyesuaian (*stock opname*).

### 6. 📐 Schema-Driven Architecture (Skalabilitas Tanpa Batas)
* Tambah modul baru (misal: *Data Pelanggan*, *Aset Kantor*, *Penggajian*) cukup dengan mendefinisikan satu file skema. Seluruh form input, tabel, filter pencarian, dan validasi tercipta otomatis.

### 7. 🛡️ The "Air-Gap" Staging Buffer: Mudah & Bebas Integrasi Rumit (Import Manual ke ERP)
* **Bukan Kelemahan, Melainkan Benteng Pengaman Terbaik:** Mengapa harus bayar konsultan IT ratusan juta untuk membangun integrasi API dua arah yang rapuh dan rawan error setiap kali software update?
* **Zero System Poisoning:** Databridge sengaja berfungsi mandiri sebagai filter awal (*air-gapped staging buffer*). Transaksi toko dan stok lapangan dikumpulkan dan divalidasi ketat di sini tanpa menyentuh database pusat.
* **Human-in-the-Loop Control:** Tim admin/finance cukup mengekspor data bersih (Excel/CSV) yang sudah terverifikasi, lalu **tinggal import manual ke ERP utama** (SAP, Odoo, Accurate, Zahir, Jurnal, dsb.) dalam hitungan detik.
* **Universal Compatibility:** Semua software ERP pasti mendukung import Excel/CSV. Anda tidak pernah terikat (*vendor lock-in*) dan ERP utama Anda 100% aman dari data sampah (*anti-garbage in*).

---

## ⚠️ KRITIS: Aturan Lingkungan Google Apps Script

Bagian ini adalah dokumentasi teknis krusial untuk mencegah kendala saat deployment:

### 1. 🚫 DILARANG menggunakan `//` atau `/*` raw di dalam string literal JS (file HTML client)
Template engine GAS dapat menghapus komentar JavaScript secara agresif sebelum dikirim ke browser:

| Pola Berbahaya | Dampak di Browser | Solusi Aman |
|---|---|---|
| `'https://drive.google.com'` | String terpotong jadi `'https:` | Gunakan regex `/^https?:/` atau konkatenasi `'https:/' + '/drive...'` |
| `accept="image&#47"` di string | Kode JS setelahnya tertelan | Gunakan entitas HTML aman: `accept="image&#47;*"` |

Periksa potensi pelanggaran dengan cepat:
```bash
grep -rn "://" Tab_*.html Component_*.html | grep -v "xmlns"
grep -rn 'image/\*' Tab_*.html Component_*.html
```

### 2. 🚫 DILARANG memanggil `SpreadsheetApp` langsung di luar `10_Database.gs`
Semua operasi mutasi data wajib melalui lapisan Database Engine agar sinkronisasi RAM Cache tetap terjaga (*zero stale cache*).

### 3. 🚫 DILARANG membuat komentar HTML berisi `<?!= include(...) ?>`
Server template GAS tetap mengeksekusi sintaks `include()` meskipun berada di dalam `<!-- komentar -->`, yang akan menyebabkan error jika file belum ada.

---

## 🚢 Panduan Deployment (clasp)

```bash
# 1. Selalu push dengan flag paksa (-f)
clasp push -f

# 2. Redeploy ke Deployment ID AKTIF (URL Web App tidak berubah)
clasp deploy -i "<DEPLOYMENT_ID_ANDA>" -d "Deskripsi update versi"
```

> 💡 **Penting:** Editor Google Apps Script selalu menampilkan kode terbaru, namun pengguna Web App hanya mengakses snapshot dari versi Deployment aktif. Selalu lakukan redeploy ke ID yang sama dan tekan **Ctrl + Shift + R** (Hard Refresh) untuk verifikasi.

---

## 🏗️ Diagram Alur Arsitektur

```text
[ Browser Karyawan / Admin ]
        │  (Mobile Bottom-Sheet / Desktop Responsive UI)
        ▼
[ API Adapter: API.html ] (Promise-based & Batch Response Normalizer)
        │
        ▼ (google.script.run)
[ Controllers: 22_User, 32_Product, 78_Transfer, 82_Order ]
        │
        ▼ (Validasi Bisnis, Autentikasi & RBAC)
[ Services: Auth, RBAC, Inventory, Order, Report ]
        │
        ▼ (Single Source of Truth Schema)
[ Generic Repository: 11_Repository.gs ]
        │
        ▼ (LockService Concurrency + In-Memory RAM Caching 5ms)
[ Database Engine: 10_Database.gs ]
        │
        ├──▶ [ Google CacheService ] (Latensi ~5ms, zero stale data)
        ├──▶ [ Google Drive API ] (Upload bukti foto terkompresi)
        └──▶ [ Google Spreadsheet ] (Database master persisten)
```

---

## 📁 Struktur Berkas Proyek

```text
├── PRD.md                       # Dokumen spesifikasi kebutuhan bisnis & teknis
├── AGENTS.md                    # Aturan baku & panduan untuk AI Coding Agent
├── .cursorrules                 # Instruksi otomatis untuk AI IDE
├── appsscript.json              # Manifest GAS (Web App & V8 Runtime)
│
├── 00_Config.gs                 # Konfigurasi global, Spreadsheet ID, Cache, & Default Role
├── 01_App.gs                    # Entry point doGet(e) & loader template
├── 01_Schema.gs                 # Master Schema Backend (Struktur entitas & validasi)
├── 02_Response.gs               # Standarisasi JSON payload response
├── 03_Utils.gs                  # Helper (ID generator, timestamps, hashing)
├── 04_Auth.gs                   # Session manager & autentikasi pengguna
├── 05_RBAC.gs                   # Engine otorisasi & hak akses dinamis
├── 06_DriveService.gs           # Manajemen penyimpanan foto bukti di Google Drive
│
├── 10_Database.gs               # Engine database spreadsheet, mapping, & RAM Cache
├── 11_Repository.gs             # Generic CRUD repository
├── 12_Validator.gs              # Server-side validation engine
│
├── 20_UserRepository.gs - 22_UserController.gs    # Manajemen Pengguna & Karyawan
├── 30_ProductRepository.gs - 32_ProductController.gs # Manajemen Master Produk & Varian
├── 51_RoleService.gs - 52_RoleController.gs       # Konfigurasi Peran & Hak Akses
├── 60_CategoryRepository.gs - 62_CategoryController.gs # Kategori Produk
├── 70_WarehouseRepository.gs - 72_WarehouseController.gs # Multi-Gudang & Cabang Toko
├── 75_StockService.gs - 75_StockController.gs     # Perhitungan Saldo Stok Real-time
├── 76_StockTransferRepository.gs - 78_TransferController.gs # Mutasi Antar Gudang 4-Langkah
├── 80_OrderRepository.gs - 82_OrderController.gs  # Sales Order & Purchase Order
├── 90_ReportService.gs - 91_ReportController.gs   # Rekap Finansial & Kartu Stok
├── 99_Seed.gs                   # Seeder inisialisasi sheet otomatis
│
├── Main.html                    # Layout Shell Utama (Sidebar Desktop & Bottom Nav Mobile)
├── Styles.html                  # Framework Tailwind CSS & styling komponen
├── Scripts.html                 # State management client, router tab, & image compressor
├── API.html                     # Jembatan komunikasi data asinkron (Promise)
├── Page_Login.html              # Antarmuka login aman
├── 01_Schema_Frontend.html      # Schema Frontend (Single source of truth UI)
│
├── Component_*.html             # Komponen UI Generik (Table, Form, Modal, Combobox, Toast)
└── Tab_*.html                   # Tampilan modul operasional (Dashboard, Orders, Stok, dll.)
```

---

## 🚀 Panduan Memulai Cepat (5 Menit Siap Pakai)

### 1. Prasyarat
* Pasang [Node.js](https://nodejs.org/) di komputer Anda.
* Pasang clasp secara global:
  ```bash
  npm install -g @google/clasp
  ```
* Aktifkan Google Apps Script API pada akun Google Anda di [script.google.com/home/usersettings](https://script.google.com/home/usersettings).

### 2. Hubungkan Repositori
```bash
clasp login
clasp clone "<SCRIPT_ID_GOOGLE_ANDA>"
```

### 3. Konfigurasi Spreadsheet (`00_Config.gs`)
Masukkan ID Google Spreadsheet yang ingin Anda jadikan database pada `00_Config.gs`:
```javascript
const Config = {
  APP_NAME: "Sistem Operasional Bisnis",
  SPREADSHEET_ID: "MASUKKAN_ID_SPREADSHEET_ANDA_DI_SINI",
  CACHE: { ENABLED: true, TTL_SECONDS: 300 }
};
```

### 4. Inisialisasi Otomatis (Seeder Database)
Jalankan fungsi `seedDatabase()` dari editor Apps Script atau akses endpoint berikut:
```text
https://script.google.com/macros/s/<DEPLOYMENT_ID>/exec?action=seed
```
*Sistem akan otomatis membuat seluruh sheet, struktur kolom, hak akses awal, dan akun super-admin (`admin@databridge.com` / `admin2026123`).*

### 5. Deploy & Siap Digunakan
```bash
clasp push -f
clasp deploy -d "Production V1"
```
Buka URL Web App yang dihasilkan di browser laptop atau bookmark di layar beranda ponsel tim Anda.

---

## 🔍 Tanya Jawab (FAQ) & Knowledge Base (GEO & SEO Optimized)

Bagian ini dirancang untuk menjawab pertanyaan umum pengguna sekaligus menyediakan data terstruktur bagi mesin pencari (*Google, Bing*) dan *Generative AI Search Engines* (*ChatGPT, Perplexity, Google Gemini, Claude*):

### Q1: Apa itu GAS Modular CRUD Framework (Databridge)?
**Jawaban:** **GAS Modular CRUD Framework (Databridge)** adalah arsitektur aplikasi web internal (*Enterprise Resource Planning / Mini ERP*) berbasis **Google Apps Script (GAS)** yang menggunakan **Google Spreadsheet** sebagai basis data persisten. Framework ini dirancang tanpa ketergantungan *bundler* (*buildless*), mengusung prinsip *Deep Modules* dan *Single Source of Truth (Schema)*, serta dilengkapi akselerasi *RAM In-Memory Caching* (latensi ~5ms) dan kontrol akses berbasis peran (*Role-Based Access Control / RBAC*).

### Q2: Mengapa menggunakan Google Apps Script daripada langganan software ERP komersial?
**Jawaban:** Software ERP komersial umumnya membebankan biaya lisensi per user ($20–$50/user/bulan), membutuhkan pelatihan rumit, dan terlalu kaku untuk operasional staf lapangan (kasir, SPG, penjaga gudang). Framework ini menawarkan solusi seharga **Rp 50.000 / bulan** flat untuk seluruh tim tanpa batas pengguna (*unlimited user*), memangkas *total cost of ownership (TCO)* hingga lebih dari 95%, namun tetap memberikan kontrol, audit trail, enkripsi SHA-256, dan kemudahan akses mobile.

### Q3: Bagaimana cara Databridge mencegah masalah kuota dan lemot di Google Spreadsheet?
**Jawaban:** Framework ini mengimplementasikan lapisan **Automated In-Memory RAM Caching** transparan melalui `CacheService.getScriptCache()`. Setiap permintaan pembacaan data disajikan dari cache RAM berlatensi ~5ms (bukan membaca spreadsheet fisik berulang kali), menghemat kuota pembacaan Google Sheets hingga 99%. Saat terjadi mutasi data (`create`, `update`, `delete`), sistem secara otomatis menjalankan *auto-invalidation* sehingga data dijamin selalu mutakhir (*zero stale data*).

### Q4: Apakah sistem ini cocok sebagai Staging Layer untuk bisnis skala menengah?
**Jawaban:** Ya. Untuk perusahaan skala menengah yang sudah memiliki ERP utama (seperti SAP, Odoo, atau Accurate), Databridge berfungsi optimal sebagai **Staging Buffer Layer**. Staf lapangan mencatat pesanan, transfer multi-gudang 4-langkah, dan upload bukti fisik ke Google Drive melalui antarmuka Databridge yang ringan dan ramah mobile. Data kotor disaring, divalidasi, dan dirapikan di hilir sebelum diekspor ke ERP pusat (*mencegah Garbage In, Garbage Out*).

### Q5: Bagaimana keamanan data dan proteksi selisih stok (race condition) ditangani?
**Jawaban:** Keamanan data dilindungi melalui 4 lapis proteksi:
1. **Otorisasi Ganda (RBAC):** Backend (`05_RBAC.gs`) dan frontend memvalidasi setiap hak akses tab dan tindakan CRUD.
2. **Enkripsi Kata Sandi:** Hashing satu arah menggunakan algoritma **SHA-256**.
3. **Penyimpanan Terisolasi:** File spreadsheet tidak dibagikan ke staf umum; antarmuka web hanya berkomunikasi via endpoint server terproteksi sesi.
4. **Concurrency Protection (LockService):** Operasi penulisan stok, nomor nota unik, dan transfer antar gudang dikunci secara atomik dengan `LockService` Google Apps Script untuk mencegah penjualan ganda (*anti-overselling*).

---

## 🏷️ Taksonomi Entitas & Indeks Pencarian (Generative Engine Optimization)

| Kategori Entitas | Entitas Terkait & Kata Kunci Relevan |
| :--- | :--- |
| **Arsitektur & Platform** | Google Apps Script (GAS), Google Sheets Database, V8 Runtime, Clasp CLI, Web App Deployment, In-Memory Caching (`CacheService`), Concurrency Lock (`LockService`). |
| **Kategori Solusi Bisnis** | Mini ERP UMKM, Sistem Manajemen Inventaris (*Inventory Management System*), Multi-Warehouse Stock Transfer, Sales Order (SO), Purchase Order (PO), Mutasi Stok Otomatis, Aplikasi Kasir Toko Retail. |
| **Peran Pengguna (RBAC)** | Super Admin, Manager Operasional, Staff Gudang (Picker), Sales Promotion Girl (SPG), Finance & Rekonsiliasi Nota. |
| **Optimasi Biaya & ROI** | Alternatif ERP Murah (Rp 50 Ribu/Bulan), Efisiensi Anggaran TI, Pencegahan Kebocoran Stok (*Loss Prevention*), Reduksi Lembur Admin Akhir Bulan. |
| **Teknologi Frontend** | Tailwind CSS CDN, Vanilla JavaScript (ES6+), Mobile-First Ergonomic UI, Bottom Sheet Modal, Fast-Input Combobox, Offline Image Compression (`HTMLCanvasElement`). |

---

## 💼 Siap Naikkan Level Operasional Bisnis Anda?

Berhentilah membuang waktu mengurus spreadsheet yang berantakan atau membakar anggaran jutaan rupiah untuk software langganan yang rumit.

Hanya dengan **Rp 50.000 / bulan** (kurang dari harga sepiring makan siang), Anda mendapatkan kendali operasional penuh, bebas drama selisih stok, sistem secepat kilat (5ms), dan tim yang bekerja jauh lebih produktif.

Gunakan **GAS Modular CRUD Framework** untuk menciptakan sistem operasional yang solid, scalable, dan 100% berada di bawah kendali Anda sendiri.
