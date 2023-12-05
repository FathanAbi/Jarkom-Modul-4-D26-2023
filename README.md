# Jarkom-Modul-2-D26-2023


* Fathan Abi Karami (5025211156)
* Alya Putri Salma (5025211174)

## Topologi
![](./img/Topologi.png)

## Pembagian Subnet
![](./img/Pembagian%20Subnet%20REVISI.drawio.png)

## VLSM (Cisco Packet Tracer)
## Subnetting
Pertama Hitung jumlah Host pada tiap subnet dan rute nya. kemudian tentukan juga netmasknya pada tiap subnet

![](./img/Tabel%20Rute%20REVISI.png)

Dapat dilihat total Hostnya ada 4257, sehingga netmask subnet besar yang akan digunakan adalah /19 (255.255.224.0).

Setelah itu buat subnetting tree menggunakan metode VLSM

![](./img/Subnet%20VLSM%20REVISI.drawio.png)

Setelah cari NID, Netmask, dan Broadcast Address tiap Subnet

![](./img/Tabel%20Subnet%20VLSM%20REVISI.png)

Kemudian Implementasikan pada Cisco Packet Tracer

## Implementasi pada CPT
## Topologi:

![](./img/CPT.png)

## Routing:

### Aura:

![](./img/Aura%20Routing.png)

### Denken:

![](./img/Denken%20Routing.png)

### Frieren:

![](./img/Fern%20Routing.png)

### Flamme:

![](./img/Flamme%20Routing.png)

### Fern:

![](./img/Fern%20Routing.png)

### Himmel:

![](./img/Himmel%20Routing.png)

### Eisen:

![](./img/Eisen%20Routing.png)

### Lugner:

![](./img/Lugner%20Routing.png)

### Linie:

![](./img/Linie%20Routing.png)

### Lawine:

![](./img/Lawine%20Routing.png)

### Heiter:

![](./img/Heiter%20Routing.png)

## Testing
### A3 (RoyalCapital & WilleRegion)
![](./img/A3.png)

### A5 (LakeKorridor)
![](./img/A5.png)

### A8 (LaubHills & AppettitRegion)
![](./img/A8.png)

### A9 (RohrRoad)
![](./img/A9.png)

### A11 (SchwerMountains)
![](./img/A11.png)

### A13 (Stark)
![](./img/A13.png)

### A15 (TurkRegion)
![](./img/A15.png)

### A16 (GrobeForest)
![](./img/A16.png)

### A18 (GranzChannel)
![](./img/A18.png)

### A20 (BredtRegion & Heiter)
![](./img/A20.png)

### A21 (Sein & RiegelCanyon)
![](./img/A21.png)

### A22 (Richter & Revolte)
![](./img/A22.png)



## CIDR (GNS3)

## Revisi
Terdapat revisi yaitu jumlah ip yang harusnya 4255. bukannya 4257, hal ini disebabkan kelompok kami menghitung subnet Aura-Cloud0, seperti pada template, sehingga kelebihan 2 IP.

Revisi juga terdapat saat tes routing dimana tes routing Fern-linie dan SchwerMountains-Lugner mengalami kegagalan. Hasik revisinya adalah menambah ruting.

![](./img/Testing%20Routing%20Demo%20Revisi.png)
