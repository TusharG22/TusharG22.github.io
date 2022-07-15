<!DOCTYPE html>
<html>
    <head>
        <title>Portfolio Website</title>
        <link rel="stylesheet" type="text/css" href="stylesheet.css">

        <link rel="preconnect" href="https://fonts.gstatic.com">
        <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100;0
        ,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=
        swap" rel="stylesheet">

        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" 
        integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous"
         referrerpolicy="no-referrer" />

    </head>
    <body>
        <!---hero Section start-->
        <div class="hero">
            <nav>
                <h2 class="logo">Port<span>folio<span></span></h2>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#Aboutme">About Me</a></li>
                    <li><a href="#Services">Services</a></li>
                    <li><a href="#">Skills</a></li>
                    <li><a href="#Contact">Contact Me</a></li>
                </ul>
                <a href="https://www.youtube.com/channel/UCKJHgrlVHHQRNsqbOTU_q4Q" class="btn">Subscribe</a>
            </nav>

            <div class="content">
                <h4>Hello, my name is</h4>
                <h1>Tushar <span>Gaurav</span></h1>
                <h3>I'm a <span>Web Developer</span></h3>
                <div class="EMAIL">
                    <form>
                        <input type="email" name="email" id="mail" placeholder="Enter your Email">
                        <input type="submit" name="submit" value="Lets Start">
                    </form>
                </div>
            </div>
        </div>

        <!--About section start-->
        <a name="Aboutme"></a>
        <section class="about">
            <div class="main">
                <img src="imgpro/main2.png">
                <div class="about-text">
                    <h2>About Me</h2>
                    <h5>Student <span>& Developer</span></h5>
                    <p>Hey I am Tushar Gaurav. I am currently in my second year pursuing Btech in Computer Science from
                        VIT, Vellore. I am a member of TAG Club, VIT under technical domain. I am currently intersted in web development 
                        and game development. At present I know HTML and CSS only. My hobbies include playing sports and video games, watching movies, listening to music 
                        and sleeping(XD)!!  
                    </p>
                    <a href="https://www.linkedin.com/in/tushar-gaurav-7a74a5239/" class="button">Let's Connect</a>
                </div>
            </div>
        </section>

        <!--servive section start-->
        <a name="Services"></a>
        <div class="service">
            <div class="title">
                <h2>Dead Serious For</h2>
            </div>
            
            <div class="box">
                <div class="card">
                    <i class="fa-solid fa-bars"></i>
                    <h5>Web Development</h5>
                    <div class="pra">
                        <p>Noob Web Developer with the basic knowledge of HTML and CSS. Open to learning new tech stacks like React.js, Bootstrap and more.
                        </p>

                        <p style="text-align :center;">
                            <button>Read More</button> 
                         </p>
                    </div>
                </div>

                <div class="card">
                    <i class="fa-solid fa-users"></i>
                    <h5>Game Development</h5>
                    <div class="pra">
                        <p>A Rookie Game Developer. I have come up with a 3-D Character Controller & 2-D Classic Adventure Game. Check it out on my itch.
                        <p style="text-align :center;">
                            <button>Read More</button> 
                         </p>
                    </div>
                </div>

                <div class="card">
                    <i class="fa-solid fa-basketball"></i>
                    <h5>Dub Nation</h5>
                    <div class="pra">
                        <p>
                            An avid basketball enthusiast. My story with this sport starts from NBA 2k16 and today this love is for Golden State Warriors.
                        </p>

                        <p style="text-align :center;">
                        <button>Read More</button> 
                         </p>
                    </div>
                </div>

            </div>
        </div>


        <!--Contact Me-->
        <a name="Contact"></a>
        <div class="contact-me">
            <p>How did I do? Let me know by leaving a review.</p>
            <a href="https://docs.google.com/forms/d/e/1FAIpQLSdTV5RYSKqUBzHHPlqyW89Y2w15hCZfxqrxxnXLQlXYD8BNiA/viewform?usp=sf_link" class="button">Review</a>
        </div>

        <!--footer start-->
        <footer>
            <p>Tushar Gaurav</p>
            <p>Find Below the Links For my Social Media Accounts. Let's Connect : </p>
            <div class="social">
                <a href="https://www.instagram.com/tushar_gaurav_2201/"><i class="fa-brands fa-instagram"></i></a>
                <a href="https://www.facebook.com/tushar.gaurav.39589/"><i class="fa-brands fa-facebook-f"></i></a>
                <a href="https://www.linkedin.com/in/tushar-gaurav-7a74a5239/"><i class="fa-brands fa-linkedin-in"></i></a>
                <a href="https://www.youtube.com/channel/UCKJHgrlVHHQRNsqbOTU_q4Q"><i class="fa-brands fa-youtube"></i></a>
            </div>
            <p class="end">&copy; 2022 &bull; Tushar Gaurav</p>
        </footer>
    </body>
</html>

