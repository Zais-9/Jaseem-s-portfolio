# Jaseem-s-portfolio
Responsive personal portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link  rel="stylesheet" href="home.css"/>
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css'  rel='stylesheet' >
    <title>Personal responsive portfolio webPage</title>
</head>



  /* Basic styling to reset margins and paddings */
  *{
    margin:0;
     padding:0;
     box-sizing:border-box;
     text-decoration: none;
     border: none;
     outline:none;
     scroll-behavior: smooth;
     font-family: "poppins", sans-serif;
 }
 :root{
    --bg-color:white;
    --second--bg-color:blue;
    --text-color:black;
    --main-color:red;
}
 html{
     font-size:50%;
     overflow-x: hidden;
 }
 body{
    background:var(--bg-color);
    color:var(--text-color);
    padding: 10rem;
 }
 /* Styling the navigation bar */
 .header{
     position:fixd;
     padding:4rem 12% 4rem;
     background-color:var(--second--bg-color);
     display: flex;
     align-items: center;
     justify-content: space-between;  
 }
 .logo {
     font-size: 5rem;
     font-weight: 800px;
     color:var(--text-color);
     cursor:pointer;
     transition: 0.3s ease;
 }
 .logo span{
    color:var(--main-color);
 }
 .navbar a{
     font-size: 2rem;
     color:var(--text-color);
     margin-left: 3rem;
     font-weight: 500;
     transition: 0.3s ease;
     font-family:calibri;
     padding-right: 6x;
     padding-left:12px;
     border-bottom: 3px solid transparent;
 }
 .navbar a:hover,
 .navbar a.active{
    color:var(--main-color);
    border-bottom: 3px solid var(--main-color);
 }
 input{
     background-color:lightcyan;
     margin-left: 10px;
     border:2px solid whitesmoke;
     border-radius:2px;
     padding:5px;
 }
 .home-content h1{
     font-size:4rem;
     line-height:1;
     font-weight: 700;
     margin-top:1.5rem;
 }
 .home-content h1 span{
     color: var(--main-color);
 }
 .home-image img{
    float:right;
     position:relative;
     width:30vw;
     border-radius: 50%;
     box-shadow: 0 0 25spx var(--main-color);
     cursor:pointer;
     transition: 0.4s ease-in-out;
 }
 .home-image :hover{
    box-shadow: 0 0 10px var(--main-color),
                 0 0 20px var(--main-color),
                 0 0 50px var(--main-color);
    transform: scale(1.03);
 }
 #pic2{
    float:left;
    border-radius: 75px;
    gap:5rem;
 }
 .social-icons a{
 display: inline-flex;
 justify-content:center;
 align-items: center;
 width:4.5rem;
 height:4.5rem;
 background: transparent;
 border:2px solid var(--main-color);
 font-size: 3rem;
 border-radius:50%;
 color:var(--main-color);
 margin:28rem 1.5rem 3rem 0 ;
 transition:0.3s ease;
 }
 .social-icons a:hover{
     color: var(--main-color);
     transform: scale(1.3) translateY(-5px);
     box-shadow: 10 10 25% var(--main-color);
    background-color:var(--main-color);
     color:var(--text-color);
 }
 .home-content p{
    text-align: justify;
     font-size: 2rem;
     font-weight:40;
     height:50px;
     color:var(--text-color);
 }
 .text-animation{
     color:var(--main-color);
     font-size:25px;
     font-weight:600;
     min-width:280px;
 }
 .text-animation span{
     position: relative;
     color:var(--text-color);
 }
.text-animation{
   color:var(--main-color);
    font-size: 2rem;
}
.about{
    min-height:75vh;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10rem;
    background-color: var(--bg-color);
    color: var(--text-color);
}
.heading{
    text-align: center;
    font-size:3rem;
    margin:5rem 0;  
}
.about-content h2{
    text-align: left;
    line-height: 0.3rem;
}
.about-content p{
    font-size:2rem;
    text-align: justify;
    margin:1.5rem 0 2.5rem ;
    color:var(--text-color);
}
.btn{
    text-decoration: none;
    gap:2rem;
    padding:.5rem 2rem;
    height:4.5rem;
    width:9.3rem;
    color:var(--main-color);
    background-color: black;
    font-size:1.5rem;
    outline:none;
    border: 2px solid var(--main-color);
    border-radius: 2rem;
    cursor:pointer;
   position:0.3;
}
.btn:hover{
    transform: scale(1.05);
    background-color: red;
    box-shadow: 10 10 25% var(--main-color);
    color:var(--text-color);
}
.home-image img{
    float:right;
     position:relative;
     width:30vw;
     border-radius: 50%;
     box-shadow: 0 0 25spx var(--main-color);
     cursor:pointer;
     transition: 0.4s ease-in-out;
 }
 .home-image :hover{
    box-shadow: 0 0 10px var(--main-color),
                 0 0 20px var(--main-color),
                 0 0 50px var(--main-color);
    transform: scale(1.03);
 }
  #pic2{
    float:left;
    border-radius: 75px;
    gap:5rem;
 }

/* Styling the services page */
.services{
    background-color: var(--bg-color);
    color:black;
}
.services h2{
    margin-bottom: 5rem;
    color:var(--text-color);
}
.services-container{
    display:flex;
    grid-template-columns: repeat(3,1fr);
    align-items: center;
    gap:1rem;
}
.services-box{
    display:flex;
    align-items: center;
    justify-content: center;
    background-color: var(--main-color);
    height: 520px;
    border-radius: 3rem;
    border:5px solid transparent;
    cursor:pointer;
    transition:0.4s ease-in-out;
}
.services-box:hover{
    background-color: var(--bg-color);
    color:black;
    border:5px solid var(--text-color);
    transform: scale(1.03);
}
.services-box .services-info{
    height: 80%;
    display: flex;
    flex-direction: column;
    text-align: center;
    justify-content: center;
    align-items: center;
    padding: 2rem ;
}
.services-info h4{
    font-size: 2rem;
    margin: 1rem 0;
    font-weight: 600;
}
.services-info p{
    margin-bottom: 3rem;
    font-size: 2rem;
    font-weight: 400;
    line-height:1;
    color:black;
}
.services-info i{
    font-size: 2rem;
}

/* Styling the projects pages */
.projects{
    background: url(pic10.jpg) center no-repeat;
    background-size: cover;
}
.projects-box{
    display: flex;
    grid-template-columns: repeat(3,1fr);
    place-items:center;
    margin:5rem 0;
    row-gap:5rem;
}
.projects-card{
    height: 600px;
    max-width: 450px;
    background-color:rgba(0,0,0,0.127);
    border:2px solid var(--main-color);
    border-radius: 5rem;
    display:flex;
    flex-direction:column;
    align-items: center;
    justify-content: center;
    text-align: center;
    gap: 2rem;
    padding:5rem 2rem;
    overflow:hidden;
    cursor: pointer;
    box-shadow: 0 0 5px var(--main-color);
    transition: 0.4s ease;
}
.projects-card:hover{
    box-shadow: 0 0 25px var(--text-color),
                0 0 50px var(--main-color);
    transform:scale(1.02);
}
.projects-card img{
   max-width:18vw;
   object-fit:cover;
   border-radius:10%;

}
h2{
    font-size: 3rem;
    color:var(--text-color)
}
.projects-card h3{
    font-size: 3rem;
    color:var(--text-color)
}
.projects-card p{
    font-size: 13px;
    color:var(--bg-color);
}

/* Styling the contact pages */
.contact{
    background-color: var(--bg-color);
}
.contact h2{
    margin-bottom: 3rem;
    color: var(--text-color);
}
.contact form{
    display: flex;
    align-items: center;
    justify-content: center;
    gap:3rem;
    margin: 5rem auto;
    text-align: center;
}
.contact form .input-box{
    display: flex;
    justify-content:center;
    flex-wrap: wrap;
}
.contact form .input-box input,
.contact form textarea{
width:100%;
padding:2.5rem;
font-size:1.8rem;
color:var(--text-color);
background-color: var(--bg-color);
border-radius: 2rem;
border:2px solid var(--main-color);
margin: 1.5rem 0;
resize:none;
}
.contact form .btn{
    margin-top:2rem;
}


/* Styling the blog page */
.blogs{
    background: url(pic9.jpg) center no-repeat;
    background-size: cover;
}
.blogs h1{
    margin-bottom: 5rem;
    color:white;
}
 p{
    font-size: 15px;
    color:var(--bg-color);
    
 }

/* Styling the footer page */
.footer{
     position: relative;
     bottom:0;
     width:100%;
     padding:40px 0;
     background-color: var(--main-color);
}
.footer .social{
     text-align: center;
     padding-bottom: 25px;
     color:var(--mai-color);
 }
 .footer .social a{
     font-size: 25px;
     color:var(--bg-color);
     width:42px;
     height:42px;
     line-height: 42px;
     display:inline-block;
     text-align:center;
     border:2px solid var(--bg-color);
     border: 50%;
     margin:0 10px;
     transition:0.3s ease; 
     background-color: var(--text-color);
 }
 .footer .social a:hover{
     transform: scale(1.2)translateY(-10px);
     background-color: var(--bg-color);
     color:var(--mai-color);
     box-shadow: 0 0 25px var(--text-color);
     border:2px solid var(--text-color);
 }
 .footer ul{
     margin-top:0;
     padding:0;
     font-size: 18px;
     line-height: 1.6;
     margin-bottom: 0;
     text-align: center;
 }
 .footer ul li a{
    text-decoration: none;
    color:var(--text-color);
     border-bottom: 3px solid transparent;
     transition: 0.3s ease;
 }
 .footer ul li a:hover{
     border-bottom: 3px solid var(--bg-color);
     color:var(--bg-color);
 }
 .footer ul li {
     display:inline-block;
     padding:0 15px;
}
.footer .copyright{
    margin-top: 50px;
    text-align: center;
    font-size: 16px;
    color:var(--text-color);
}
.number{
    text-decoration: none;
    color:var(--text-color);
   text-align: center;
   font-size:10rem;
}
.number:hover{
    color:var(--bg-color);
}
    




    
<body>
<header class="header">
       <a href="Home-page.html" class="logo">
        <span>Jaseem's</span>Portfolio
       </a>
       
        
       
    <nav class="navbar">
      <a href="Home-page.html" class="active">Home</a>
      <a href="About.html">About</a>
      <a href="Services.html">Services</a>
      <a href="Projects.html">Projects</a>
      <a href="Contact.html"  >Contact</a>
      <a href="Footer.html">Footer</a>
    </nav>
</header>


<section class="home" id="home">
    <div class="home-content">
            <h1>Hi, It's <span>Jaseem</span></h1>
           <h3 class="text-animation"><span>I am</span> Web Designer</h3>

           <div class="home-image">
            <img src="pic1.jpg">
        </div>
        <br><br>

            <p><b>Here's an example of a "About My-self": </b>
           <br>

                "I am a person who is positive about every aspect of life. There are many things I like to do, to see, and to experience. I like to read, I like to write; I like to think, I like to dream; I like to talk, I like to listen. I like to see the sunrise in the morning, I like to see the moonlight at night; I like to feel the music flowing on my face, I like to smell the wind coming from the ocean. I like to look at the clouds in the sky with a blank mind, I like to do thought experiments when I cannot sleep in the middle of the night. I like flowers in spring, rain in summer, leaves in autumn, and snow in winter. I like to sleep early, I like to get up late; I like to be alone, I like to be surrounded by people. I like country's peace, I like metropolis' noise; I like the beautiful west lake in Hangzhou, I like the flat cornfield in Champaign.
                
                I always wanted to be a great writer, like Victor Hugo who wrote "Les Miserable", or like Roman Roland who wrote "John Christopher". They have influenced millions of people through their books. I also wanted to be a great psychologist, like William James or Sigmund Freud, who could read people's mind. Of course, I am nowhere close to these people, yet. I am just someone who does some teaching, some research, and some writing. But my dream is still alive.
                
                This is a brief introduction of myself. If you are interested in knowing more, read my articles or take a look at my pictures. Do not expect too much, and keep your sense of humor."
                 </p>
                 <br>

                <div class="social-icons">
                    <a href="https://github.com/Zais-9">
                        <i class="bx bxl-github"></i>
                    </a>
                    <a href="https://www.facebook.com/profile.php?id=100090462123865&mibextid=ZbWKwL">
                        <i class="bx bxl-facebook"></i>
                    </a>
                    <a href="https://www.linkedin.com/in/md-jaseem-99ba482a9?utm_source=share&utm_campaign
                            =share_via&utm_content=profile&utm_medium=android_app">
                        <i class="bx bxl-linkedin-square"></i>
                    </a>
                    <a href="#">
                        <i class="bx bxl-instagram-alt"></i>
                    </a>
                </div>
                <a href="blogs.html" class="btn">Blogs</a>
        
            

            <div class="home-image">
                <img id="pic2" src="pic2..jpg">
            </div>
            <p><b>Here's an example of a "About My passionate [ IT Industry]":</b>
                <br>
                “I am a recent graduate of [University of Culcutta] with a degree in [Major]. I am passionate about [ IT Industry] and eager to learn and grow. I have strong [web desighn, python, IoT etc] and am a quick learner. I am looking for an entry-level position where I can use my skills and knowledge to contribute to a team and make a positive impact.”
                
                I am a person who is positive about every aspect of life. There are many things I like to do, to see, and to experience. I like to read, I like to write; I like to think, I like to dream; I like to talk, I like to listen. I like to see the sunrise in the morning, I like to see the moonlight at night; I like to feel the music flowing on my face, I like to smell the wind coming from the ocean. I like to look at the clouds in the sky with a blank mind, I like to do thought experiment when I cannot sleep in the middle of the night. I like flowers in spring, rain in summer, leaves in autumn, and snow in winter. I like to sleep early, I like to get up late; I like to be alone, I like to be surrounded by people. I like country’s peace, I like metropolis’ noise; I like the beautiful west lake in Hangzhou, I like the flat cornfield in Champaign. I like delicious food and comfortable shoes; I like good books and romantic movies. I like the land and the nature, I like people. And, I like to laugh.This is a brief introduction of myself. If you are interested in knowing more, read my articles or take a look at my pictures. Do not expect too much, and keep your sense of humor.
                <br><br>
                <b>
                
                1. Begin with an attention-grabbing introduction. ...
                <br>
                2. Mention your relevant professional experience. ...
                <br>  
                3. Include important awards and achievements. ...
                <br>
                4. Share relevant personal details. ...
                <br>
                5. End with a professional yet friendly tone.
            </b>
            </p>
           
        </section>    



         <header class="header">
        <a href="Home-page.html" class="logo">
         <span>Jaseem's</span>Portfolio
        </a>
        
         
        
     <nav class="navbar">
       <a href="Home-page.html" class="active">Home</a>
       <a href="About.html">About</a>
       <a href="Services.html">Services</a>
       <a href="Projects.html">Projects</a>
       <a href="Contact.html"  >Contact</a>
       <a href="Footer.html">Footer</a>
     </nav>
 </header>
    
    <section class="about" id="about">

        
        

         <div class="about-content">
                <h2 class="heading">About <span>Me</span></h2>
                <h3 class="text-animation">Web Developer</h3>

                <div class="home-image">
                    <img src="pic3.png">
                </div>
                <p><b>Here's an example of "About Me": </b>
                    <br>
         
                         "I am a person who is positive about every aspect of life. There are many things I like to do, to see, and to experience. I like to read, I like to write; I like to think, I like to dream; I like to talk, I like to listen. I like to see the sunrise in the morning, I like to see the moonlight at night; I like to feel the music flowing on my face, I like to smell the wind coming from the ocean. I like to look at the clouds in the sky with a blank mind, I like to do thought experiments when I cannot sleep in the middle of the night. I like flowers in spring, rain in summer, leaves in autumn, and snow in winter. I like to sleep early, I like to get up late; I like to be alone, I like to be surrounded by people. I like country's peace, I like metropolis' noise; I like the beautiful west lake in Hangzhou, I like the flat cornfield in Champaign.
                         
                         I always wanted to be a great writer, like Victor Hugo who wrote "Les Miserable", or like Roman Roland who wrote "John Christopher". They have influenced millions of people through their books. I also wanted to be a great psychologist, like William James or Sigmund Freud, who could read people's mind. Of course, I am nowhere close to these people, yet. I am just someone who does some teaching, some research, and some writing. But my dream is still alive.
                         
                         This is a brief introduction of myself. If you are interested in knowing more, read my articles or take a look at my pictures. Do not expect too much, and keep your sense of humor."
                        </p>
                <a href="ReadMore.html" class="btn">Read More</a>
                <a href="./CV.pdf" class="btn" download>
                    <i class="fa-solid fa-download"></i>Dawnload CV</a>
                <br><br>

                <p><b>Here's an example of "About Me": </b>
                    <br>
         
                    In your introduction as a software developer, consider including key information such as your educational background, the programming languages you specialize in, and any notable projects or experiences. Highlighting your skills and passions will help others understand your expertise and interests.
                    
                    I am a person who is positive about every aspect of life. There are many things I like to do, to see, and to experience. I like to read, I like to write; I like to think, I like to dream; I like to talk, I like to listen. I like to see the sunrise in the morning, I like to see the moonlight at night; I like to feel the music flowing on my face, I like to smell the wind coming from the ocean. I like to look at the clouds in the sky with a blank mind, I like to do thought experiment when I cannot sleep in the middle of the night. I like flowers in spring, rain in summer, leaves in autumn, and snow in winter. I like to sleep early, I like to get up late; I like to be alone, I like to be surrounded by people. I like country’s peace, I like metropolis’ noise; I like the beautiful west lake in Hangzhou, I like the flat cornfield in Champaign. I like delicious food and comfortable shoes; I like good books and romantic movies. I like the land and the nature, I like people. And, I like to laugh.
                    <br><br>
                    <b>
                    1. Include important awards and achievements. ...
                    <br>
                    3. Share relevant personal details. ...
                    <br>
                    4. End with a professional yet friendly tone.
                    <br>
                    5. Decide what you want your language to do and who it's for.
                    <br>
                    6. reate rules for how to write code in it.
                    <br>
                    7. ake tools that check and organize code.
                    <br>
                    8. ive meaning to your code structures.
                    <br>
                    9. dd features for managing data.
                    <br>
                    10. uild a compiler or interpreter.
                    </b>
                </b>
                </p>
                <div class="home-image">
                    <img id="pic2" src="pic4.jpg">
                </div>
                </div>
            </section>

<script src="project.js"></script>


</body>
</html>
