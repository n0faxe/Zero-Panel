Ninja Zero Panel 1.0.2 - Portable
=====================================

Cara menjalankan
----------------
1. Extract seluruh folder ini ke lokasi mana pun (path boleh mengandung spasi).
2. Double-click "Start Panel.bat".
3. Buka http://127.0.0.1:8100 di browser.

Panel tidak membuka browser otomatis. Perubahan port:

  set PORT=8101
  "Start Panel.bat"
  REM lalu buka http://127.0.0.1:8101

Atau langsung: node.exe app.cjs --port=8101

Access Key
----------
Panel terkunci sampai Access Key Zero diaktifkan. Di kartu Access Key, salin
"Your Device ID", generate key lewat bot Discord zero-license-bot, lalu tempel
key NZPANEL.... dan klik Activate Access Key.

PENTING: Device ID dihitung dari hostname + CPU + platform. Key yang dibuat di
komputer lain TIDAK akan berfungsi di sini. Generate ulang key untuk host ini.

Data & keamanan
---------------
- data/license.json menyimpan key aktif. Jangan dibagikan.
- Quick login menyimpan username + password di browser localStorage.
- Panel hanya listen di 127.0.0.1. Jangan ubah ke 0.0.0.0 tanpa autentikasi.

Feature
---------------
- Auto Levelling
- Auto Exam
- Auto Eudemon
- Clan War Panel

Lisensi
--------
Folder ini membawa binary Node.js. Sertakan LICENSE Node.js saat
mendistribusikan ulang. Panel ini bukan produk resmi Ninja Zero / Ninja Saga.

Pembuat tidak bertanggung jawab untuk penyalah gunaan panel ini.
