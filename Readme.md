#OPERATOR
Dalam bahasa pemograman, terdapat istilah operand dan operator. Operand adalah nilai asal yang digunakan didalam proses operasi, sedangkan operator adalah instruksi yang diberikan untuk mendapatkan hasil dari proses tersebut.

#Jenis Operator Berdasarkan Jumlah Operand
Berdasarkan jumlah operand, operator dapat dibedakan menjadi 3, yaitu Operator Unary, Binary dan Ternary.
1.Operator unary adalah operator yang hanya memiliki 1 operand, contohnya karakter – (tanda minus). Tanda minus digunakan membuat sebuah angka menjadi negatif, contohnya: -5, atau karakter + untuk menegaskan nilai positif, contohnya: +5.
2.Operator binary adalah operator yang memiliki 2 operand. Operator jenis ini adalah yang paling banyak digunakan, misalkan 5×2, atau 10/3.
3.Operator Ternary adalah operator yang memiliki 3 operand. Didalam PHP hanya dikenal 1 operator ternary, yaitu operator kondisi (? :). Kita akan mempelajari operator ini dalam tutorial selanjutnya.

#Langkah-langkah 


langkah pertama masukan nilai

a=input (“masukan nilai a:”)
b=input (“masukan nilai b:”)

langkah kedua penggabungan

print (“variable a= ,a”)
print (“variable b= ,b”)

langkah  ketiga akan menggunakan variable a dan b, kita harus menggunakan '%s' agar sistem membacanya string bukan integer

print (“hasil penggabungan {1}&{0}=%d”.format(a,b) %(a+b))

langkah selanjutnya aakan mengkonversikan tipe data variable a dan b

a=int(a)
b=int(b)

akan menjumlahkan nilai variable a dan b
print(“hasil penjumlahan {1}+{0}=%d”.format(a,b) %(a+b)

langkah selanjutnya akan melakukan pembagian nilai variable a dengan b
print(“hasil pembagian {1}/{0}=%d”.format(a,b) %(a/b))

