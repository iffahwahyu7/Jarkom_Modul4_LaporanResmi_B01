# Jarkom_Modul4_LaporanResmi_B01

## Subnetting & Routing

Soal :

![alt text](img/soal.jpg)
 
Hasil subnetting :

![alt text](img/subnetting.jpg)

#### A. VLSM

![alt text](img/vlsm_tree.jpg)

perhitungan :

![alt text](img/perhitungan_vlsm.JPG)

![alt text](img/perhitungan_routing_vlsm.JPG)

Routing di UML

SURABAYA
```
route add -net 192.168.0.8 netmask 255.255.255.252 gw 192.168.0.14
route add -net 192.168.0.128 netmask 255.255.255.128 gw 192.168.0.14
route add -net 192.168.0.16 netmask 255.255.255.240 gw 192.168.0.6
route add -net 192.168.2.0 netmask 255.255.254.0 gw 192.168.0.6
route add -net 192.168.8.0 netmask 255.255.252.0 gw 192.168.0.14
route add -net 192.168.16.0 netmask 255.255.248.0 gw 192.168.0.14
route add -net 192.168.12.0 netmask 255.255.252.0 gw 192.168.0.6
route add -net 192.168.0.0 netmask 255.255.255.252 gw 192.168.0.6
route add -net 192.168.24.0 netmask 255.255.252.0 gw 192.168.0.6
route add -net 192.168.1.0 netmask 255.255.255.0 gw 192.168.0.6
route add -net 10.151.83.16 netmask 255.255.255.252 gw 192.168.0.6
```

PASURUAN
```
route add -net 192.168.0.128 netmask 255.255.255.128 gw 192.168.0.10
route add -net 192.168.16.0 netmask 255.255.248.0 gw 192.168.0.10
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.0.13
```

PROBOLINGGO
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.0.9
```

BATU
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.0.5
route add -net 192.168.0.16 netmask 255.255.255.240 gw 192.168.2.3
route add -net 192.168.24.0 netmask 255.255.252.0 gw 192.168.0.2
route add -net 192.168.1.0 netmask 255.255.255.0 gw 192.168.0.2
route add -net 10.151.83.16 netmask 255.255.255.252 gw 192.168.0.2
```

MADIUN
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.2.1
```

KEDIRI
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.0.1
route add -net 192.168.24.0 netmask 255.255.252.0 gw 192.168.1.3
```

BLITAR
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.168.1.1
```

#### B. CIDR

Hasil subnetting:

![alt text](img/cidr.png)

![alt text](img/cidr_tree.jpg)

![alt text](img/cidr_cpt.jpg)

Set-up CPT:

![alt text](img/s-surabaya.png)

![alt text](img/s-surabaya1.png)

![alt text](img/s-surabaya2.png)

![alt text](img/s-surabaya3.png)

![alt text](img/s-batu.png)

![alt text](img/s-batu1.png)

![alt text](img/s-batu2.png)

![alt text](img/s-batu3.png)

![alt text](img/s-banyuwangi.png)

![alt text](img/s-blitar.png)

![alt text](img/s-blitar1.png)

![alt text](img/s-bojonegoro.png)

![alt text](img/s-bondowoso.png)

![alt text](img/s-jember.png)

![alt text](img/s-jombang.png)

![alt text](img/s-kediri.png)

![alt text](img/s-kediri1.png)

![alt text](img/s-kediri2.png)

![alt text](img/s-lumajang.png)

![alt text](img/s-madiun.png)

![alt text](img/s-madiun1.png)

![alt text](img/s-malang.png)

![alt text](img/s-mojokerto.png)

![alt text](img/s-nganjuk.png)

![alt text](img/s-pasuruan.png)

![alt text](img/s-pasuruan1.png)

![alt text](img/s-pasuruan2.png)

![alt text](img/s-probolinggo.png)

![alt text](img/s-probolinggo1.png)

![alt text](img/s-probolinggo2.png)

![alt text](img/s-sampang.png)

![alt text](img/s-sidoarjo.png)

![alt text](img/s-tulungagung.png)

Routing:

![alt text](img/batu.png)

![alt text](img/batu1.png)

![alt text](img/blitar.png)

![alt text](img/kediri.png)

![alt text](img/pasuruan.png)

![alt text](img/probolinggo.png)

![alt text](img/surabaya.png)

![alt text](img/surabaya1.png)
