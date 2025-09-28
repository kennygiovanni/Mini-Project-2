print("Halo Selamat Datang Di Program Daftar Hasil Pertandingan Sepak Bola🙋 ")
print("-" * 85)

users = {
     "Admin": (456, "admin"),
     "Viewer": (789, "viewer" )
}

daftar_pertandingan = []

def login():
 try:
    print("Silakan login untuk melanjutkan.")
    print("Login sebagai admin")
    print("Nama: Admin, Password: 456")
    print("Login sebagai viewer")
    print("Nama: Viewer, Password: 789")
    print("-" *85)
    nama = (input("Masukkan Nama: "))
    password = int(input("Masukkan Password: "))

    if nama in users:
     pw, role = users[nama]
     if password == pw:
      print(f"Anda berhasil login sebagai {role}.")
      return role

    else:
      print("Login gagal, silakan coba lagi.")
      return login()
 except ValueError:
    print("Input tidak boleh huruf atau angka desimal, silakan masukkan password dalam bentuk angka.")

def tambah_pertandingan(): 
 try:
    tim_1 = input("Masukkan nama tim 1: ")
    tim_2 = input("Masukkan nama tim 2: ")

    skor_tim1 = int(input("Masukkan skor tim 1: "))
    skor_tim2 = int(input("Masukkan skor tim 2: "))
    
    tanggal = input("Masukkan tanggal pertandingan (DD-MM-YYYY):")

    pertandingan = (tim_1, skor_tim1, tim_2, skor_tim2, tanggal)
    daftar_pertandingan.append(pertandingan)
    print("Pertandingan berhasil ditambahkan: ")
    print(f"{pertandingan[4]} | {pertandingan[0]} {pertandingan[1]}-{pertandingan[3]} {pertandingan[2]}")
        
    if skor_tim1 > skor_tim2:
        print(f"{pertandingan[0]} menang 🎉")
    elif skor_tim2 > skor_tim1:
         print(f"{pertandingan[2]} menang 🎉")
    else:
         print("Pertandingan imbang")
        
         print("-" *85)
 except ValueError:
    print("Input tidak boleh huruf atau angka desimal, silakan masukkan angka.")

def lihat_pertandingan():
    if not daftar_pertandingan:
        print("-" *85)
        print("Belum ada pertandingan yang ditambah")
        print("-" *85)
    else:
        print("-" *85)
        print("Daftar Hasil Pertandingan Sepak Bola")
        print("-" *85)
        for index, pertandingan in enumerate(daftar_pertandingan, start=1):
            print(f"{index}. {pertandingan[4]} | {pertandingan[0]} {pertandingan[1]}-{pertandingan[3]} {pertandingan[2]}")
        print("-" *85)

def hapus_pertandingan():
    if not daftar_pertandingan:
        print("-" *85)
        print("Belum ada pertandingan yang ditambah")
        print("-" *85)
    else:
        lihat_pertandingan()
        try:
            index_daftarpertandingan = int(input("Masukkan nomor pertandingan yang ingin dihapus (1, 2, 3, dst): ")) - 1
            if 0 <= index_daftarpertandingan < len(daftar_pertandingan):
                pertandingan_dihapus = daftar_pertandingan.pop(index_daftarpertandingan)
                print(f"Pertandingan pada tanggal {pertandingan_dihapus[4]} {pertandingan_dihapus[0]} vs {pertandingan_dihapus[2]} telah dihapus.")
            else:
                print("Nomor pertandingan tidak valid, silakan masukkan nomor pertandingan yang benar.")
        except ValueError:
            print("Input tidak valid harus angka, silakan masukkan nomor pertandingan yang benar.")
 
def keluar_menu():
    keluar = input("Klik 1 untuk keluar dan ketik 2 untuk kembali ke menu utama: ")
    if keluar == "1":
        pilihan_keluar = input("Ketik 1 untuk keluar dari program atau 2 untuk login kembali: ")
        if pilihan_keluar == "1":
         print("Terima kasih telah menggunakan program ini. Sampai jumpa!")
         exit()
        elif pilihan_keluar == "2":
         role = login()
         if role == "admin":
            menu_admin()
         elif role == "viewer":
            menu_viewer()          
        else:
         print("Pilihan tidak valid, silakan pilih 1 atau 2.")
         keluar_menu()
        
    elif keluar == "2":
        while True:
         try:
            print("1. Tambah hasil pertandingan")
            print("2. Lihat hasil pertandingan")
            print("3. Hapus hasil pertandingan")
            print("4. Keluar")

            pilihan = int(input("Pilih menu 1/2/3: "))

            if pilihan == "1":
                tambah_pertandingan()
            elif pilihan == "2":
                lihat_pertandingan()
            elif pilihan == "3":
                hapus_pertandingan()
            elif pilihan == "4":
                keluar_menu()
                break
            else:
                print("Pilihan tidak valid, silakan pilih 1, 2, atau 3.")
                continue
         except ValueError:
                print("Input tidak boleh huruf atau angka desimal, silakan masukkan angka yang benar.")
             
    else:
        print("Pilihan tidak valid, silakan pilih 1 atau 2.")


def menu_admin():
 while True:
    print("MENU ADMIN")
    print("1. Tambah hasil pertandingan")
    print("2. Lihat hasil pertandingan")
    print("3. Hapus hasil pertandingan")
    print("4. Keluar")

    pilihan = input("Pilih menu 1/2/3/4: ")

    if pilihan == "1":
        tambah_pertandingan()
    elif pilihan == "2":
        lihat_pertandingan()
    elif pilihan == "3":
        hapus_pertandingan()
    elif pilihan == "4":
        keluar_menu()
        break

    else:
        print("Pilihan tidak valid, silakan pilih 1, 2, 3, atau 4.")

def menu_viewer():
    while True:
        print("MENU VIEWER")
        print("1. Lihat hasil pertandingan")
        print("2. Keluar")

        pilihan = input("Pilih menu (1/2): ")

        if pilihan == "1":
            lihat_pertandingan()
        elif pilihan == "2":
            keluar_menu()
            break
        else:
            print("Pilihan tidak valid.")


role = login()
if role == "admin":
    menu_admin()
elif role == "viewer":
    menu_viewer()          

