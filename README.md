<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adithy Shibu - Portfolio</title>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Adithy Shibu</h1>
        <h3>B.Tech Student | Federal Institute of Science and Technology (FISAT)</h3>

        <p>
            Welcome to my personal portfolio website. This webpage presents information about
            my academic journey, technical skills, projects, interests, achievements, and
            contact details. As an engineering student, I am passionate about learning new
            technologies and applying theoretical concepts to practical applications.
        </p>

        <nav>
            <a href="#profile">Profile</a> |
            <a href="#education">Education</a> |
            <a href="#skills">Skills</a> |
            <a href="#projects">Projects</a> |
            <a href="#media">Media</a> |
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <hr>

    <!-- Profile Section -->
    <section id="profile">
        <h2>Profile Summary</h2>

        <img src="adithy.jpg" alt="Adithy Shibu Photo" width="220">

        <p>
            My name is Adithy Shibu and I am currently pursuing my Bachelor of Technology
            degree at Federal Institute of Science and Technology (FISAT). I am enthusiastic
            about engineering innovations and enjoy exploring modern technologies that can
            solve real-world challenges. Through academic studies and project development,
            I continuously work on improving my technical knowledge and problem-solving skills.
        </p>

        <p>
            I believe engineering is not only about understanding concepts but also about
            implementing them to create meaningful solutions. My areas of interest include
            renewable energy systems, robotics, automation, electronics, and embedded systems.
        </p>
    </section>

    <hr>

    <!-- Education Section -->
    <section id="education">
        <h2>Educational Qualifications</h2>

        <table border="1">
            <caption><strong>Academic Details</strong></caption>

            <tr>
                <th>Course</th>
                <th>Institution</th>
                <th>Status</th>
            </tr>

            <tr>
                <td>B.Tech</td>
                <td>Federal Institute of Science and Technology (FISAT)</td>
                <td>Currently Pursuing</td>
            </tr>

            <tr>
                <td>Higher Secondary Education</td>
                <td>Completed</td>
                <td>Passed</td>
            </tr>

            <tr>
                <td>Secondary Education</td>
                <td>Completed</td>
                <td>Passed</td>
            </tr>
        </table>

        <p>
            My academic journey has helped me gain knowledge in engineering fundamentals,
            practical laboratory experiments, project development, and teamwork. I actively
            participate in technical activities that enhance my understanding of engineering concepts.
        </p>
    </section>

    <hr>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Technical Skills</h2>

        <ul>
            <li>Basic Programming in C</li>
            <li>HTML Fundamentals</li>
            <li>Electronics and Circuit Analysis</li>
            <li>Problem Solving</li>
            <li>Robotics Concepts</li>
            <li>Renewable Energy Applications</li>
            <li>Project Documentation</li>
        </ul>

        <h3>Soft Skills</h3>

        <ol>
            <li>Communication</li>
            <li>Leadership</li>
            <li>Team Collaboration</li>
            <li>Adaptability</li>
            <li>Time Management</li>
        </ol>
    </section>

    <hr>

    <!-- Projects -->
    <section id="projects">
        <h2>Academic Projects</h2>

        <article>
            <h3>Solar Copra Dryer</h3>

            <p>
                The Solar Copra Dryer project was developed to improve the traditional
                process of drying coconuts for copra production. The system utilizes solar
                energy as a sustainable heat source, reducing dependence on conventional fuels.
                This project promotes eco-friendly drying techniques while improving efficiency
                and product quality.
            </p>
        </article>

        <article>
            <h3>Rover Project</h3>

            <p>
                The Rover Project focuses on designing and developing a mobile robotic vehicle
                capable of navigating different terrains. The rover can be used for remote
                monitoring, exploration, and data collection. Through this project, I gained
                experience in mechanical design, electronics integration, and system control.
            </p>
        </article>
    </section>

    <hr>

    <!-- Achievements -->
    <section>
        <h2>Achievements and Activities</h2>

        <ul>
            <li>Participated in technical workshops and seminars.</li>
            <li>Completed project-based learning activities.</li>
            <li>Worked collaboratively in team projects.</li>
            <li>Actively involved in academic presentations.</li>
        </ul>
    </section>

    <hr>

    <!-- Gallery -->
    <section>
        <h2>Gallery</h2>

        <figure>
            <img src="rover.jpg" alt="Rover Project" width="300">
            <figcaption>Rover Project Demonstration</figcaption>
        </figure>

        <figure>
            <img src="solar-dryer.jpg" alt="Solar Copra Dryer" width="300">
            <figcaption>Solar Copra Dryer Model</figcaption>
        </figure>
    </section>

    <hr>

    <!-- Audio and Video -->
    <section id="media">
        <h2>Multimedia Section</h2>

        <h3>Audio Introduction</h3>

        <audio controls>
            <source src="intro.mp3" type="audio/mpeg">
            Audio not supported.
        </audio>

        <p>
            This audio recording contains a brief introduction about my academic background,
            interests, and future career aspirations.
        </p>

        <h3>Project Demonstration Video</h3>

        <video width="500" controls>
            <source src="project.mp4" type="video/mp4">
            Video not supported.
        </video>

        <p>
            The video demonstrates the working principles and functionality of my engineering projects.
        </p>
    </section>

    <hr>

    <!-- Useful Links -->
    <section>
        <h2>Useful Links</h2>

        <p>
            Visit the official website of
            <a href="https://fisat.ac.in" target="_blank">
                Federal Institute of Science and Technology
            </a>.
        </p>

        <ul>
            <li><a href="https://github.com" target="_blank">GitHub</a></li>
            <li><a href="https://www.linkedin.com" target="_blank">LinkedIn</a></li>
            <li><a href="mailto:adithy@example.com">Send Email</a></li>
        </ul>
    </section>

    <hr>

    <!-- Contact Form -->
    <section id="contact">
        <h2>Contact Form</h2>

        <form action="#">

            <fieldset>
                <legend>Personal Information</legend>

                <label>Name:</label><br>
                <input type="text" name="name"><br><br>

                <label>Email:</label><br>
                <input type="email" name="email"><br><br>

                <label>Phone Number:</label><br>
                <input type="tel" name="phone"><br><br>

                <label>Date of Birth:</label><br>
                <input type="date"><br><br>

                <label>Gender:</label><br>

                <input type="radio" name="gender"> Male
                <input type="radio" name="gender"> Female
                <br><br>

                <label>Select Area of Interest:</label><br>

                <input type="checkbox"> Robotics<br>
                <input type="checkbox"> Renewable Energy<br>
                <input type="checkbox"> Electronics<br><br>

                <label>Message:</label><br>
                <textarea rows="5" cols="40"></textarea><br><br>

                <input type="submit" value="Submit">
                <input type="reset" value="Clear">
            </fieldset>

        </form>
    </section>

    <hr>

    <!-- Extra Tags Demonstration -->
    <section>
        <h2>Additional HTML Tags Used</h2>

        <p><strong>Strong Tag:</strong> Important information.</p>
        <p><em>Emphasis Tag:</em> Highlighted text.</p>
        <p><mark>Marked Text Example</mark></p>
        <p>H<sub>2</sub>O (Subscript Example)</p>
        <p>x<sup>2</sup> + y<sup>2</sup> (Superscript Example)</p>

        <details>
            <summary>Click to View Career Objective</summary>
            <p>
                To become a skilled engineer capable of contributing innovative
                solutions in the fields of robotics, renewable energy, and technology.
            </p>
        </details>
    </section>

    <hr>

    <!-- Footer -->
    <footer>
        <p>
            © 2026 Adithy Shibu | Student Portfolio
        </p>

        <p>
            Federal Institute of Science and Technology (FISAT)
        </p>
    </footer>

</body>
</html>
