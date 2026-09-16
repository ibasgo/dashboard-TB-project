TB Dashboard v5 — finishing release

Perubahan utama dibanding v4:
- palet warna dashboard lebih konsisten dan modern;
- direct labels pada tren hasil pengobatan, tipe diagnosis, dan lokasi anatomi;
- label peta menggunakan repel agar kecamatan pusat kota tidak terlalu bertumpuk;
- setiap tab Peta memiliki grafik pasangan yang relevan;
- LTFU dan meninggal pada peta ditampilkan sebagai proporsi (%) dengan denominator outcome tercatat;
- grafik jenis kelamin menampilkan jumlah dan persentase;
- visual Detail Garis Outcome yang redundan di halaman Puskesmas dihapus;
- heatmap dan bar chart memakai warna yang lebih konsisten.

Paket disarankan:
install.packages(c("tidyverse", "readxl", "scales", "sf", "ggrepel", "patchwork"))

Letakkan file tb_2021.xlsx ... tb_2025.xlsx di folder data/ lalu render tb-dashboard-v5.qmd.
