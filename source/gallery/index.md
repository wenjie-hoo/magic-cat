<body>
<div id="gallery" >
   <img class="drawing" src="https://s2.loli.net/2022/08/05/tBJmQDA5ZOhMwN6.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/Qof4unCSsgJdMIR.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/H4Zq6MD9hd7wkgQ.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/UukTsqDH65GvYPS.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/YoFHLUgAMVRrBsC.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/cYulvI7krmn12ya.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/xAWR8Xe4gUM7IPS.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/JfoUqKOPHuWFnN8.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/RxOIB4mbJuGFqiw.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/r9hAQTGvE64BwP5.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/V6l7kh4Hf3YWZbF.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/NtnoiAk4RE18G9Z.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/A6gM792laK8bDLT.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/nBtQleKDMzuIyFJ.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/3RTYpW59MEnldXU.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/hZDuPHLCtbjK581.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/jWwxUTqFV4uty5J.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/LwWYjsPO3RHapQI.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/sD2kUZ8Ad4IcMXV.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/bD6HA9eVJdLimBq.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/8tIAlG9RLar2wzx.jpg">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/WVNF1RwXbhsLlIG.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/4BbEZHVXPnpR1Fz.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/ao1C4V5iGXcvmMY.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/PfUSqNa1bXtcDVv.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/qcKutbsn4PBQUhx.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/3AQkP51TOZflueh.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/9Lcqo5wOQztyCih.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/uGoUl9mYEVr47Lt.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/NtnoiAk4RE18G9Z.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/FTfu2jSZtNC9LJP.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/qoGNlDCOTcfxWZu.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/N8HDsYdXBjnbUKR.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/2p5YdJFUC7NGETI.jpg">
    <img class="drawing" src="https://s2.loli.net/2022/08/05/1OrT4bYstpxk8dJ.jpg">
   
</div> 
 </body>
</html>

<style>
    #gallery {
    line-height:0;
    -webkit-column-count:4; /* split it into 5 columns */
    -webkit-column-gap:5px; /* give it a 5px gap between columns */
    -moz-column-count:5;
    -moz-column-gap:5px;
    column-count:4;
    column-gap:5px;
 }
    #gallery img {
    width: 100% !important;
    height: auto !important;
    filter: grayscale(100%);
    transition: filter 1s;
    margin-bottom:5px; /* to match column gap */
 }
 @media (max-width: 1200px) {
    #gallery {
     -moz-column-count:    4;
     -webkit-column-count: 4;
     column-count:         4;
    }
 }
 @media (max-width: 1000px) {
    #gallery {
     -moz-column-count:    3;
     -webkit-column-count: 3;
     column-count:         3;
    }
 }
 @media (max-width: 800px) {
    #gallery {
     -moz-column-count:    3;
     -webkit-column-count: 3;
     column-count:         3;
    }
 }
 @media (max-width: 400px) {
    #gallery {
     -moz-column-count:    2;
     -webkit-column-count: 2;
     column-count:         2;
    }
 }
#gallery img:hover {
    filter:none;
 }

		*{
			margin: 0;
			padding: 0;
		}
		.drawing{
			width: 100px;
			margin: 10px;
		}
		.drawing:hover{
			cursor: zoom-in;
		}
		.wrapper{
			position: fixed;
			top: 0;
			right: 0;
			bottom: 0;
			left: 0;
			z-index: 999;
			background-repeat: no-repeat;
			background-attachment: fixed;
			background-position: center;
			background-color: rgba(52, 52, 52, 0.8);
			background-size: 50%;
		}
		.wrapper:hover{
			cursor: zoom-out;
		}
</style>

<script src="../about/jquery-3.3.1.min.js"></script>
<script>
    $(function(){
        $('.drawing').click(function(){
            $(this).after("<div class='wrapper'></div>");
            var imgSrc = $(this).attr('src');
            $(".wrapper").css("background-image", "url(" + imgSrc + ")");
            $('.wrapper').fadeIn(1000);
            $('.wrapper').click(function(){
                $('.wrapper').fadeOut(1000).remove();
            });
        });
    });
    var cards = $(".drawing");
    for(var i = 0; i < cards.length; i++){
    var target = Math.floor(Math.random() * cards.length -1) + 1;
    var target2 = Math.floor(Math.random() * cards.length -1) +1;
    cards.eq(target).before(cards.eq(target2));
}
</script>
