<body>
<div id="gallery" >
   <img class="drawing" src="https://s2.loli.net/2022/08/05/tBJmQDA5ZOhMwN6.jpg" alt="Glendalough" title="Glendalough,Ireland &#10;2021-10-10">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/H4Zq6MD9hd7wkgQ.jpg" alt="MU" title="Maynooth,Ireland &#10;2021-9-12">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/cYulvI7krmn12ya.jpg" alt="The Royal Mile" title="Edinburgh,Scotland &#10;2020-1-30">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/xAWR8Xe4gUM7IPS.jpg" alt="Edinburgh Castle" title="Edinburgh,Scotland &#10;2020-1-30">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/JfoUqKOPHuWFnN8.jpg" alt="Powerscourt" title="Powerscourt Gardens,Ireland &#10;2021-10-29">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/r9hAQTGvE64BwP5.jpg" alt="Graduation" title="Xiamen,China &#10;2018-10-30">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/3RTYpW59MEnldXU.jpg" alt="Fake football team" title="Howth,Dublin,Ireland &#10;2021-10-3">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/jWwxUTqFV4uty5J.jpg" alt="karaoke" title="Maynooth,Ireland &#10;2022-7-6">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/bD6HA9eVJdLimBq.jpg" alt="Temple Bar" title="Dublin,Ireland &#10;2021-9-14">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/4BbEZHVXPnpR1Fz.jpg" alt="Giant's Causeway " title="Belfast,Northern Ireland &#10;2021-12-28">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/3AQkP51TOZflueh.jpg" alt="Wat Chedi Luang" title="Chiang Mai,Thailand &#10;2018-4-22">
   <img class="drawing" src="https://s2.loli.net/2022/08/05/NtnoiAk4RE18G9Z.jpg" alt="Kota Kinabalu" title="Kota Kinabalu,Malaysia &#10;2019-3-4">
   <img class="drawing" src="https://s2.loli.net/2022/08/12/62EAdIxlRFvyV3K.jpg" alt="Belfast" title="Belfast,Northern Ireland &#10;2021-12-27">
   <img class="drawing" src="https://s2.loli.net/2022/09/10/RE3dk5TcOgrhGIK.jpg" alt="MU" title="Maynooth,Ireland &#10;2022-09-07">
   <img class="drawing" src="https://s2.loli.net/2022/09/10/q7E9BLHOIR2XFMP.jpg" alt="Dublin" title="Dublin, Ireland &#10;2021-09-18">
   <img class="drawing" src="https://s2.loli.net/2022/09/10/pBvVL6NEOQgrtTw.jpg" alt="MU" title="Maynooth,Ireland &#10;2022-09-07">
   <img class="drawing" src="https://s2.loli.net/2023/09/23/nY7jahmd2EClrJG.jpg" alt="Christmas" title="Katowice,Poland &#10;2022-11-27">
   <img class="drawing" src="https://s2.loli.net/2023/09/23/Zm4HAsa681OoEWz.jpg" alt="one day trip" title="Klodzko,Poland &#10;2023-02-05">
   <img class="drawing" src="https://s2.loli.net/2023/09/23/2QoUObd7cLMVI3A.jpg" alt="Puy de Dôme" title="Clermont-Ferrand,France &#10;2023-02-19">
   <img class="drawing" src="https://s2.loli.net/2023/09/23/YKHrG2lthCAqW5J.jpg" alt="we were drunk" title="Wroclaw,Poland &#10;2023-02-19">   
   <img class="drawing" src="https://s2.loli.net/2023/09/23/hdyF5HmBGltsA3b.jpg" alt="color festival" title="Wroclaw,Poland &#10;2023-06-10">   
   <img class="drawing" src="https://s2.loli.net/2023/11/14/gCc7otbxYzTeLJy.jpg" alt="poland independence day" title="Wroclaw,Poland &#10;2023-11-11">
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
    transition: filter 0.5s;
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
			background-attachment: scroll;
			background-position: center;
			background-color: rgba(52, 52, 52, 0.8);
			background-size: 60%;
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
