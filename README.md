# Ex.07 Restaurant Website
# Date:27.11.2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Restaurant</title>
    <style>
        * {
            margin: 0px; 
            padding: 0px;  
            box-sizing: border-box;
        }  
        body {
            margin: 0;
            padding: 0;
        }
        .container {
            height: 100%;
            width: 100%;  
            background-color: rgb(133, 86, 86);  
            background-image: url('https://img.freepik.com/free-photo/golden-cutlery-with-textile-plate-dark-background-top-view_1220-6580.jpg');
            background-size: cover;  
            background-position: center;   
        }
        .nav-bar {  
            display: flex;  
            align-items: center;  
            justify-content: space-between;  
            padding: 30px 80px;
        }
        .nav-bar .title {
            color: #fff;
            font-size: 67px;
        }
        .nav-bar p {
            position: absolute;
            margin-top: 120px;
            margin-left: 50px;
            color: #fff;
            font-size: 20px;
            font-weight: 500;
        }
        .menu li {
            list-style: none;
            display: inline-block;
        }
        .menu li a {
            text-decoration: none;
            color: #fff;
            font-size: 27px;
            font-weight: 600;
            margin-left: 25px;
            transition: .4s ease;
        }
        .menu li a:hover {
            color: crimson;
            padding: 10px 20px;
            border: 2px solid #fff;
        }
        .home {
            height: 400px;
            padding: 70px;
        }
        .title-1 {
            font-size: 56px;
            color: #fff;
            font-weight: 600;
        }
        .home p {
            color: yellow;
            font-size: 25px;
            padding-top: 10px;
        }
        .card {
            background-image: url('https://img.freepik.com/free-photo/golden-cutlery-with-textile-plate-dark-background-top-view_1220-6580.jpg');
            background-size: cover;
            height:100%;
            max-width: 100%;
            margin: 1px;
            text-align: center;
            padding: 20px; 
        }
        .card h2{
            color:#fcf6f6;
        }
        .card-row {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .card-item {
            flex-basis: 30%;
            margin: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .card-item img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 10px 10px 0 0;
        }
        .card-item h3 {
            font-size: 18px;
            margin-top: 10px;
            color: #fcf6f6;
        }
        .card-item p {
            font-size: 14px;
            color: #fffcfc;
        }
        .card-item span {
            font-size: 16px;
            font-weight: bold;
            color: #fcf6f6;
        }
    </style>
</head>  
<body>  
    <div class="container"> 
        <div class="nav-bar">  
            <h1 class="title"> L’Angolo del Gusto</h1> 
            <p>The Corner of Taste</p>  
            <ul class="menu"> 
                <li><a href="#">HOME</a></li>  
                <li><a href="#">PRODUCT</a></li> 
                <li><a href="#">SERVICES</a></li>  
                <li><a href="#">CONTACT</a></li> 
                <li><a href="#">ABOUT</a></li>
            </ul>  
        </div>
        <div class="home">
            <h1 class="title-1">"Savor the Flavor, Taste the Tradition"<br></h1>
            <p>Where every meal is a celebration of flavor and togetherness.<br>Enjoy authentic dishes, warm hospitality, and unforgettable memories!<br>Buon appetito!</p>
            <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-05 155556.png" alt="Image Description" width="700" height="400">                                            <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-05 154930.png" width="600" height="400">
        </div>
    </div>
    <section class="card">
        <h2>Today's Specials</h2>
        <div class="card-row">
            <div class="card-item">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0b/RedDot_Burger.jpg/1200px-RedDot_Burger.jpg" alt="Burger">
                <h3>Burger Delight</h3>
                <p>Juicy beef patty, crispy bacon, melted cheddar, and caramelized onions.</p>
                <span>$12.99</span>
            </div>
            <div class="card-item">
                <img src="https://images.ctfassets.net/j8tkpy1gjhi5/5OvVmigx6VIUsyoKz1EHUs/b8173b7dcfbd6da341ce11bcebfa86ea/Salami-pizza-hero.jpg" alt="Pizza">
                <h3>Italian Pizza</h3>
                <p>Homemade crust, marinara sauce, mozzarella cheese, and fresh basil.</p>
                <span>$14.99</span>
            </div>
            <div class="card-item">
                <img src="https://images.immediate.co.uk/production/volatile/sites/30/2014/05/Epic-summer-salad-hub-2646e6e.jpg "alt="Salad">
                <h3>Fresh Garden Salad</h3>
                <p>Mixed greens, cherry tomatoes, cucumber, and balsamic vinaigrette.</p>
                <span>$8.99</span>
            </div>
            <div class="card-item">
                <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2021/12/orange-juice-recipe.jpg" alt="juice">
                <h3>Fresh Garden Salad</h3>
                <p>Mixed greens, cherry tomatoes, cucumber, and balsamic vinaigrette.</p>
                <span>$8.99</span>
            </div>
            <div class="card-item">
                <img src="https://cdn.apartmenttherapy.info/image/upload/f_jpg,q_auto:eco,c_fill,g_auto,w_1500,ar_1:1/k%2FPhoto%2FRecipes%2F2023-01-Caramelized-Tomato-Paste-Pasta%2F06-CARAMELIZED-TOMATO-PASTE-PASTA-039" alt="pasta">
                <h3>Fresh Garden Salad</h3>
                <p>Mixed greens, cherry tomatoes, cucumber, and balsamic vinaigrette.</p>
                <span>$8.99</span>
            </div>
            <div class="card-item">
                <img src="https://api.vip.foodnetwork.ca/wp-content/uploads/2022/03/tomato-egg-drop-soup-feat.jpg?w=3840&quality=75" alt="soup">
                <h3>Fresh Garden Salad</h3>
                <p>Mixed greens, cherry tomatoes, cucumber, and balsamic vinaigrette.</p>
                <span>$8.99</span>
            </div>
        </div>
    </section>
</body>
</html>
administation page
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - My Restaurant</title>
    <style>
     *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

body {
    font-family: Arial, sans-serif;
    background-image: url('https://img.freepik.com/free-photo/golden-cutlery-with-textile-plate-dark-background-top-view_1220-6580.jpg');
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #ffffff;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #99816d; 
}

main {
    padding: 40px 20px;
    text-align: center;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
}


.team {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 30px;
    justify-items: center;
    margin-top: 30px;
}

.member {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.member img {
    width: 100%;
    height: auto;
    border-radius: 50%;
    margin-bottom: 15px;
    border: 4px solid #f4a261; 
}

.member h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
    color: #333;
}

.member p {
    font-size: 1.1rem;
    color: #777;
}

.member:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

h3 {
    margin-bottom: 10px;
    font-size: 1.5rem;
    color: #333;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
    <header>
        <h1>Administration Team</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="admin.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Meet Our Team</h2>
        <div class="team">
            <div class="member">
                <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-14 102403.png" alt="Member 1">
                <h3>Jessie</h3>
                <p>CEO</p>
            </div>
            <div class="member">
                <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-14 101807.png" alt="Member 2">
                <h3>Jane<h3>
                <p>Marketing Manager</p>
            </div>
            <div class="member">
                <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-14 101847.png" alt="Member 3">
                <h3>Henry<h3>
                <p>Operations Manager</p>
            </div>
            <div class="member">
                <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-14 101917.png" alt="Member 4">
                <h3>Victor<h3>
                <p>HR Manager</p>
            </div>
            <div class="member">
                <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-14 101952.png"alt="Member 5">
                <h3>Thomas<h3>
                <p>Executive Chef</p>
            </div>
            <div class="member">
                <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-14 102232.png" alt="Member 6">
                <h3>Charles<h3>
                <p>Customer Service Manger</p>
            </div>
        </div>
    </main>
</body>
</html>
contact page
<body>
    <style>
    *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
  
  body {
    font-family: Arial, sans-serif;
    background-image: url(https://img.freepik.com/free-photo/vintage-old-rustic-cutlery-dark_1220-4886.jpg?t=st=1734152671~exp=1734156271~hmac=9b48fcfca0e1347ad01be238ff23b3220e9a0226cfcb15493b1591997718139c&w=1060);
    background-size: cover;
    background-position:center;
    color: #333;
  }
  #contact {
    background-color: #b5a7a7;
    padding: 80px 20px;
    margin: 200px auto;
    max-width: 600px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
  }
  
  #contact h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
  }
  
  #contact p {
    font-size: 1.2rem;
    margin-bottom: 20px;
    color: #555;
  }
  
  address {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #333;
  }
  
  address br {
    margin-bottom: 10px;
  }
  
  #contact:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
  }
    </style>
     <section id="contact">
    <h2>Contact Us</h2>
    <p>Visit us at:</p>
    <address>
      123 Main Street, Cityville, India
      <br>
      Phone: (123) 456-7890
      <br>
      Email: info@myrestaurant.com
    </address>
  </section>
  </body>
  </html>
```
# OUTPUT:
![Screenshot 2024-12-14 105246](https://github.com/user-attachments/assets/073a210f-d286-4965-a295-64d3d41d2d52)
![Screenshot 2024-12-05 163521](https://github.com/user-attachments/assets/3c155ef0-00c6-4e7b-8f4c-77b02ea8ea11)
![Screenshot 2024-12-14 104743](https://github.com/user-attachments/assets/54a236c4-3b4c-4aa0-821b-09c122ec9f18)
![Screenshot 2024-12-14 104643](https://github.com/user-attachments/assets/9985cc09-2bf5-4ffc-ac86-a46579e5bed4)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
