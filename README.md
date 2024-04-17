https://eclectic-begonia-5a06fe.netlify.app/




<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recipe Page</title>
</head>
<body>
    <header>
        <div class="logo">Flavoursome Recipes</div>
        <div class="nav-bar">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="">Recipe</a></li>
                <li><a href="#">Categories</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>
    </header>
    <div class="hero">
        <div class="content">
            <h4>Unleash Your Culinary Passion</h4>
            <h1>Discover Taste Sensations</h1>
            <h3>Elevate Your Cooking Game</h3>
            <div class="button">Start Cooking</div>
        </div>
    </div>
    <!----About Section Start---------------------------------->
    <section class="about" style="background-color: green">
        <div class="main">
            <div class=".about-text">
                <h2>About Us</h2>
                <p>Welcome to our recipe website, where culinary inspiration meets delicious creations! Whether you're a
                    seasoned chef or a passionate home cook, we are here to ignite your taste buds and guide you on a
                    delightful culinary journey. Our extensive collection of recipes covers a wide rage of cuisines, from comfortion classics to innovtive fusion dishes. 
                    Each recipes is thoughtfully crafted,tested,and presented with step by step instructions.</p>

                    <h4 style="color: azure;">Quick Chicken Alfredo Pasta Recipe</h4>
                    <ul>
                        <li>1 lbs chicken</li> 
                        <li> Salt to taste </li>
                        <li>Paprika to taste </li>
                        <li>1 medium onion</l1>
                        <li>4 medium garlic cloves</li>
                        <li>12 oz jarred classic alfredo sauce </li>
                        <li>  Chicken boullion seasoning to taste</li>
                    </ul> 

            </div>
        </div>
        <h2>Follow the Video for More Intructions</h2>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/lAU-H7V8Up4?si=lRe8DD88Wcd5wslr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    
    </section>

    <!---------categories section-------------------------------->
    <div class="categories">
        <h2>categories</h2>
        <div class="box">
            <div class="ca-card">
                <img src="./img/lasagne-768x512.webp" alt="">
                <div class="content">
                    <h3>Main Courses</h3>
                    <p>Lorem ipsum dolor sit amet,consectetur adipiscing elit.</p>
                    <button>Read More</button>
                </div>
            </div>
            <div class="ca-card">
                <img src="./img/download (2).jpg" alt="">
                <div class="content">
                    <h3>Desserts</h3>
                    <p>Lorem ipsum dolor sit amet,consectetur adipiscing elit.</p>
                    <button>Read More</button>
                </div>
            </div>
            <div class="ca-card">
                <img src="./img/download (1).jpg" alt="">
                <div class="content">
                    <h3>Healthy Eats</h3>
                    <p>Lorem ipsum dolor sit amet,consectetur adipiscing elit.</p>
                    <button>Read More</button>
                </div>
            </div>
            <div class="ca-card">
                <img src="./img/images.jpg" alt="">
                <div class="content">
                    <h3>Baking</h3>
                    <p>Lorem ipsum dolor sit amet,consectetur adipiscing elit.</p>
                    <button>Read More</button>
                </div>
            </div>
        </div>
    </div>

    
      <!------------contact section-------------------------->
      <section class="contact">
        <div class="contact-info">
            <h2>Contact Information</h2>
            <p><strong>Address:</strong> 2405 Mothoa street, Dobsonville,Soweto,Gauteng</p>
            <p><strong>Phone:</strong>0640506929</p>
            <p><strong>Email:</strong>keitumetsekobo@gmail.com</p>
        </div>
        <div class="contact-form">
            <h2>Contact Form</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" name="name" id="name" required><br><br>
                <label for="email">Email:</label>
                <input type="email" name="email" id="email" required><br><br>
                <label for="message">Message:</label>
                <textarea name="message" id="message"  required></textarea><br><br>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>
<footer>
    <div class="social-icons">
        <a href="#" class="fa fa-facebook"></a>
        <a href="#" class="fa fa-twitter"></a>
    
    </div>
    <h5>KEITUMETSE © 2024 By Flavoursome Recipes </h5>
</footer>
        
 
</body>
</html>
