# Panduan Integrasi SYNAPSE Universal B2B Sales Intelligence Engine

Panduan singkat untuk menggunakan SYNAPSE di ChatGPT, Google Gemini, dan Claude.

Repository: [SYNAPSE Universal B2B Sales Intelligence Engine](https://github.com/ysiswoadiguna-source/SYNAPSE-Universal-B2B-Sales-Intelligence-Engine)

---

## 1. ChatGPT

Gunakan file knowledge SYNAPSE yang sudah tersedia. Tidak perlu membuat ZIP.

1. Buka [ChatGPT](https://chatgpt.com/).
2. Buat **Project** baru dan beri nama `SYNAPSE Sales Intelligence`.
3. Unggah file `SYNAPSE Universal B2B Sales Intelligence Engine_26.4.1.MD` ke Project.
4. Tambahkan instruksi Project berikut:

   > Gunakan file SYNAPSE sebagai knowledge base utama. Ikuti aturan analisis, klasifikasi bukti, penilaian opportunity, dan Next Best Action yang tercantum di dalamnya.

5. Mulai percakapan dengan menempelkan chat customer, email, atau data CRM yang ingin dianalisis.

**Referensi:** [Projects di ChatGPT](https://help.openai.com/id-id/articles/10169521-projects-in-chatgpt)

> Catatan: Project merupakan cara praktis untuk menyimpan file dan instruksi yang digunakan kembali. Ketersediaan fitur dapat bergantung pada akun atau workspace.

---

## 2. Google Gemini

Gemini Skills memerlukan file `SKILL.md` sebagai instruksi utama. Paket ZIP SYNAPSE yang disiapkan berisi instruksi Skill dan file knowledge SYNAPSE sebagai referensi.

1. Unduh paket ZIP SYNAPSE yang disediakan.
2. Buka [Google Gemini](https://gemini.google.com/).
3. Masuk ke **Customize → Skills → Create → Upload**.
4. Unggah ZIP SYNAPSE.
5. Tinjau isi Skill, lalu pilih **Create**.
6. Uji Skill menggunakan contoh percakapan customer.

**Referensi:** [Bantuan Gemini Skills](https://support.google.com/gemini/answer/17094296?hl=en)

> Catatan: Nama menu dan ketersediaan fitur dapat berbeda menurut akun, wilayah, atau perubahan antarmuka Gemini.

---

## 3. Claude

Claude mendukung penggunaan custom Skills melalui paket ZIP.

1. Unduh paket ZIP SYNAPSE yang sama.
2. Buka [Claude](https://claude.ai/).
3. Masuk ke **Customize → Skills → + Create skill → Upload a skill**.
4. Unggah ZIP SYNAPSE.
5. Selesaikan proses impor dan aktifkan Skill.
6. Uji Skill menggunakan contoh percakapan customer.

**Referensi:** [Panduan custom Skills Claude](https://support.claude.com/id/articles/12512198-cara-membuat-keterampilan-khusus)

> Catatan: Ikuti persyaratan dan petunjuk yang ditampilkan di akun Claude saat proses impor.

---

## 4. Prompt untuk Menguji SYNAPSE

Setelah integrasi selesai, gunakan prompt berikut untuk menguji hasilnya:

```text
Analisis percakapan customer berikut menggunakan SYNAPSE Universal B2B Sales Intelligence Engine.

1. Tentukan posisi opportunity saat ini.
2. Identifikasi buying signals, risiko, dan key unknown.
3. Berikan estimasi probability (0–99%) dan confidence.
4. Tentukan satu Next Best Action.
5. Buat draft WhatsApp yang sesuai dengan tahap hubungan customer.

Bedakan fakta dan asumsi. Jangan mengarang informasi.

[Tempel percakapan customer di sini]
```

## 5. Prinsip Penggunaan

- Gunakan file knowledge SYNAPSE sebagai acuan analisis.
- Jangan menganggap asumsi sebagai fakta.
- Jangan mengarang harga, spesifikasi, komitmen, atau informasi customer yang belum tersedia.
- Bandingkan hasil di masing-masing platform karena respons AI dapat berbeda.

---

**SYNAPSE Universal B2B Sales Intelligence Engine**  
*Less guessing. Smarter selling. Better decisions.*
