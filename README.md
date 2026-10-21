# sailox-workspace

Backup berkala isi workspace VM Muse — proyek Sailox (bot & panel) dan file kerja Veo. Tanpa secret, session, cache, atau node_modules.

## Rencana isi
- `sailox-bot/` — bot WhatsApp Sailox (repo utamanya tetap di Etherveo/sailox-bot)
- `sailox-panel/` — panel pengelola bot di Library Muse
- File kerja lain di workspace yang relevan

## Aturan main
- Jangan pernah commit: file `.env`, `config.js`, session WhatsApp, `creds.json`, token, isi `databases/`, `node_modules/`, cache, log, dan arsip zip besar. Pagar utamanya adalah `.gitignore` di repo ini — selalu cek daftar file sebelum push.
- Backup dijalankan berkala atas perintah Veo, belum otomatis.
- Repo ini public demi akses yang lancar; karena itu aturan secret di atas bersifat mutlak.

## Catatan struktur ke depan
Pertimbangan Veo: pindah ke GitHub Organization **Miraisentris** dengan satu repo per project. Status sailox-bot (digandakan, fork yang tetap menerima update, atau tetap di Etherveo) belum diputuskan.
