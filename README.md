# portfolio-using-HTML-and-CSS
#htmlcode
<!DOCTYPE html>
<html>
<head>
  <title>Portfolio</title>
  <link rel="stylesheet" href="styles.css"> </head>
<body>
  <header>
    <h1> Ruchi kumari &#10084;</h1>
    <img src="c:\Users\LENOVO\OneDrive\Pictures\logo.jpg" alt="Your Logo">
    <p>Storyteller| Journaler | Content Creator
    </p>
  </header>

  <section id="about">
    <img src="c:\Users\LENOVO\OneDrive\Pictures\web profile.jpg" alt="Your Profile Picture">
    <h2>About Me</h2>
    <p> Hello floks! 
        I am Ruchi. i love sharing my thoughts, experiences, and expertise through content creation.
        i help those who struggle to express themselves through my writing. i have a passion for story
        writing and have been maintaining a journal for the past 5 years. now i aspire to work as a 
        content creator.
    </p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li> Storyteller </li>
      <li> Journaler </li>
      <li> Content Creator </li>
      </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class=" writings ">
      <h3> story writing </h3>
      <a href="project2-link.html">View Project</a>
      <h3> poem </h3>
      <a href="project3-link.html">View Project</a>
    </div>
    </section>
    <section id="resume">
      <h2>Resume</h2>
      <a href="your-resume.pdf"target="_blank">Download Resume</a>
    </section>
  <footer>
    <p>&copy; 2024 Ruchi kumari </p>
    <ul>
      <li><a href="ruchiuptowork@email.com">Contact</a></li>
      <li><a href="tel:1234567890">Phone</a></li>
    </ul>
  </footer>
</body>
</html>

#csscode
body {
  font-family: Arial, sans-serif;
  background-color: antiquewhite;
}

header {
  text-align: center;
}

#about img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
}

#skills ul {
  list-style: none;
  padding: 0;
}

.project {
  border: 1px solid #ccc;
  padding: 20px;
  margin-bottom: 20px;
}
