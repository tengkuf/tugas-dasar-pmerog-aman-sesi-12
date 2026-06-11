from aritmatika import *
from konversi import *
from ubah_bilangan import *

while True:
    print("\n=== MENU UTAMA ===")
    print("1. Aritmatika")
    print("2. Konversi")
    print("3. Ubah Bilangan")
    print("4. Keluar")

    pilihan = input("Pilih menu: ")

    if pilihan == "1":
        print("\n=== ARITMATIKA ===")
        print("1. Penjumlahan")
        print("2. Perpangkatan")
        print("3. Perkalian")

        p = input("Pilih operasi: ")

        a = float(input("Masukkan bilangan pertama: "))
        b = float(input("Masukkan bilangan kedua: "))

        if p == "1":
            print("Hasil =", tambah(a, b))
        elif p == "2":
            print("Hasil =", pangkat(a, b))
        elif p == "3":
            print("Hasil =", kali(a, b))

    elif pilihan == "2":
        print("\n=== KONVERSI ===")
        print("1. CM ke M")
        print("2. M ke CM")

        p = input("Pilih konversi: ")

        nilai = float(input("Masukkan nilai: "))

        if p == "1":
            print("Hasil =", cm_ke_m(nilai), "m")
        elif p == "2":
            print("Hasil =", m_ke_cm(nilai), "cm")

    elif pilihan == "3":
        print("\n=== UBAH BILANGAN ===")
        print("1. Desimal ke Biner")
        print("2. Desimal ke Oktal")
        print("3. Desimal ke Hexadesimal")

        p = input("Pilih konversi: ")

        nilai = int(input("Masukkan bilangan desimal: "))

        if p == "1":
            print("Hasil =", desimal_ke_biner(nilai))
        elif p == "2":
            print("Hasil =", desimal_ke_oktal(nilai))
        elif p == "3":
            print("Hasil =", desimal_ke_heksa(nilai))

    elif pilihan == "4":
        print("Terima kasih.")
        break

    else:
        print("Pilihan tidak valid!")
