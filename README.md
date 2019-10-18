# Latihan Operator pada Python
Operator adalah simbol khusus pada Python yang merupakan perhitungan aritmatika atau logika.
Nilai yang dioperasikan operator disebut operand.
Latihan kali ini adalah operator aritmatika
Operator aritmatika termasuk dalam operator yang paling sering digunakan dalam pemrograman.

# Operator aritmatika terdiri dari:
Operator				Simbol
Penjumlahan				  +
Pengurangan				  -
Perkalian				  *
Pembagian				  /
Sisa bagi				  %
Pemangkatan				  **

# Contoh kode yang salah:
a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
print("variable a=" ,a)
print("variable b=" ,b)
print("hasil penggabungan {1}&{0}=%s" .format(a,b) %(a+b))
a=int(a)
b=int(b)
print("hasil penjumlahan {1}+{0}=%s" .format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%s" .format(a,b) %(a/b))

# Contoh kode yang benar:
a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
print("variable a=" ,a)
print("variable b=" ,b)
print("hasil penggabungan {0}&{1}=%s" .format(a,b) %(a+b))
a=int(a)
b=int(b)
print("hasil penjumlahan {0}+{1}=%s" .format(a,b) %(a+b))
print("hasil pembagian {0}/{1}=%s" .format(a,b) %(a/b))

# Apa yang salah?
1. %d adalah fungsi untuk bilangan bulat desimal sedangkat %s adalah fungsi untuk Konversi string melalui str () sebelum memformat.
2. {1}&{0}=%s Seharusnya adalah {0}&{1}=%s. Karna jika {1}&{0}=%s hasilnya akan terbalik jadi variable b dahulu baru variable a. Berbeda dengan {0}&{1}=%s variable a dahulu baru variable b. {0} adalah variable a, {1} adalah variable b.

# Penjelasan
a=input("masukkan nilai a:") //menginput variable a
b=input("masukkan nilai b:") //menginput variable b
print("variable a=" ,a) //menginput variable a yang sudah diisi
print("variable b=" ,b) //menginput variable b yang sudah diisi
print("hasil penggabungan {0}&{1}=%s" .format(a,b) %(a+b)) //hasil penggabungan varible a dan b
a=int(a) //variable a yang sudah diinput
b=int(b) //variable b yang sudah diinput
print("hasil penjumlahan {0}+{1}=%s" .format(a,b) %(a+b)) //hasil penjumlahan variable a dan b
print("hasil pembagian {0}/{1}=%s" .format(a,b) %(a/b)) //hasil pemabagian variable a dan b
