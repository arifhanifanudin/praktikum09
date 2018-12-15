# praktikum09

# Pengertian Array

Array merupakan tipe data terstruktur yang berguna untuk menyimpan sejumlah data yang bertipe sama. Bagian yang menyusun array disebut elemen array(isi), yang masing-masing elemen dapat diakses tersendiri melalui indeks array.

Antara satu Variabel dengan variabel lain di dalam array dibedakan berdasarkan Subscript Sebuah subscript berupa bilangan di dalam Kurung siku […] Melalui subscript inilah masing-masing elemen array dapat diakses.

# contoh array

# Latihan01

" Menentukan Nilai Maximum dan Minimum "

Deskripsi algoritma :

1. mulai program

2. int proses(int n,int max,int min,int jumlah);

3. if(n==0){
   
   cout<<endl;
   
   cout<<" NILAI MAKSIMUM       : "<<max<<endl;
   
   cout<<" NILAI MINIMUM        : "<<min<<endl;
   
   cout<<" JUMLAH SELURUH DERET : "<<jumlah<<endl<<endl;
   
   return 0;
   
   }

4. else{
   
   cout<<" Masukkan Bilangan : ";cin>>x;
   
    jumlah+=x;

   if(x<min)
   
   {
   
    min=x;
   
   }

   
    if(x>max)
   
   {
   
      max=x;
   
   }
   
5. return proses(n-1,max,min,jumlah);

# program C++

#include <iostream>
  
#include <cstdlib>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

using namespace std;

class maxmin

  {
  
   public:
   
          maxmin();
          
          int proses(int n,int max,int min,int jumlah);
          
   private:
   
          int n, max, min, jumlah, x;
          
  };

maxmin::maxmin()

{

  cout<<"\tMenampilkan Maximum, Minimum, dan Jumlah Sejumlah n Bilangan "<<endl;
  
  cout<<endl;
  
}

int maxmin::proses(int n, int max, int min, int jumlah)

{

if(n==0){

   cout<<endl;
   
   cout<<" NILAI MAKSIMUM       : "<<max<<endl;
   
   cout<<" NILAI MINIMUM        : "<<min<<endl;
   
   cout<<" JUMLAH SELURUH DERET : "<<jumlah<<endl<<endl;
   
   return 0;
   
  }

else{

   cout<<" Masukkan Bilangan : ";cin>>x;
   
      jumlah+=x;

   if(x<min)
   
   {
   
      min=x;
      
   }

   if(x>max)
   
   {
   
      max=x;
      
   }
   
    return proses(n-1,max,min,jumlah);
    
 }
 
}

int main(int argc, char *argv[]){

    maxmin x;
    
    x.proses(5,1,1,0);

    system("PAUSE");

    return EXIT_SUCCESS;
}


# Foto Hasil

# Latihan02

" Menentukan Modus "

Deskripsi Algoritma :

1. mulai program 
2. mencari modus dari data 1 sampai 10
3. masukan jumlah data = 10
4. masukan nilai-1 sampai nilai -10
5. setiap data di hitung frekuensi kemunculan nya
6. dari frekuensi tersebut dapat di tentukan modus dari data tersebut
7. selesai

# program C++

# Foto Hasil

# Latihan03

" Perkalian Matriks "

Deskripsi Algoritma :

1. input int a1,b1,temp sebagai variabel untuk mengambil baris dan kolom

2. deklarasikan char pil sebagai variabel untuk membuat pilihan mengulang atau tidak

3. deklarasikan ulang sebagai pilihan ulang

4. deklarasikan int hasil untuk hasil perkalian matriks

5. deklarasikan int AA sebagai variabel matriks A

6. deklrasikan int BB sebagai variabel matriks B

# program C++

# Foto Hasil

# Latihan04

" Transpose Matriks "

Matriks transpose yaitu matriks yang diperoleh dari memindahkan elemen-elemen baris menjadi elemen pada kolom atau sebaliknya.
Transpose matriks A dilambangkan dengan AT Contoh: A3×2 =, maka AT =, perhatikan bahwa ordo dari AT adalah 2 x 3.
Algoritma Transpose Matrik

1. Masukkan ordo matrik(n)
2. Input matrik di dalam array [0][0] sampai dengan array[n][n]
3. ditampilkan matrik tersebut
4. menukar matrik[i][j] menjadi matrik[j][i]
5. ditampilkan hasil matrik tranpose

# program C++

# Foto Hasil




