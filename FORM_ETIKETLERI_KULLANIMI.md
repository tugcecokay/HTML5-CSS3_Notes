###FORM ETİKETLERİ KULLANIMI

 - datalist :

		<input list="tarayicilar">
		<datalist id="tarayicilar">
		<option value="IE 8"></option>
		<option value="Firefox"></option>
		<option value="Chrome"></option>
		<option value="Opera"></option>
		<option value="Safari"></option>
	</datalist>
	
 - keygen:
 
	 	<form action="demo_keygen.asp" method="get">
 				 Username: <input type="text" name="usr_name">
  				 Encryption: <keygen name="security"></keygen><input type="submit"></form>

 - output :

		<form oninput="x.value=parseInt(a.value)+parseInt(b.value)">0
				<input type="range" id="a" value="50">100
				+<input type="number" id="b" value="50">
				=<output name="x" for="a b"></output>
				</form>

###YAPISAL ETİKETLER KULLANIMI

 - article ve header
	
		<article>
 				 <header>
   					 <h1>Most important heading here</h1>
   					 <h3>Less important heading here</h3>
   					 <p>Some additional information here.</p>
 				 </header>
 			 <p>Lorem Ipsum dolor set amet....</p>
			</article>
			
 
 -  section:
		
		<section>
 				 <h1>WWF</h1>
  				<p>The World Wide Fund for Nature (WWF) is an international organization working on issues regarding the conservation, research and restoration of the environment, formerly named the World Wildlife Fund. WWF was founded in 1961.</p>
			</section>

 - aside:
			
			<aside>
				 <h4>Epcot Center</h4>
 				 <p>The Epcot Center is a theme park in Disney World, Florida.</p>
			</aside>

 
 - nav :
		
		<nav>
				<a href="/html/">HTML</a> |
				<a href="/css/">CSS</a> |
				<a href="/js/">JavaScript</a> |
				<a href="/jquery/">jQuery</a>
			</nav>


 - figure :

			<figure>![The Pulpit Rock](img_pulpit.jpg)<figcaption> The Pulpit Rock </figcaption></figure>

 - footer :
 
			<footer>
			  <p>Posted by: Tuğçe Çokay</p>
			  <p>Contact information: <a href="mailto:tugcecokay@gmail.com">someone@example.com</a>.</p>
			</footer>
			

####YAPISAL OLMAYAN ANLAMSAL ETİKETLER KULLANIMI

 - bdi :

				*   User <bdi>hrefs</bdi>: 60 points
				*   User <bdi>jdoe</bdi>: 80 points
				*   User <bdi>إيان</bdi>: 90 points

 - details ve summary :

			<details><summary>Copyright 1999-2014.</summary>- by Refsnes Data. All Rights Reserved.All content and graphics on this web site are the property of the company Refsnes Data.</details>

 - dialog :
			
			<div><dialog>This is an open dialog window</dialog></div>

 - mark :
			
				<p>Do not forget to <mark>smile</mark> today :).</p>

 - progress:

			Downloading progress:<progress value="22" max="100"></progress>
	
 - meter:
			
			Display a gauge:<meter value="2" min="0" max="10">2 out of 10</meter><meter value="0.6">60%</meter>
 - time :
			
				We open at <time>10:00</time> every morning. I have a date on <time datetime="2008-02-14 20:00">Valentines day</time>.
	
 - wbr:
			
			This is a veryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryvery<wbr>longwordthatwillbreakatspecific<wbr>placeswhenthebrowserwindowisresized.
