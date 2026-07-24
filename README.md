<!DOCTYPE html>
<html lang="en">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Muhammad Arham | AI Engineer Portfolio</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Segoe UI', sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#050505;
    color:white;
}


/* Navbar */

nav{
    position:fixed;
    top:0;
    width:100%;
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    background:rgba(5,5,5,.9);
    backdrop-filter:blur(10px);
    z-index:100;
}


.logo{
    font-size:30px;
    font-weight:bold;
}

.logo span{
    color:#00ff88;
}


nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
}



/* Hero */

.hero{

height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;

}


.hero h1{

font-size:55px;

}


.hero h2{

margin:20px;
color:#00ff88;

}


.hero p{

max-width:700px;
color:#aaa;
font-size:18px;
line-height:1.7;

}


.btn{

display:inline-block;
margin:30px 10px;
padding:14px 35px;
border-radius:30px;
border:1px solid #00ff88;
color:white;
text-decoration:none;
transition:.3s;

}


.btn:hover{

background:#00ff88;
color:black;

}




section{

padding:100px 10%;

}


.title{

font-size:40px;
margin-bottom:30px;

}



.about p{

color:#aaa;
font-size:18px;
line-height:1.8;

}




/* Skills */

.skills{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
gap:20px;

}


.skill{

background:#111;
padding:20px;
text-align:center;
border-radius:15px;
border:1px solid #222;

}




/* Projects */


.projects{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;

}



.card{

background:#111;
padding:30px;
border-radius:20px;
border:1px solid #222;
transition:.3s;

}


.card:hover{

transform:translateY(-10px);
border-color:#00ff88;

}



.card h3{

color:#00ff88;
margin-bottom:15px;

}


.card p{

color:#aaa;
line-height:1.7;

}



/* Experience */


.box{

background:#111;
padding:30px;
border-radius:20px;

}


.box h3{

color:#00ff88;

}



/* Contact */


.contact{

text-align:center;

}


.contact a{

color:#00ff88;

}



footer{

text-align:center;
padding:30px;
background:#111;
color:#aaa;

}



</style>

</head>


<body>


<nav>

<div class="logo">
Arham<span>.</span>
</div>


<div>

<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>

</div>


</nav>





<section class="hero">


<div>


<h1>
Muhammad Arham Abdul Qayyum
</h1>


<h2>
Full Stack Developer | AI/ML Engineer
</h2>


<p>

Building intelligent software systems using Artificial Intelligence,
Machine Learning, Computer Vision and modern web technologies.

</p>


<a class="btn" href="https://github.com/arhamsolution-me">
GitHub
</a>


<a class="btn" href="mailto:arham.solution.me@gmail.com">
Contact
</a>


</div>


</section>






<section id="about" class="about">


<h2 class="title">
About Me
</h2>


<p>

I am a Computer Science student and AI Engineer passionate about
building real-world software solutions.

My focus areas include AI applications, full-stack development,
automation systems, computer vision and intelligent agents.

</p>


</section>







<section id="skills">


<h2 class="title">
Technical Skills
</h2>


<div class="skills">

<div class="skill">Python</div>
<div class="skill">C++</div>
<div class="skill">JavaScript</div>
<div class="skill">React</div>
<div class="skill">Node.js</div>
<div class="skill">Flask</div>
<div class="skill">PostgreSQL</div>
<div class="skill">MongoDB</div>
<div class="skill">PyTorch</div>
<div class="skill">TensorFlow</div>
<div class="skill">OpenCV</div>
<div class="skill">YOLO</div>

</div>


</section>






<section id="projects">


<h2 class="title">
Featured Projects
</h2>


<div class="projects">


<div class="card">

<h3>
Cortex AI
</h3>

<p>
AI assistant with memory, automation and intelligent workflows.
</p>

</div>



<div class="card">

<h3>
LexiBase AI
</h3>

<p>
AI database assistant that converts natural language into database intelligence.
</p>

</div>




<div class="card">

<h3>
Computer Vision Systems
</h3>

<p>
Vision solutions using YOLO, OpenCV and deep learning models.
</p>

</div>



</div>


</section>







<section>


<h2 class="title">
Experience
</h2>


<div class="box">

<h3>
Full Stack AI Engineer
</h3>


<p>
Developing AI-powered applications, automation systems,
and scalable software products.
</p>


</div>


</section>







<section id="contact" class="contact">


<h2 class="title">
Let's Connect
</h2>


<p>

Email:
<a href="mailto:arham.solution.me@gmail.com">
arham.solution.me@gmail.com
</a>

</p>


<p>

GitHub:
<a href="https://github.com/arhamsolution-me">
arhamsolution-me
</a>

</p>


</section>




<footer>

© 2026 Muhammad Arham Abdul Qayyum

</footer>



<script>

console.log("Portfolio Ready");

</script>


</body>

</html>
