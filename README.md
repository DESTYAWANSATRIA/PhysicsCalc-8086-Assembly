# 📘 Kinematics Calculator 8086

Program kalkulator kinematika (jarak, kecepatan, waktu, percepatan) yang dibuat menggunakan **Assembly 8086**.

---

## 🚀 Tentang Proyek
Program ini dibuat untuk menghitung besaran-besaran dasar dalam **gerak lurus (kinematika)**, yaitu:

- Kecepatan
- Jarak
- Waktu tempuh
- Percepatan

Seluruh proses input-output memanfaatkan interrupt **INT 21h** dan **INT 16h**, dengan perhitungan manual tanpa fungsi bawaan.

---

## ✨ Fitur Utama
- Menghitung **kecepatan** berdasarkan jarak & waktu  
- Menghitung **jarak** berdasarkan kecepatan & waktu  
- Menghitung **waktu** berdasarkan jarak & kecepatan  
- Menghitung **percepatan**  
- Sistem input angka buatan sendiri (InputNo)  
- Output desimal menggunakan prosedur View & ViewNo  
- Menu interaktif dan mudah digunakan  
- Dapat dijalankan menggunakan MASM, TASM, EMU8086, atau DOSBox

---

## 🧠 Rumus yang Digunakan

| Besaran | Rumus |
|--------|--------|
| Kecepatan (v) | v = s / t |
| Jarak (s) | s = v × t |
| Waktu (t) | t = s / v |
| Percepatan (a) | a = Δv / t |

---

## ▶️ Cara Menjalankan Program

### 💻 Menggunakan TASM
```bash
tasm kinematics_calc.asm
tlink kinematics_calc.obj
