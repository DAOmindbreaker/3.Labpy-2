<h1> Program Sederhana Python Mencari Bilangan Terbesar & Terkecil </h1>

Setelah saya posting "Labpy-1", sekarang saya ingin memposting cara membuat program sederhana.
Yang di butuhkan hanyalah statement IF.

Struktur Algoritma
1. Mulai
2. Inisiasi bil1,bil2,bil3 sebagai integer.
3. Baca bil1.
4. Baca bil2.
5. Baca bil3.
6. Jika bil1 > bil2 dan bil1 > bil3 maka kerjakan langkah 8, selain itu
7. Jika bil2 > bil1 dan bil2 > bil3 maka kerjakan langkah 9, selain itu kerjakan langkah 10.
8. Cetak “Bilangan Terbesar Bilangan Pertama”.
9. Cetak “Bilangan Terbesar Bilangan Kedua”.
10. Cetak “Bilangan Terbesar Bilangan Ketiga”.
11. Selesai

***Step pada source code***

print ('program untuk menentukan bilangan terbesar dan terkecil')

def pengulangan():

    print ('masukkan 3 bilangan yang diinginkan!')
    a=int(input('bilangan1 = '))
    b=int(input('bilangan2 = '))
    c=int(input('bilangan3 = '))

    if a>b and a>c:
        if b>c:
            print (a, 'terbesar dan', c, 'terkecil')
        else:
            print (a, 'terbesar dan', b, 'terkecil')
    elif b>a and b>c:
        if a>c:
            print (b, 'terbesar dan', c, 'terkecil')
        else:
            print (b, 'terbesar dan', a, 'terkecil')
    else:
        if a>b:
            print (c, 'terbesar dan', b, 'terkecil')
        else:
            print (c, 'terbesar dan', a, 'terkecil')

    print ('')
    print ('ingin coba lagi? (ya/tidak)')
    x=input()
    if x=='ya':
        return pengulangan()
    if x=='tidak':
        print('terimakasih telah menggunakan program ini.')

pengulangan()

***Gambaran Flowchart***

![2013-01-17_082540](https://user-images.githubusercontent.com/46983614/67663464-2bff2f00-f998-11e9-9af4-8b55e2346a7d.jpg)

***Screenshoot Code 1***

![Screenshot (16)](https://user-images.githubusercontent.com/46983614/67663571-68328f80-f998-11e9-99fb-f4d0947e5e51.png)

***Screenshoot Code 2***

![Screenshot (17)](https://user-images.githubusercontent.com/46983614/67663620-813b4080-f998-11e9-959a-c5a594578d0e.png)

***Screenshoot Hasil***

![Screenshot (18)](https://user-images.githubusercontent.com/46983614/67663685-a760e080-f998-11e9-97e6-8ef820e0772c.png)


***Semoga Bermanfaat***




