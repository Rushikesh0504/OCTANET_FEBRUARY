<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Page title</title>
    <style>
        nav{
           display:flex;
           height:90px;
           width: 100%;
           position:sticky;
           z-index: 99;
           top: 0;
           left: 0;
           box-shadow: 0 6px 31px -2px rgba(0, 0, 0, 0.1);
           }
        .top_img{
            height: 140px;
            width: 300px;
            border-radius:50%;
            border-top:8px solid #F4BB44;
            border-bottom:8px solid #FF8830;
           }
           .link{
                text-decoration:none;
                margin-left:50px;
                margin-top:25px;
                font-size:40px;
                color:#F4BB44;
               }
            .link:hover{
                color:black;
               border-bottom:2px solid black;
                border-radius:10px;
            }
            
            .main_img{
                display:flex;
                position: absolute;
                top:130px;
                left:110px;
                height: 800px;
                width: 850px;
                
             } 
             h1{
                 display:flex;
                 position: absolute;
                 top:49vh;
                 left:50px;
                 font-size:9em;
                 color:rgb(58,91,11);
                 font-style:bold;
                 }
                 
           h3{
               display:flex;
                 position: absolute;
                 top:85vh;
                 left:50px;
                 font-size:5em;
                color: rgba(0, 3, 0, 0.5);
                 
                  font-weight: 600;
           }
           .button{
               display:flex;
               position:absolute;
               top:125vh;
               left:55px;
               font-size:40px;
               text-align: center;
               padding: 20px 10px;
               background-color:pink;
               margin-top:70px;
               border:2px solid green;
               border-radius: 0.4rem;
               font-size: 40px;
               box-shadow: 0 10px 20px rgba(0, 0, 0, 0.19), 0 6px 6px rgba(0, 0, 0, 0.23);
           }
           .button:hover{
               background-color:#D0FFBC
           }
           footer{
           background-color:white;
           margin:50px;
           position: absolute;
           bottom: -60vh;
           font-size:40px;
           margin-left:100px;
           
           }
           footer a{
               
               text-decoration:none;
               border-bottom:5px solid black;
               background-color:#FDFD96;
               margin:2px;
           }
           h6{
               font-size:40px
           }
           
           
        </style>
</head>
        <body>
           <nav>
            <a href="#"> <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSr8x7iBX7fY3Mb0A13tlUHGtUd_HbLNlGr6g&usqp=CAU" alt="" class="top_img"></a>
       <a href="#" class="link">About</a>
       <a href="#"class="link">services<a>
       <a href="#" class="link">contact us</a>
        </nav>
    
    <div class="main"> 
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS9xGaELhWr1Z8qXz2k0fcRdb2wqVJG9KmbIg&usqp=CAU " alt="" class="main_img">
        
        <h1> FRESH,<br> JUICY, <br>HEAVENLY.</h1>
        <h3> 100% Organic, luscious varieties of mangoes nurtured in Ratnagiri, renowned as The Gem of the Konkan. </h3>
        </div>
        <button class="button">BUY NOW</button>
       <footer>
      Contact to 
      <a href="mailto:rushikeshdhenge5@gmail.com">Rushikesh Nilesh Dhenge
      </a>
     <br><h6>&copy copyright protected!!</h6>
    </footer>
</body>
</html>
