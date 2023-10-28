# cardmaking
This is a card project where I have used HTML and CSS.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercise 3</title>
    <style>
        *{
            margin: 0px;
            padding: 0px;
            box-sizing: border-box;
        }
        
         body{
            background-color: #d8cece;
            height: 100vh;
            width: 100vw;
            
            display: flex;
            align-items: center;
            justify-content: center;
             
        }  
        .card{
            border: 1.5px solid rgb(119, 117, 117);
            margin: 60px;
            background-color: #fff;
            border-radius: 15px;
            width: 320px;
            height: 540px;
            display: flex;
            justify-content: center;
            align-items: center;
            padding-left: 10px;
        }
        .img img{
            width: 290px;
            height: 290px;
            
            
            
            display: flex;
            flex-direction: column;
            
            align-items: center;
            border: 2px solid rgb(60, 54, 54);
            margin-bottom: 20px;
            margin-top: 10px;
        }
        .about{
            margin-left: 5px;
            margin-bottom: 15px;
        }

         
        
        .about span{
            
            
            background-color: rgb(253, 251, 251);
            cursor: pointer;
            border-radius: 10px;
            margin-left: 20px;
            
            align-items: center;
            padding: 4px 8px;
            
            
            border: 1px solid rgb(195, 188, 188);
        }
        
        .h1{
            padding-left: 30px;
            padding-top: 30px;
            padding-bottom: 30px;
        }
        .text{
            padding-top: 6px;
            padding-bottom: 12px;
            padding-left: 10px;
            
        }
        .foot{
            background-color: rgb(212, 212, 219);
            padding: 2px 20px 2px 20px ;
            margin-left: 35px;
            font-size: 10px;
            width: 50px;
            height: 20px;
            text-decoration: none;
            cursor:zoom-in;
            
            
            
        }
    </style>
</head>
<body>
    <!-- card.png is a file which contains a card Image.
    Write html and css code to design this card. Use #html -->
    <div class="card">
        <div class="img">
            
        <img   src="card.png" alt="Nature image">
        <div class="about">
            <span class="Nature">Nature</span>
            <span class="Lake">Lake</span>
        </div>
        <h1>Boby Kumari</h1>
        <p class="text">Boby Kumari is Student of B.Sc. IT who loves coding and want to become a good Web developer. Besides tech,
            She loves to travel and explore nature . She  wants to fly high in the open sky like an eagle. 
        </p>
        <a class="foot" href="#">Read More</a>
    </div>
    </div>

    
</body>
</html>
