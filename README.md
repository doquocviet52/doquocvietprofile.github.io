<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Đỗ Quốc Việt - Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      color: white;

      /* ⭐ BACKGROUND CHUẨN CHẠY TRÊN GITHUB */
      background-image: url('images/neymar.jpg');
      background-size: cover;
      background-position: center;
      background-attachment: fixed;

      /* làm mờ nhẹ */
      backdrop-filter: blur(2px);
    }

    /* Thanh tác vụ trên */
    .topbar {
      width: 100%;
      padding: 15px 0;
      background: rgba(0,0,0,0.65);
      text-align: center;
      font-size: 22px;
      font-weight: bold;
    }

    /* Header */
    .header {
      width: 100%;
      height: 230px;
      background: rgba(0, 0, 0, 0.45);
      position: relative;
    }

    /* Avatar */
    .avatar {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      border: 5px solid white;
      position: absolute;
      bottom: -75px;
      left: 50%;
      transform: translateX(-50%);
      box-shadow: 0 0 20px cyan;
    }

    /* Content */
    .container {
      text-align: center;
      padding: 20px;
      margin-top: 120px;
    }

    .card {
      background: rgba(0, 0, 0, 0.65);
      padding: 25px;
      max-width: 650px;
      margin: 25px auto;
      border-radius: 15px;
      backdrop-filter: blur(6px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.4);
    }

    h1, h2 {
      margin: 10px 0;
      text-shadow: 0 0 8px black;
    }

    /* Footer */
    .footer {
      margin-top: 40px;
      padding: 15px;
      text-align: center;
      background: rgba(0,0,0,0.75);
      font-size: 15px;
    }
  </style>
</head>

<body>

  <div class="topbar">⚽ VIET'S FOOTBALL PORTFOLIO ⚽</div>

  <div class="header"></div>

  <!-- ⭐ Avatar -->
  <img class="avatar" src="https://github.com/user-attachments/assets/7ecaaff8-b9e7-4c5e-a0f7-19d5a5647b4b" alt="avatar">

  <div class="container">
    <h1>Đỗ Quốc Việt</h1>
    <p>Football Lover | Frontend Developer | Student</p>

    <div class="card">
      <h2>Thông tin cá nhân</h2>
      <p><strong>Họ và tên:</strong> Đỗ Quốc Việt</p>
      <p><strong>Lớp:</strong> Bạn điền vào</p>
      <p><strong>Số điện thoại:</strong> Bạn điền vào</p>
      <p><strong>Email:</strong> moonzred706@gmail.com</p>
      <p><strong>Địa chỉ:</strong> Bến Tre, Việt Nam</p>
      <p><strong>Sở thích:</strong> Bóng đá, game, đọc sách</p>
    </div>

    <div class="card">
      <h2>Giới thiệu</h2>
      <p>
        Xin chào! Mình là Việt – một người đam mê bóng đá và công nghệ.
        Portfolio này được thiết kế theo phong cách bóng đá, đặc biệt dành cho fan Neymar Jr.
      </p>
    </div>
  </div>

  <div class="footer">
    © 2025 Đỗ Quốc Việt — Portfolio phong cách Neymar Jr
  </div>

</body>
</html>

