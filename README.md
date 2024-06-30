# 401fullstack
#code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
            
        }
        .navbar {
            display: flex;
            justify-content: space-around;
            align-items: center;
            background-color: #333;
            padding: 10px;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            text-align: center;
        }
        .navbar a:hover {
            background-color: #ddd;
            color: black;
        }
        .content {
            padding: 20px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .gallery img {
            width: 100%;
            max-width: 200px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .food-item {
            flex: 1 1 calc(25% - 20px);
            background-color: #fff;
            margin: 10px;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .food-item img {
            width: 100%;
            border-bottom: 1px solid #ddd;
        }
        .food-item h3 {
            margin: 0;
            padding: 15px;
            background-color: #333;
            color: white;
        }
        .food-item p {
            padding: 0 15px 15px 15px;
        }
    </style>
</head>
<body>
    <div class="navbar" id="navbar">
        <a href="#home">Home</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </div>
    <div id="home" class="content">
        <h1>Welcome to Food Gallery</h1>
        <p>Explore our collection of delicious foods from around the world.</p>
    </div>
    <div id="gallery" class="content">
        <h1>Food Gallery</h1>
        <div class="gallery">
            <div class="food-item">
                <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2015/10/pizza-recipe-1.jpg" alt="Pizza">
                <h3>Pizza</h3>
                <p>A delicious dish made with a base of dough topped with cheese, tomatoes, and various other ingredients.</p>
            </div>
            <div class="food-item">
                <img src="https://t4.ftcdn.net/jpg/01/40/22/91/360_F_140229175_GLtXWJfCCo3f2BH469WpYaHGPXX3t54z.jpg" alt="Sushi">
                <h3>Sushi</h3>
                <p>A Japanese dish consisting of vinegar-flavored rice combined with various ingredients such as seafood, vegetables, and occasionally tropical fruits.</p>
            </div>
            <div class="food-item">
                <img src="https://assets.epicurious.com/photos/5c745a108918ee7ab68daf79/1:1/w_2560%2Cc_limit/Smashburger-recipe-120219.jpg" alt="Burger">
                <h3>Burger</h3>
                <p>A sandwich consisting of one or more cooked patties of ground meat, placed inside a sliced bread roll or bun.</p>
            </div>
            <div class="food-item">
                <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2023/05/red-sauce-pasta-recipe.jpg" alt="Pasta">
                <h3>Pasta</h3>
                <p>An Italian dish typically made from durum wheat dough, commonly served with a variety of sauces and ingredients.</p>
            </div>
            <div class="food-item">
                <img src="https://images.immediate.co.uk/production/volatile/sites/30/2014/05/Epic-summer-salad-hub-2646e6e.jpg?resize=768,574" alt="Salad">
                <h3>Salad</h3>
                <p>A dish consisting of mixed pieces of food, typically with at least one raw ingredient, often served with a dressing.</p>
            </div>
            <div class="food-item">
                <img src="https://static.tnn.in/thumb/msid-105675192,thumbsize-89532,width-1280,height-720,resizemode-75/105675192.jpg" alt="chicken biryani">
                <h3>Chicken Biryani</h3>
                <p>Biryani is a celebratory rice and meat dish cherished in the Indian sub-continent. A traditional biryani consists of fluffy basmati rice layered over tender & succulent pieces of meat, accompanied with the mesmerizing aromas of spices, herbs & caramelized onions.</p>
            </div>
        </div>
    </div>
    <div id="contact" class="content">
        <h1>Contact Us</h1>
        <p>Email: contact@foodgallery.com</p>
        <p>Phone: (123) 456-7890</p>
    </div>
</body>
</html>
