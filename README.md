# Kottox TV Home

Launcher ringan untuk Google TV, tanpa iklan. Repositori ini hanya berisi rilis APK.

## Fitur

- Aplikasi bisa disusun dan disembunyikan
- Rekomendasi YouTube per kategori
- Waktu shalat dan kartu pengingat, bisa dimatikan
- Cuaca dan tanggal Hijriah, bisa dimatikan
- Mode anak dengan PIN
- Tombol Input untuk pindah ke HDMI

## Pasang

Nyalakan USB debugging di TV, lalu unduh APK dari halaman [Releases](../../releases/latest):

```bash
adb connect ALAMAT_IP_TV:5555
adb install -r Kottox-TV-Home-*.apk
```

Aplikasi ini tidak otomatis menjadi launcher utama selama launcher Google masih aktif. Mematikan launcher Google dapat menghilangkan panel cepat dari tombol setelan remote dan membuat Wi-Fi TV meminta sandi lagi. Lakukan dengan risiko sendiri.
