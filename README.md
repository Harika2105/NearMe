# Ex04 Places Around Me
## Date:26-11-2024 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html
<html>
    <head>
        <title>MY TOWN</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>VENKATAGIRI KOTA</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>S.HARIKA(24002063)</b></font>
        </h3>
<center>
    <img src="image.png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="FIVESTAR CHICKEN (KOLI HUT)" title="FIVESTAR CHICKEN (KOLI HUT)" href="Fivestar.html" coords="224,341,355,390" shape="rect">
        <area target="" alt="V.Kota High School (EM)" title="V.Kota High School (EM)" href="School.html" coords="140,289,241,335" shape="rect">
        <area target="" alt="KAREEM LODGE" title="KAREEM LODGE" href="Lodge.html" coords="518,390,638,420" shape="rect">
        <area target="" alt="Aanjaneyaswamy Temple" title="Aanjaneyaswamy Temple" href="Temple.html" coords="799,332,947,359" shape="rect">
        <area target="" alt="H.Ambalal Jewellers" title="H.Ambalal Jewellers" href="Jewellers.html" coords="1023,313,1154,356" shape="rect">
    </map>
</center>
 </body>
</html>

Fivestar.html
<html>
<body bgcolor="orange">
    <h1 align="center">
        <font  size="10" color="red">
            VENKATAGIRI KOTA
        </font>
    </h1>
    <h2 align="center">
        
        FIVESTAR CHICKEN (KOLI HUT)
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="Fivestar chicken.png" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                Five Star is a franchise that has achieved extraordinary success.
                Originating in 1985 within the vibrant streets of Thailand, precisely on Ladprao 80 Street,
                the brand embarked on an extraordinary journey that transformed it into a global powerhouse.
                
        </li>
        <br>
        <li>
            <font size="4">
                The Five-star manok franchise is owned and operated by one of the renowned companies in Thailand,
                CHAROEN POKPHAND FOODS or CPF is presently one of the biggest chicken producers in the Philippines.
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                Popular Chicken Retailers in Venkatagirikota, Chittoor ; Fivestar Chicken (Koli Hut). 
                4.2192 Ratings. Kgf Road venkatagirikota ; Haleem Chicken Center. 3.36 ...

 
            </font>
        </li>
    </h3>
</body>

</html>

School.html
<html>
<body bgcolor="orange">
    <h1 align="center">
        <font  size="10" color="red">
            VENKATAGIRI KOTA
        </font>
    </h1>
    <h2 align="center">
        
        V.Kota High School (EM)
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="v.kota high scl.png" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                V.KOTA EM PS, K G F ROAD, V.KOTA was established in 1996 and it is managed by the Pvt. Unaided.
                It is located in Rural area. It is located in V.KOTA block of CHITTOOR district of ANDHRA PRADESH.
        </li>
        <br>
        <li>
            <font size="4">
                The school consists of Grades from 1 to 5.
                The school is Co-educational and it doesn't have an attached pre-primary section. 
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                The school does not need ramp for disabled children to access classrooms.
                The school has no computers for teaching and learning purposes.
                The school is not having a computer aided learning lab. The school is Not Applicable providing mid-day meal.
                

            </font>
        </li>
    </h3>
</body>

</html>

Lodge.html
<html>
<body bgcolor="orange">
    <h1 align="center">
        <font  size="10" color="red">
            VENKATAGIRI KOTA
        </font>
    </h1>
    <h2 align="center">
        
        KAREEM LODGE
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="Kareem lodge.png" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                It stands located at Nh75, Venkatagirikota-517424.
                The business strives to make for a positive experience through its offerings.

        </li>
        <br>
        <li>
            <font size="4">
                Popular Lodging Services in Venkatagirikota, Chittoor · 
                Teja Lodge and Kalyana Mandapam · Kadatanayana Palli · C Sampangi Reddy · Sri Varasiddi Vinayaka Residency
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                The place is budget-friendly, with clean rooms and fresh, delicious food. 
                The online booking process was smooth, and the staff were courteous and accommodating.

 
            </font>
        </li>
    </h3>
</body>

</html>

Temple.html
<html>
<body bgcolor="orange">
    <h1 align="center">
        <font  size="10" color="red">
            VENKATAGIRI KOTA
        </font>
    </h1>
    <h2 align="center">
        
        Aanjaneyaswami Temple
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="Aanjaneyaswamy temple.png" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                Hanuman Temple in Gudupalle Venkatagirikota,Chittoor listed under Temples in Chittoor.
        </li>
        <br>
        <li>
            <font size="4">
                The temple was built in 1969 and was registered in the year 1972. 
                The total area of the temple is around 5 acres. “Sri Hanumajjayanthi” is celebrated for 12 days
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                Kote Anjaneya is a temple of Hanuman located in Tumkur, Karnataka.
                The temple has a 75 feet tall Hanuman statue at the entrance which was inaugurated in May 2005
            </font>
        </li>
    </h3>
</body>

</html>

Jewellwes.html
<html>
<body bgcolor="orange">
    <h1 align="center">
        <font  size="10" color="red">
            VENKATAGIRI KOTA
        </font>
    </h1>
    <h2 align="center">
        
        H.Ambalal Jewellers
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="Ambalal Jewellars.png" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                H.Ambalal Jewellers in Venkatagirikota,Chittoor listed under Jewellery Showrooms in Chittoor.
        </li>
        <br>
        <li>
            <font size="4">
                Good looking showroom with a nice ambience. Trustworthy with good quality gold and reasonable prices. 
                Vast collection of designs available in 18k, 22k and 24k ...

            </font>
        </li>
        <br>
        <li>
            <font size="4">
                Louis-Francois Cartier - Cartier
                Known as "the jewellers of kings and the king of jewellers", the brand was created in Paris in 1847 by Louis-Francois Cartier.
                 Louis-Francois Cartier was born into a poor working-class Parisian household in 1819.

 
            </font>
        </li>
    </h3>
</body>

</html>

```

## OUTPUT
![alt text](harika/mapapp/static/image.png)

![alt text](<harika/mapapp/static/Fivestar chicken.png>)
![alt text](<harika/mapapp/static/v.kota high scl.png>)
![alt text](<harika/mapapp/static/Kareem lodge.png>)
![alt text](<harika/mapapp/static/Aanjaneyaswamy temple.png>)
![alt text](<harika/mapapp/static/Ambalal Jewellars.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
