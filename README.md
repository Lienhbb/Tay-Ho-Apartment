<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Căn hộ Westlake Harmony</title>
  <style>
    body {
      font-family: 'Noto Sans JP', sans-serif;
      margin: 0; padding: 0; background: #fafafa; color: #333;
    }
    header {
      background: #ffffff; padding: 40px 20px; text-align: center;
      border-bottom: 1px solid #eee;
    }
    header h1 {
      margin: 0; font-size: 2.4em;
      color: #2c3e50;
    }
    section {
      max-width: 900px; margin: 50px auto;
      background: white; border-radius: 8px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.05);
      padding: 30px;
    }
    .gallery {
      display: grid; grid-template-columns: repeat(auto-fill,minmax(250px,1fr));
      gap: 10px; margin: 20px 0;
    }
    .gallery img {
      width: 100%; height: auto; border-radius: 6px;
    }
    h2 {
      border-bottom: 2px solid #eee; padding-bottom: 10px;
      color: #34495e; margin-bottom: 20px;
    }
    .amenities ul, .reviews ul {
      list-style: none; padding: 0;
    }
    .amenities li, .reviews li {
      margin-bottom: 10px; padding-left: 20px;
      position: relative;
    }
    .amenities li::before {
      content: "✔️"; position: absolute; left: 0;
    }
    .reviews blockquote {
      margin: 20px 0; padding: 15px;
      background: #f0f0f0; border-left: 4px solid #2ecc71;
    }
    .contact {
      text-align: center; margin-top: 30px;
    }
    .contact button {
      padding: 12px 24px; background: #3498db;
      border: none; border-radius: 4px; color: white;
      font-size: 1em; cursor: pointer;
    }
    footer {
      text-align: center; padding: 20px; background: #f9f9f9;
      color: #777; font-size: 0.9em;
    }
  </style>
</head>
<body>

<header>
  <h1>Căn hộ Westlake Harmony</h1>
  <p>Phong cách Nhật Bản đương đại bên Hồ Tây, Hà Nội</p>
</header>

<section class="intro">
  <h2>Giới thiệu căn hộ</h2>
  <p>Căn hộ nằm tại vị trí trung tâm Tây Hồ, gần Hồ Tây, thiết kế tối giản theo phong cách Nhật Bản: thoáng, gọn gàng và yên tĩnh. Phù hợp với gia đình hoặc các bạn yêu thích không gian sáng, ấm áp.</p>
</section>

<section class="gallery-section">
  <h2>Hình ảnh căn hộ & tiện nghi</h2>
  <div class="gallery">
    <img src="https://source.unsplash.com/800x600/?minimalist,apartment" alt="Phòng khách">
    <img src="https://source.unsplash.com/800x600/?japanese,kitchen" alt="Phòng bếp">
    <img src="https://source.unsplash.com/800x600/?bedroom,japanese" alt="Phòng ngủ">
    <img src="https://source.unsplash.com/800x600/?taitoa,zen,garden" alt="Ban công / góc thư giãn">
  </div>
</section>

<section class="location">
  <h2>Vị trí & tiện ích</h2>
  <p>Căn hộ chỉ cách Hồ Tây vài phút đi bộ, rất thuận tiện để tận hưởng thiên nhiên, café, hoặc các hoạt động du lịch quanh hồ. Gần chợ, siêu thị, nhà thuốc, và khu ẩm thực.</p>
  <iframe src="https://www.google.com/maps?q=Hồ+Tây+Hà+Nội&output=embed" style="width:100%; height:350px; border:0; border-radius:6px;"></iframe>
</section>

<section class="amenities">
  <h2>Tiện ích</h2>
  <ul>
    <li>Wi-Fi tốc độ cao</li>
    <li>Máy giặt, máy sấy</li>
    <li>Nhà bếp đầy đủ dụng cụ</li>
    <li>Máy lạnh và điều hòa nhiệt độ</li>
    <li>Bãi đỗ xe riêng & bảo vệ 24/7</li>
  </ul>
</section>

<section class="reviews">
  <h2>Đánh giá từ khách</h2>
  <blockquote>
    “Căn hộ rất sạch sẽ và yên tĩnh. Rất thích góc ban công nhìn ra Hồ Tây buổi sáng.” – Minh
  </blockquote>
  <blockquote>
    “Thiết kế theo phong cách Nhật Bản khiến mình cảm thấy thư thái và thoải mái.” – Linh
  </blockquote>
</section>

<section class="contact">
  <h2>Đặt phòng / Liên hệ</h2>
  <button onclick="window.location.href='https://www.airbnb.com/l/oXv1iCop'">
    Đặt phòng trên Airbnb
  </button>
</section>

<footer>
  © 2025 Westlake Harmony • Thiết kế tối giản phong cách Nhật Bản
</footer>

</body>
</html>
