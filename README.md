# Sistem Monitoring Jaringan Menggunakan Zabbix pada Simulasi GNS3

Proyek ini membahas perancangan dan implementasi sistem monitoring jaringan menggunakan Zabbix pada lingkungan simulasi GNS3. Simulasi menggunakan MikroTik Cloud Hosted Router (CHR), Cisco IOSv, dan Zabbix Appliance sebagai server monitoring. Seluruh perangkat dihubungkan melalui Switch1 untuk membentuk jaringan lokal yang memungkinkan komunikasi antarperangkat.

Implementasi mencakup penyiapan lingkungan simulasi GNS3, konfigurasi konektivitas perangkat menggunakan DHCP, serta integrasi perangkat jaringan ke dalam sistem monitoring Zabbix. Pemantauan dilakukan menggunakan protokol SNMP pada perangkat MikroTik dan Cisco, sedangkan Zabbix Server menggunakan protokol ZBX. Hasil implementasi menunjukkan bahwa ketiga host berhasil didaftarkan dan dipantau melalui dashboard Zabbix, termasuk pemantauan status ketersediaan perangkat dan pendeteksian peristiwa restart pada router.

## Ruang Lingkup Implementasi

- Perancangan topologi jaringan menggunakan GNS3.
- Penyiapan GNS3 Server VM melalui VMware Workstation.
- Implementasi MikroTik CHR 7.16-1 dan Cisco IOSv 15.9(3)M6.
- Penyiapan Zabbix Appliance sebagai server monitoring.
- Konfigurasi konektivitas jaringan menggunakan DHCP.
- Integrasi perangkat MikroTik dan Cisco menggunakan SNMP.
- Pendaftaran dan pemantauan host melalui Zabbix.
- Pemantauan status ketersediaan perangkat dan peristiwa restart melalui dashboard.

## Perangkat dan Perangkat Lunak

- GNS3 GUI
- GNS3 Server VM
- VMware Workstation
- MikroTik CHR 7.16-1
- Cisco IOSv 15.9(3)M6
- Zabbix Appliance

## Hasil Implementasi

Sistem berhasil mendaftarkan tiga host, yaitu Kelompok 2 Cisco, Kelompok 2 Mikrotik, dan Zabbix Server. Seluruh host berstatus Enabled. Dashboard Zabbix menampilkan informasi ketersediaan perangkat serta mendeteksi peristiwa restart pada perangkat Cisco dan MikroTik.

## Dokumentasi

Laporan lengkap proyek tersedia pada berkas:

`laporan-monitoring-zabbix-gns3.pdf`
