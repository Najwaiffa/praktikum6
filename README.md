 # Praktikum 6

## Latihan 

Dictionary adalah Koleksi item yang berasosiasi dimana setiap pasangan terdiri _key_ dan _value_.

_Key_ dan _Value_ sebagai 'Key' : 'Value'

Dictionary ditulis dengan dipisahkan koma dalam ```{}```

seperti:

```
telepon = {'Ari' : '081267888', 'Dina' : '087677776'}
```

Untuk menambahkan elemen dictionary 

```
telepon['Riko'] = '087654544'
```

dan untuk menampilkan kontak 
```
print(telepon['Ari'])
```

untuk mengubah dictionary

```
telepon['Dina'] = '088999776'
```
Untuk menampilkan hasil semua nama/key nya menggunakan perintah

```
print(telepon.keys())
```

hasil yang dikeluarkan

![gambar](gambar/a.png)

Untuk menampilkan semua nomor telepon/value

```
print(telepon.values())
```

hasil yang dikeluarkan

![gambar](gambar/a1.png)

Daftar Nama dan Nomor menggunakan perintah ```for```

```
for nama,nomor in telepon.items():
    print("%s \t| %s " % (nama,nomor))
```

Output nya akan menghasilkan

![gambar](gambar/a2.png)

Untuk menghapus kontak Dina bisa menggunakan ```del``` 
seperti:

``` 
del telepon['Dina']
```

Maka kontak Dina akan terhapus

![gambar](gambar/a3.png)
