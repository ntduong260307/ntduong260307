@import url('https://fonts.googleapis.com/css2?family=ZCOOL+QingKe+HuangYou&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Teko:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Righteous&display=swap');
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border-radius: 0px;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

body {
    position: relative;
    scroll-behaviour: smooth;
    font-family: ZCOOL QingKe HuangYou;
    background: black
}

.Border {
    font-size: 12px;
    position: relative;
    min-height: 100%;
    box-sizing: border-box;
    padding-bottom: 80px;
    background-color: #222;
    text-align: center;
    background-color: BLACK;
    padding: 0px;
    margin: 8px;
    border-style: double;
    border-radius: 10px;
    border-color: #ccc;
    border-width: 2px;
    animation-name: bodyborder;
    animation-iteration-count: infinite;
    animation-duration: 5s;
    animation-direction: right
}

.BlurWebs {
    animation: blur 3s linear 1 0s forwards
}

::-webkit-scrollbar {
    width: 8px;
    height: 15px
}

::-webkit-scrollbar-track {
    box-shadow: inset 0 0 5px grey;
    border-radius: 10px
}

::-webkit-scrollbar-thumb {
    background: #00ffbc;
    border-radius: 10px
}

::-webkit-scrollbar-thumb:hover {
    background: #00ffbc
}

.MangXaHoiFtXuanNghiep div {
    border: 2px solid white;
    border-radius: 7px;
    color: white;
    padding: 10px 24px;
    cursor: pointer;
    width: 43%;
    margin: auto 29%;
    transition: 0.5s;
    text-align: center;
    text-shadow: -1px 0 5px CYAN, 0 1px 5px RED, 1px 0 5px CYAN, 0 -1px 5px RED
}

.MangXaHoiFtXuanNghiep:after {
    content: "";
    clear: both;
    display: table
}

.MangXaHoiFtXuanNghiep div:not(:last-child) {
    border-right: none
}

.MangXaHoiFtXuanNghiep div:hover {
    transform: translateY(-3px);
    transition: 0.5s
}

.TikTok {
    background: rgb(35, 165, 63);
    background: linear-gradient(138deg, rgb(50, 184, 133) 0%, rgba(222, 94, 94, 1) 21%, rgba(223, 86, 86, 1) 37%, rgba(223, 86, 86, 1) 46%, rgba(235, 49, 43, 1) 66%)
}

.Facebook {
    background: rgb(131, 58, 180);
    background: linear-gradient(90deg, rgba(51, 51, 255, 1) 100%, rgba(51, 51, 255, 1) 100%, rgba(51, 51, 255, 1) 100%)
}

.Github {
    background: rgb(22, 22, 24);
    background: linear-gradient(139deg, rgba(88, 101, 242, 1) 41%, rgba(152, 100, 230, 1) 75%)
}

.Telegram {
    background: rgb(0, 255, 255);
    background: linear-gradient(139deg, rgba(0, 255, 255, 1) 41%, rgba(0, 255, 240, 1) 75%)
}

.ThongTinThanhToan {
    transition: .5s;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    background-color: #252525;
    padding: 14px;
    border-radius: 10px;
    box-shadow: 0 2px 2px 1px #555;
    color: #ffffff;
    width: 80%;
    margin-left: auto;
    margin-right: auto;
    margin-top: 10px;
    margin-bottom: 10px;
    border-radius: 2px;
    box-shadow: 0 0 7px 3px #33FFFF
}

.ThongTinThanhToan:hover {
    background-color: #353535;
    box-shadow: 0 2px 2px 1px #555;
    transform: scale(0.95);
    border-radius: 2px;
    box-shadow: 0 0 7px 3px #33FFFF
}

.ThongTinThanhToanTitle {
    padding: 0 0;
    margin: 0 0;
    font-size: 23px;
    font-weight: 700;
    color: #00FFFF
}

.ThongTinThanhToanText {
    padding: 0 0;
    margin: 5 0;
    font-size: 20px;
    font-weight: 500;
    color: #00CC33;
    margin-top: 5px
}

.Blob {
    background: black;
    border-radius: 50%;
    margin: 10px;
    height: 150px;
    width: 150px;
    background: #111845a6;
    box-sizing: border-box;
    overflow: hidden;
    box-shadow: 0 0 10px 1px #FFFFFF;
    animation: blur 3s linear 1 0s forwards;
    animation: pulse 3s infinite
}

.NameFtXuanNghiep {
    color: #FFFFFF;
    padding: 0;
    font-size: 22px;
    line-height: 1.8;
    margin-bottom: 0;
    text-shadow: -1px 0 5px CYAN, 0 1px 5px RED, 1px 0 5px CYAN, 0 -1px 5px RED
}

.TieuSu {
    text-align: center;
    color: #fff;
    font-size: 22px;
    font-weight: bold;
    text-shadow: -1px 0 5px CYAN, 0 1px 5px RED, 1px 0 5px CYAN, 0 -1px 5px RED
}

hr.ThanhGachNgang {
    border: 0.5px solid #FFFFFF;
    border-style: double;
    margin-left: 20px;
    margin-right: 20px
}

.Trang {
    color: white;
    -webkit-mask: linear-gradient(-60deg, white 30%, #0004, white 70%)right/300% 100%;
    background-repeat: no-repeat;
    animation: shimmer 1s infinite
}

.Cuoi {
    padding: 40px 0;
    color: #ffffff
}

.Footer .XuanNghiepFtCopyright {
    margin-top: 15px;
    text-align: center;
    font-size: 20px;
    color: #aaa;
    margin-bottom: 0
}

.rainbow {
    margin-top: 15px;
    text-align: center;
    font-size: 16px;
    color: #aaa;
    margin-bottom: 0;
    animation: colorRotate 2.5s linear 0s infinite
}

@keyframes colorRotate {
    from {
        color: #FFFFFF
    }
    10% {
        color: #FF0000
    }
    30% {
        color: #00FF00
    }
    45% {
        color: #0000FF
    }
    55% {
        color: #FFFF00
    }
    65% {
        color: #00FFFF
    }
    75% {
        color: #00FF00
    }
    85% {
        color: #0000FF
    }
    100% {
        color: #FF66CC
    }
}

.Topnav {
    overflow: hidden
}

.Topnav a {
    font-family: 'ZCOOL QingKe HuangYou';
    float: left;
    display: block;
    color: pink;
    text-align: center;
    padding: 12px 14px;
    text-decoration: none;
    font-size: 17px;
    border-bottom: 3px solid transparent
}

.Topnav a:hover {
    border-bottom: 3px solid #00ffff;
    margin-left: 2px;
    transition: 0.5s
}

.Topnav a.Active {
    border-bottom: 3px solid #00ff00;
    margin-left: 5px
}

#Toast {
    visibility: hidden;
    min-width: 250px;
    margin-left: -125px;
    background-color: #333;
    color: gold;
    text-align: center;
    border-radius: 50px;
    border: 3px solid green;
    padding: 16px;
    position: fixed;
    z-index: 1;
    left: 50%;
    bottom: 35px;
    font-size: 20px
}

#Toast.show {
    visibility: visible;
    -webkit-animation: fadein 2.0s, fadeout .2.0s 2.0s;
    animation: fadein 2.0s, fadeout 2.0s 2.0s
}

.NoScript {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 25px;
    margin: 20px;
    flex-direction: column;
    border-radius: 20px;
    border: 3px double cyan;
    background-color: #252525;
    color: #fff
}

@keyframes pulse {
    0% {
        transform: scale(0.99)
    }
    50% {
        transform: scale(1.1)
    }
    100% {
        transform: scale(0.99)
    }
}

@keyframes bodyborder {
    20% {
        border-color: cyan
    }
    40% {
        border-color: lime
    }
    60% {
        border-color: red
    }
    80% {
        border-color: yellow
    }
    90% {
        border-color: orange
    }
}

@keyframes shimmer {
    100% {
        -webkit-mask-position: left
    }
}

@-webkit-keyframes fadein {
    from {
        bottom: 0;
        opacity: 0
    }
    to {
        bottom: 35px;
        opacity: 1
    }
}

@keyframes fadein {
    from {
        bottom: 0;
        opacity: 0
    }
    to {
        bottom: 35px;
        opacity: 1
    }
}

@-webkit-keyframes fadeout {
    from {
        bottom: 35px;
        opacity: 1
    }
    to {
        bottom: 0;
        opacity: 0
    }
}

@keyframes fadeout {
    from {
        bottom: 35px;
        opacity: 1
    }
    to {
        bottom: 0;
        opacity: 0
    }
}

@keyframes blur {
    from {
        opacity: 0;
        filter: blur(3px)
    }
    to {
        opacity: 1;
        filter: blur(0px)
    }
}

@keyframes snow {
    0% {
        background-position: 0px 0px, 0px 0px, 0px 0px
    }
    50% {
        background-position: 500px 500px, 100px 200px, -100px 150px
    }
    100% {
        background-position: 500px 1000px, 200px 400px, -100px 300px
    }
}