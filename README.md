<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Cortez Elegance</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    header, footer {
      background-color: #222;
      color: #fff;
      padding: 20px 0;
    }
    .product {
      display: inline-block;
      width: 250px;
      margin: 20px;
      border: 1px solid #ccc;
      border-radius: 10px;
      padding: 10px;
      background-color: #f9f9f9;
    }
    .product img {
      width: 100%;
      border-radius: 8px;
    }
    .btn {
      background-color: #000;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 6px;
      margin-top: 10px;
      cursor: pointer;
    }
    #qrisModal {
      display: none;
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background-color: rgba(0,0,0,0.7);
      justify-content: center;
      align-items: center;
      z-index: 99;
    }
    #qrisModal img {
      width: 300px;
      border-radius: 10px;
    }
    [12.31, 8/4/2025] ChatGPT: .close {
        color: white;
        font-size: 16px;
        margin-top: 10px;
      }
      form {
        margin-top: 30px;
        background-color: #eee;
        padding: 20px;
        border-radius: 10px;
        width: 90%;
        max-width: 400px;
        margin-left: auto;
        margin-right: auto;
      }
      input, button {
        width: 100%;
        padding: 10px;
        margin-top: 10px;
      }
    </style>
  </head>
  <body>
  
  <header>
    <h1>Cortez Elegance</h1>
    <p>Simple • Stylish • Elegance</p>
  </header>
  
  <!-- Katalog Produk -->
  <div class="product">
    <h3>GFS SR KINKA BLOUSE</h3>
    <img src="baju1.jpg.jpeg" alt="Blouse 1">
    <p>MAROON</p>
    <P>Rp 45.000</P>
    <P>bahan katun rayon diamond gfs khusus dibuat pabrik penghasil rayon terbaik untuk gfs, berkualitas nyaman dan lembut dengan gramasi yang pas</P>
    <button class="btn" onclick="showQRIS()">CHECKOUT</button>
  </div>
  
  <div class="product">
    <h3>GFS SR KINKA BLOUSE</h3>
    <img src="baju2.jpg.jpeg" alt="Blouse 2">
    <P>NAVY</P>
    <p>Rp 45.000</p>
    <p>bahan katun rayon diamond gfs khusus dibuat pabrik penghasil rayon terbaik untuk gfs, berkualitas nyaman dan lembut dengan gramasi yang pas</p>
    <button class="btn" onclick="showQRIS()">CHECKOUT</button>
  </div>

  <div class="product">
    <h3>GFS SR KINKA BLOUSE</h3>
    <img src="baju3.jpg.jpeg" alt="Blouse 3">
    <P>WHITE</P>
    <p>Rp 45.000</p>
    <p>bahan katun rayon diamond gfs khusus dibuat pabrik penghasil rayon terbaik untuk gfs, berkualitas nyaman dan lembut dengan gramasi yang pas</p>
    <button class="btn" onclick="showQRIS()">CHECKOUT</button>
  </div>

  <div class="product">
    <h3>GFS SR KINKA BLOUSE</h3>
    <img src="baju4.jpg.jpeg" alt="Blouse 4">
    <P>BLACK</P>
    <p>Rp 45.000</p>
    <p>bahan katun rayon diamond gfs khusus dibuat pabrik penghasil rayon terbaik untuk gfs, berkualitas nyaman dan lembut dengan gramasi yang pas</p>
    <button class="btn" onclick="showQRIS()">CHECKOUT</button>
  </div>

  <div class="product">
    <h3>GFS SR KINKA BLOUSE</h3>
    <img src="baju5.jpg.jpeg" alt="Blouse 5">
    <P>UNGU</P>
    <p>Rp 45.000</p>
    <p>bahan katun rayon diamond gfs khusus dibuat pabrik penghasil rayon terbaik untuk gfs, berkualitas nyaman dan lembut dengan gramasi yang pas</p>
    <button class="btn" onclick="showQRIS()">CHECKOUT</button>
  </div>

  <div class="product">
    <h3>GFS SR KINKA BLOUSE</h3>
    <img src="baju6.jpg.jpeg" alt="Blouse 6">
    <P>COKLAT</P>
    <p>Rp 45.000</p>
    <p>bahan katun rayon diamond gfs khusus dibuat pabrik penghasil rayon terbaik untuk gfs, berkualitas nyaman dan lembut dengan gramasi yang pas</p>
    <button class="btn" onclick="showQRIS()">CHECKOUT</button>
  </div>
  
  <div class="product">
    <h3>House of smith Jaket Bomber Pria - Bomen Black #5</h3>
    <img src="baju7.jpg.jpeg" alt="Blouse 6">
    <P>HITAM</P>
    <p>Rp 230.000</p>
    <p>Fitur Utama:
      Bahan: Polar Fleece with Embroidery, menawarkan perpaduan sempurna antara kelembutan dan Kenyamanan.
      Desain: Embroidery Simpel dan Elegan yang cocok untuk berbagai kesempatan.
      Warna: Black, mudah dipadukan dengan berbagai pakaian.
    note: untuk warna bisa tulis di kolom pembayaran</p>
    <button class="btn" onclick="showQRIS()">CHECKOUT</button>
  </div>
  
  <div class="product">
    <h3>Otsky Kaos Pria Pocket Cotton Combed 24s Tshirt vol 1</h3>
    <img src="baju8.jpg.jpeg" alt="Blouse 6">
    <P>All Color</P>
    <p>Rp 70.000</p>
    <p>keterangan Produk:
         Cotton 24s 170-180 Gsm.
         Warna Tidak Cepat Pudar
         Lembut, Mudah Menyerap Keringat, Tidak Gerah, dan Tidak Kaku.
         Kualitas jahitan terbaik
         Kelengkapan Produk (Packaging Set)
         Free Sticker</p>
    <button class="btn" onclick="showQRIS()">CHECKOUT</button>
  </div>

  <div class="product">
    <h3>Celana Pendek Boardshort Dewasa kolor Boxer kolor Short Pants</h3>
    <img src="baju9.jpg.jpeg" alt="Blouse 6">
    <P>hitam.mocca.hijau army.abu-abu</P>
    <p>Rp 50.000</p>
    <p>Bahan Microsuede (Santai gak kaku sama adem jadi nyaman saat dipakai)
      Cocok dipakai saat nongkrong santai, jogging santai, surfing, liburan di pantai, gym dan olahraga ringan lainnya
      DETAIL CELANA:
        Pinggang Elastis/Bisa Melar
        pengencang (Bagian pinggang bisa di atur
        jangan takut ke gedean atau kelonggaran di bagian pinggang)
        Satu Kantong Saku Belakang
        Dua Kantong Saku di Kiri dan Kanan</p>
    <button class="btn" onclick="showQRIS()">CHECKOUT</button>
  </div>
    
   <!-- Modal QRIS -->
  <div id="qrisModal" onclick="closeQRIS()">
    <div>
      <img src="pembayaran.jpg.jpeg" alt="QRIS">
      <p class="close">Klik di mana saja untuk menutup</p>
    </div>
  </div>
  
  <!-- Form Upload Bukti -->
  <form action="https://wa.me/6281246213782" method="get" target="_blank">
    <h3>Upload Bukti Pembayaran</h3>
    <input type="text" name="text" placeholder="Nama lengkap" required>
    <input type="text" name="text" placeholder="Nama produk & jumlah" required>
    <input type="text" name="text" placeholder="Size" required>
    <input type="text" name="text" placeholder="Alamat" required>
    <input type="text" name="text" placeholder="Pembayaran via" required>
    <input type="file" accept="image/*" required>
    <button type="submit">Kirim Bukti via WhatsApp</button>
  </form>
  
  <footer>
    <p>&copy; 2025 Cortez Elegance</p>
    <p>ig : jonecortez_</p>
    <p>wa.me : 081246213782</p>
  </footer>  
  
  <script>
    function showQRIS() {
      document.getElementById("qrisModal").style.display = "flex";
    }
    function closeQRIS() {
      document.getElementById("qrisModal").style.display = "none";
    }
  </script>
  
  </body>
  </html>
