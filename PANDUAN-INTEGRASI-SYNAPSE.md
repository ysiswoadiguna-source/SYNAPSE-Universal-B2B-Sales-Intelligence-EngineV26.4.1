# SYNAPSE Universal B2B Sales Intelligence Engine — Panduan Integrasi

Panduan ini menjelaskan cara menggunakan **satu file `SKILL.md` gabungan** di ChatGPT, Google Gemini, dan Claude. File tersebut sudah berisi instruksi kerja dan knowledge base SYNAPSE, sehingga untuk distribusi single-file ini tidak diperlukan file `REFERENCE.md` terpisah.

**Repository:** [SYNAPSE Universal B2B Sales Intelligence Engine](https://github.com/ysiswoadiguna-source/SYNAPSE-Universal-B2B-Sales-Intelligence-Engine)  
**File utama:** [`SKILL.md`](SKILL.md)

## 1. ChatGPT Projects

1. Buka [ChatGPT](https://chatgpt.com/).
2. Buat Project bernama `SYNAPSE Sales Intelligence`.
3. Unggah file `SKILL.md` dari repository ke Project.
4. Buka pengaturan Project dan masukkan instruksi berikut:

   ```text
   Gunakan file SKILL.md SYNAPSE yang diunggah sebagai kerangka kerja utama. Ikuti aturan klasifikasi bukti, metode kualifikasi opportunity, panduan probability dan confidence, standar komunikasi, serta logika Next Best Action di dalamnya. Jangan mengarang informasi customer, produk, harga, waktu, atau kompetitor yang belum tersedia.
   ```

5. Mulai chat di dalam Project dan tempel percakapan customer, catatan CRM, atau email yang ingin dianalisis.

Panduan resmi: [Projects in ChatGPT](https://help.openai.com/id-id/articles/10169521-projects-in-chatgpt)

## 2. Google Gemini Skills

1. Buka [Google Gemini](https://gemini.google.com/).
2. Buka **Customize → Skills**, lalu pilih **Create/Upload** (nama menu dapat berbeda sesuai tampilan).
3. Pilih satu file `SKILL.md` dari repository ini.
4. Periksa nama Skill dan instruksi yang terdeteksi, lalu klik **Create**.
5. Aktifkan atau pilih Skill saat dibutuhkan, lalu uji dengan percakapan customer.

Panduan resmi: [Create and manage skills for Gemini Apps](https://support.google.com/gemini/answer/17094296?hl=id)

Gemini memerlukan metadata dan instruksi Skill berada di dalam `SKILL.md` pada tingkat utama. Versi ini disiapkan untuk alur satu file tersebut.

## 3. Claude Skills

Ikuti alur unggah yang tersedia di akun Claude Mas:

1. Buka [Claude](https://claude.ai/).
2. Jika diminta, aktifkan **Code execution and file creation** atau **Create and edit files** di pengaturan kemampuan.
3. Buka **Customize → Skills**, lalu pilih **Create skill / Upload a skill**.
4. Jika antarmuka menerima file Markdown langsung, unggah `SKILL.md`.
5. Jika antarmuka meminta ZIP, buat folder `synapse-sales-intelligence`, masukkan hanya `SKILL.md`, lalu kompres folder itu menjadi ZIP:

   ```text
   synapse-sales-intelligence.zip
   └── synapse-sales-intelligence/
       └── SKILL.md
   ```

6. Selesaikan impor, aktifkan Skill, lalu uji menggunakan percakapan customer.

Panduan resmi: [Use skills in Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude) · [How to create custom skills](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills)

## 4. Uji Integrasi

Setelah instalasi, tempel prompt ini:

```text
Analisis percakapan customer berikut menggunakan SYNAPSE Universal B2B Sales Intelligence Engine.

1. Tentukan posisi opportunity dan tahap pembelian saat ini.
2. Identifikasi buying signals, keberatan, risiko, dan informasi penting yang belum diketahui.
3. Perkirakan probability opportunity (0–99%) dan nyatakan confidence secara terpisah.
4. Rekomendasikan satu Next Best Action utama beserta alasannya.
5. Buat draft balasan untuk customer yang natural dan sesuai tahap hubungan serta proses penjualan.

Pisahkan fakta, klaim, dan inferensi. Jangan mengarang informasi yang belum tersedia.

[Tempel percakapan customer di sini]
```

## 5. Catatan Penggunaan

- Gunakan `SKILL.md` gabungan sebagai sumber utama kerangka SYNAPSE.
- Bedakan fakta terverifikasi, klaim customer, inferensi, hipotesis, dan hal yang belum diketahui.
- Jangan mengarang harga, stok, spesifikasi, detail kompetitor, tanggal, atau komitmen.
- Tinjau hasil analisis AI sebelum dipakai dalam komunikasi dengan customer.
- Jangan mengunggah data customer yang rahasia kecuali berwenang dan sudah memeriksa pengaturan data platform.

---

**Lebih sedikit menebak. Jualan lebih cerdas. Keputusan lebih baik.**
