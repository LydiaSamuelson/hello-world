<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Lydia Samuelson</title>
<link type="text/css" href="https://github.com/LydiaSamuelson/style.css.git" rel="stylesheet">
</head>
<style> 
	body{
	background-color: #687864;
	color: #F7F9FB;
	margin: 3%;
	font-family: Lucidia, Georgia, Times, Arial ;}
	
header{background-color: #31708E;
		text-align: center;
		}
#navigation{
	padding: .5em;
	font-size: 2em;
	margin: 0;
	}
		
a:link {color: #8FC1E3;
		text-decoration: none;}
a:visited {color: #8FC1E3;}
a:hover {color: #F7F9FB;}

img{
	max-width: 40%;
	margin: 2%;
	padding: 0;}
	
.center{
	display: block;
	margin-left: auto;
	margin-right: auto;
	max-width: 60%;
	}
	
main{
	margin: 0.5rem;
	padding: 1rem;
	border: 2px solid #F7F9FB;}

div.transbox {
	background-color: #5085A5;
	padding: 0.5 rem;
	}
	
.pad {padding: 0rem 3rem .5rem 3rem;}
p{ padding: 0.5em;}

.padie {padding: 0rem 2rem .5rem 2rem;}

/*why does .pad not want to work for the resume half?*/

h2, h3, dl {padding: 0.5rem 2rem 0rem 0.5rem;}

h1 {padding: 1rem;
	font-size: 3em;
	margin: 0;}
	

#copyright {font-style: italic;
			font-size: .75em;
			margin: 2%;
			padding: ;}

span{float: right;}

.ref {
		display: flex;
		justify-content: space-between;
		}
		
/*is there a way to leave a designated amount of space between flex items? 
Does that come down to original padding again?*/
			
@media screen and (min-width: 40em) {
#about { 
		display: grid;
			grid:
				[top-line] "pic about" auto
				[second-line] "contact what" auto
				/[pic] auto [about] auto;
				grid-gap: 10px;}
			#uno {grid-area: pic;}
			#dos {grid-area: contact;}
			#tres {grid-area: about;}
			#quatro {grid-area: what;}
	.center {
			padding: 0rem;
			min-height: auto;
			min-width: 100%;}
			}
	
@media screen and (min-width: 55em) {
	#layout {
		display: grid;
			grid:
				[top-line] "education skills" auto
				[second-line] "we oe" auto
				[third-line] "rh references" auto
				/[education] auto [skills] auto;
				grid-gap: 10px;}
			#one {grid-area: education;}
			#two {grid-area: skills;}
			#three {grid-area: references;}
			#four {grid-area: we;}
			#five {grid-area: oe;}
			#six {grid-area: rh;}
			#tres {grid-area: about;
				font-size: 1em;}
			}
@media screen and (min-width: 80em){
	#layout {
		display: grid;
		grid:
			[top-line] "education skills references" auto
			[second-line] "we oe rh" auto
			/[education] auto [we] auto [skills] auto;
			grid-gap: 10px;}
		#one {grid-area: education;}
		#two {grid-area: skills;}
		#three {grid-area: references;}
		#four {grid-area: we;}
		#five {grid-area: oe;}
		#six {grid-area: rh;}
		#quatro {grid-area: what;
				font-size: 1.5em;}
		#tres {grid-area: about;
				font-size: 1.5em;}
	}
@media (prefers-color-scheme: dark) {
		body {
			background-image: radial-gradient(farthest-side at right bottom, #CB2D6F,
			#501F3A 50%, #0F292f);
			color: #ccc;}
		header, div.transbox {
			background-color: rgba(0, 0, 0, 0.3);}
		main { border: 2px solid #ccc;}
		a:link {color: #CB2D6F;
		text-decoration: none;}
		a:visited {color: #14A098;}
		a:hover {color: #501F3A;}
	}
		
</style>
<body>

<header>

<h1>Lydia Samuelson</h1>

<p id="navigation">
	<a href="index.html" alt="home page">About</a> | 
	<a href="resume.html" alt="resume">Resume</a>
	</p>
	
</header>

<main>
<div id="about">
<picture id="uno">
	<source
		srcset="images/darkmode.jpg"
		media="(prefers-color-scheme: dark)">
	<img src="images/portrait.jpeg" alt="Lydia Samuelson" class="center">
</picture>

	<div class="transbox" id="dos">	
<h2 class="pad">Contact</h2>
<p class="pad">
	Barton Hall, Anders<br>
	285 Richardson Ct. Room 171<br>
	Ames, IA 50013-0023<br>
	<br>(515) 421-2447<br>
	<br><a href="mailto:lydiasam@iastate.edu">lydiasam@iastate.edu</a>
</p>
	</div>
	
	<div class="transbox" id="tres">
<h2 class="pad">About</h2>
<p class="pad">Lydia Samuelson is an English and Technical Communications major from Des Moines, IA.
She aims for a balanced education. While she has a heart for English, her passion is 
forging connections between what she knows and what she has yet to learn. She feels 
Technical Communications is a way to diversify her learning while synthesizing 
information to help others.</p>
<p class="pad">In her free time, Lydia enjoys hiking, crafting with pyrography and polymer clay, 
reading, and writing. Her thirst for learning has led her to pick up many tricks and 
hobbies (such as knife-throwing and beekeeping), and she is always on the lookout 
for more.</p>
	</div>
	
	<div class="transbox" id="quatro">
<h2 class="pad">What I’m Doing</h2>
<p class="pad">Lydia is currently a junior with plans to extend her education through
graduate school, specifically the MFA in Creative Writing and Environment at Iowa State 
University. Her goal is to leave ISU with a book published, experience in editing, 
and the skills to educate others.</p>
<p class="pad">Outside of class, Lydia is active in many extracurriculars. She acts as 
President of Barton Anders Honors House to plan community events and improvements. 
In Sketch Literary Journal, Lydia is the non-fiction board editor as well as a 
fiction board member. Recently, she has taken up the task of exploring the many 
hidden corners of the ISU campus. Her greatest discovery is a German math textbook 
from 1812.</p>
	</div>
	</div>
</main>

<p id="copyright">Copyright &copy; 2021 by Lydia Samuelson. All rights reserved.</p>

</body>
</html>
