Hi!👋 I'm Wenjie(Clark) Hu, a recent computer science graduate from Maynooth University. I'm very interested in self-driving and data science, and most of my experience is in Python and its ecosystem of tools. Other than tech, I like playing table tennis, hiking and cultural exchange. I currently live in Ireland.
<br>
<table rules="none" align="center">
	<tr>
		<td>
			<center>
			<div>
				<img class='drawing' src="https://s2.loli.net/2022/08/05/NasGkxwg14IbMyj.jpg" width="100%" />
				</div>
				<br/>
			</center>
		</td>
		<td>
			<center>
				<img class='drawing' src="https://s2.loli.net/2022/08/05/vdC7NzFZYmgtkJn.jpg" width="100%" />
				<br/>
			</center>
		</td>
	</tr>
</table>

***

# Work 
## Production Enginner at <u>WeRide</u>, Guangzhou,China [Mar 2021 - Aug 2021]
At [WeRide](https://www.weride.ai/en/), I worked as a test-developer responsible for data analysis and high-definition map related work. There, I touched the top-level of self-driving technology in the world.
<br>
<table rules="none" align="center">
	<tr>
		<td>
			<center>
			<div>
				<img class="drawing" src="https://s2.loli.net/2022/08/05/PQcuM6ZqbxJC8wG.jpg" width="100%" />
			</div>
				<br/>
			</center>
		</td>
		<td>
			<center>
			<div>
				<img class="drawing" src="https://s2.loli.net/2022/08/05/PESytRIedc6qNBw.jpg" width="100%" />
			</div>	
				<br/>
			</center>
		</td>
		<td>
			<center>
				<img class="drawing" src="https://s2.loli.net/2022/08/05/bM3qVNftOlKrYk2.jpg" width="100%" />
				<br/>
			</center>
		</td>            
	</tr>
</table>

## Test Enginner at <u>MoonX</u>, Shenzhen,China [Dec 2018 - Mar 2021]
During my time at [MoonX](https://www.weride.ai/en/muyue-en/), I worked closely with businesses and delivered self-driving vehicles to clients. I was also responsible for autonomous vehicle road testing and data analysis. I got my hands dirty in Cyber-RT, Linux, Python, and Docker and have comprehensive knowledge of autonomous driving systems.
<br>
<table rules="none" align="center">
	<tr>
		<td>
			<center>
			<div>
				<img class="drawing" src="https://s2.loli.net/2022/08/05/nlgXcvJ98KoSwrW.jpg" width="100%" />
			</div>
				<br/>
			</center>
		</td>
		<td>
			<center>
				<div>
				<img class="drawing" src="https://s2.loli.net/2022/08/05/hV2dcMH9g5GZIlK.jpg" width="100%" />
				</div>
				<br/>
			</center>
		</td>
	</tr>
</table>

***

# Education

## A Computer Science and Engineering graduate from Maynooth University, Ireland.

- I have accomplished a Natural Language Processing project using the Stanford Parser and NLTK packages.

***

# Contact
[wenjie.hoo@outlook.com](mailto:wenjie.hoo@outlook.com)

***

<style>
		*{
			margin: 0;
			padding: 0;
		}
		.drawing{
			width: 1000px;
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

<script src="./jquery-3.3.1.min.js"></script>
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
</script>