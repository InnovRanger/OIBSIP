/* PORTFOLIO CODE */
/* HTML Code */
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@200..700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="styles.css">

    <title>My Portfolio</title>
    
</head>
<body>
    <!---- NAVBAR ---->
    <nav>
        <div class="left">
            <a href="/">Deborah</a>
        </div>
        <div class="right">
            <a href="http://linkedin.com" target="_blank" rel="noopener no-referrer"></a>
            <i class="fa-brands fa-linkedin-in"></i>
            <span>LinkedIn</span>
           
            <a href="http://github.com" target="_blank" rel="noopener no-referrer"></a>
            <i class="fa-brands fa-square-github"></i>
            <span>Github</span>

            <a href="mailto:deborah33@gmail.com" target="_blank" rel="noopener no-referrer"></a>
            <i class="fa-regular fa-envelope"></i>
            <span>E-Mail</span>
        </div>
    </nav>
    <main>
        <!----Section 1: Hero section---->
        <section class="hero-section">
            <div class="text">
                <h2>Hi I'm Deborah</h2>
                <p>Hi, I am Casey Lee, a software developer with a Masters degree in Computer Science and three years of experience in full-stack development. I have expertise in Java, Python, and JavaScript, and I’ve contributed to several open-source projects. My portfolio showcases my ability to build scalable web applications, and I pride myself on writing clean, efficient code.</p>
            <div class="links"> 
                
                <a href="#Skills">
                    <i class="fa-solid fa-code"></i>
                    <span>Skills</span>
                </a>

                <a href="#Testimony">
                    <i class="fa-solid fa-pen"></i>
                    <span>Testimony</span>
                </a>

                <a href="#Contact">
                    <i class="fa-solid fa-envelope"></i>
                    <span>Contact</span>
                </a>
            </div>
            </div>

            <div class="headshot">
                <img src="https://img.freepik.com/premium-photo/indian-college-girl-showing-thumb-white-background-generative-ai_802140-1478.jpg?ga=GA1.1.1515239657.1729784689">
            </div>
        </section>

        <!----Section 2: Skills section---->
        <section id="Skills" class="skills-section">
            <h2>Skills</h2>  
            <div class="text">
                Python is commonly used for developing websites and software, task automation, data analysis, and data visualisation. C is a general-purpose computer programming language for system administration, network programming, and embedded software.C++ is used in fields such as system software, game development, embedded systems, scientific computing and high-performance applications. Java is a multi-platform, object-oriented, and network-centric language that can be used as a platform in itself. Programming skills, or coding skills, are the skills we use to write instructions for computers, applications, or software. They include different programming languages and concepts. What skills do I need to code? To start, you'll need knowledge of at least one programming language.   
            </div>
            <div class="cells">
                <div class="cell">
                    <img src="https://i0.wp.com/junilearning.com/wp-content/uploads/2020/06/python-programming-language.webp?resize=1024%2C1024&ssl=1">
                    <span>HTML</span>
                </div>

                <div class="cell">
                    <img src="https://img.icons8.com/?size=512&id=40670&format=png">
                    <span>C</span>
                </div>

                <div class="cell">
                    <img src="https://w7.pngwing.com/pngs/646/751/png-transparent-the-c-programming-language-computer-programming-programmer-others-blue-class-logo-thumbnail.png">
                    <span>C++</span>
                </div>

                <div class="cell">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQYxbb6SR81a9Fe_hBTvejMWf7iwJ3YIgqffw&s">
                    <span>Java</span>
                </div>
            </div>
        </section>

        <!---Section 3: Testimony section---->
        <section id="Testimony" class="testimony-section">
            <h2>Testimony</h2>
            <div class="group">
                <div class="person-details">
                    <img src="https://img.freepik.com/premium-photo/south-indian-college-girl-student-white-top-is-standing-campus-holding-sheets-papers_905085-5.jpg">
                    <p>Sara Hebzibah</p>
                    <p> Software Engineer </p>
                </div>
                <div class="text">
                I have always had a passion for helping others; this trait stems from the example my parents have set for me. I was exposed to consistent love and kindness, a respect my parents displayed to not only me, but strangers as well. I’ve experienced both poverty and wealth. I was raised in poverty, sharing a two-bedroom apartment with my family of six members. I watched my parents struggle as they attempted to create a comfortable life for my brothers and I. Their devotion to God, alongside their generosity and hard work, is what allowed me to experience life of wealth as well. My family now runs multiple home health businesses, which I would otherwise inherit. However, I have decided to take a different direction as this is not where my passion lies. I chose nursing with the similar intent that AUHS states; providing competent, caring, and evidence-based nursing services to diverse patient populations. I wish to build and develop my caring skills into something with academic backing so I know that as well as being well; meaning, my interventions can be medically effective.   
                </div>
            </div>
        </section>

        <!---Section 4: Contact section-->
        <section id="Contact" class="contact-section">
            <h2>Contact</h2>
            <div class="group">
                <div class="text">
                    India, country that occupies the greater part of South Asia. It is made up of 28 states and eight union territories, and its national capital is New Delhi, built in the 20th century just south of the historic hub of Old Delhi to serve as India’s administrative center. India remains one of the most ethnically diverse countries in the world. Apart from its many religions and sects, India is home to innumerable castes and tribes, as well as to more than a dozen major and hundreds of minor linguistic groups from several language families unrelated to one another.
                </div>
                <form>
                    <label for="name"> Name</label>
                    <input type="text" id="name">

                    <label for="email"> Email</label>
                    <input type="email" id="email">

                    <label for="message"> Message</label>
                    <textarea id="message" cols="30" rows="10"></textarea>
                    <button type="submit">Send Message</button>
                </form>
            </div>
        </section>
    </main>
</body>
</html>

/* CSS Code */
:root{
    --text-color: #030806;
    --link-color: #0c1102;
    /*--background-color: #7ecfb0; */
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
html{
    scroll-behavior: smooth;
}

body {
    background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR-GD3_uU-bL9HqEhOhrIg8trjjQgRK8G0oGDdid4gSq5r8Jh2xC9n-vSDRZAPisb7GESc&usqp=CAU");
    background-position: center;
    background-size: cover;
    height: fit-content;
    position: relative;
  }
/*body{
    font-family:'Oswald', sans-serif ;
    /*background-color: var(--background-color);
    max-width: 1400px;
    margin: 0 auto;
}*/

a {
    color: var(--link-color);
    text-decoration: none;
}

/* Navbar */
nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 0 50px;
    height: 50px;
}

nav .left a{
    color: var(--text-color);
    font-size: 20px;
    font-weight: 700;
}

nav .right a{
    color: var(--text-color);
    font-size: 20px;
    font-weight: 700;
    margin: 0 12px;
}

nav .right a:last-child{
    color: var(--link-color);
    /*background-color: var(--text-color);*/
    padding: 9px 17px;
    border-radius: 5px;
}

nav .right a span{
    margin-left: 5px;
}

/* Section 1: Hero*/
.hero-section {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 0 50px;
    margin:55px 0 ;
    margin-bottom: 100px;
    gap: 45px;
}

.hero-section .text{
    flex: 10;
}

.hero-section .text h2{
    font-size: 50px;
}

.hero-section .text .links{
    margin-top: 25px;
}

.hero-section .text .links a{
    display: inline-block;
    padding: 6px 12px;
    border: 3px solid var(--link-color);
    border-radius: 5px;
    margin-right: 8px;
    margin-bottom: 10px;
    transition: 1s;
}
.hero-section .text .links a:hover{
    color: var(--text-color);
    border: 2px solid var(--text-color);
}

.hero-section .headshot{
    flex: 4;
    display: flex;
    justify-self: right;
}

.hero-section .headshot img{
    width: 400px;
    border-radius: 45%;
}
/*section 2: skills*/
.skills-section{
    padding: 0 50px;
    margin-bottom: 50px;
}

.skills-section h2{
    text-align: center;
    font-size: 25px;
}

.skills-section .text{
    text-align: center;
    margin-bottom: 20px;
    flex-wrap: wrap;
}
.skills-section .cells .cell{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
    width: 200px;
    padding: 10px 20px;
    margin: 10px;
    border: 1.5px solid #010204;
    border-radius: 5px;

}

.skills-section .cells .cell img{
    width: 40px;
    height: 40px;
    object-fit: contain;
    border-radius: 2px;
}

.skills-section .cells{
    display: flex;
    justify-self: center;
}

/*section 3: testimony*/
.testimony-section{
    padding: 0 50px;
    margin-bottom: 100px;
}

.testimony-section h2{
    font-size: 35px;
    margin-bottom: 30px;
}

.testimony-section .group{
    display: flex;
    align-items: center;
    gap: 50px;
}

.testimony-section .group .person-details{
    text-align: center;
    flex: 3;
}

.testimony-section .group .person-details img{
    width: 200px;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 10px;
}

.testimony-section .group .person-details p{
    font-weight: 600;
}

.testimony-section .group .person-details p:last-child{
    font-weight: normal;
}

.testimony-section .group .text{
    flex: 7;
}
/*section 4:contact*/
.contact-section{
    padding: 0 50px;
    margin-bottom: 100px;
}

.contact-section h2{
    font-size: 35px;
}

.contact-section .group{
    display: flex;
    gap: 50px;
}

.contact-section .group .text{
    flex: 3;
    margin-bottom: 20px;
}

.contact-section .group form{
    flex: 3;
    display: flex;
    flex-direction: column;
}

.contact-section .group form input,
.contact-section .group form textarea{
    font-family: 'Oswald', sans-serif ;
    border: 2px solid var(--link-color);
    /*background-color: transparent;*/
    padding: 15px;
    outline: none;
    resize: none;
}

.contact-section .group form button{
    font-size: 16px;
    font-family: 'Oswald', sans-serif ;
    color: #eeefff;
   /* background-color: var(--link-color);*/
    border: none;
    height: 50px;
    cursor: pointer;
    transition: 2s ;
}

.contact-section .group form button:hover{
    filter: brightness(.9);
}
@media (max-width: 800px){
    /*section 1:Hero*/
    .hero-section .text h2{
        font-size: 40px;
    }
}
@media (max-width: 740px){
    /*section 1:Hero*/
    .hero-section{
        flex-direction: column-reverse;
    }
    .hero-section .headshot img{
        width: 300px;
    }
    /*section 3: testimony*/
    .testimony-section h2{
        text-align: center;
    }
    .testimony-section .group{
        flex-direction: column;
    }
    .contact-section .group{
        flex-direction: column;
    }
}

@media (max-width: 600px){
    nav {
        padding: 0 20px;
    }
    nav .right a{
        font-size: 20px;
    }

    nav .right a:last-child{
        color: var(--text-color);
        background-color: transparent;
        padding: 0;
    }
    nav .right a span{
        display: none;
    }
    /*section 1 : hero*/
    .hero-section{
        padding: 0 20px;
    }
    .hero-section .text h2{
        font-size: 30px;
    }
    /*section 2: skills*/
    .skills-section{
        padding: 0 20px;
    }

    .skills-section .cells .cell span{
        font-size: 16px;
    }
    /*section 3: Testimony*/
    .testimony-section{
        padding: 0 20px;
    }
    /*section 4:contact*/
    .contact-section{
        padding: 0 20px;
    }
}
