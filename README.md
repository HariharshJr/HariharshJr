- 👋 Hi, I’m @HariharshJr
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
HariharshJr/HariharshJr is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<!DOCTYPE html>
<html>
<head>
<title>MANOJ A T -portfolio</title>
<style>
body 
{
    font-family: Arial, sans-serif;
margin: 0;
padding: 0;
background-color: aliceblue;
}

header {background-color: rgb(0, 0, 0);
color: azure;
text-align: center;
padding: 2rem 0;
position: relative; /* add this */
}

.header-content h1 { 
    font-size: 2.5rem;
}

/* add style for the round profile picture */
.profile-picture
 {
    width: 100px;
    height: 100px;
    border-radius: 75%;
    object-fit: cover;
    position: absolute;
    top: 75px;
    left: 75px;
}
nav
{
background-color: dodgerblue;
color: brown;
text-align: center;
}
  nav ul
{
list-style-type: none;
padding: 0;
}
nav ul li {
    display: inline;
    margin: 0 20px;
}
nav ul li a {
    text-decoration: none;
    color: antiquewhite;
}

.section-content 
{
    background-color: darkviolet;
    padding: 2rem;
    margin: 1rem;
    border-radius: 20px;
    box-shadow: 0 0 10px rebeccapurple;
}

.download-button {
    background-color: aquamarine;
    color: blueviolet;
    padding: 0.5rem 1rem;
    text-decoration: none;
    border-radius: 20px;
    display: inline-block;
    margin-top: 10px;
}

.download-button:hover{
    background-color: coral;
}

footer{
    text-align: center;
    padding: 1rem 0;
    background-color: darkred;
    color: black;
}

ul {
    list-style-type: disc;
    padding-left: 20px;
}
</style>
</head>
<body>
<header>
    <div class="header-content">
        <!-- Add your peofile picture here -->
        <img src="img.manoj.jpeg" alt="your profile picture" class="profile-picture">
        <h1>MANOJ A T</h1>
        <p>studing Bsc computer science in AVASC College</p>
 </div>
</header>

<nav>
    <ul>
        <li><a herf="#about">ABOUT</a></li>
        <li><a herf="#education">EDUCATION</a></li>
        <li><a herf="#skills">SKILLS</a></li>
        <li><a herf="#projects">PROJECTS</a></li>
        <li><a herf="#resume">RESUME</a></li>
    </ul>
</nav>

<section id="about">
    <div class="section-content">
        <h2>About Me</h2>
        <p> Hello Everybuddy ,I am sabarish 
            from Thiruvaiyaru,
            I am studying avasc. 
        </p>
</div>
</section>

<section id="education">
    <div class="section-content">
       <h2>Education</h2>
       <p>Bsc Computer science IIIrd Year
                  AVASC
        </p>
    </div>
</section>

<section id="skills">
    <div class="section-content">
      <h2>Skills</h2>
      <ul>
            <li>Type writting(junior)</li>
             <li>To understanding to other person</li>_
              <li>I know C,C++,Java,python lanuages</li>
        </ul>
    </div>
</section>

    <section id="project">
        <div class="section-content">
          <h2>projects</h2>
          <ul>
                <li><a href="#">project 1</a> </li>
                 <li><a href="#">project 2</a></li>
                 <!-- Add more projects -->_
            </ul>
        </div>
    </section>
    <section id ="Resume">
        <center>
            <div class="section-content">
                <h2>resume</h2>
                <a href="https://resume.naukri.com/resume-editor?download=true&resumeId=3967322" class="download-button">view me</a>

            </div>
        </center>

    </section>

    <footer>
        <p>&copy; 2023 D.sabarish</p>
    </footer>
    <script>
        document.querySelectorAll('a[herf^="#"]').forEach(anchor =>  {anchor.addEventListener('click',function(e) {
            e.preventDefault();
            const targetId = this.getAttributes('herf').substring(1);
            const targetElement = document.getElementById(targetId);

            if(targetElement) {
                window.scrollTo({
                    top: targetElement.offsetTop,
                    behavior: 'smooth'
                });
            }
        });
    });
    </script>
  </body>
</html>
