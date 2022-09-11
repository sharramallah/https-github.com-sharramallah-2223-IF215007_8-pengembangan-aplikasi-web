# PROPOSAL : Aplikasi Layanan Wargi RT 06

# Permsalahan 
- Kebutuhan warga RT 06 terkait persuratan, laporan tamu dan lain lain sulit dipenuhi karena bentroknya jadwal Pak RT dan warganya

# Rancangan Solusi
Aplikasi layanan yang membantu warga RT 06 untuk melayani segala kebutuhan seperti Persuratan, Lpaoran secara online, mudah dna praktis

# Use Case
- User Daftar dan Login
- User bisa melihat statistik data warga RT06
- User memilih layanan sesuai kebutuhan
- User mengisi inputan layanan yang dipilih

# Struktur Data

Admin
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|integer|999|
|nama|string|sharin|
|token|varchar|001rt6|

User
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|integer|999|
|nama|string|Abiyya|
|umur|integer|20|
|tempatlahir|string|Bandung|
|tanggallahir|date|17-09-2002|
|kepalakeluarga|string|Wawan|
|alamatrumah|varchar|Jln. Warakawuri|
|No Rumah|varchar|5A|

Laporan Tamu
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|integer|999|
|nama|string|ayam|

Layanan Persuratan
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|integer|999|
|nama|string|ayam|

Data Warga
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|integer|999|
|nama|string|ayam|
