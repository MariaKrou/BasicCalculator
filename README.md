<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
</head>

<style>
.row1{
	width:200px;
	margin-left:20px;
}
</style>

<script>
$(document).ready(function(){

	$("#btn1").click(function(){
		var a1=$("#a").val()/1;
		var b1=$("#b").val()/1;
		//alert(a1);
		//alert(b1);
		c1=a1+b1;
		$("#c").val(c1);
	});
	
	
	$("#btn2").click(function(){
		var a1=$("#a").val()/1;
		var b1=$("#b").val()/1;
		c1=a1-b1;
		$("#c").val(c1);
	});
	
	$("#btn3").click(function(){
		var a1=$("#a").val()/1;
		var b1=$("#b").val()/1;
		c1=a1*b1;
		$("#c").val(c1);
	});
	
	$("#btn4").click(function(){
		var a1=$("#a").val()/1;
		var b1=$("#b").val()/1;
		c1=a1/b1;
		$("#c").val(c1);
	});
	
});
</script>

<body>
<br><br>
<div class="container-fluid">
	<label for="a">A:</label>
	<input type="number" id="a" value="0">
</div>
<br>
<div class="container-fluid">
	<label for="a">B:</label>
	<input type="number" id="b" value="0">
</div>
<br>
<div class="container-fluid">
	<div class="row row1">
		<div class="col-md-2">
			<button type="button" id="btn1">+</button>
		</div>
		<div class="col-md-2">
			<button type="button" id="btn2">-</button>
		</div>
		<div class="col-md-2">
			<button type="button" id="btn3">*</button>
		</div>
		<div class="col-md-2">
			<button type="button" id="btn4">/</button>
		</div>
	</div>
</div>
<br>
<div class="container-fluid">
	<label for="a">C:</label>
	<input type="number" id="c" disabled>
</div>
</body>
</html>
