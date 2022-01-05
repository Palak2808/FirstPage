# FirstPage
It is a code to create a first page for a website which includes a login form.




<!DOCTYPE html>
<html>
<head>
    <title>FirstPage</title>
    <style>
        .navbar {
            background-color: #0D167B;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            display: flex;
            flex-direction: row;
            justify-content: center;
            padding: 20px;
            border: 2px solid #0D167B;
            border-radius: 50px;
        }

        .navbar a {
            text-decoration: none;
            color: white;
            font-size: 20px;
            margin: 5px 30px;
        }
        body {
            background-color: #FDFBE8;
        }
        .container {
            background-color: #FFF4D4;
            margin-left: 530px;
            margin-top: 15px;
            padding: 10px;
            display: inline-flex;
            flex-direction: column;
            border:1px solid black;
        }
        .container:hover{
            border:2px solid black;
        }
       input[type=text],select{
             width: 400px;
             height:30px;
             border:1px solid black;
             border-radius: 5px;
       }
       input[type=email]{
             width: 400px;
             height:30px;
             border:1px solid black;
             border-radius: 5px;
       }
       input[type=number]{
            width: 400px;
             height:30px;
             border:1px solid black;
             border-radius: 5px;
       }
         button{
            width: 410px;
             height:40px;
             margin-top: 15px;
             background-color: #002FB2;
             color:white;
             border-radius: 20px;
       }

    </style>
</head>

<body>
    <nav class="navbar">
        <a href="project.html">Home</a>
        <a href="room.html">Rooms</a>
        <a href="contact.html">Contact us</a>
        <a href="#">About us</a>
        <a href="blog.html">Blog</a>
    </nav>
    <div class="container">
        <h3 align="center">Login</h3> 
        <div class="username">
          <h3>Username</h3>  
         <input type="text" placeholder="Your username..">
         <h3>Email-id</h3>
         <input type="email" placeholder="Your email address..">
         <h3>Adhar Card Number</h3>
         <input type ="number"  placeholder="Adhar Card Number..">
         <h3>Mobile number</h3>
         <input type="number" id="number" placeholder="Mobile number..">
         <h3>Country</h3>
         <input type="text"  placeholder="Your Country..">
         
        </div>
        <div><button>Submit</button></div>
        

    </div>

</body>

</html>
