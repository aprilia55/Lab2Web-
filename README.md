# Praktikum 2: CSS Dasar

## Profil
- **Nama**  : Alfarizki Aprilia Putri  
- **NIM**   : 312410455  
- **Kelas** : TI.24.A5  
- **Mata Kuliah** : Bahasa Pemrograman  

---

## Tujuan
1. Mahasiswa mampu memahami konsep dasar CSS.  
2. Mahasiswa mampu memahami aturan penulisan pada CSS.  
3. Mahasiswa mampu memahami selector sebagai pengontrol CSS.  
4. Mahasiswa mampu membuat pengaturan CSS pada HTML.  

---

## Langkah Praktikum

### 1. Membuat Dokumen HTML Dasar
Saya membuat file `lab2_css_dasar.html` dengan struktur HTML dasar yang berisi header, navigation, dan sebuah div dengan ID `intro`.  

**Screenshot:**  
![Screenshot HTML Dasar](screenshot-html-dasar.png)  

---

### 2. Menambahkan CSS Internal
Saya menambahkan **CSS internal** di bagian `<head>` menggunakan tag `<style>`.  
CSS ini digunakan untuk mengatur tampilan `body`, `header`, dan `h1`.  

**Screenshot:**  
![Screenshot CSS Internal](screenshot-css-internal.png)  

---

### 3. Menambahkan Inline CSS
Saya menambahkan **inline CSS** pada elemen `<p>` dengan properti `text-align` dan `color`.  

**Screenshot:**  
![Screenshot Inline CSS](screenshot-inline-css.png)  

---

### 4. Membuat CSS Eksternal
Saya membuat file baru `style_eksternal.css` kemudian menghubungkannya ke HTML dengan tag `<link>`.  
CSS eksternal ini digunakan untuk mengatur tampilan navigasi (`nav`) dan link (`a`).  

**Screenshot:**  
![Screenshot CSS Eksternal](screenshot-css-eksternal.png)  

---

### 5. Menambahkan CSS Selector (ID & Class)
Saya menambahkan CSS selector berupa **ID** (`#intro`) dan **Class** (`.button`, `.btn-primary`) di file `style_eksternal.css`.  
Lalu saya menerapkannya pada elemen di HTML.  

**Screenshot:**  
![Screenshot Selector](screenshot-selector.png)  

---

## Pertanyaan & Jawaban

1. **Eksperimen CSS**  
   Saya mencoba mengganti warna background, font-size, dan padding menggunakan CSS. Hasilnya tampilan web berubah sesuai properti yang ditambahkan.  

2. **Perbedaan `h1 {}` dengan `#intro h1 {}`**  
   - `h1 {}` → berlaku untuk semua elemen `<h1>` di halaman.  
   - `#intro h1 {}` → hanya berlaku untuk `<h1>` yang ada di dalam elemen dengan ID `intro`.  

3. **Prioritas CSS (internal, eksternal, inline)**  
   - Inline CSS → paling kuat.  
   - Internal CSS → menengah.  
   - Eksternal CSS → paling lemah.  

   Contoh:  
   ```html
   <p style="color:red;">Teks ini tetap merah walau ada CSS internal & eksternal</p>
