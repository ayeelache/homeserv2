<!DOCTYPE html>
<!--notes-->
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Homeserv</title>
  <link rel="stylesheet" href="css/main.css">
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="js/main.css">
  <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
</head>
<body>
 <div class="container-fluid">
	<div class="grid"> 
		<div class="row">
			<div class="col-sm-12" align="center" ><img src="css/banner.png" style="width:100%;" border="0" alt="Null">
				<!--banner-image (stripes + logo)-->
			</div>
		</div>
		<div class="row">
			<div class="col-sm-12" align="right" style="background-color:orange;">
				<p><strong>69 walter road homeserv</strong></p></div>
		</div>
		<div class="row">
			<div class="col-sm-12" align="center"><img src="http://placehold.it/1200x300" style="width:100%;" border="0" alt="Null"><!--scrolling image from our collection-->
		</div>
		<div class="row">
			<div class="col-sm-12" align="right" style="background-color:orange;">
				<p><strong>watch dat tv</strong></p></div>
		</div>
		<div class="row">
			<div class="col-sm-3" align="center" style="background-color:red;">
				<img src="http://placehold.it/300x100" style="width:100%;" border="0" alt="Null">
				<h3>First</h3>
			</div>
			<div class="col-sm-3" align="center" style="background-color:purple;">
					<img src="http://placehold.it/300x100" style="width:100%;" border="0" alt="Null">
				<h3>Second</h3>
			</div>
			<div class="col-sm-3" align="center" style="background-color:yellow;">
					<img src="http://placehold.it/300x100" style="width:100%;" border="0" alt="Null">
				<h3>Third</h3>
			</div>
			<div class="col-sm-3" align="center" style="background-color:pink;">
					<img src="http://placehold.it/300x100" style="width:100%;" border="0" alt="Null">
				<h3>Fourth</h3>
		</div>
		<div class="row">
			<div class="col-sm-12" align="right" style="background-color:orange;">
				<p><strong>watch dat tv</strong></p></div>
		</div>
		<div class="row">
			<div class="col-sm-6" align="left" style="background-color:grey;">
				<h2>RSS Feed</h2>
			</div>
			<div class="col-sm-6" align="left" style="background-color:green;">
				<h2>Important Contacts</h2>
				<button class="accordion">Dr Danuta Young</button>
				<div class="panel">
				  <p>Muritai Health Centre<br>
					  04 562 7606<br>
					  149 Muritai Rd, Eastbourne, Lower Hutt</p>
				</div>
				<button class="accordion">Lesley Gummer, Midwife</button>
				<div class="panel">
				  <p>Mobile	+64-272558425<br>
					  Work	+64-45866851</p>
				</div>
				<button class="accordion">Jane and Charlie</button>
				<div class="panel">
				  <p>+64-63773524<br>
					  31 Edith Street, Masterton</p>
				</div>
				<button class="accordion">Carol</button>
				<div class="panel">
				  <p>Lorem ipsum...</p>
				</div>
				<button class="accordion">Megan</button>
				<div class="panel">
				  <p>Lorem ipsum...</p>
				</div>
				<button class="accordion">Lisa and Geoff</button>
				<div class="panel">
				  <p>Lorem ipsum...</p>
				</div>
			</div>
		</div>
		</div>
	</div>
  </div>
</div>
</body>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
    acc[i].onclick = function(){
        this.classList.toggle("active");
        this.nextElementSibling.classList.toggle("show");
  }
}
</script>
