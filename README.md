# Ultimate Gitignore & Git Automation

Skrip ini memudahkan manajemen `.gitignore` untuk multi-project dan submodules, sekaligus melakukan commit batch otomatis dengan Git LFS.

---

## 1. ultimate_gitignore.sh

Skrip Bash untuk **auto-update `.gitignore`** berdasarkan project type:

- Node.js
- Python
- Java / Android
- iOS / Swift
- Sistem / editor / logs / backup

### Fitur
- Deteksi project type secara rekursif (termasuk submodules).
- Tambahkan rules umum (`.DS_Store`, `.vscode/`, `*.log`, dll.).
- Tambahkan rules spesifik tiap bahasa/framework.
- Merge dengan rules lama dan hapus duplikat otomatis.

### Cara Pakai
1. Jadikan executable:
   ```bash
   chmod +x ultimate_gitignore.sh