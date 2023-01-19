<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
    <link rel="shortcut icon" href="https://i.imgur.com/R4YNDY5.jpg" type="image/x-icon">
    <title>XuanNghiep | Profile</title>
    <link rel="stylesheet" href="assets/XuanNghiep1.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" />
    <link rel="stylesheet" href="assets/XuanNghiep2.css" />
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons+Round" rel="stylesheet">
    <meta name="author" content="Đây Là Website Của NghiepMeow-Dev, Rất Mong Được Chào Đón Bạn !">
    <meta property="og:title" content="HELLO TA CHI HẢO - THIS IS Bố Nghiệp !">
    <meta property="og:type" content="website">
    <meta property="og:url" content="http://subxuannghiep.com">
    <meta property="og:image" content="http://thanhdieu.com/files/thanhdieugirl.jpg">
    <meta property="og:image:width" content="120">
    <meta property="og:image:height" content="120">
    <meta property="og:site_name" content="NghiepMeow">
    <meta name="theme-color" content="#00FFFF" />
    <script src='https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js' type='text/javascript'></script>
</head>
</div>

<body class="Border" onLoad="onCreate()">
    <div class="BlurWebs">
        <div class="Topnav">
            <a class="Active">HOME</a>
            <a style="color:red;">
                <span id="fps">60.0</span> FPS</a>
        </div>
        <br>
        <!-- ===== ❀ NƠI EDIT AVATAR ❀ ===== -->
        <p align="center">
            <img class="Blob" src="https://img.win3000.com/m00/48/02/085e1a8c2dec126cfd3ec0b17994bbec.jpg" width="96" height="96" alpha="@XuanNghiep@"></p>
        <h2 class="NameFtXuanNghiep" align="center">
            Lưu Xuân Nghiệp <i class="fa fa-check-circle"></i></h2>
        <h2 class="TieuSu">
            Hey brother, I'm a Developer.<br>I like website design :3</h2>
        <br>
        <hr class="New"><br>
        <!-- Thông Tin Liên Hệ -->
        <h2 class="NameFtXuanNghiep">
            Contact Social
        </h2>
        <ul class="icons">
            <br>
            <div class="MangXaHoiFtXuanNghiep">
                <a id="TikTok" onClick="TikTok()">
                    <div class="TikTok">TikTok</div>
                </a>
                <br>
                <a id="Facebook" onClick="Facebook()">
                    <div class="Facebook">Facebook</div>
                </a>
                <br>
                <a id="Github" onClick="Github()">
                    <div class="Github">Github</div>
                </a>
                <br>
                <a id="Telegram" onClick="Telegram()">
                    <div class="Telegram">Telegram</div>
                </a>
                <br>
            </div>
            <br>
            <hr class="New"><br>
            <!-- ===== Thông Tin Thanh Toán - Có Thể Thêm Đoạn Văn Bản Giới Thiệu Ngắn Về Bản Thân  <button> <i class="fa fa-clone"></button> ===== -->
            <div class="NameFtXuanNghiep">
                <h2>Mobile Banks</h2>
            </div>
            <div class="ThongTinThanhToan">
                <p class="ThongTinThanhToanTitle">Vietcombank</p>
                <p class="ThongTinThanhToanText">STK: 1030477114|| CTK LUU XUAN NGHIEP</p>
            </div>
            <br>
            <div class="ThongTinThanhToan">
                <p class="ThongTinThanhToanTitle">Momo Bank</p>
                <p class="ThongTinThanhToanText">STK 0378202427 || CTK LUU XUAN NGHIEP</p>
            </div>
            <br>
            <div class="ThongTinThanhToan">
                <p class="ThongTinThanhToanTitle">MBBANK</p>
                <p class="ThongTinThanhToanText">STK: 0166688889999 || CTK LUU XUAN NGHIEP</p>
            </div>
            <br>
            <br>
            <hr class="ThanhGachNgang">
            <br>
            <br>
            <div class="NameFtThanhDieu">
                <h2><i class="fas fa-code"></i> Skill Languages </h2>
                <br>
            </div>
            <ul class="xuannghiepftskill outline">
                <li class="thanhdieutransform">Javascript</li>
                <li class="xuannghieptransform">Typescript</li>
                <br>
                <li class="xuannghieptransform">Yêu Em</li>
                <li class="xuannghieptransform">Html/Css</li>
                <br>
            </ul>
            <br>
            <!-- ===== Thanh Gạch Ngang ===== -->
            <hr class="ThanhGachNgang">
            <footer class="Cuoi Trang">
                <p class="XuanNghiepFtCopyright">
                    <!-- ===== Thông điệp cuối cùng cho người xem ===== -->
                    <p class="rainbow" class="copyright">Created by
                        <a style="text-decoration: none;" class="copyright" href="https://www.facebook.com/NghiepMeow.Developer">
                            <font class="rainbow" color="white"> XuanNghiep</font>
                        </a>
                        <br> <strong>All rights reserved - © 2022 </strong></p>
            </footer>
    </div>
    <div id="Toast">Welcome to the website Lưu Xuân Nghiệp :)</div>
    <script type="text/javascript" src="./javascript/index.js"></script>
    <script type="text/javascript">
        var fps = document.getElementById("fps");
        var startTime = Date.now();
        var frame = 0;

        function tick() {
            var time = Date.now();
            frame++;
            if (time - startTime > 1000) {
                fps.innerHTML = (frame / ((time - startTime) / 1000)).toFixed(1);
                startTime = time;
                frame = 0;
            }
            window.requestAnimationFrame(tick);
        }
        tick();
    </script>
</body>

</html>