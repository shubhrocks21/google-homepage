# Responsive-cv
It is for responsive CV by HTML &amp; CSS 
<html>
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE-edge">
        <meta name="viewport" content="width=device-width,initial-scale=1.0"> 
        <link href="https://fonts.googleapis.com/css2?family=Norican&family=Roboto:wght@300&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
             integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous" />
        <link rel="stylesheet" href="style.css" />
        <title>Resume</title>
        <style>
            /*{
                width: 100%;
            }*/
            body{
                background-image:url( 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPpHMwuO0LG4SNW58VMvftYy5s0Ia-d4aw-g&usqp=CAU')
            }
            .background{
                color: white;
                display: flex;
                justify-content: space-evenly;
                padding: 2%;
            }
            @media only screen and(min-width:500px){
                
                
            }
            .name{
                 margin-left: 115px;
                 color: white;
                  margin-top: 81px;
                  font-family: system-ui;
                 font-size: 19px;
                 width: 75%;
                 float: left;
            }
            .image{
                width: 25%;
                height: 50%;
                float: right;
                border-radius: 3%;
                border: 1px solid;
                margin-right: 39px;
                box-shadow: 2px 2px 15px #f7f2f2;
            }
        </style>
    </head>
    <body>
        <div class="background">
                <div style="padding-left:40% ;"> Home </div>
                <div> About </div>
                <div> Skills </div>
                <div> Experiences </div> 
                <div> Portfolio </div>
                <div> Pricing </div>
                <div> Blog </div>
                <div> Contact </div>
            </div>
            <div>
                <div class="name">
                    <img class="image"src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS92eisuWOx3tEjeW14mT9ACVgXDwIRBGtnww&usqp=CAU">
                    <h4>Hello I'm</h4>
                    <h1 style="margin-bottom: 0px;">shubham jani</h1>
                    <h3 style="margin-top: 0px;">Web Developer</h3>
                    <label> <i style="margin-top: 37px; margin-right: 12px;" class="fas fa-envelope"></i> jani.shubham21@gmail.com</label><br>
                    <label> <i style="margin-top: 15px; margin-right: 9px;" class="fas fa-phone-alt"></i>   6263797493</label><br>
                    <label><i style="margin-top: 15px; margin-right: 9px;" class="fas fa-map-marker-alt"></i> shubham jani</label><br>

                </div>
                   
            </div>
                
        </div>
    </body>
</html>
