<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Đỗ Quốc Việt - Football Portfolio</title>

  <style>
    /* ===== RESET ===== */
    body {
      margin: 0;
      font-family: "Poppins", Arial, sans-serif;
      color: white;
      /* SỬA LỖI: XÓA ![] VÀ XUỐNG DÒNG */
      background: url('![neymar jpg](https://github.com/user-attachments/assets/ff378da2-f95e-4a1d-b8ed-4ef8e039bdff)
') 
      no-repeat center center fixed;
      background-size: cover;
    }

    /* Overlay mờ giúp chữ dễ đọc */
    .overlay {
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.55);
      position: fixed;
      top: 0;
      left: 0;
      z-index: -1;
    }

    /* ===== NAVBAR ===== */
    .navbar {
      width: 100%;
      padding: 18px 0;
      background: rgba(0, 0, 0, 0.65);
      backdrop-filter: blur(6px);
      text-align: center;
      position: fixed;
      top: 0;
      left: 0;
      z-index: 10;
    }

    .navbar a {
      color: white;
      text-decoration: none;
      margin: 0 25px;
      font-size: 20px;
      font-weight: bold;
      transition: 0.3s;
    }

    .navbar a:hover {
      color: #00ffea;
    }

    /* ===== HERO SECTION ===== */
    .hero {
      text-align: center;
      padding-top: 160px;
      padding-bottom: 100px;
    }

    .avatar {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      border: 6px solid #00ffea;
      box-shadow: 0 0 25px #00e1ff;
      object-fit: cover;
    }

    .hero h1 {
      font-size: 45px;
      margin-top: 25px;
      font-weight: 700;
      text-shadow: 0 0 10px black;
    }

    .hero p {
      font-size: 22px;
      opacity: 0.9;
    }

    /* ===== CARD SECTIONS ===== */
    .section {
      max-width: 900px;
      margin: 40px auto;
      padding: 25px 35px;
      background: rgba(0, 0, 0, 0.55);
      border-radius: 15px;
      backdrop-filter: blur(4px);
      box-shadow: 0 0 20px rgba(0,0,0,0.45);
    }

    h2 {
      font-size: 28px;
      margin-bottom: 15px;
      color: #00ffea;
    }

    p, li {
      font-size: 18px;
      line-height: 1.6;
    }

    /* ===== FOOTER ===== */
    .footer {
      width: 100%;
      background: rgba(0, 0, 0, 0.7);
      text-align: center;
      padding: 18px 0;
      font-size: 17px;
      margin-top: 60px;
    }
  </style>

</head>
<body>
  <div class="overlay"></div>

  <!-- NAVBAR -->
  <div class="navbar">
    <a href="#home">Trang chủ</a>
    <a href="#info">Thông tin</a>
    <a href="#skills">Kỹ năng</a>
    <a href="#career">Sự nghiệp</a>
    <a href="#contact">Liên hệ</a>
  </div>

  <!-- HERO SECTION -->
  <div class="hero" id="home">
    <!-- SỬA LỖI LINK IMG -->
    <img class="avatar" src="![viett jpg](https://github.com/user-attachments/assets/a7eee74b-c6bb-4450-ba1c-fff916365646)
" alt="avatar">
    <h1>Đỗ Quốc Việt</h1>
    <p>Football Player | Winger | Playmaker</p>
  </div>

  <!-- THÔNG TIN CÁ NHÂN -->
  <div class="section" id="info">
    <h2>Thông tin cá nhân</h2>
    <p><strong>Họ và tên:</strong> Đỗ Quốc Việt</p>
    <p><strong>Lớp:</strong> 12V?</p>
    <p><strong>Số điện thoại:</strong> 0704828957</p>
    <p><strong>Email:</strong> moonzred706@gmail.com</p>
    <p><strong>Địa chỉ:</strong> Bến Tre, Việt Nam</p>
    <p><strong>Vị trí thi đấu yêu thích:</strong> RW – LW – CAM</p>
  </div>

  <!-- KỸ NĂNG -->
  <div class="section" id="skills">
    <h2>Kỹ năng thi đấu</h2>
    <ul>
      <li>Tốc độ bứt phá tốt</li>
      <li>Qua người, rê bóng kỹ thuật</li>
      <li>Chuyền bóng và tạo cơ hội</li>
      <li>Sút xa uy lực</li>
      <li>Tầm nhìn chiến thuật cao</li>
    </ul>
  </div>

  <!-- SỰ NGHIỆP -->
  <div class="section" id="career">
    <h2>Sự nghiệp & Thành tích</h2>
    <p>Hành trình theo đuổi đam mê bóng đá và phát triển bản thân theo phong cách thi đấu sáng tạo giống Neymar Jr.</p>
    <ul>
      <li>Tham gia giải bóng đá cấp trường</li>
      <li>Đạt nhiều danh hiệu MVP & Top ghi bàn</li>
      <li>Thi đấu trong các giải phong trào tỉnh</li>
      <li>Trưởng nhóm chiến thuật đội bóng lớp</li>
    </ul>
  </div>

  <!-- FOOTER -->
  <div class="footer" id="contact">
    © 2025 — Đỗ Quốc Việt | Football Portfolio
  </div>

</body>
</html>

