# Portofolio Digital — Rizqullah Hilmi Arif Hendarto

Template portofolio statis HTML, CSS, dan JavaScript untuk dipublikasikan melalui GitHub Pages.

## Struktur folder

- `index.html` — seluruh bagian portofolio.
- `style.css` — desain responsif, tema teknologi dan multimedia.
- `script.js` — menu mobile, filter sertifikat, dan lightbox galeri.
- `assets/images/projects/` — gambar proyek.
- `assets/images/certificates/` — scan/foto sertifikat.
- `assets/images/gallery/` — foto dan thumbnail video.
- `assets/images/profile/` — foto profil jika nanti ditambahkan.

## Cara mengganti gambar

Salin gambar milikmu ke folder yang sesuai, lalu gunakan nama berikut atau ubah `src` / `data-lightbox` pada `index.html`:

### Proyek
- `assets/images/projects/ormawa-awards-cover.jpg`
- `assets/images/projects/web-database-cover.jpg`

### Sertifikat
- `assets/images/certificates/certificate-01.jpg`
- `assets/images/certificates/certificate-02.jpg`
- `assets/images/certificates/certificate-03.jpg`

### Galeri
- `assets/images/gallery/photo-01.jpg`
- `assets/images/gallery/photo-02.jpg`
- `assets/images/gallery/photo-03.jpg`
- `assets/images/gallery/video-cover.jpg`

Gambar sertifikat akan tampil di modal/lightbox ketika kartu diklik. Pastikan gambar sertifikat cukup jelas untuk dibaca, tetapi jangan publikasikan nomor identitas atau informasi pribadi yang tidak diperlukan. Gunakan hanya dokumentasi proyek yang boleh dibagikan.

## Cara menambah sertifikat

Duplikasi salah satu elemen `<article class="certificate-card" ...>` di `index.html`, lalu ubah:
- `data-category="it"` menjadi `it` atau `creative`
- nama gambar pada `data-lightbox`
- judul resmi sertifikat, penerbit, dan tahun sesuai dokumen asli.

## Cara menambah proyek

Duplikasi kartu proyek, ganti gambar, judul, ringkasan, teknologi, peran, dan URL demo/repository. Jangan menuliskan teknologi atau kontribusi yang tidak benar-benar digunakan/dikerjakan.

## Cara menambah video

Ganti gambar `video-cover.jpg` dengan thumbnail buatan sendiri. Ubah kartu galeri video menjadi tautan ke URL video publik, atau tambahkan modal video jika diperlukan. Jangan mengunggah video besar ke repository; gunakan platform video untuk file video dan tautkan dari website.

## Publikasi melalui GitHub Pages

1. Buat repository baru di GitHub, misalnya `portfolio`.
2. Unggah seluruh isi folder ini ke root repository (pastikan `index.html` berada di root).
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
5. Tunggu proses deployment, kemudian buka URL yang ditampilkan GitHub Pages.

URL biasanya berbentuk `https://USERNAME.github.io/portfolio/`. Untuk situs akun, repository khusus bernama `USERNAME.github.io` dapat menggunakan URL `https://USERNAME.github.io/`.

## Checklist sebelum dipublikasikan

- [ ] Ganti semua placeholder gambar dengan dokumentasi asli.
- [ ] Verifikasi nama, penerbit, dan tanggal setiap sertifikat.
- [ ] Perbarui teknologi dan kontribusi proyek sesuai fakta.
- [ ] Hapus kartu timeline yang belum diisi.
- [ ] Ubah tautan `Detail proyek` dari `#` menjadi URL yang valid atau hapus tautannya.
- [ ] Uji tampilan di desktop dan ponsel.
- [ ] Pastikan data internal, informasi orang lain, dan informasi sensitif tidak ikut terunggah.
