<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Bites</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            background-color: white; 
            color: red;
            padding: 20px 0;
            text-align: center;
        }

        header img {
            max-width: 300px; /* Adjust the width as needed */
            max-height: 900px;
            margin: 10px auto;
            display: block;
        }

        header h1 {
            font-size: 2.5em;
            margin: 10px 0;
        }

        header p {
            font-size: 1.2em;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav a {
            color: white;
            padding: 15px 20px;
            text-decoration: none;
            font-size: 1.1em;
        }

        nav a:hover {
            background-color: #ff6f61;
        }

        .hero {
            background-image: url('https://scontent.fmnl13-1.fna.fbcdn.net/v/t39.30808-6/470231973_1119429223014991_3953652457905251637_n.jpg?stp=dst-jpg_s960x960_tt6&_nc_cat=104&ccb=1-7&_nc_sid=cc71e4&_nc_eui2=AeFfaspiS59S0gAv23CSBW8UrhFIPJn0ejmuEUg8mfR6OX1U24kz81bai7GTDfnJq4dVhFBNsFKctAfmi6boZsM1&_nc_ohc=-xY4E4ex2NUQ7kNvgFL5OOi&_nc_zt=23&_nc_ht=scontent.fmnl13-1.fna&_nc_gid=ACiy8doEWxOSqa3xY_fq2jX&oh=00_AYDRjI8bOPXNBHwc6Bw5frlIV5gcTYKDanzuxGlpJIoC3A&oe=676987AF');
            background-size: cover;
            background-position: center;
            color: red;
            text-align: center;
            padding: 80px 20px;
        }

        .hero h1 {
            font-size: 3.5em;
            margin: 0;
        }

        .hero p {
            font-size: 1.5em;
        }

        .menu {
            padding: 20px;
            text-align: center;
        }

        .menu h2 {
            margin-bottom: 20px;
            font-size: 2.5em;
            color: red;
        }

        .menu-item {
            display: inline-block;
            margin: 10px;
            width: 200px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
        }

        .menu-item img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }

        .menu-item h3 {
            margin: 10px 0 5px;
            font-size: 1.3em;
        }

        .menu-item p {
            margin: 0;
            color: red;
            font-size: 1.1em;
        }

        .contact {
            background-color: lightslategray;
            padding: 20px;
            text-align: center;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }

        @media (max-width: 768px) {
            .menu-item {
                width: 45%;
            }
        }

        @media (max-width: 480px) {
            .menu-item {
                width: 90%;
            }
        }
    </style>
</head>
<body>

    <header>
        <img src="http://www.parklanehotel.com.ph/wp-content/uploads/2017/03/manuel.png" alt="Manuel'sRestaurant">
        <h1>MANUEL'S RESTAURANT</h1>
        <p>Experience the taste of perfect spicy foods!</p>
    </header>

    <nav>
        <a href="#menu">MENU</a>
        <a href="#about">ABOUT US</a>
        <a href="#contact">CONTACT</a>
    </nav>

    <section class="hero">
        <h1>Welcome to Manuel's Restaurant</h1>
        <p>Where every meal is a masterpiece.</p>
    </section>

    <section id="menu" class="menu">
        <h2>OUR MENU</h2>

        <div class="menu-item">
            <img src="https://drivemehungry.com/wp-content/uploads/2019/07/szechuan-noodles-garlic-chili-oil-2.jpg">
            <h3>Szechuan Noodles</h3>
            <p>₱95.00</p>
        </div>

        <div class="menu-item">
            <img src="https://feelgoodfoodie.net/wp-content/uploads/2017/04/Ground-Beef-Tacos-9.jpg">
            <h3>Spicy Beef Tacos</h3>
            <p>₱85.00</p>
        </div>

        <div class="menu-item">
            <img src="https://www.koreanbapsang.com/wp-content/uploads/2014/03/DSC_5089.jpg">
            <h3>Kimchi Jjigae (Kimchi Stew)</h3>
            <p>₱115.00</p>
        </div>

        <div class="menu-item">
            <img src="https://i1.wp.com/www.evseats.com/wp-content/uploads/2017/09/Creamy-Cajun-Shrimp-and-Grits-7.jpg?w=2400">
            <h3>Spicy Shrimp and Grits</h3>
            <p>₱115.00</p>
        </div>

        <div class="menu-item">
            <img src="https://www.koreanbapsang.com/wp-content/uploads/2010/05/DSC5922-1026x1536.jpg">
            <h3>Spicy Pork Bulgogi</h3>
            <p>₱125.00</p>
        </div>

        <div class="menu-item">
            <img src="http://champagne-tastes.com/wp-content/uploads/2016/05/spicy-fish-tacos-small-1.jpg">
            <h3>Spicy Fish Tacos</h3>
            <p>₱95.00</p>
        </div>

        <div class="menu-item">
            <img src="https://www.queensleeappetit.com/wp-content/uploads/2020/05/Homemade-Lemon-Iced-Tea-recipe-queensleeappetit.com-3.jpg">
            <h3>Lemon Iced Tea</h3>
            <p>₱75.00</p>
        </div>

        <div class="menu-item">
            <img src="https://vintagekitty.com/wp-content/uploads/2020/07/Cucumber-Lemonade-7559-2-2000px-scaled.jpg">
            <h3>Lemon Cucumber Cooler</h3>
            <p>₱75.00</p>
        </div>

        <div class="menu-item">
            <img src="https://togetherasfamily.com/wp-content/uploads/2021/10/party-punch-2.jpg">
            <h3>Tropical Fruit Punch</h3>
            <p>₱75.00</p>
        </div>

        <div class="menu-item">
            <img src="https://www.thespruceeats.com/thmb/lkVq8tmD_olwmIunrMHsT7HSx2M=/1937x1547/filters:fill(auto,1)/GettyImages-88179070-5826aff03df78c6f6a67db50.jpg">
            <h3>Chocolate Banana Smoothie</h3>
            <p>₱75.00</p>
        </div>

        <div class="menu-item">
            <img src="http://www.ohhowcivilized.com/wp-content/uploads/2014/07/0714-matcha-milkshake-2.jpg">
            <h3>Matcha Milkshake</h3>
            <p>₱75.00</p>
        </div>
    </section>

    <section id="about" class="contact">
        <h2>ABOUT US</h2>
        <p>Manuel's Restaurant has been serving gourmet meals since 2027. Our passion for food and drink has made us a top choice for food lovers everywhere.</p>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Email: Manuel'sRestaurant.com</p>
        <p>Phone: 09069462191</p>
        <p>Address: San Emmanuel Crossing Road, Tacurong City</p>
    </section>

    <footer>
        <p>&copy; 2027 Manuel's Restaurant. All Rights Reserved.</p>
    </footer>

</body>
</html>
