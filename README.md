# Wep.site
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Üyelik Formu</title>
  <style>
    body { font-family: Arial, sans-serif; background-color: #f2f2f2; }
    nav { text-align: center; padding: 20px; background-color: #0072ff; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-size: 18px; }
    nav a:hover { text-decoration: underline; }
    .form-container { background-color: white; padding: 30px; border-radius: 10px; max-width: 400px; margin: auto; box-shadow: 0 0 10px rgba(0,0,0,0.2); }
    input[type="text"], input[type="email"], input[type="password"] {
      width: 100%;
      padding: 12px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #4CAF50;
      color: white;
      padding: 12px;
      width: 100%;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 10px;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <nav>
    <a href="index.html">Ana Sayfa</a>
    <a href="hakkimda.html">Hakkımda</a>
    <a href="kayit.html">Üye Ol</a>
    <a href="iletisim.html">İletişim</a>
    <a href="hizmetler.html">Hizmetlerim</a>
    <a href="blog.html">Blog</a>
    <a href="faq.html">SSS</a>
    <a href="privacy.html">Gizlilik Politikası</a>
  </nav>

  <div class="form-container">
    <h2>Üye Ol</h2>
    <form action="kayit.php" method="POST">
      <input type="text" name="adsoyad" placeholder="Ad Soyad" required>
      <input type="email" name="email" placeholder="Email Adresi" required>
      <input type="password" name="sifre" placeholder="Şifre" required>
      <button type="submit">Kayıt Ol</button>
    </form>
  </div>

</body>
</html>
