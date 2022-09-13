# MODE
- DIRECT
- REJECT
- GAME
- SOSMED
- STREAMING
- INDONESIA
- ADSBLOCK
- BESTPING (2 ISP)
- BESTPING ETH 1
- BESTPING ETH 2
- LOADBALANCE (2 ISP)
- ISP 1 X ISP 2 (PENGGABUNGAN 2 MODE ETH)

# PENTING
- Semua settingan dengan mode **"BESTPING"** dan **"LOADBALANCE"** akan ter-refresh otomatis setiap 90 detik.
- Ada 2 opsi type, pada bagian **"proxy_provider"** dan **"rule_provider"**.<br>
• file : Maka **"proxy_provider"** dan **"rule_provider"** tidak akan teredit otomatis.<br>
• http : Maka **"proxy_provider"** dan **"rule_provider"** maka akan teredit setiap hari jika ada update terbaru.

# CARA IMPOR
<h3>ONLINE</h3>
<h4>PERSIAPAN</h4>
<br>- Akses Internet
<br>- Config <b>"MUFID-ABDULOH.YAML"</b>

<h3>OFFLINE</h3>
<h4>PERSIAPAN</h4>
Download File :<br>
Config :<br>
<b>- "MUFID-ABDULOH.YAML"</b><br>
Proxy Provider :<br>
<b>- "AKUN-INDONESIA.YAML"<br>
- "ETH-1.YAML"<br>
- "ETH-2.YAML"</b><br>
Rule Provider :<b><br>
- "DIRECT.YAML"<br>
- "REJECT.YAML"<br>
- "ADBLOCK.YAML"<br>
- "GAME.YAML"<br>
- "INDONESIA.YAML"<br>
- "SOSMED.YAML"<br>
- "STREAMING.YAML"</br><br>











# H
- Config         : <b>./MUFID-ABDULOH.YAML</b></br
- Proxy Provider : <b>./proxy_provider/AKUN-INDONESIA.YAML</b></br>
- Proxy Provider : <b>./proxy_provider/ETH-1.YAML</b></br>
- Proxy Provider : <b>./proxy_provider/ETH-2.YAML</b></br>
- Rule Provider  :

# FUNGSI
<h3>FILES</h3>

TEMPAT             | NAMA FILE           | FUNGSI
-------------------|---------------------|---------
./                 | CONFIG              | MENGATUR SEMUANYA
./proxy_provider/  | AKUN-INDONESIA.YAML | BERISI AKUN, UNTUK MENGARAHKAN RULE KE SERVER INDONESIA.
./proxy_provider/  | ETH-1.YAML          | BERISI AKUN KHUSUS ETH 1.
./proxy_provider/  | ETH-2.YAML          | BERISI AKUN KHUSUS ETH 2.
./rule_provider/   | DIRECT.YAML         | BERISI DOMAIN & PORT, SEMUA YANG ADA DI SINI AKAN DI TERUSKAN LANGSUNG KE ISP TANPA VPN.
./rule_provider/   | REJECT.YAML         | BERISI DOMAIN & PORT, SEMUA YANG ADA DI SINI DI AKAN TOLAK UNTUK MENGAKSES INTERNET.
./rule_provider/   | ADBLOCK.YAML        | BERISI DOMAIN & PORT IKLAN, SEMUA YANG ADA DI SINI DI ATUR MELALUI "PROXIES - ADBLOCK".
./rule_provider/   | GAME.YAML           | BERISI DOMAIN & PORT GAME, SEMUA YANG ADA DI SINI DI ATUR MELALUI "PROXIES - GAME".
./rule_provider/   | INDONESIA.YAML      | BERISI DOMAIN & PORT YANG HANYA BISA DI AKSES DENGAN SERVER INDONESIA, DI SETTING MENJADI MODE "BESTPING".
./rule_provider/   | SOSMED.YAML         | BERISI DOMAIN & PORT SOSMED, DI SETTING MENJADI MODE "BESTPING".
./rule_provider/   | STREAMING.YAML      | BERISI DOMAIN & PORT STREAMING, DI SETTING MENJADI MODE "LOADBALANCE".


<h3>MODE</h3>

MODE | FUNGSI
------------ | -------------
GLOBAL | SEMUA PAKET TANPA RULE AKAN MENGGUNAKAN MODE INI.
DIRECT | PAKET LANGSUNG KE MODEM TANPA VPN.
REJECT | PAKET DI TOLAK UNTUK MENGAKSES INTERNET.
BESTPING | SEMUA AKUN AKAN DI PILIH OTOMATIS DENGAN LATENSI TERKECIL
BESTPING ETH 1 | SEMUA AKUN ETH 1, AKAAN DI PILIH DENGAN LATEMSI TERKECIL.
BESTPING ETH 2 | SEMUA AKUN ETH 2, AKAAN DI PILIH DENGAN LATEMSI TERKECIL.
LOADBALANCE | MODE KESEIMBANGAN.
LOADBALANCE ETH 1 | SEMUA AKUN DI ETH 1 AKAN DI PROSES JADI LOADBALANCE
LOADBALANCE ETH 2 | SEMUA AKUN DI ETH 2 AKAN DI PROSES JADI LOADBALANCE
INDONESIA | PAKET AKAN MENGGUNAKAN SERVER INDONESIA.
ETH 1 | PAKET ETH 1 ATAU ISP 1 DI ATUR MENGGUNAKAN MODE INI.
ETH 2 | PAKET ETH 2 ATAU ISP 2 DI ATUR MENGGUNAKAN MODE INI.



# PENTING
<font color="green"> Some green text </font>
