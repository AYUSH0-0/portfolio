# portfolio
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AYUSH - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@200;400&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(128, 15, 233);
            color: white;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;

        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(145, 51, 233);


        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            list-style: none;
            margin: 0 23px;

        }

        nav ul li a {
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {

            color: rgb(16, 16, 192);
            font-size: 1.02rem;
        }

        main hr {
            border: 0;
            background-color: blueviolet;
            height: 1.2px;
            margin: 60px 84px;
        }


        .left {
            font-size: 1.5rem;
        }

        .firstsection {
            display: flex;
            justify-content: space-around;
            margin: 135px 0;
            align-items: center;
        }

        .firstsection>div {
            width: 30%;
        }

        .leftsection {
            font-size: 3rem;

        }

        .leftsection .buttons {
            padding: 50px 0;
        }

        .leftsection .btn {
            padding: 12px;
            background-color: rgb(56, 231, 135);
            color: white;
            border: 2px solid white;
            border-radius: 6px;
            cursor: pointer;

        }

        .rightsection img {
            width: 70%;

        }

        .purple {
            color: rgb(13, 202, 108);
        }

        .text-gray {
            color: rgb(20, 20, 20);
        }

        #element {
            color: rgb(13, 202, 108);

        }

        .secondsection {
            max-width: 80vw;
            margin: auto;
            height: 80vh;
        }

        .secondsection h1 {
            font-size: 1.9rem;
        }

        .secondsection .box {
            background-color: white;
            width: 60vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondsection .vertical {
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 190px;

        }

        .image-top {
            width: 34px;
            position: relative;
            top: -32px;
            left: -9;
        }

        .vertical-title {
            position: relative;
            top: 75px;
            width: 150px;
            font-size: 14px;

        }

        .vertical-desc {
            position: relative;
            top: 86px;
            color: rgb(14, 13, 13);
            width: 150px;
            font: 9px;

        }

        .footer {
            background-color: rgb(25, 25, 26);


        }

        .footer {
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;
        }

        .footer ul {
            list-style: none;
        }

        .footer div {
            width: 123px;
        }

        footer .footer-right {
            text-align: center;
            color: rgb(128, 122, 122);
            padding: 12px 0;
        }
    </style>
</head>

<body>
    <header>


        <nav>
            <div class="left">Ayush's Portfolio</div>
            <div class="right">
                <ul>
                
                    <li><a href="https://www.linkedin.com/in/ayush-kumar-1015a1229/">About</a></li>
                    <a href="/contact.html">Contact me</a>
                    <ul class="contact-details">
                        <li>Email: ayushmoriya35@gmail.com.com</li>
                        
                </ul>
            </div>
        </nav>


    </header>
    <main>
        <section class="firstsection">
            <div class="leftsection">
                Hi, My name is <span class="purple">Ayush</span>


                <div>I am a passionate </div>
                <span id="element"></span>
                <div class="buttons">

                    <button class="btn"><a href="Resume-Ayush-Kumar.pdf" target="_blank" rel="noopener noreferrer">View
                            Resume</a></button>
                    <button class="btn"><a href="https://github.com/AYUSH0-0" target="_blank"
                            rel="noopener noreferrer">Visit GitHub</a></button>
                </div>
            </div>

            <div>
                <img src="bg.png.png" alt="">
            </diV>

        </section>
        <hr>
        <section class="secondsection">
            <span class="text-gray"> What I have done so far</span>
            <h1>Work Experience</h1>
            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="bharat.jpeg" alt="">

                    <div class="vertical-title">
                        Web Development Intern
                    </div>
                    <div class="vertical-desc">
                        <P> My web developer internship at Bharat Intern was not just about writing code; it was about
                            being
                            part of a team that's shaping digital experiences</p>
                        <p> The practical skills, collaborative spirit, and commitment to innovation have prepared me
                            for a dynamic journey ahead in the world of web development.</p>

                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="younity.png" alt="">

                    <div class="vertical-title">

                        Business and research intern
                    </div>
                    <div class="vertical-desc">
                        <P>My Business and Research internship at Younity was a transformative experience that equipped
                            me with practical skills and insights to excel in the business world</P>
                        <p> The exposure to real-world challenges, guidance from industry experts, and a culture of
                            innovation have shaped my journey in profound ways.</p>

                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="ed.jpeg" alt="">

                    <div class="vertical-title">

                        Data Analytics Intern
                    </div>
                    <div class="vertical-desc">
                        <P> My internship at Edulyt was not only a platform for skill development but also a
                            transformative
                            experience that solidified my passion for data analytics.</P>
                        <P> The practical exposure, guidance from
                            experienced professionals, and the culture of growth have prepared me to take the next steps
                            in
                            my journey.</P>

                    </div>
                </div>

            </div>

        </section>


    </main>
    <footer>
        <div class="footer">
            <div class="footer-first">
                <h3>Ayush's Developer Portfolio</h3>
            </div>
            <div class="footer-second">
                
            </div>

            <div class="footer-third">
                <ul>
                    <li></li>
                    <li></li>
                    <li></li>
                </ul>
            </div>
            <div class="footer-rights">
                Copyrights &#169; Ayush'sportfolio.com | All rights reserve
            </div>
        </div>

    </footer>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

    <!-- Setup and start animation! -->
    <script>
        var typed = new Typed('#element', {
            strings: ['Web Developer.', 'with a strong interest in data analytics.'],
            typeSpeed: 50,
        });
    </script>
</body>

</html>![younity](https://github.com/AYUSH0-0/portfolio/assets/78579992/75c58e72-c104-4785-873d-0aaf56689c52)
![web dev](https://github.com/AYUSH0-0/portfolio/assets/78579992/c4505edd-43af-4426-965f-77c1430b7c1c)
![f](https://github.com/AYUSH0-0/portfolio/assets/78579992/e8a02c9f-e87e-4c14-ac8b-68fac8a1762c)
![ed](https://github.com/AYUSH0-0/portfolio/assets/78579992/5c0e5163-3647-4996-a257-6170bd49e06a)
![bharat](https://github.com/AYUSH0-0/portfolio/assets/78579992/9c5873c4-5a81-4d92-8d0b-3bed8e811e52)
![bg png](https://github.com/AYUSH0-0/portfolio/assets/78579992/9dad81bf-9fa5-4275-814f-7f14b4cd1b57)
