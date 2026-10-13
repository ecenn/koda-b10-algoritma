# Algoritma

## Soal 1: Memindahkan Air
- Memindahkan air di dalam gelas.
- Gelas A berisikan teh.
- Gelas B berisikan kopi.
- Isi Gelas A dipindahkan ke Gelas B dan sebaliknya tanpa mencampur.

### Penyelesaian Deskriptif
1. Mulai
2. Siapkan Gelas A dan Gelas B
3. Siapkan Gelas X (gelas tambahan)
4. Tuangkan isi Gelas A ke Gelas X
5. Tuangkan isi Gelas B ke Gelas A
6. Tuangkan isi Gelas X ke Gelas A
7. Selesai

## Soal 2: Bilangan Ganjil atau Genap
- Membuat algoritma menentukan bilangan ganjil atau genap.

### Penyelesaian Deskriptif
1. Mulai
2. Masukkan bilangan (x)
3. Hitung nilai sisa bagi 2 dari bilangan (remainder)
4. Apabila nilai remainder adalah 0, maka hasilnya adalah bilangan genap
5. Apabila nilai remainder bukan 0, maka hasilnya adalah bilangan ganjil
6. Selesai

### Flowchart

```mermaid

flowchart LR

a((start))
b[/x/]
x[remainder = x % 2]
c{remainder == 0}
d[/''genap''/]
e[/''ganjil''/]
z(((stop)))

a --> b
b --> x
x --> c
c --true--> d
c --false--> e
d --> z
e --> z

```

### Pseudocode

    DECLARE x : INTEGER
    DECLARE remainder : INTEGER
    remainder <- x MOD 2

    IF remainder = 0 THEN
        OUTPUT "genap"
    ELSE
        OUTPUT "ganjil"
    ENDIF

## Soal 3: Luas dan Keliling Lingkaran
- Membuat algoritma menghitung luas dan keliling lingkaran.

### Penyelesaian Deskriptif
1. Mulai
2. Menghitung jari-jari lingkaran (r)
3. Mengalikan jari-jari lingkaran (r) dengan jari-jari lingkaran (r) dan dikalikan lagi dengan nilai 3.14 (pi) untuk menghasilkan luas lingkaran
4. Mengalikan jari-jari lingkaran (r) dengan nilai 3.14 (pi) dan dikalikan lagi dengan angka 2 untuk menghasilkan keliling lingkaran
5. Selesai

### Flowchart

```mermaid

flowchart LR


a((start))
b[/r/]
c[luas = r * r * pi]
d[/luas/]
e[keliling = 2 * pi * r]
f[/keliling/]
z(((stop)))

a --> b
b --> c
c --> d
d --> e
e --> f
f --> z

```

<!--
flowchart stuffs:
(()) - start
((())) - stop
[//] - input/output
[] - process
{} - decision
-->