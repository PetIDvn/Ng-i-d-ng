<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Khảo sát người nuôi thú cưng</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background-color: #f9f9f9;
    }
    form {
      background-color: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      max-width: 600px;
      margin: auto;
    }
    label {
      font-weight: bold;
    }
    textarea, input[type="text"], input[type="email"] {
      width: 100%;
      margin: 10px 0;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      padding: 10px 20px;
      background-color: #28a745;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #218838;
    }
  </style>
</head>
<body>
  <h2>Khảo sát người nuôi thú cưng</h2>
  <form action="https://formspree.io/f/xvgaodeg" method="POST">
    <label>1. Bạn nuôi thú cưng nào?</label><br>
    <input type="checkbox" name="pet_type" value="Chó"> Chó<br>
    <input type="checkbox" name="pet_type" value="Mèo"> Mèo<br>
    <input type="checkbox" name="pet_type" value="Khác"> Khác<br><br>

    <label>2. Bạn thường gặp khó khăn gì khi chăm sóc thú cưng?</label><br>
    <textarea name="problems" rows="3" placeholder="Ghi rõ các vấn đề..."></textarea><br><br>

    <label>3. Bạn có thường đưa thú cưng đi khám thú y hay dịch vụ thú cưng khác không?</label><br>
    <input type="radio" name="visit_vet" value="Thường xuyên"> Thường xuyên<br>
    <input type="radio" name="visit_vet" value="Thỉnh thoảng"> Thỉnh thoảng<br>
    <input type="radio" name="visit_vet" value="Hiếm khi"> Hiếm khi<br><br>

    <label>4. Bạn có sử dụng app để quản lý thông tin thú cưng của mình chưa?</label><br>
    <input type="radio" name="use_app" value="Có"> Có<br>
    <input type="radio" name="use_app" value="Không"> Không<br><br>

    <label>5. Khi bạn cần tìm thú y, bạn có thích có nền tảng giúp bạn tìm được phòng khám gần nhất và chức năng 24/7 khi cần thiết không?</label><br>
    <input type="radio" name="navigation_need" value="Có"> Có<br>
    <input type="radio" name="navigation_need" value="Không"> Không<br><br>
   
    <label>6. Bạn có e ngại mỗi lần đến thú y sẽ có trường hợp khám bệnh sai hoặc gây hại cho bé nhà bạn không?</label><br>
    <input type="radio" name="sợ bị gây hại" value="Có"> Có<br>
    <input type="radio" name="sợ bị gây hại" value="Không"> Không<br><br>

    <label>7. Nếu có một app giúp bạn:</label><br>
    <input type="checkbox" name="app_feature" value="Mang thú cưng bên mình qua app"> Lưu trữ và bảo mật thông tin của thú cưng bạn cũng như tạo cảm giác thú cưng luôn bên bạn<br>
    <input type="checkbox" name="app_feature" value="Tìm dịch vụ gần và uy tín"> Tìm dịch vụ gần và uy tín mà không còn phải đi quá xa<br>
    <input type="checkbox" name="app_feature" value="Rút gọn thời gian đặt lịch"> Rút gọn thời gian đặt lịch thay vì phải ngồi chờ khi tiệm quá đông<br>
    <input type="checkbox" name="app_feature" value="Minh bạch thông tin sức khỏe thú cưng"> Minh bạch thông tin thú cưng hỗ trợ bảo vệ thú cưng của bạn<br>
    <input type="checkbox" name="app_feature" value="Bảo vệ quyền lợi người nuôi và nhiều giảm giá"> Bảo vệ quyền lợi chủ nuôi thú cưng và nền tảng nhiều ưu đãi giảm giá<br><br>

     <label>8. Theo bạn, một chiếc móc khoá thú cưng cá nhân hoá sẽ mang lại giá trị gì cho bạn?</label><br>
    <input type="checkbox" name="keychain_value" value="Gợi nhớ thú cưng"> Gợi nhớ thú cưng dù ở xa<br>
    <input type="checkbox" name="keychain_value" value="Kỷ niệm"> Là vật kỷ niệm đáng yêu<br>
    <input type="checkbox" name="keychain_value" value="Cá tính"> Thể hiện tình cảm và cá tính<br>
    <input type="checkbox" name="keychain_value" value="Gắn PId"> Hữu ích khi lạc thú cưng (gắn PId)<br>
    <input type="checkbox" name="keychain_value" value="Để khoe bạn bè"> Là nơi lưu trữ toàn bộ thông tin của thú cưng bạn<br>
    <input type="checkbox" name="keychain_value" value="Có cũng được, không có cũng ok mà"> Có cũng được, không có cũng ok mà<br><br>

     <label>9. Bạn hiện tại ở quận mấy?:</label><br>
    <textarea name="Khu vuc" rows="3" placeholder="Ý kiến của bạn..."></textarea><br><br>
    
    <label>10.  Bạn ở độ tuổi nào?:</label><br>
    <input type="radio" name="age" value="15-25"> 15-25<br>
    <input type="radio" name="age" value="26-35"> 26-35<br>
    <input type="radio" name="age" value="36+"> 36+<br><br>
   
    <button type="submit">Gửi khảo sát</button>
  </form>
</body>
</html>
