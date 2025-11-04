<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ae389bea-2295-4dc8-b9e1-d8834d12b07b" />
 Program Penjumlahan Dua Matriks
 Perangkat program:

int[][] A, B, C
→ Deklarasi array dua dimensi untuk menyimpan matriks A, B, dan hasil C.

Perulangan bersarang (for i dan for j)
→ Untuk mengakses setiap elemen baris dan kolom matriks.

A[i][j] = input.nextInt();
→ Mengisi elemen matriks A.

B[i][j] = input.nextInt();
→ Mengisi elemen matriks B.

C[i][j] = A[i][j] + B[i][j];
→ Menjumlahkan elemen dari A dan B pada posisi yang sama.

System.out.print(C[i][j] + "\t");
→ Menampilkan hasil matriks penjumlahan.

 Cara kerjanya:

Program meminta ukuran matriks (baris dan kolom), lalu menginput elemen-elemen dari matriks A dan B. Setelah semua data dimasukkan, program menambahkan elemen yang berada di posisi yang sama dan menyimpannya ke dalam matriks C. Hasil akhirnya ditampilkan dalam bentuk tabel matriks. Program ini menunjukkan penerapan array 2 dimensi dan looping bersarang (nested loop).
