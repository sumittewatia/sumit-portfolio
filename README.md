<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Portfolio</title>

  
</head>
<style>
    

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}



body {
    font-family: 'Poppins', sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
}



.header {
    background-color: #0750b5;
    color: white;
    padding: 15px 0;
}

.nav-parent {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.3rem;
}

.nav-child {
    display: flex;
    gap: 20px;
}

.nav-child a {
    color: white;
    text-decoration: none;
    font-size: 0.85rem;
  
}
.animated-text{
    color: red;
}


.hero {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 45px 0;
    gap: 30px;
   
}

.hero-text {
    flex: 1;
}

.hero-text h1 {
    font-size: 2.5rem;
}


.hero-text p {
    margin-top: 12px;
    font-size: 0.9rem;
}



.hero-image img {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    object-fit: cover;
}



.about {
    padding: 10px 0 25px;
}

.about h2,
.skills h2,
.projects h2,
.contact h2 {
    font-size: 1.3rem;
    margin-bottom: 15px;
}

.about p {
    font-size: 0.85rem;
 
}



.skills {
    padding: 15px 0 30px;
}

.skills-parent {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
}

.skill-child {
    background-color: #0750b5;
    color: white;
    padding: 15px;
    text-align: center;
    border-radius: 5px;
    transition: 0.3s;
}



.skill-child h3 {
    font-size: 1rem;
}

.skill-child p {
    font-size: 0.8rem;
}


.projects {
    padding: 15px 0 30px;
}

.projects-parent {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
}

.project-child {
    background-color: white;
    padding: 35px 20px;
    text-align: center;
    border-radius: 6px;
}


.project-child h3 {
    font-size: 1rem;
    margin-bottom: 8px;
}

.project-child p {
    font-size: 0.8rem;
}


.contact {
    padding: 15px 0 30px;
}

.contact-form {
    width: 320px;
    max-width: 100%;
    margin: auto;
    background-color: white;
    padding: 20px;
    display: flex;
    flex-direction: column;
    gap: 10px;
    border-radius: 5px;
    box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 9px;
    border: 1px solid #b5c9e8;
    border-radius: 3px;
    font-family: inherit;
    font-size: 0.8rem;
}

.contact-form button {
    background-color: #0750b5;
    color: white;
    border: none;
    padding: 10px;
    border-radius: 3px;
  
}

.footer {
    background-color: #0750b5;
    color: white;
    text-align: center;
    padding: 15px;
    font-size: 0.8rem;
}



.back-button {
    position: fixed;
    bottom: 15px;
    right: 15px;
    background-color: #0750b5;
    color: white;
    padding: 8px 12px;
    text-decoration: none;
    font-size: 2px;
    border-radius: 3px;
   
}

.back-button:hover {
    background-color: #ff684f;
}

    .hero-text h1 {
        font-size: 2rem;
    }

    .hero-text h2 {
        font-size: 1.5rem;
    }

    .hero-image {
        width: 150px;
        height: 150px;
    }

    .nav-child {
        gap: 10px;
    }


  
 .class1{
    color: #333;
    background-color: rgb(148, 148, 250);
    margin: 20px;
    font-size: 20px;
   border-radius: 100px;
    border-color: #1d1615;
 }
   


</style>

<body>

    <header class="header" id="home">
        <div class="container nav-parent">

            <h2 class="logo">My Portfolio</h2>

            <nav class="nav-child">
                <a href="#home">Home</a>
                <a href="#about">About</a>
                <a href="#skills">Skills</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </nav>

        </div>
    </header>


    <section class="hero container">

        <div class="hero-text">
            <h1>Hi, I am</h1>

            <h2 class="animated-text">Full Stack Developer</h2>

            <p>
                Building modern web applications with clean and creative designs.
            </p>
        </div>

        <div class="hero-image">
            <img src="https://www.bing.com/th/id/OIP.NvB2ejF7-CyfaykkL5a_RAHaHa?w=193&h=193&c=8&rs=1&qlt=90&o=6&dpr=1.3&pid=ImgAns&rm=2" alt="My Profile Photo"  >
        </div>

    </section>



    <section class="about container" id="about">

        <h2>About Me</h2>

        <p>
            Hello! My name is harsh. I am a Computer Science student
            interested in web development and technology. I enjoy learning
            new skills and creating simple, useful and responsive websites.
            My goal is to become a skilled developer and build creative
            projects using modern technologies.
        </p>

    </section>



    <section class="skills container" id="skills">

        <h2>My Skills</h2>

        <div class="skills-parent">

            <div class="skill-child">
                <h3>HTML</h3>
                <p>Beginner</p>
            </div>

            <div class="skill-child">
                <h3>CSS</h3>
                <p>Beginner</p>
            </div>

            <div class="skill-child">
                <h3>JavaScript</h3>
                <p>Learning</p>
            </div>

        </div>

    </section>


 
    <section class="projects container" id="projects">

        <h2>My Projects</h2>

        <div class="projects-parent">

            <div class="project-child">
                <h3>Project 1</h3>
                <p>My first web development project.</p>
            </div>

            <div class="project-child">
                <h3>Project 2</h3>
                <p>A responsive personal portfolio website.</p>
            </div>

        </div>

    </section>


   
    <section class="contact container" id="contact">

        <h2>Contact Me</h2>

        <form class="contact-form">

            <input type="text" placeholder="Name" required>

            <input type="email" placeholder="Enter your email" required>

            <textarea placeholder="Write your message" rows="3" required></textarea>

            <button type="submit">Send</button>

        </form>

    </section>


  
    <footer class="footer">

        <p>© 2026 All Rights Reserved</p>

    </footer>


  <button class="class1">
    To the previous
  </button>


</body>
</html>
