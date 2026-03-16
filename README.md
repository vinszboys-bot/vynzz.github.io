# vynzz.github.io
payment
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RIAN-SAMA Payment</title>

<style>
body{
  margin:0;
  font-family: Arial, sans-serif;
  background: radial-gradient(circle,#0b0016,#000);
  color:white;
  text-align:center;
}

.container{
  max-width:400px;
  margin:30px auto;
  padding:20px;
}

.title{
  font-size:28px;
  font-weight:bold;
  color:#b88cff;
  text-shadow:0 0 10px #b88cff;
}

.avatar{
  width:120px;
  height:120px;
  border-radius:20px;
  margin:15px auto;
  box-shadow:0 0 25px #b88cff;
  object-fit:cover;
}

.card{
  background:linear-gradient(180deg,#2a004a,#130022);
  padding:20px;
  border-radius:20px;
  margin-top:20px;
  box-shadow:0 0 20px #7a2cff;
}

h2{
  margin-top:0;
  color:#d8b4ff;
}

.method{
  text-align:left;
  margin:15px 0;
  background:#1c0033;
  padding:12px;
  border-radius:12px;
}

.copy-btn{
  float:right;
  background:#8a3cff;
  border:none;
  color:white;
  padding:6px 12px;
  border-radius:8px;
  cursor:pointer;
}

.qris-img{
  width:100%;
  border-radius:15px;
  margin-top:10px;
  box-shadow:0 0 20px #b88cff;
}

.small{
  font-size:12px;
  opacity:0.8;
}
</style>
</head>

<body>

<div class="container">

<div class="title">VYNZZ STORE Payment</div>

<img src="https://i.imgur.com/8Km9tLL.jpg" class="avatar">

<div class="card">
<h2>Metode Pembayaran</h2>

<div class="method">
<b>GOPAY</b><br>
Atas nama: Dwi f*** yan**<br>
082213686547
<button class="copy-btn" onclick="copyText('087840701xxx')">Salin</button>
</div>

<div class="method">
<b>DANA</b><br>
Atas nama: Muhammad Fariz maulana<br>
082213686547
<button class="copy-btn" onclick="copyText('08539774xxx')">Salin</button>
</div>

<p class="small">
Wajib kirimkan bukti pembayaran agar diproses.
</p>
</div>

<div class="card">
<h2>Pembayaran QRIS</h2>

<img src="https://i.imgur.com/2nCt3Sbl.png" class="qris-img">

<p class="small">Klik / Pindai QRIS di atas untuk membayar</p>
</div>

</div>

<script>
function copyText(text){
  navigator.clipboard.writeText(text);
  alert("Nomor berhasil disalin!");
}
</script>

</body>
</html>
