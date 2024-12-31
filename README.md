# Rens 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" context="width=device-width, intial-scale=1.0">
    <title>My Personal Website</title>
    <style>
        body {
            background-image: url(image2.jpg);
            font-family:Arial, san-serif;
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            margin: 20px;
            padding: 0px;

    }
        header {
            display:flex;
            align-items: flex-end;
            justify-content: space-between;
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 24px;
            color: red;
            margin: 0;
        }
        header img {
            height: 100px; /*adjust height as needed */
            border-radius: 5px;
            box-shadow: 0 0 10px rgb(0, 0, 0, 0.1);

        }

        nav {
            background-color: rgba(248, 245, 245, 0.507);
            padding: 0px 0px;
            margin-bottom: 20px;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            align-items: center;
        }

        nav ul li {
            margin-left: 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: black;
            font-size: 18px;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: rgb(55, 0, 255);
        }

        nav ul li img {
            height: 40px; /* adjust this to your logo's size*/
            width: auto; /*keeps the aspect ratio*/
        }

        h2 {
            text-align: left;
            color: black;
        }

        /* Card Style */
        .card-container {
            display: flex;
            justify-content: space-between;
            gap: 20px;
            margin-top: 20px;
        }

        .card {
        background-color: rgba(255, 255, 255, 0.484);
        border-radius: 10px;
        box-shadow: 0 4px 6px black;
        width: 40%;
        padding: 15px 20px;
        color: rgba #d3d6e6
        } 

        .card h3 {
            font-size: 20px;
            margin-bottom: 20px;
        }

        .card p {
            font-size: 18px;
        }
            
    </style>
</head>
<body>
    <!-- Header Section with Flexbox -->
     <header>
        <marquee><h1>Welcome to my Personal Website!</h1></marquee>
     </header>

     <!-- Navigation Bar -->
      <nav> 
         <ul>
             <li><img src="rens.jpg" alt="Picture of me"/></li>
             <li><a href="Home rens.html"><h4>Home</h4></a></li>
             <li><a href="about me rens.html"><h4>About Me</h4></a></li>
             <li><a href="contact me rens.html"><h4>Contact Me</h4></a></li>
         </ul>
      </nav>

      <h2>Hello!</h2>
      <marquee scrollamount="5" direction="right"><img src="cow.gif" width="110" height="60" alt="gif"/></marquee>
    
      <!-- Cards Section -->
    <div class="card-container">
        <div class="card">
            <h3>The Story</h3>
            <p>Discover the life of Reinlly Italia Bajar, himself. Let's explore his story!</p>
            <img src="goo.gif" width="120" height="70" alt="gif"/>
        </div>
        <div class="card">
            <h3>About Me</h3>
            <p>Learn more about his personalities, stories, and hobbies. Discover what makes him special.</p>
            <img src="bee0.gif" width="130" height="80" alt="gif"/>
        </div>
        <div class="card">
            <h3>Contact Me</h3>
            <p>Get in touch with him for any questions and other informations about him. He is here to help you!</p>
            <img src="bird.gif" width="130" height="80" alt="gif"/>
        </div>
    </div>
    <marquee scrollamount="4" direction="left"><img src="zombie6.gif" width="130" height="70" alt="cute"></marquee>
    
</body>
</html>

