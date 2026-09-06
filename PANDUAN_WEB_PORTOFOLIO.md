# Brief: Website Portofolio — Moch. Alfan Miftachul Huda

> **Cara pakai file ini:** Salin seluruh isi file ini dan tempelkan sebagai prompt/instruksi ke AI coding agent (Claude Code, Cursor, dsb). Agent akan punya semua konteks, struktur, dan konten yang dibutuhkan untuk langsung membangun dan men-deploy situs ini ke GitHub Pages tanpa perlu banyak bertanya balik.

---

## 1. Tujuan Proyek

Buatkan saya website portofolio pribadi, satu halaman (single-page), untuk dilampirkan sebagai **portofolio URL** pada lamaran program *Professional Development Program (PDP) Technology* di BCA Finance. Audiens utamanya adalah tim rekrutmen non-teknis maupun teknis, jadi tampilan harus profesional, cepat dibaca, dan enak dilihat di HP maupun desktop.

## 2. Spesifikasi Teknis

- **Stack:** HTML + CSS + sedikit JavaScript vanilla (tanpa framework berat). Boleh pakai satu file `index.html` dengan CSS terpisah (`style.css`), atau struktur sederhana lain — prioritaskan simpel dan mudah di-maintain.
- **Hosting:** GitHub Pages, dari repo bernama `alternatif-omg.github.io` (root user page) — kalau nama repo ini sudah dipakai untuk hal lain, boleh pakai repo project biasa (misal `portfolio`) dengan GitHub Pages diaktifkan dari branch `main`, folder `/root` atau `/docs`.
- **Responsive:** wajib enak dilihat di mobile (recruiter sering buka dari HP).
- **Aksesibilitas dasar:** kontras warna cukup, ukuran font terbaca, alt text di gambar.
- **Performa:** ringan, tanpa dependency besar, loading cepat (halaman ini akan dibuka lewat link singkat dari form pendaftaran, harus first impression bagus & cepat).
- **Tidak perlu backend/database** — semuanya statis.

## 3. Struktur Halaman (urutan section)

1. **Hero / Header** — nama, tagline singkat, tombol/link ke CV & GitHub.
2. **About / Summary** — ringkasan profil.
3. **Experience** — pengalaman kerja (timeline sederhana).
4. **Projects** — studi kasus proyek, masing-masing dengan tempat untuk screenshot/diagram.
5. **Organizational Experience** — pengalaman organisasi/komunitas.
6. **Skills** — grid/list kategori skill teknis.
7. **Contact / Footer** — email, telepon, LinkedIn, GitHub.

## 4. Konten (siap pakai)

### Hero
- **Nama:** Moch. Alfan Miftachul Huda
- **Tagline:** Infrastructure, Security & Data Science — Fresh Graduate Informatics Engineering
- **Kontak:** alfanhuda2004@gmail.com · +62 823-3136-8208
- **Links:** [LinkedIn](https://linkedin.com/in/alfanmiftachul) · [GitHub](https://github.com/alternatif-omg)

### About
> Fresh graduate in Informatics Engineering (UIN Maulana Malik Ibrahim Malang, 2026, GPA 3.83/4.00) with a dual foundation spanning Infrastructure/Security and Data Science. Hands-on experience in DevSecOps (vulnerability assessment, CI/CD automation, containerization with Docker, Prometheus + Grafana monitoring, Linux hardening, network design) built through an ongoing internship and self-initiated portfolio projects, complemented by two data-focused internships, a machine-learning thesis (EfficientNet-B3 + CBAM), and active involvement in a campus data science community. Currently expanding into cloud platforms (AWS/GCP/Azure) and application/database development.

### Experience (timeline, urut dari terbaru)

**DevOps Engineer Intern** — PT Sentra Vidya Utama (SEVIMA), Apprenticeship / MagangHub Program
*Aug 2026 – Present · Surabaya, Indonesia*
- Performed vulnerability assessment (VA) scans on the SINDE web application and investigated remediation solutions to strengthen application security as part of DevSecOps practices.
- Built a Grafana monitoring dashboard to track server load per domain, improving visibility into infrastructure performance across multiple domains.
- Contributed to CI/CD pipeline activities, working cross-functionally with the engineering team.

**Data Analyst Intern** — Badan Pusat Statistik (BPS) Malang
*July 2025*
- Built a data-matching model to improve data accuracy across the agency's information system, and supported system/data readiness for the 2026 Economic Census under strict cross-team timelines.

**Data Scientist Project-Based Intern** — ID/X Partners (Rakamin Academy)
*March 2024*
- Managed a dataset end-to-end (cleaning, structuring, documentation) to ensure data integrity throughout the analysis process.

### Projects (studi kasus — sisipkan area screenshot di tiap kartu)

1. **Vulnerability Assessment & Monitoring Dashboard** *(SEVIMA — real work)*
   Stack: `Grafana` `CI/CD` `DevSecOps` `Vulnerability Assessment`
   - VA scan pada aplikasi web SINDE + investigasi remediasi keamanan.
   - Dashboard Grafana untuk memantau server load per domain.
   - Kontribusi aktivitas pipeline CI/CD lintas tim.
   *(Tidak ada repo publik — proyek internal perusahaan. Cukup deskripsi + screenshot dashboard Grafana generik jika diizinkan, atau tanpa gambar.)*

2. **Nimbus Shop — Cloud-Native CI/CD & Deployment Planning**
   Stack: `Docker` `GitHub Actions` `Kubernetes`
   Repo: https://github.com/alternatif-omg/nimbus-shop
   - Pipeline CI dengan GitHub Actions untuk build automation & containerization aplikasi e-commerce.
   - Rancangan arsitektur deployment berbasis Kubernetes untuk skalabilitas.

3. **Monitoring Stack Deployment**
   Stack: `Prometheus` `Grafana` `Node Exporter`
   Repo: https://github.com/alternatif-omg/Monitoring_Stack
   - Deployment Prometheus + Grafana + Node Exporter untuk visibilitas real-time CPU/RAM/disk/network.
   - Custom alert rule (mis. ambang CPU) untuk monitoring proaktif.

4. **Linux Server Setup & Hardening**
   Stack: `Ubuntu Server 22.04` `Nginx` `UFW` `Fail2ban` `BIND9`
   Repo: https://github.com/alternatif-omg/Linux-Server
   - Hardening Nginx web server (UFW, SSH hardening, Fail2ban).
   - Setup DNS server BIND9 + automated daily backup via cron.

5. **Network Infrastructure Design**
   Stack: `Cisco Packet Tracer` `VLAN` `ACL` `DHCP`
   Repo: https://github.com/alternatif-omg/network-infrastructure
   - Desain jaringan kantor tersegmentasi (VLAN + inter-VLAN routing / Router-on-a-Stick).
   - Kebijakan akses berbasis ACL.

> **PENTING untuk agent:** di setiap kartu proyek, buat placeholder box/figure yang jelas bertuliskan "Tambahkan screenshot di sini" (misal `<div class="screenshot-placeholder">`) supaya saya bisa gampang mengganti dengan gambar asli nanti. Jangan generate atau pakai gambar palsu/stock photo yang tidak relevan.

### Organizational Experience
**Creative Media Team** — DSE (Data Science Enthusiast), UIN Maulana Malik Ibrahim Malang
*Oct 2023 – May 2025*
- Contributed to visual content creation and design for the community's publications and social media.

### Skills
- **Cloud & Containerization:** Docker, docker-compose, Kubernetes (deployment planning); learning AWS/GCP/Azure
- **CI/CD & DevSecOps:** GitHub Actions, build automation, vulnerability assessment (VA)
- **Networking:** TCP/IP, VLAN, routing, DHCP, ACL, DNS (BIND9)
- **Systems & Security:** Linux (Ubuntu Server administration & hardening), UFW, Fail2ban, SSH hardening
- **Monitoring & Reliability:** Prometheus, Grafana, Node Exporter, automated backup (cron)
- **Scripting, Database & Tools:** Bash, cron, node-cron, PostgreSQL, Prisma ORM, Git, Cisco Packet Tracer

### Footer
- Email: alfanhuda2004@gmail.com
- Phone: +62 823-3136-8208
- LinkedIn: linkedin.com/in/alfanmiftachul
- GitHub: github.com/alternatif-omg
- Lokasi: Malang, Indonesia

## 5. Desain / Gaya Visual

- Warna dasar navy/dark-blue (`#1F3864` atau sejenis) sebagai aksen, latar putih/abu muda — konsisten dengan CV & portofolio PDF yang sudah dibuat, supaya identitas visual seragam.
- Font sans-serif bersih (system font stack atau Google Fonts seperti Inter/Calibri-alike).
- Section berjarak jelas, whitespace cukup, jangan padat.
- Boleh tambahkan sedikit micro-interaction (hover di kartu project) tapi jangan berlebihan — ini bukan portofolio desainer, fokusnya kredibilitas teknis.

## 6. Langkah Deploy ke GitHub Pages (instruksikan agent untuk mengeksekusi ini)

1. Inisialisasi repo git di folder proyek (jika belum ada).
2. Buat file `index.html`, `style.css`, dan asset folder (`/assets` atau `/images`) sesuai struktur di atas.
3. Commit semua file.
4. Buat repository baru di GitHub bernama `alternatif-omg.github.io` (atau `portfolio` jika nama pertama tidak tersedia/dipakai untuk hal lain).
5. Push branch `main` ke repo tersebut.
6. Jika nama repo BUKAN `alternatif-omg.github.io`: aktifkan GitHub Pages lewat **Settings → Pages → Source: Deploy from branch → `main` / root**.
7. Tunggu beberapa menit, lalu verifikasi situs bisa diakses di:
   - `https://alternatif-omg.github.io` (jika repo user page), atau
   - `https://alternatif-omg.github.io/portfolio` (jika repo project page).
8. Berikan saya URL final yang bisa langsung saya masukkan ke form pendaftaran BCA Finance.

## 7. Yang TIDAK boleh dilakukan agent

- Jangan mengarang detail proyek yang tidak ada di brief ini (misalnya jumlah user, metrik performa spesifik, dsb).
- Jangan menambahkan foto profil/stock image acak — biarkan area foto kosong dengan placeholder jika hero section butuh gambar.
- Jangan membuat klaim berlebihan ("expert", "world-class") — bahasa tetap profesional dan proporsional untuk fresh graduate.
