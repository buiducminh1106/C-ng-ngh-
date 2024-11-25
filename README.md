<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Trang Web Hoàn Chỉnh</title>
    <style>
        /* Định nghĩa kiểu cho các phần tử của trang */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #333;
            overflow: hidden;
        }

        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #ddd;
            color: black;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            width: 100%;
            bottom: 0;
            margin-top: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        .button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #45a049;
        }

        .card {
            display: inline-block;
            width: 30%;
            margin: 10px;
            background-color: #fff;
            padding: 15px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            text-align: center;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Chào Mừng Đến Với Trang Web Của Tôi</h1>
        <p>Đây là một trang web mẫu sử dụng HTML, CSS và JavaScript</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#home">Trang Chủ</a>
        <a href="#about">Giới Thiệu</a>
        <a href="#services">Dịch Vụ</a>
        <a href="#contact">Liên Hệ</a>
    </nav>

    <!-- Main Content -->
    <div class="container">
        <!-- Home Section -->
        <section id="home">
            <h2>Trang Chủ</h2>
            <p>Chào mừng bạn đến với trang web của tôi. Đây là nơi tôi chia sẻ các thông tin thú vị về công việc và cuộc sống của mình.</p>
            <img src="https://i.ex-cdn.com/vietnamfinance.vn/files/f1/news/quynhanh/2018/7/11/vnf-cong-nghe.jpg" alt="Placeholder Image">
        </section>

        <!-- About Section -->
        <section id="about">
            <h2>Giới Thiệu</h2>
            <p>Tôi là một lập trình viên đam mê công nghệ và phát triển phần mềm. Đây là nơi tôi chia sẻ những dự án của mình.</p>
        </section>

        <!-- Services Section -->
        <section id="services">
            <h2>Dịch Vụ</h2>
            <div class="card">
                <h3><a href="Phat_trien.html" >Phát triển Web</a></h3>
                <p>Tạo ra các trang web tương tác và dễ sử dụng.</p>
            </div>
            <div class="card">
                <h3><a href="Ung_dung.html" >Ứng dụng di động</a></h3>
                <p>Phát triển ứng dụng di động cho các nền tảng iOS và Android.</p>
            </div>
            <div class="card">
                <h3><a href="Cong_nghe.html" >Tư Vấn Công Nghệ</a></h3>
                <p>Cung cấp các dịch vụ tư vấn công nghệ cho doanh nghiệp và cá nhân.</p>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Liên Hệ</h2>
            <p>Để liên hệ với tôi, vui lòng gửi email đến: <strong>example@mail.com</strong></p>
            <a href="mailto:example@mail.com" class="button">Gửi Email</a>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Trang Web Của Tôi. Tất cả quyền được bảo vệ.</p>
    </footer>

    <script>
        // Thêm JavaScript cơ bản, nếu cần
        console.log("Trang web đã sẵn sàng!");
    </script>

</body>
</html>
