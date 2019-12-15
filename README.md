<html>
<head>
    <title>Sarah CV</title>
	<link href="css/styles.css" rel="stylesheet" type="text/css" media="screen"/>
    <meta charset="utf-8" />
    <meta http-equiv="Content-type" content="text/html; charset=utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
	
	<!-- Project name: HTML web page - CV
	     Course: Web Application Development
		 Student name: Sarah Sarač
		 Faculty: IUS, Software engineering
		 Due date: 27.10.2019
		 Purpose: Learn basics of HTML
	-->
   <style>
#wrapper	{ width:100%; margin:0px auto; background-image:url('bl.jpg')}
#top	{ background-color:black; width:100%;overflow:hidden;
   		border-bottom:1px #eeeeee solid;	}
#name { margin:0 0 0 10px; float:left; color:white;	}
#social-media { float:right; margin:0 10px 0 0; 	}
#social-media p { color:white; font-size:18px; margin:4px 10px 4px 0px; }
#social-media img { width:30px; height: 30px; }
#social-media ul li { display:inline; }

#banner	{ width:100%;	}
#subbanner    { width:100%; height:20%; background-color:black; padding:3px 0; overflow:hidden;}
#subbanner h3 { color:#ffffff; font-size:24px; font-weight:bold; text-align:center; line-height:50%;}


#topnav { background-color:black; clear:both;	}
#topnav ul { width:100%; float:left; margin:0px; background-color:black;
			border-bottom:3px #cccccc solid; text-align:center; }
#topnav ul li { display:inline; text-align:center;}
#topnav ul li a { float:left; padding:10px 20px; text-align:center;}


#topnav a:link { color:#ffffff;}
#topnav a:visited { color:#ffffff;}
#topnav a:active { color:#ffffff;}
#topnav a:hover { color:#ffffff; background-color:#666666;}
#topnav a:focus { color:#ffffff;}

#info{ width:100%; display:inline-block; background-color:#CCCCFF}
#info p { margin-left:15%; margin-right:15%; font-family:"Informal Roman"; font-size:30px; text-align:justify; display:inline-block;}
#info h4 { margin-left:30%; margin-right:30%;}
#info h3{ margin-left:30%; margin-right:30%; font-size:50px; font-family:"Informal Roman";}
#info ul li{ margin-left:15%; margin-right:15%; font-family:"Informal Roman"; font-size:20px; text-align:justify;}

#education { width:100%; height:50%;background-color :#CCCCFF}
#education h4 { font-size:50px; text-align:center; font-family:"Informal Roman";
}
#education table,th,td{ border:1px solid black; background-color:#EEEEEE
}
#education table { width:100%; border-collapse:collapse;
}
#education th,td{ height:50%; padding:15px; text-align:center; font-family:"Informal Roman"; font-size:20px

}

#intership { width:100%; background-color:#CCCCFF;
}
#intership h4 { text-align:center; font-size:50px; font-family:"Informal Roman";
}
#intership p { text-align:center; font-size:30px; font-family:"Informal Roman";
}


#footer { clear:both;padding:1px 0; background-color:white; margin-left:10%; margin-right:10%}
#footer p { text-align:left; color:black; font-size:20px; margin-left:10px;}


.submit {
	width:90px; height:25px; margin-left:150px; font-size:12px;
}
#footer h4 { font-size:50px; text-align:center;
}

#footer input[type=submit]{
  width: 97%;
  padding: 8px 16px;
  margin: 8px 10px;
  box-sizing: border-box;
  display:inline-block;
  color:white;
  background-color:#33CC33;
  
}
#footer select{
	width: 97%;
  		padding: 8px 16px;
  		margin: 8px 10px;
 	    box-sizing: border-box;
 	    background-color:#666666;
 	    text-align:center;
 	    color:white;
 	    border-radius:5px;
}
#footer input[type=text] {
  width: 97%;
  padding: 8px 16px;
  margin: 8px 10px;
  box-sizing: border-box;
  border: 2px solid black;
  border-radius: 4px;
  color:white;
}

#repository { height:20%; width:100%; background-color:black;
}
#repository p { font-size:20px; text-align:center; color: white;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

</style
   <body>

	<div id="wrapper">

	<div id="top">
		<div id="name">
			<h1>CV:Sarah Sarač</h1>
		</div>
		
		<div id="social-media">
			<p>Contact me on:</p>	
			<ul>
				<li><a href="https://www.facebook.com/sarah.sary.56"><img src="fb2.png"/></a></li>
				<li><a href="https://www.instagram.com/yashm.m/?hl=hr"> <img src="ig2.png"/></a></li>
			</ul>
		</div>
	</div>
	
	<div id="topnav">
		<ul>
			<li><a href="#info">BASIC INFORMATIONS</a></li>
			<li><a href="#education">EDUCATION</a></li>
			<li><a href="#intership">INTERSHIP AND EXPERIENCE</a></li>
			<li><a href="#footer">CONTACT</a></li>			
		</ul>
	</div>


	<div id="banner" style="width: 100%; height: 100%">
	<div class="slideshow-container">
		<div class="mySlides1 fade">
		<img src="sarajevo.jpg" style="width:100%"/>
		</div>
		<div class="mySlides1 fade">
		<img src="sarajevo2.jpg" style="width:100%"/>
		</div>
		<div class="mySlides1 fade">
		<img src="sarajevo3.jpg" style="width:100%"/>
	</div>
	</div>
	<script>
	var slideIndex = 0;
	showSlides();

	function showSlides() {
  	var i;
  	var slides = document.getElementsByClassName("mySlides1");
  
  	for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  	}
  	slideIndex++;
  	if (slideIndex > slides.length) {slideIndex = 1}    
  
  	slides[slideIndex-1].style.display = "block";  
  
  	setTimeout(showSlides, 3500); // Change image every 2 seconds
	}
	</script>
	</div>
	<div id="subbanner">
		<h3>WELCOME TO MY PAGE!</h3>
	</div>

  
   
   <div id="info">
   <h3>BASIC INFORMATIONS </h3>
   <h4><img src="sarah.jpg" title="Sarah"></h4>
   <p>My name is <strong>Sarah</strong> and I am 21 years old. I am born in <ins>Sarajevo</ins> in BiH where I live today. I graduated from <a href="http://www.bosnjackagim.edu.ba">
   First Bosniak High School </a> as one of the best students of the year.
   <br> Currently I am third year student of <em>Sofware Engineering</em> at <a href="https://www.ius.edu.ba/bs"> International University of Sarajevo </a> with full scholarship. 
   I am interested in web page developing and game industry. <br>I speak three languages: English, Turkish and German.
    I have been training volleyball for 5 years while I was in Primary and High School. <br>
	 </p>
  	<hr>
	</div>
	
	<div id="education">
   <h4>Education</h4>
   <table>
		<tr>
			<th> Date </th>
			<th> Total years </th>
			<th> Institution </th>
			<th> Education level </th>
			<th> Section </th>
		</tr>
		<tr>
			<td> 2004. - 2013. </td>
			<td> 9 years </td>
			<td> Alija Nametak </td>
			<td> Primary School </td>
			<td> General </td>
		</tr>
		<tr>
			<td> 2013. - 2017. </td>
			<td> 4 years </td>
			<td> First Bosniak High School </td>
			<td> High School </td>
			<td> Mathematics</td>
		</tr>
		<tr>
			<td> 2017. - now </td>
			<td> 3 years</td>
			<td> International University of Sarajevo</td>
			<td> University</td>
			<td> Software Engineering</td>
		</tr>
   </table>
   <hr>
   </div>
   
   <div id="intership">
   <h4> Intership and experience </h4>
   <p> I am currently looking for intership in my department but I have done a lot of web pages for some companies so far from home. 
   I worked in <a href="http://www.cinemacity.ba"> Cinema City </a> and volontired for Crveni Križ Sarajevo. </p> 
   </div>
   	
<div id="footer">
	<p>
	<h4>Contact me!</h4>
   <form>
		
		<p>Full Name:</p><br/>
		<input type="text" name="name"/><br/>
		
		<p>Email adress:</p><br/>
		<input type="text" name="mail"/><br/>
		
		<p>Do you already now me?</p><br/>
		<select name="persons">
		<option>Yes</option>
		<option>No</option>
				</select>

		
		<p>Phone number:</p><br/>
		<input type="text" name="number"/><br/><br/>
						
				
		<input type="submit" value="CONTACT NOW"/>
		
		</form>	
	</div>

<div id="repository">
 	<p>You can use the following link to access my first webpage were I used only HTML: 
 	<a href="https://yashmm.github.io/CV/"> First Progress </a> </p>
	<p>You can use the following link to access my  
		<a href="https://github.com/Yashmm/CV"> Repository 1 </a> </p>
	<p>You can use the following link to access my second webpage were I used HTML with CSS: 
 	<a href="https://yashmm.github.io/Sarah/"> Second Progress </a> </p>
	<p>You can use the following link to access my 
		<a href="https://github.com/Yashmm/Sarah"> Repository 2 </a> </p>
	<p><p>You can use the following link to access 
 	<a href="https://yashmm.github.com/Yashmm/yashmm"> Repository 3 </a> </p>
 	</div>

   
</body>
</html>
