# Panduan Berkontribusi — Anak Ambis Project

Terima kasih sudah mau berkontribusi ke **ANAK-AMBIS**! 🎉  
Dokumen ini berlaku org-wide (default untuk semua repo di `ANAK-AMBIS` yang belum punya `CONTRIBUTING.md` sendiri).

---

## 🚀 Alur Cepat

1. **Fork** repo target (mis: `LampungWifi`)
2. **Clone** fork kamu:
   ```bash
   git clone https://github.com/<username-kamu>/LampungWifi.git
   cd LampungWifi
   ```
3. **Branch** baru dari `main`:
   ```bash
   git checkout -b feat/nama-fitur
   # atau fix/nama-bug, docs/nama-dokumen
   ```
4. **Coding** — jaga style konsisten, tulis commit jelas
5. **Commit & Push**:
   ```bash
   git add .
   git commit -m "feat: tambah fitur X"
   git push origin feat/nama-fitur
   ```
6. **Buka Pull Request** ke `ANAK-AMBIS/<repo>:main` — isi deskripsi, screenshot jika UI

---

## 📝 Aturan Commit

Gunakan format simpel (conventional commits):

- `feat: ...` fitur baru
- `fix: ...` perbaikan bug
- `docs: ...` dokumentasi
- `chore: ...` maintenance, deps, config
- `refactor: ...` refactor tanpa ubah fitur

Contoh: `feat: tambah filter status di dashboard`

---

## ✅ Checklist PR

- [ ] Branch dari `main` terbaru (`git pull origin main`)
- [ ] Tidak ada secret / `.env` ter-commit
- [ ] Sudah test lokal & tidak break build
- [ ] Deskripsi PR jelas (apa, kenapa, bagaimana test)
- [ ] Jika UI, lampirkan before/after screenshot

---

## 🐛 Lapor Bug / Request Fitur

- Buka **Issue** di repo terkait → pilih label `bug` / `enhancement`
- Sertakan: langkah reproduksi, expected vs actual, env (OS/browser/Node)

---

## 💬 Diskusi

- Tanya di **Issue** atau **Discussions** repo terkait
- Untuk org umum, bisa mention di Issue `.github` repo ini

---

## 📜 Kode Etik

Harap patuhi [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md). Pelanggaran bisa ditindak sesuai kebijakan maintainer.

---

## 🙏 Terima Kasih

Setiap kontribusi — kode, docs, ide, testing — sangat berharga.  
*Ambis boleh, tapi harus tuntas!* — Anak Ambis
