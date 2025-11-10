#Array

mahasiswa_list = ["Aisyah", "Marna", "Rahma", "Analaili", "Rofi"]

#Mengakses
print("Daftar Nama Mahasiswa:", mahasiswa_list)
print("Mahasiswa pertam:", mahasiswa_list[0])

#Menambah
mahasiswa_list.append("Atilla")
print("Setelah menambah Atilla:", mahasiswa_list)

#Menghapus
mahasiswa_list.remove("Aisyah")
print("Setelah menghapus Aisyah:", mahasiswa_list)

#DICTIONARY

mahasiswa = {
    "nama": "Saleha",
    "nim": "D0425011",
    "jurusan": "Sistem Informasi",
    "kelas": "Sisfo A",
    "angkatan": 2025,
    "alamat": "Oting, Sulawesi Barat",

    "nilai": {
        "algoritma_pemrograman":89,
        "struktur_data": 85,
        "basis_data": 90,
        "pemrograman_python": 88
    },

    "mata_kuliah_diambil": [
        "Algoritma Pemrograman",
        "Basis Data",
        "Pemrograman Python",
        "Kalkulus Informatika"
    ]
}

#Menampilkan data
print("\nData Mahasiswa:", mahasiswa)

#Mengakses data
print("Nama:", mahasiswa["nama"])
print("Kelas:", mahasiswa["kelas"])
print("Nilai Python:", mahasiswa["nilai"]["pemrograman_python"])

#Update nilai
mahasiswa["nilai"]["pemrograman_python"] = 88
print("Nilai Python Setelah Update:", mahasiswa["nilai"]["pemrograman_python"])

#Menambah data baru
mahasiswa["status"] = "Aktif"
print("Setelah menambah status:", mahasiswa)
