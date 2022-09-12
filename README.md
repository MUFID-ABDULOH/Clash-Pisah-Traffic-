# FITUR
- DIRECT
- REJECT
- GAME
- INDONESIA
- ADSBLOCK
- BESTPING
- LOADBALANCE
- ISP 1 X ISP 2

# CARA INPOR
<h3>ONLINE</h3>
<h4>PERSIAPAN</h4>
<br>- Akses Internet
<br>- Config <b>"MUFID-ABDULOH.YAML"</b>

<h3>OFFLINE</h3>
<h4>PERSIAPAN</h4>
- Config         : ./MUFID-ABDULOH.YAML </br>
- Proxy Provider : ./proxy_provider/AKUN-INDONESIA.YAML </br>
- Proxy Provider : ./proxy_provider/ETH-1.YAML </br>
- Proxy Provider : ./proxy_provider/ETH-2.YAML </br>
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
DIRECT | PAKET LANGSUNG KE MODEM TANPA VPN
REJECT | PAKET DI TOLAK UNTUK MENGAKSES INTERNET
BESTPING | AKUN AKAN DI PILIH OTOMATIS DENGAN LATENSI TERKECIL
LOADBALANCE | MODE KESEIMBANGAN
INDONESIA | PAKET AKAN MENGGUNAKAN SERVER INDONESIA 


# PENTING
<font color="green"> Some green text </font>
