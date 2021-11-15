# output

1. output


```y

print("           UNIVERSITAS TEKNOLOGI SUMBAWA")
print("         Jl. Olat Maras, Dusun Batu Alang")
print("-"*60)
print("         Nama      : Muhammad fahroji")
print("         NIM       : 20.01.013.010")
print("         Jurusan   : Teknik Informatika")
print("         Fakultas  : Rekayasa Sistem")
print("-"*60)
```
![image](https://user-images.githubusercontent.com/93015185/141779095-2193dfe2-1504-4eb0-83da-f49d27662bbb.png)

2. kecepatan


```y
judul = "DATA KECEPATAN MOBIL"
print(judul.rjust(40))
print("="*60)
v = int(input("Kecepatan Rata-rata(km/jam) : "))
t = int(input("Waktu Tempuh (jam)          : "))
s = v*t
print(f"Jarak tempuh       : {s} km")
print("="*60)
```
![image](https://user-images.githubusercontent.com/93015185/141779547-82d85bec-7528-4ecb-a94d-8a8578e3f87d.png)

3. program menghitung pembelian

```y
a = "PROGRAM MENGHITUNG PEMBELIAN"
print(a.rjust(40))
print("-"*50)
hs = int(input("harga satuan : Rp. "))
jp = int(input("jumlah pembelian : "))
disc = 0.10
ht = hs*jp*disc
print(f"harga total : Rp. {ht}")
```
![image](https://user-images.githubusercontent.com/93015185/141780532-62b1d4fe-92a5-454a-91d4-d8e6cda2986c.png)

4. program penjualan buku


```
a = "PROGRAM PENJUALAN BUKU"
print(a.rjust(35))
print("-"*50)
hs = int(input("harga satuan : Rp. "))
jp = int(input("jumlah pembelian : "))
disc = 0.5
ht = hs*jp*disc

print(f"harga total : Rp. {ht}")
```
![image](https://user-images.githubusercontent.com/93015185/141783864-20938639-369d-4ffb-83bb-33e8be0845aa.png)


5. menghitung tagihan telpon

```y
a = "PROGRAM MENGHITUNG TAGIHAN TELEPHONE"
print(a.rjust(35))
print("-"*50)
print("DATA PELANGGAN")
np = str(input("Nama Pelanggan : "))
prk = int(input("Percakapan : "))
s = int(input("SMS : "))

print("TAGIHAN")

ab = 20000
print(" Abonemen : Rp. ", int(ab))


bp = prk*1000
print("Biaya Percakapan : Rp. ", int(bp))

bs = s*300
print("Biaya SMS : Rp. ", int(bs))

tt = ab*bp*bs

print(f"total tagihan : Rp. {tt}")
```
![image](https://user-images.githubusercontent.com/93015185/141790194-92030b8a-606f-45ef-8c84-a20541e1cbc3.png)
![image](https://user-images.githubusercontent.com/93015185/141790138-72408484-1966-4754-b192-6acea42754b2.png)

