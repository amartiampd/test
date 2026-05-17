# Tugas Praktikum Modul 7 – Logic Gate TinkerCard

Amartia Ma'rufi Permata Dewi_H1H025024
Isnanisa Rasyidah_H1H025024
Zayyan Khairul Aziz_H1H025067

---

## 1. AND

Gerbang AND menghasilkan output logika 1 hanya ketika semua input bernilai 1. Jika salah satu input bernilai 0 maka output menjadi 0. Pada praktikum digunakan IC **74HC08**.

![Rangkaian AND](and.png)

| A | B | Output (A AND B) |
|:-:|:-:|:----------------:|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

---

## 2. OR

Gerbang OR menghasilkan output 1 apabila salah satu atau kedua input bernilai 1. Output hanya bernilai 0 ketika seluruh input bernilai 0. Gerbang ini diimplementasikan menggunakan IC **74HC32**.

![Rangkaian OR](or.png)

| A | B | Output (A OR B) |
|:-:|:-:|:---------------:|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

---

## 3. NOT

Gerbang NOT berfungsi membalik nilai input. Jika input bernilai 1 maka output menjadi 0 dan sebaliknya. Gerbang NOT sering disebut inverter dan menggunakan IC **74HC04**.

![Rangkaian NOT](not.png)

| A | Output (NOT A) |
|:-:|:--------------:|
| 0 | 1 |
| 1 | 0 |

---

## 4. NAND

Gerbang NAND merupakan kebalikan dari gerbang AND. Output akan bernilai 0 hanya ketika seluruh input bernilai 1. Selain itu output bernilai 1. Gerbang NAND menggunakan IC **74HC00**.

![Rangkaian NAND](nand.png)

| A | B | Output (A NAND B) |
|:-:|:-:|:-----------------:|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

---

## 5. NOR

Gerbang NOR merupakan kebalikan dari gerbang OR. Output akan bernilai 1 hanya ketika semua input bernilai 0. Gerbang NOR menggunakan IC **74HC02**.

![Rangkaian NOR](nor.png)

| A | B | Output (A NOR B) |
|:-:|:-:|:----------------:|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 0 |

---

## 6. XOR

Gerbang XOR menghasilkan output 1 jika kedua input berbeda. Gerbang XOR menggunakan IC **74HC86**.

![Rangkaian XOR](xor.png)

| A | B | Output (A XOR B) |
|:-:|:-:|:----------------:|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

---

## 7. XNOR

Gerbang XNOR menghasilkan output 1 jika kedua input sama. Gerbang XNOR dapat dibentuk dari kombinasi XOR dan NOT.

![Rangkaian XNOR](xnor.png)

| A | B | Output (A XNOR B) |
|:-:|:-:|:-----------------:|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |
