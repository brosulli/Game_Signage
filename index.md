<!DOCTYPE html>
<html>
<head>
	<title>Green Park Apprenticeship Hub</title>
	<style type="text/css">
		img.resize {
		  max-width:40%;
		  max-height:40%;
		}
		@font-face {
			font-family: "CiscoSansTT";
			src: url(https://site.samhastings.co.uk/DigitalSignage/CiscoSansTT-ExtraLight.ttf);    
		}
		h1 {
			margin-bottom: -50px;
		}
		body {
			/* [typeface & colour] */
			font-family: CiscoSansTT;
			font-size: 50px;
			text-decoration: none;
			text-align: center;
			position: absolute;
			top: 50%;
			left: 50%;
			transform: translate(-50%, -50%);
			color: #FFFFFF;
			background-color: #00bceb;
			margin-bottom: 50px;

		}
		time {
			position: absolute;
			top: 0%;
			left: 100%;
			font-size: 30px;
			color: #00bceb;
			border-radius: 250px;
  			background: #FFFFFF;
  			padding: 20px; 
		}
		a {
			font-size: 30px;
			color: #FFFFFF;
			border-radius: 50px;
  			background: #6ebe4a;
  			padding: 20px;
			text-decoration: none;
		}
	</style>
	<script type="text/javascript" src="jquery-1.11.3.min.js"></script>
		<script type="text/javascript" src="https://www.google.com/jsapi"></script>
		<script type="text/javascript">
			function show( show1 ) {
			  document.getElementById(show1).style.display="block";
			}
			function hide( hide1 ) {
			  document.getElementById(hide1).style.display="none";
			}
			function tog( tog1 ) {
			  document.getElementById(tog1).style.backgroundColor="#777777";
			}
			function toh( toh1 ) {
			  document.getElementById(toh1).style.backgroundColor="#ffffff";
			}
		</script>
</head>
<body>
<img class="resize" src="https://site.samhastings.co.uk/DigitalSignage/logo.png" alt="Cisco Logo">
<h1>Welcome</h1>
<p>to the Green Park Apprenticeship Hub</p>
<br>
<table style="width:100%">
  <tr>
  	<td>
  		<a href="https://quickdraw.withgoogle.com/">Quick, Draw!</a>
  	</td>
  	<td>
  		<a href="https://trends.google.com/trends/">Trends</a>
  	</td>
  	<td>
  		<a href="https://geoguessr.com/world/play">GeoGuessr</a>
  	</td>
	<td>
  		<a href="http://www.kyberheimen.com/">More Games</a>
  	</td>
  </tr>
</table>
</body>
<time OnLoad="document.form1.q.focus();">	
			    <div class="time" id="time">
				    <script>
					    //document.getElementById("main").innerHTML = Date();
					    function updateClock() {
						    var m = new Date();
						    var dateString =
						      ("0" + m.getHours()).slice(-2) + ":" +
						      ("0" + m.getMinutes()).slice(-2);
						
						    // set the content of the element with the ID time to the formatted string
						    document.getElementById('time').innerHTML = dateString;
						    // call this function again in 1000ms
						    setTimeout(updateClock, 1000);
					    }
					    updateClock(); // initial call
			    	    </script>
			    </div>  
		</div>
	</time>
</html>
