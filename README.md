# Project Responsive Web Design using Bootstrap
## Date: 10.05.24

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :

Developed By : Meenu.S
Register No. : 212223230124
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" 
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        a{
            text-decoration: none;
            text-align: center;
            color: wheat;
            font-size: 15px;
            padding: 15px;
            font-weight: bold;
        }
        a:hover{
            color: lightskyblue;
        }
        #h{
            color: goldenrod;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 30px;
            padding: 10px;
            text-align: left;
        }
        h6{
            text-align: center;
            font-family: 'Times New Roman', Times, serif;
        }
        
    </style>
</head>
<body style="background-image: url(bg1.jpg);background-repeat: no-repeat;background-size:cover;">
    <div class="d-flex align-items-center" style="background-color: black;">
          <img src="D.png" alt="" style="width: 150px;height: 150px;border-radius: 50%;">
          <h1 id="h"><b>DREAM<br>DEVELOPERS</b></h1>
          <a href="home.html" style="padding-left: 200px;">HOME</a>
          <a href="people.html">PEOPLE</a>
          <a href="product.html">PRODUCTS</a>
          <a href="contact.html">CONTACT</a>
          <div style="padding-left: 240px;">
          <nav class="navbar bg-body-tertiary">
            <div class="container-fluid">
              <form class="d-flex" role="search">
                <input class="form-control me-2" type="search" placeholder="Enter to Search" aria-label="Search">
                <button class="btn btn-primary" type="submit">Search</button>
              </form>
            </div>
           </div>
        </nav>
    </div>
    <div class="my-5 d-flex align-items-center">
        <div class="card" style="width: 18rem;margin: 5%;margin-top: 0%;">
            <img src="CSD.png" class="card-img-top" alt="">
            <div class="card-body">
              <p class="card-text"><b>Custom software development</b> allows companies to ensure that their software
             solutions meet their needs and deliver the best results, whether by introducing automation into
             their working processes or validating and developing an idea for a new product that will give
             them a competitive edge in the market.</p>
            </div>
          </div>
          <div class="card" style="width: 18rem;margin: 5%;margin-top: 0%;">
            <img src="WD.jpg" class="card-img-top" alt="">
            <div class="card-body">
              <p class="card-text"><b>Web development</b> services contain the full range of activities necessary
              to build a web solution, be it a simple website or a complex, unique solution. Web development 
              includes everything from creating the code to hosting, optimising and maintaining web pages.</p>
            </div>
          </div>
          <div class="card" style="width: 18rem;margin: 5%;margin-top: 0%;">
            <img src="MAD.jpg" class="card-img-top" alt="">
            <div class="card-body">
              <p class="card-text">From a business standpoint, <b>Mobile Application Development</b> is often seen 
                as a way to reach new customers or markets. For example, mobile apps can be used by retailers 
                to provide customers with a better version of the brand's website and improve the in-store 
                shopping experience.</p>
            </div>
          </div>
          <div class="card" style="width: 18rem;margin: 5%;margin-top: 0%;">
            <img src="Cloud.jpg" class="card-img-top" alt="">
            <div class="card-body">
              <p class="card-text">The process of developing software applications that are designed to run 
                in the cloud is known as <b>Cloud Software Development</b>. It involves using cloud computing 
                services and platforms to develop, test and manage software applications.</p>
            </div>
          </div>
    </div>
    <div class="fixed-bottom" style="background-color: lightskyblue;color: navy;">
        <h6>Designed & Developed by MEENU.S © 2024</h6>
    </div>
</body>
</html>
~~~
## OUTPUT:

![image](https://github.com/Meenu2823/Pharma/assets/139416219/59ffcd51-d20a-4094-996a-a5c18eb3f30a)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
