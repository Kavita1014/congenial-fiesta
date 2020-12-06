# congenial-fiesta
My First Web Design
<html lang="en">
    <head>
        <meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
        <style>
* {
  box-sizing: border-box;
}


body {
  font-family: Arial, Helvetica, sans-serif;
  background-color: white;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

h2 {
  background-color:white;
  padding: 10px 30px 10px 30px;
  text-align: left;
  font-size: 35px;
  color:aqua;
}
.demo{
    background-color:white;
  padding: 0px 30px 0px 30px;
  text-align: left;
  font-size: 16px;
  color:rgb(125, 235, 125); 
}
.jam{
    background-color:white;
  text-align: left;
  padding: 0px 30px 0px 30px;
  font-size: 16px;
  color:rgb(158, 158, 158);  
}
.left {
  background-color:aqua;
  padding:20px;
  float:left;
  width:50%; 
  color:white;
}
.right {
  background-color:#4CAF50;
  padding:20px;
  float:left;
  width:50%; 
  color:white;
}
@media screen and (max-width:800px) {
  .left, .right {
    width:100%; 
  }
}
  .button {
  background-color: hsl(120, 60%, 70%);
  color: white;
  padding: 16px 100px;
  text-align: center;
  font-size: 16px;
  margin: 4px 2px;
  transition: 0.3s;
  cursor: pointer;
  box-shadow: 10px 10px 5px grey;
}

        </style>
    </head>
    <body>

        <h2>
            Join Our Community
        </h2>
        <p class="demo"> 30-day, hassel-free money back guarantee </p>
        <p class="jam">gain access to our full library of tutorials along with expert code reviews.<br>
        perfect for any developers who are serious about honing their skills.</p>

        <div class="left">
    <h3>Monthly subscription</h3>
  <p style=height:126px><br>
  <b style=font-size:30px>$29</b> per month<br>
  full access for less than $1 a day<br>
  <button class="button">Sign Up</button>
  </p>
</div>

<div class="right">
    <h3>Why us</h3>
  <p>
  Tutorial by industry expert<br>
  Peer & expert code review<br>
  Coding excercise<br>
  Access to our Github repos<br>
  Community forum<br>
  Flashcard decks<br>
  New video every week
  </p>
</div>
    </body>
</html>
