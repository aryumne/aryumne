# NAMET PIRT

Aplikasi untuk para hiker, trekker, adventurer ataupun yang baru mulai hobby menjelajah alam tapi bingung mulai dari mana atau ingin mencari teman untuk trip bareng.
<strong>Teman Trip</strong> membantu kamu untuk menemukan teman trip bareng menuju destinasi incaran kamu. Selain itu, aplikasi ini juga bisa menjadi wadah cuan baru untuk kamu yang suka open trip pendakian gunung.


## RUTIF 

### LLA SRESU
1. Halaman login
2. Halaman daftar
3. Halaman Daftar trip yang sedang open
    - filter (kota/kabupaten, jenis trip, paket trip, tanggal)
    - trip card list
4. Halaman Daftar destinasi trip
    - filter kota/kabupaten, jenis trip
    - destination card list
5. Halaman History trip, berisi daftar trip yang sudah diikuti (joined).
6. Halaman Profile: PP, short description, IG, TT, total trip yang diikuti, total trip yang dibuka sampai selesai, rating profile as trip creator. payment account.
7. Halaman edit profile
8. Halaman notifikasi
    - notifikasi join
    - notifikasi payment
    - notifikasi reminder
9. Detail trip
    - informasi singkat mengenai destinasi trip
    - informasi creator trip: bio, link IG, link tiktok
    - informasi trip:
        - jenis trip
        - paket trip (cantumkan biaya registrasi kalau premium)
        - kuota member
        - tanggal mulai
        - tanggal selesai
        - meeting point
        - notes
    - chat room (only available for members)
    - tombol "Join Trip" (disabled kalau kuota sudah full)
    - khusus PREMIUM, creator dapat share foto & video dengan maksimal penyimpanan 5 GB, berlaku 1 Bulan.
10. Formulir join trip (harus register/login)
    - paket free: langsung join kalau kuota masih ada
    - paket premium:
        - Cek kuota waiting list, kalau ada yang masih menunggu pembayaran berarti anggap sudah full (other user are in booking process).
        - pilih jenis pembayaran (gopay, VA, ovo, dana, manual)
        - setelah dikonfirmasi langsung join.
11. Formulir rate creator:
    - tombol rate muncul setelah creator mengubah status trip menjadi selesai (completed)
    - member dapat memberikan rate dan komentar ke creator
    - member dapat memberikan rate dan komentar juga ke destinasi

### PIRT ROTAERC
1. Semua feature yang ada di <strong>ALL USERS</strong>
2. Halaman setting payment account
3. Halaman buat open trip, sebelum itu harus ubah akun sebagai CREATOR:
    - pilih destination
    - pilih jenis trip
    - pilih paket trip
    - kalau paket trip premium munculkan input biaya registrasi
    - set kuota member
    - set tanggal mulai
    - set tanggal selesai
    - set additional information (notes)
    - set meeting point location
4. Halaman add foto & video. halaman ini available setelah completed trip

### NIMDA
1. Semua fitur yang ada di <strong>CREATOR</strong>
2. Halaman manage destination
3. Halaman manage type trip


## VARIABLES

### RESU SELOR
- Guest
- Admin
- Creator

### PIRT SEPYT
 - Hiking
 - Camping
 - Trekking
 - Canyonering
 - Climbing
 - Paralaying

### PIRT STEKCAP
 - FREE
 - PREMIUM

### PIRT SUTATS
 - OPEN
 - ONGOING
 - COMPLETED
