<!DOCTYPE html>
<html>
<head>
	<title>Product</title>
	<link rel="stylesheet" type="text/css" href="mystyle.css">
	<link href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300" rel="stylesheet" type='text/css'>
	<link href="https://fonts.googleapis.com/css?family=Muli" rel="stylesheet" type='text/css'>
</head>
<body>
    <div class="holder">
		<h3>Step 1: Your details</h3>
			<div class="gen_in">
				<p>Name</p> <input type="text" name="name" placeholder="first and last name">
			</div>
			<div class="gen_in">
				<p>Email</p> <input type="text" name="email" placeholder="example@domain.com">
			</div>
			<div class="gen_in">
				<p>Phone</p> <input type="text" name="phone" placeholder="e.g. +447500000000">
			</div>

		<h3>Step 2: Delivery address</h3>
			<div class="gen_in">
				<p>Address</p><br> <textarea placeholder="Billing Address"></textarea>
			<div class="gen_in">
				<p>Post code</p> <input type="text" name="Post Code"  placeholder="Billing Zip Code">
			</div>
			<div class="gen_in">
				<p>Country</p> <input type="text" name="Country" placeholder="country">
			</div>

		<h3>Step 3: Card details</h3>
			<div class="gen_pay">
				<p>Card Type</p>
				<form id="cards">
				  <input type="radio" name="card" value="visa" checked> <img src="visa.png"> </input>
				  <input type="radio" name="card" value="amex"> <img src="amex.png"> </input>
				  <input type="radio" name="card" value="master"> <img src="Mastercard-logo-2016-640x455.png"> </input>
				</form> 
			</div>
			<div class="gen_in">
				<p>Card number</p> <input type="text" name="card" placeholder="card number">
			</div>
			<div class="gen_in">
				<p>Security code</p> <input type="text" name="sec_code" placeholder="security code">
			</div>
			<div class="gen_in">
				<p>Name on card</p> <input type="text" name="card_name" placeholder="Name on the Card">
			</div>
		<br/>
		<input type="submit" name="submit" value="BUY IT!">
	</div>
</body>
</html>
