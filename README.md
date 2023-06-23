<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <link rel="stylesheet" href="checkout.css">
</head>
<body>
<h2>Checkout Form</h2>

<p>plese free to pay with any payment cards</p>
<div class="row"> 
    <div class="col-74">
        <div class="container">
            <form action="action_pag.php">
<div class="row">
<div class="col-50">
<h3>Billing Address</h3>

<label for="fname"><i class="fa fa-user" ></i>Full Name</label>
<input type="text" id="fname" name="firstname" placeholder="andy">

<br>
<label for="Email"><i class="fa fa-envelope" ></i>Email</label>
<input type="text" id="email" name="Email" placeholder="andy@poquee.com">
<br>
<label for="Address"><i class="fa fa-address-card-o" ></i>Address</label>
<input type="text" id="ddress" name="address" placeholder="kigali 744 ST">
<br>

<label for="ciyt"><i class="fa fa-institution" ></i>city</label>
<input type="text" id="city" name="city" placeholder="KIGALI">

<div class="row">
<div class="col-50">
<label for="zip">zip</label>
<input type="text" id="zip" name="zip" placeholder="250">
</div>
</div>
</div>
<div class="clo-50">
<h3>Payment</h3>
<label for="fname">ALL CARDS ARE ACCEPTED</label>
<div class="icon-container">
    <i class="fa fa-cc-visa" style="color: navy"></i>
    <i class="fa fa-cc-amex" style="color: blue"></i>
    <i class="fa fa-cc-mastercard" style="color: red"></i>
    <i class="fa fa-cc-discover" style="color: orange"></i>
</div>
<br>
<label for="cname">Name on card</label>
<input type="text" id="cname" name="cardname" placeholder="andy poquee">
<br>
<label for="ccnum">card number</label>
<input type="text" id="ccnum" name="carnumber" placeholder=" 1111 - 3333 - 5555 - 9999">
<br>
<label for="expmonth">Exp month</label>
<input type="text" id="expmonth" name="expmonth" placeholder="May">
<br>
<div class="row">
<div class="col-50">
<label for="expyear">exp year</label>
<input type="text" id="expyear" name="expyear" placeholder="2023">
</div>
<br>
<div class="col-50">

<label for="cvv">CVV</label>
<input type="text" id="cvv" name="cvv" placeholder="213">
<br>
</div>
</div>
<div>
</div>

<label>
<input type="checkbox" checked="checked" name="andy">
andy Shipping billing address

</label>

<input type="submit" value="continue to check" class="btn">

</form>
</div>
</div>
<div class="col-50">
<div class="container">
<h4>cart <span class="price" style="color: black"> <i class="fa fa-shopping-cart"></i></b>4</span> </h4>
<p> <a href="#">product 1</a> <span class="price">$200</span></p>
<p> <a href="#">product 2</a> <span class="price">$300</span></p>
<p> <a href="#">product 3</a> <span class="price">$400</span></p>
<p> <a href="#">product 4</a> <span class="price">$500</span></p>
<button>submit</button>
<hr>
<p>Total <span class="price" style="color: black"> <b>$1200</b></span> </p>
<button>submit</button>
    </div>
</div>
</div>

</div>
</div>
</body>
</html>



body{
    font-family: Arial;
    font-size: 15px;
    padding: 7px;

}

*{
box-sizing: border-box;

}

.row{
    display: -ms-flexbox;
    display: flex;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    margin: 8px;

}

.col-25{
-ms-flex: 50%;
flex: 50%;
}
.col-50{
-ms-flex: 50%;
flex: 50%;
}

.col-75{
    -ms-flex: 75%;
    flex: 75%;
}

.col-25,
.col-50,
.col-75{

background-color: #f2f2f2;
padding: 5px 20px 15px 20;
border: 2px solid lightgray;
border-radius: 2px;

}

.container{
    background-color: #f2f2f2;
    padding: 5px 20px 15px 20;
    border: 5px solid lightgray;
    border-radius: 3px;

}

input[type=text]{
width: 100%;
margin-bottom: 10px;
padding: 2px;
border: 1px solid #ccc;
border-radius: 3px;
}

label{
margin-bottom: 10px;
display: block;

}

.icon-container{

margin-bottom: 20px;
padding: 7px 0;
font-size: 24px;

}

.btn{
background-color: #04AA6D; 
color: wheat;
padding: 11PX;
margin: 10PX 0;
width: 100%;
border: none;   
border-radius: 3PX;
cursor: pointer;
font-size: 17px;
}

.btn:hover{

background-color: #45a049;

}

a{
color: #2196F3;
}

hr{
border: 1px solid lightslategray ;


}

span.price{

    float: right;
    color: grey;
}

@media (max-width: 800px){
.row{
flex-direction: column-reverse;
}
.col-25{
 margin-bottom: 20px;
}

}
