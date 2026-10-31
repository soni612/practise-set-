# practise-set-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Form</title>
    <style>
        *{
            margin: 0px;
            padding: 0px;
        }
        body{
            background-image: url('https://plus.unsplash.com/premium_photo-1667927477995-bc148fa9e3d7?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D');
            background-repeat: no-repeat;
            background-size: cover;
        }
        .container{
            background-color: bisque;
            height: 450px;
            width: 800px;
            margin-left: 300px;
            margin-top: 35px;
            border-radius: 15px;
            display: flex;
            flex-direction: row;
            gap: 10px;
        }
        .navbar{
            height: 50px;
            /* background-color: brown; */
            margin-top: 20px;
        }
        a{
            margin: 110px;
            text-decoration: none;
           color:black;
           font-size: 18px;
        }
        .box{
            height: 440px;
            width: 395px;
            /* background-color: pink; */
            /* border: 2px solid black;   */
        }
        #text>h1{
            margin:40px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; 
        }
        #text>p{
             margin-left: 40px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; 
        }
        
        .btn{
            margin-left: 40px;
            
        }
        
        .button{
            background-color: red;
            padding: 5px;
            border: none;
            font-family:Georgia, 'Times New Roman', Times, serif;
            border-radius: 5px;

        }
        .button:hover{
            background-color:rgb(229, 188, 138);
            font-size: 15px;
            border: 1px solid black;
        }
        #img>img{
            height: 300px;
            width: 300px;
            border-radius:50%;
            margin: 50px;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <a href="">About us</a>
        <a href="https://i.pinimg.com/1200x/d3/44/d4/d344d4d71ce7e44caf9250d6b611ec48.jpg">Menu</a>
        <a href="">Reviews</a>
        <a href="">Contacts</a>
        <a href="">Shop</a>    
    </div>
    <div class="container">
        <div class="box" id="text">
            <h1>Taste the tradition,<br>served fresh daily</h1>
            <p>Where authentic taste meets modern dinning- experience freshness,tradition,and a touch of luxury in every meal.</p>
            <br>
            <div class="btn">
                <button id="order" class="button">Order now</button>   
                <button id="book" class="button">Book now</button>
            </div>
        </div>
        <div class="box" id="img">
            <img src="https://plus.unsplash.com/premium_photo-1673108852141-e8c3c22a4a22?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D" alt="">

        </div>
    </div>
</body>
</html>
