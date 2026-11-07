# Pentest Report Generator

Alat command line (Python) yang mengubah catatan temuan penetration testing menjadi laporan HTML yang rapi.

## Rencana

- Menulis temuan dalam file YAML
- Menghitung skor dan tingkat keparahan dari vektor CVSS v3.1
- Mengimpor hasil pemindaian nmap (XML)
- Menghasilkan laporan HTML yang bisa dicetak menjadi PDF dari browser

## Status

Dalam pengerjaan bertahap.

- [x] Hari 1: format data temuan
- [ ] Hari 2: pembaca dan validasi file temuan
- [ ] Hari 3: penghitung skor CVSS v3.1
- [ ] Hari 4: pengimpor hasil nmap
- [ ] Hari 5: template laporan HTML
- [ ] Hari 6: laporan contoh dan panduan pemakaian

## Etika dan batasan

Alat ini hanya untuk mendokumentasikan pengujian pada sistem milik sendiri atau yang secara resmi mengizinkan.
Data contoh di repo ini fiktif dan memakai alamat dokumentasi (192.0.2.0/24).