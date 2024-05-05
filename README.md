# Ex.07 Software Product Company Website
## Date: 05/05/24

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
~~~
home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:rgb(125, 205, 151);
            color:#054122;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:45%;
        }
        a{
            color:#007cb9;
            text-decoration: none;
        }
        a:hover{
            color:yellow;
            cursor:pointer;
 }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
      
        .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: rgb(16, 18, 17);
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:rgb(126, 219, 235);
        
        }
        .heading1{
            color:#592de9;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:#f4eef5;
            text-align: justify;
            font-size: 30px;
            margin-left: 30px;
        }
        .edge{
            padding-left: 900px;
            border-radius: 5px;
        }
        .box{
            text-align: center;
            
        }
 p{
            color:#d4176c;
            text-align: center;
        }
    
        .bottomdiv{
 background-color:rgb(125, 205, 151);
            color:#007cb9;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 105px;

        }
        table{
            margin-left: 40px;
            
        }
    </style>
</head>
<body background="c:\Users\admin\Pictures\Screenshots\background.png">
    <div class="header">
        <nav id="nav">
            <h1>
                ACCENTURE
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="employee.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="Contact.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
" TOGETHER WE REIN>ENTED "         
Every day we embrace change and 
create value for all our stakeholders,
 in every part of the world.<b></i></pre></div>
        <div class="edge">
            <div class="box">
            <h1 class="heading1">LOGIN HERE</h1>
            <br>
            <br>
            <form>
                <table cellpadding="15px" cellspacing="15px">
                    <tr>
                        <td>
                           <p> Username:</p>
                        </td>
                        <td>
                            <input type="email" name="name" placeholder="Enter a Email">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <p> Password:</p>
                        </td>
                        <td>
                            <input type="password" name="pwd" placeholder="Enter a Password">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" value="LOGIN" style="background-color: purple; color:white;">
                        </td>
                    </tr>
                </table>
                
            </form>
            </div>
        </div>
    <div class="bottomdiv">
        <p> Developed by DHANUSYA K (212223230043)</p>
    </div>
</body>
<html>
~~~
~~~
product.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>product</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(125, 205, 155);
            color:#05512a;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#05512a;
        }
        li:hover{
            color:rgb(199, 215, 72);
            cursor:pointer;
        }
 input{
            width: 18%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:rgb(7, 58, 9);
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:rgb(125, 205, 155);
            cursor:pointer;
        }
        a{
            color:#05512a;
            text-decoration: none;
        }
        a:hover{
            color:rgb(199, 215, 72);
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#eaeaf4;
        }
      p{
            color:#090807;
            text-align: center;
        }
   b{
            width: 300px;
            height: 200px;
        }
    h1{
            color:#074b29;
            text-align: center;
        }
        .bottomdiv{
 background-color:rgb(125, 205, 155);
            color:#05521a;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 230px;

        }
    </style>
</head>
<body background="c:\Users\admin\Pictures\Screenshots\background.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">ACCENTURE</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="employee.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
               <b><img src="c:\Users\admin\Pictures\Screenshots\1.png" ></b>
                <h1>CASE STUDY</h1>
                <p>Creating five-star associate experiences: Marriott International
                    Accenture and Marriot International created a new global HR hub that delivers employee experiences.</p>
            </div>
            <div class="box">
                <img src="c:\Users\admin\Pictures\Screenshots\2.png">
                <h1>RESEARCH REPORT</h1>
                <p>Reinvention in the age of generative AI
                    Five imperatives the C-suite must address to reinvent in the age of generative AI.</p>
            </div>
            <div class="box">
                <img src="c:\Users\admin\Pictures\Screenshots\3.png">
                <h1>CASE STUDY</h1>
                <p>Generative AI in the driver's seat: BMW
                    Accenture and BMW teamed up to create a new platform that uses generative AI to drive decisions.</p>
            </div>
        </div>
    </div>
    <div class="bottomdiv">
        <b> Developed by DHANUSYA K (212223230043) </b>
    </div>
</body>
</html>
~~~
~~~
employee.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>employees</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(125, 205, 155);
            color:#00521a;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#00521a;
        }
        li:hover{
            color:#00521a;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:#0d0f0d;
text-decoration: none;
        }
        a:hover{
            color:#00521a;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#ecf3ee;
        }
        .bottomdiv{
            background-color:rgb(125, 205, 155);
            color:#00521a;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 0.7px;

        }
        img{
            border-radius: 50%;
            width: 200px;
            display: inline;
            padding:3px;
            
        }
        .person{
            margin:100px;
            text-align: center;
        }
        b,p{
            color:#f4f2f2;
            text-align: center;
        }
      
</style>
</head>
<body background="c:\Users\admin\Pictures\Screenshots\background.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">ACCENTURE</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="employee.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">EMPLOYEES</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-05-05 155157.png" class="MyPic">
                </td>
		

                <td>
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-05-05 155305.png" class="cofoundar">
                </td>
		
                <td>
                   <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-05-05 155320.png" class="cofoundar">
                </td>
                <td>
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-05-05 155329.png" class="PV Sindhu">
                </td>
                <td>
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-05-05 155337.png" class="Sania Nehwal">
                </td>
            </tr>
            <tr>
                <td>
                    <b>Virat Kohli</b>
                    <p>CEO</p>
                </td>
                <td>
                    <b>MS Dhoni</b>
                    <p>Co-Founder</p>
                </td>
                <td>
                    <b>Dinesh Karthik</b>
                    <p>CTO,Co-Founder</p>
                </td>
                <td>
                    <b>Shreyas Iyer</b>
                    <p>Director</p>
                </td>
                <td>
                    <b>Rohit Sharma</b>
                    <p>Asst.Director</p>
                </td>
              
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
<p> Developed by DHANUSYA K (212223230043)</p>
    </div>
</body>
</html>
~~~
~~~
contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contact</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(162, 231, 245);
            color:#013a48;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#120f0f;
  }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:rgb(246, 238, 238);
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:rgb(6, 9, 8);
            cursor:pointer;
        }
        a{
            color:b#111212;
            text-decoration: none;
        }
        a:hover{
color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#ada7a5;
        }
        .table1{
            color:rgb(245, 241, 241);
            font-size: large;
        }
        .contactus{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color:#0f0e0f;
        }
        .table2{
            color:#050a07;
            font-size: large;
            background-color:rgb(116, 221, 239);
            border-radius: 5px;
            border-style:dotted;
            border-color: rgb(9, 67, 31);

        }
        .queries{
            margin-left:600px;
        }
        .bottomdiv{
            background-color:rgb(125, 188, 205);
            color:#0c0c0c;
            text-align: center;
            position:relative;
display:block;
            margin-top: 24px;

        }
    </style>
</head>
<body background="c:\Users\admin\Pictures\Screenshots\background.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">ACCENTURE</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="employee.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contactus">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    <td>
                        K.K.Nagar, Anna main road, chennai-600078
</td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        chennai
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        accentureweb@gamil.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        8428454444
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h3 class="heading3">QUERIES</h3>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
 NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter your name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter your E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            MESSAGE :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter your text">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" style="background-color: white; color:#007cb9;">
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p> Developed by DHANUSYA K (212223230043) </p>
        </div>
    </div>
</body>
</html>
~~~

## OUTPUT:
![Screenshot 2024-05-05 161438](https://github.com/Dhanu654/softweb/assets/148514965/21f84d16-20c1-4b8a-bd86-fb3649cbd10e)
![Screenshot 2024-05-05 161505](https://github.com/Dhanu654/softweb/assets/148514965/778d69e8-a3eb-4d12-b827-c6d2290f2dc6)
![Screenshot 2024-05-05 161604](https://github.com/Dhanu654/softweb/assets/148514965/169a5f6e-f3f1-4db6-8d7e-c1f8652360ee)
![Screenshot 2024-05-05 161724](https://github.com/Dhanu654/softweb/assets/148514965/7925e8dd-0274-4ced-a8e9-1f12892f71ff)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
