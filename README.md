
<style>
/* UI Object */
body{_text-align:center}
#wrap{width:1400px;margin:0 auto;_text-align:left}
#header{width:100%}
#container{*display:inline-block;width:100%}
#container:after{display:block;clear:both;content:''}
.snb{float:left;width:250px;height:480px;margin-right:20px}
#content{float:left;width:860px}
.aside{float:right;width:250px;height:480px}
#footer{width:100%}
/* Layout Color - 실제 서비스 적용 후 아래 코드는 삭제 하세요 */
div{margin:0 0 10px;padding:10px 0;color:#2d2c2d;font-family:Tahoma;font-size:14px;font-weight:bold}
#wrap{_width /**/:620px;padding:10px;border:1px solid #bdbdbd;background:#f7f7f7}
#header{width:auto;margin-top:10px;padding:10px}
#header,#container{position:relative;width:auto;padding:10px;border:2px solid #bfbfbf;background:#e5e5e5}
.snb{position:relative;margin-top:10px;margin-right:5px;border:1px solid #bdbdbd;background:#fff;text-align:center}
#content{position:relative;height:480px;margin-top:10px;border:1px solid #bdbdbd;background:#fff;text-align:center}
.aside{position:relative;margin-top:10px;border:1px solid #bdbdbd;background:#fff;text-align:center}
#footer{width:auto;padding:10px;border:2px solid #bfbfbf;background:#e5e5e5}
/* //UI Object */
</style>



<!--ui object -->
<div id="wrap">
<p>한이음</p>
<!--header -->
<div id="header">
<p>IoT기반 드론을 이용한 화재 예방시스템</p>
</div>
<!--//header -->
<!--container -->
<div id="container">
<!--snb -->
<div class="snb">
<p>가스센서</p>
</div>
<!--//snb -->
<!--content -->
<div id="content">

<video width="800" height="450" controls autoplay preload="auto">
	<source src="IMG_3973.mp4" type="video/mp4">
</video>
<hr>
<script type="text/javascript">
    function printTime() {
        var clock = document.getElementById("clock");
        //id값인 <span>태그를 변수clock에 저장
        var now = new Date(); 
        //객체 생성
        
        clock.innerHTML = 
            //태그내부에 태그 설정
        now.getFullYear() + "년 " + 
        (now.getMonth() + 1) + "월 " +
        now.getDate() + "일 " + 
        now.getHours() + "시 " + 
        now.getMinutes() + "분 " + 
        now.getSeconds() + "초";
        setTimeout("printTime()", 1000); 
        //1초마다 printTime()함수 호출
    }
    window.onload = function() { //html 로딩시 콜백함수 호출
        printTime();
    }
</script>
<body>
    <span id="clock"></span>
</body>

</div>
<!--//content -->
<!--aside -->
<div class="aside">
<p>타임라인</p>
</div>
<!--//aside -->
</div>
<!--//container -->
<!--footer -->
<div id="footer">
	<center>
<p>dr.one.421421@gmail.com</p>
</center>
</div>
<!--//footer -->
</div>
<!--//ui object -->

<!-- <body style="overflow:hidden; margin:0">
	<script language="javascript">
        function autoResizeDiv()
        {
            document.getElementById('main').style.height = window.innerHeight +'px';
        }
        window.onresize = autoResizeDiv;
        autoResizeDiv();
    </script>
</body> -->
