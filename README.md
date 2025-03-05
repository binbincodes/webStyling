

# 🎨 **Responsive Aesthetic UI**  

## 🌟 **Deskripsi**  
Proyek ini adalah latihan dalam mendesain tampilan web yang estetis dan responsif menggunakan **CSS**. Tema desain menggabungkan warna **palevioletred** dan **pink**, dengan elemen UI yang modern dan ramah pengguna.  

## 🎯 **Fitur Utama**  
✔ **Desain Estetis** – Menggunakan warna lembut dan tampilan modern.  
✔ **Responsif** – Menyesuaikan tampilan pada berbagai ukuran layar.  
✔ **Shadow Effect** – Efek bayangan pada elemen untuk tampilan yang lebih menarik.  
✔ **Hover Animation** – Interaksi tombol yang dinamis.  
✔ **CSS Variables** – Memudahkan pengelolaan tema warna.  

## 🛠 **Teknologi yang Digunakan**  
- **HTML** – Struktur halaman web.  
- **CSS (Flexbox & Media Queries)** – Layout responsif dan efek visual.  

## 📌 **Struktur Kode CSS**  
```css
:root {
   --bg-primary: palevioletred;
   --bg-secondary: pink;
   --txt-primary: #ffff;
   --txt-secondary: #2222;
}

.container {
    width: 100%;
    height: 100vh;
    background-color: var(--bg-secondary);
}

.card {
    border: 2px solid var(--bg-primary);
    padding: 32px;
    margin: 8px;
    border-radius: 8%;
    box-shadow: 2px 2px 2px rgba(0, 0, 0, 0.5);
}

.btn {
    margin-top: 16px;
    padding: 8px;
    cursor: pointer;
    border: none;
    color: var(--bg-primary);
    border-radius: 8%;
}

.btn:hover {
    background-color: var(--bg-primary);
    color: var(--txt-primary);
}
```

## 📱 **Tampilan Responsif**  
- **Tablet & Desktop**: Layout **grid dengan banyak elemen**.  
- **Mobile (≤600px)**: Layout berubah menjadi **kolom** agar lebih nyaman dibaca.  

## 🚀 **Cara Menjalankan**  
1. Download atau clone proyek ini.  
2. Buka file **index.html** di browser.  
3. Eksplorasi tampilan UI yang menarik!  

## 💡 **Preview**  
![UI Preview](https://source.unsplash.com/500x300/?pastel,design)  

---

✨ **Dikembangkan oleh sabrina natasya bilbina**  
🎨 "Membuat desain web yang menarik dan fungsional!"  

---
