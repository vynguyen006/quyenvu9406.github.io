<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Web Của Tôi</title>
    <style>
        /* CSS cơ bản tạo hiệu ứng cuộn trang mượt mà */
        html { scroll-behavior: smooth; font-family: Arial, sans-serif; }
        body { margin: 0; padding: 0; }
        nav { position: fixed; top: 0; width: 100%; background: #333; padding: 15px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        section { padding: 100px 20px; height: 100vh; display: flex; justify-content: center; align-items: center; flex-direction: column; }
        #home { background: #f4f4f4; }
        #about { background: #ddd; }
    </style>
</head>
<body>

    <nav>
        <a href="#home">Trang Chủ</a>
        <a href="#about">Giới Thiệu</a>
    </nav>

    <section id="home">
        <h1>Chào mừng đến với trang web của tôi</h1>
        <p>Đây là phần Trang Chủ (#home)</p>
    </section>

    <section id="about">
        <h1>Giới Thiệu</h1>
        <p>Thông tin về bản thân hoặc sự kiện ở đây.</p>
    </section>

</body>
</html>
