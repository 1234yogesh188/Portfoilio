<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0"
    />
    <title>My Portfolio</title>
    <!-- Import React and ReactDOM -->
    <script
      src="https://unpkg.com/react@17/umd/react.development.js"
      crossorigin
    ></script>
    <script
      src="https://unpkg.com/react-dom@17/umd/react-dom.development.js"
      crossorigin
    ></script>
    <script
      src="https://unpkg.com/babel-standalone@6/babel.min.js"
    ></script>
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        color: #333;
        text-align: center;
      }

      header {
        background-color: #333;
        color: white;
        padding: 20px;
      }

      header h1 {
        font-size: 2.5rem;
      }

      section {
        margin: 20px auto;
        padding: 20px;
        max-width: 800px;
        background-color: #fff;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      h2 {
        font-size: 2rem;
        margin-bottom: 15px;
      }

      .about-section,
      .education-section,
      .experience-section,
      .skills-section,
      .projects-section {
        text-align: center;
      }

      ul {
        list-style-type: none;
      }

      .experience-item,
      .project-item {
        display: flex;
        align-items: center;
        justify-content: center;
        margin: 20px 0;
      }

      .experience-item img,
      .project-item img {
        margin-right: 20px;
        width: 150px;
        height: 150px;
      }

      footer {
        background-color: #333;
        color: white;
        padding: 10px;
      }

      footer p {
        margin: 0;
      }
    </style>
  </head>
  <body>
    <div id="root"></div>

    <script type="text/babel">
      const App = () => {
        return (
          <div className="portfolio">
            <Header />
            <About />
            <Education />
            <Experience />
            <Skills />
            <Projects />
            <Footer />
          </div>
        );
      };

      const Header = () => (
        <header>
          <h1>My Portfolio</h1>
          <p>Welcome to my personal website</p>
        </header>
      );

      const About = () => (
        <section className="about-section">
          <h2>About Me</h2>
          <p>
            Hi! I am an experienced web developer and programmer. I specialize in
            creating responsive and visually appealing websites using modern web
            technologies like HTML, CSS, JavaScript, and React.
          </p>
        </section>
      );

      const Education = () => (
        <section className="education-section">
          <h2>Education</h2>
          <p>B.Sc. Computer Science, XYZ University</p>
          <p>Courses: Java, Data Structures, Web Development, React, AI</p>
        </section>
      );

      const Experience = () => (
        <section className="experience-section">
          <h2>Experience</h2>
          <div className="experience-item">
            <img src="https://via.placeholder.com/150" alt="Experience 1" />
            <div>
              <h3>Software Developer at ABC Corp</h3>
              <p>
                Developed and maintained web applications using React and Node.js.
              </p>
            </div>
          </div>
          <div className="experience-item">
            <img src="https://via.placeholder.com/150" alt="Experience 2" />
            <div>
              <h3>Frontend Developer at XYZ Solutions</h3>
              <p>Worked on UI/UX designs and frontend development using React.</p>
            </div>
          </div>
        </section>
      );

      const Skills = () => (
        <section className="skills-section">
          <h2>Skills</h2>
          <ul>
            <li>JavaScript</li>
            <li>React.js</li>
            <li>HTML & CSS</li>
            <li>Node.js</li>
            <li>Git & GitHub</li>
          </ul>
        </section>
      );

      const Projects = () => (
        <section className="projects-section">
          <h2>Projects</h2>
          <div className="project-item">
            <img src="https://via.placeholder.com/150" alt="Project 1" />
            <div>
              <h3>Project Title 1</h3>
              <p>Short description of the project. Used React, Node.js, and MongoDB.</p>
            </div>
          </div>
          <div className="project-item">
            <img src="https://via.placeholder.com/150" alt="Project 2" />
            <div>
              <h3>Project Title 2</h3>
              <p>
                Another project description. Built with React, HTML, CSS, and JavaScript.
              </p>
            </div>
          </div>
        </section>
      );

      const Footer = () => (
        <footer>
          <p>© 2024 My Portfolio | Designed by Me</p>
        </footer>
      );

      ReactDOM.render(<App />, document.getElementById("root"));
    </script>
  </body>
</html>
