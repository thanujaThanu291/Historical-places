# Historical-places
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="external.css" rel="stylesheet">

    <!-- grid box -->
     <style>
        .a{grid-area: a1; }
        .b{grid-area: b1; }
        .c{grid-area: c1; }
        .d{grid-area: d1; }
        .e{grid-area: e1; }
        .maindiv{
            display: grid;
            grid-template-areas: 'a1 b1 c1'
            'd1 e1 f1' ;
            
            /* background-color: cadetblue;  */
            padding: 20px;
            margin: 20px;
            /* border-radius: 20px;
            box-shadow: 10px 10px 10px grey; */
            color: white;
            text-align: center;
            box-shadow: 10px 10px 10px;
            font-size: 30px;
            

        }
       .maindiv> div{
             background-color: white;  
            border: 1px solid;
            color: black; 
            margin: 20px;
            padding: 20px;
            border-radius: 50px;
             box-shadow: 10px 10px 10px grey ;
             width: 400px; 
             height: 460px;
            
        }
        img{
            border-radius: 20px;
            box-shadow: 10px 10px 10px;
        }
        p{
            text-align: left;
            font-size: 15px;
            
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
        body{
            background-color: rgb(246, 228, 238);
        }
        button{
            background-color:rgb(240, 175, 151) ;
            border: transparent;
            font-size: 20px;
            border-radius: 20px;
        }
     </style>
</head>
<body>
    <nav>
        <a> About</a>
        <a> Products</a>
        <a> Commitments</a>
        <a> Stories</a>
        <a> India Blog</a>
    </nav>
    <div class="maindiv">
        <div class="a">
            <img src="https://cdn.britannica.com/89/179589-138-3EE27C94/Overview-Great-Wall-of-China.jpg?w=800&h=450&c=crop" width="350px" height="200px">
            <p>Several walls were built from as early as the 7th century BC, with selective stretches later joined by Qin Shi Huang (220–206 BC), the first emperor of China. Little of the Qin wall remains. Later on, many successive dynasties built and maintained multiple stretches of border walls.
            </p>
            <button>Read More</button>
        </div>
        <div class="b">
         <img src="https://th-thumbnailer.cdn-si-edu.com/eBP1w0wGm1n7tZ4XtovPdnvxDOg=/800x800/filters:focal(1471x1061:1472x1062)/https://tf-cmsv2-smithsonianmag-media.s3.amazonaws.com/filer/b6/30/b630b48b-7344-4661-9264-186b70531bdc/istock-478831658.jpg" width="350px" height="200px">
                  <p>The Taj Mahal is an ivory-white marble mausoleum on the south bank of the Yamuna river in the Indian city of Agra. It was commissioned in 1632 by the Mughal emperor, Shah Jahan (reigned from 1628 to 1658), to house the tomb of his favourite wife, Mumtaz Mahal.
                </p>
                <button> Read More</button>
        </div>
        <div class="c">
            <img src="https://jdinstituteoffashiontechnology.b-cdn.net/wp-content/uploads/2024/01/redfort-770x400.jpg" width="350px" height="200px">
            <p>
                The Red Fort Complex was built as the palace fort of Shahjahanabad – the new capital of the fifth Mughal Emperor of India, Shah Jahan. Named for its massive enclosing walls of red sandstone, it is adjacent to an older fort, the Salimgarh, built by Islam Shah Suri in 1546, with which it forms the Red Fort Complex.</p>
                <button> Read More</button>
        </div>
        <div class="d">
            <img src="https://www.popradtatry.aero/wp-content/uploads/2024/09/web-banner.jpg" width="350px" height="200px">
            <p>Egypt eventually became one of the intellectual and cultural centres of the Arab and Islamic world, a status that was fortified in the mid-13th century when Mongol armies sacked Baghdad and ended the Abbasid caliphate. The Mamluk sultans of Egypt, under whom the country thrived for several centuries, established a pseudo-caliphate of dubious legitimacy. </p>
            <button>Read More</button>
        </div>
        <div class="e">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTgI8wQFO-dWhYvTqfYpQl3zl4qrK7qD6DDIQ&s" width="350px" height="200px">
            <p>Wonderla Amusement and Theme Park in Hyderabad is one of the top attractions for families and thrill-seekers alike. Known as one of the best water parks in the city, it offers over 43 exciting rides spread across four categories: High Thrill Rides, Water Rides, Family Rides, and Kids Rides.
            </p>
            <button>Read More</button>
        </div>
    </div>
</body>
</html>
