---
title: Logika Matematika

---

#### EVANI EVELINA ARTANTI 240411100182


# Logika Matematika

## Negasi
Kebalikan nilai kebenaran dari sebuah proposisi disebut negasi, jika sebuah proposisi memiliki nilai kebenaran Benar, maka negasi dari proposisi tersebut adalah salah, begitu juga sebaliknya.

| p | $\neg p$ |
| -------- | -------- |
| T     | F     |
| F     | T     |

_Contoh 1_

$p$ : Kaca akan pecah bila dibanting (pernyataan ini mempunyai nilai benar)
$\neg p$ : Kaca tidak akan pecah bila dibanting (pernyataan ini mempunyai nilai salah)

_Contoh 2_

$p$ : Semua meja terbuat dari kayu
$\neg p$ : Ada meja yang tidak terbuat dari kayu

## Konjungsi $p \wedge q$
Konjungsi dapat digambarkan sebagai suatu pernyataan, yang dapat dibentuk dengan menambahkan dua pernyataan dengan bantuan kata penghubung AND. Simbol $\wedge$ digunakan untuk konjungsi. Kita dapat membaca simbol ini sebagai "dan". Jika dua pernyataan, $p$, dan $q$ digabungkan dalam suatu pernyataan, maka konjungsi dapat ditunjukkan secara simbolis dalam bentuk $p \wedge q$. Pernyataan ini akan bernilai benar jika kedua pernyataan yang digabungkan bernilai benar.

_Contoh 1_

$p$ : 5 merupakan bilangan prima (nilai pernyataan ini benar)
$q$ : 5 merupakan bilangan ganjil (nilai pernyataan ini benar)
$p \wedge q$ : 5 merupakan bilangan prima dan ganjil (nilai pernyataan ini benar)

_Contoh 2_

$p$ : Ibukota Indonesia adalah Jakarta (nilai pernyataan ini benar) 
$q$ : Ibukota Jepang adalah Osaka (nilai pernyataan ini salah)
$p \wedge q$ : Jakarta dan Osaka adalah ibukota (nilai pernyataan ini salah)

## Disjungsi $p \vee q$
Disjungsi adalah pernyataan majemuk dengan kata hubung “atau”. Sehingga notasi “$p \vee q$” dibaca “p atau q”. Berikut adalah tabel nilai kebenaran disjungsi.

_Contoh_

$p$ : Sapi adalah hewan berkaki empat (nilai pernyataan ini benar)
$q$ : Sapi merupakan hewan karnivora (nilai pernyataan ini salah)
$p \vee q$ : Sapi adalah hewan berkaki empat atau karnivora (nilai pernyataan ini benar)

## Implikasi $p \Longrightarrow q$
Suatu pernyataan majemuk yang menyatakan hubungan sebab akibat dengan bentuk kalimat “jika P maka Q” disebut dengan implikasi atau kondisional.

_Contoh 1_

$p$ : Monica mencuci dengan mesin cuci (nilai pernyataan ini benar)
$q$ : Monica dapat mencuci dengan lebih cepat (nilai pernyataan ini benar)
$p \Longrightarrow q$ : Jika Monica mencuci dengan mesin cuci, maka Monica dapat mencuci dengan lebih cepat (nilai pernyataan ini benar)

_Contoh 2_

$p$ : Ani merupakan adik Yati (nilai pernyataan ini benar)
$q$ : Ani bukanlah keluarga Yati (nilai pernyataan ini salah)
$p \Longrightarrow q$ : Jika Ani merupakan adik Yati, maka Ani bukanlah keluarga Yati (nilai pernyataan ini salah)



## Biimplikasi $p \Leftrightarrow q$
Kalimat majemuk biimplikasi merupakan kalimat majemuk yang bercirikan kata penghubung “...jika dan hanya jika …”. Biimplikasi biasa dinotasikan dengan rangkaian $p \Leftrightarrow q$ dan dibaca dengan “$p$ jika dan hanya jika $q$”.

_Contoh_

$p$ = Astro mendapatkan gaji (BENAR)
$q$ = Astro bekerja (BENAR)
$p \Leftrightarrow q$ = Astro mendapatkan gaji jika dan hanya jika astro bekerja (BENAR)
$p$ = hasil dari ax2 adalah bilangan ganjil (SALAH)
$q$ = 2 adalah bilangan genap (BENAR)
$p \Leftrightarrow q$ = hasil dari ax2 adalah bilangan ganjil jika dan hanya jika 2 bilangan genap
(SALAH)
Bagaimana nilai kebenaran



## Soal
Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{-}&\text{-}&\text{-}\\\text{Т}&\text{Т}&\text{F}&\text{-}&\text{-}&\text{-}\\\text{T}&\text{F}&\text{T}&\text{-}&\text{-}&\text{-}\\\text{T}&\text{F}&\text{F}&\text{-}&\text{-}&\text{-}\\\text{F}&\text{T}&\text{T}&\text{-}&\text{-}&\text{-}\\\text{F}&\text{T}&\text{F}&\text{-}&\text{-}&\text{-}\\\text{F}&\text{F}&\text{T}&\text{-}&\text{-}&\text{-}\\\text{F}&\text{F}&\text{F}&\text{-}&\text{-}&\text{-}&\text{-}\end{array}$$

## Jawab

| $P$ | $Q$ | $P$ | $R \to Q$ | $P \lor (R \to Q)$ |
|:-------:|:-------:|:-------:|:-------------:|:---------------------:|
|    T    |    T    |    T    |       T       |           T           |
|    T    |    T    |    F    |       T       |           T           |
|    T    |    F    |    T    |       F       |           T           |
|    T    |    F    |    F    |       T       |           T           |
|    F    |    T    |    T    |       T       |           T           |
|    F    |    T    |    F    |       T       |           T           |
|    F    |    F    |    T    |       F       |           F           |
|    F    |    F    |    F    |       T       |           T           |

## Refference
https://oeis.org/wiki/List_of_LaTeX_mathematical_symbols
https://www.ruangguru.com/blog/logika-matematika
https://akupintar.id/info-pintar/-/blogs/memahami-logika-matematika-negasi-konjungsi-disjungsi-implikasi-dan-biimplikasi
https://akupintar.id/info-pintar/-/blogs/memahami-logika-matematika-negasi-konjungsi-disjungsi-implikasi-dan-biimplikasi
https://www-javatpoint-com.translate.goog/conjunction-in-discrete-mathematics?_x_tr_sl=en&_x_tr_tl=id&_x_tr_hl=id&_x_tr_pto=wa