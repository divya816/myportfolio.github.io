<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* General Styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #3498db;
            color: white;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        /* Header */
        header {
            padding: 30px 0;
            background-color: #2980b9;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        /* Buttons */
        button {
            background-color: white;
            color: black;
            border: none;
            padding: 12px 24px;
            font-size: 1rem;
            margin: 10px;
            border-radius: 5px;
            cursor: pointer;
            transition: 0.3s ease-in-out;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }

        button:hover {
            background-color: lightgray;
        }

        /* Sections */
        section {
            background-color: white;
            color: black;
            padding: 30px;
            margin: 20px auto;
            width: 80%;
            max-width: 800px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        /* Tables */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }

        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }

        th {
            background-color: #f2f2f2;
        }

        /* Profile Image */
        .profile-img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-top: 10px;
        }

        /* Footer */
        footer {
            background-color: black;
            color: white;
            padding: 20px;
            margin-top: 30px;
        }

        /* Smooth Scrolling */
        html {
            scroll-behavior: smooth;
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            section {
                width: 90%;
                padding: 20px;
            }

            button {
                width: 90%;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Welcome to My Portfolio</h1>
        <a href="#about"><button>About</button></a>
        <a href="#education"><button>Education</button></a>
        <a href="#skills"><button>Skills</button></a>
        <a href="#projects"><button>Projects</button></a>
    </header>

    <main>

        <!-- About Section -->
        <section id="about">
            <h1>Divya Deepika Malyavantham</h1>
            <img src="C:\Users\DELL\OneDrive\Documents\lk1.jpg" alt="Profile Picture" width="200px" height="300px">
            <p>I am an enthusiastic Electronics and Communication Engineering (ECE) undergraduate in <em><b>Sri Padmavathi Mahila Visvavidyalayam</em></b> with a strong passion for technology and innovation.</p>
        </section>

        <!-- Education Section -->
        <section id="education">
            <h1>Education</h1>
            <table>
                <tr>
                    <th>Course</th>
                    <th>Institution</th>
                    <th>Board/University</th>
                    <th>Year of Completion</th>
                    <th>Percentage</th>
                </tr>
                <tr>
                    <td>B.Tech (ECE)</td>
                    <td>Sri Padmavathi Mahila Visvavidyalayam, Tirupati</td>
                    <td>School of Engineering and Technology, Andhra Pradesh</td>
                    <td>2024</td>
                    <td>77%</td>
                </tr>
                <tr>
                    <td>Intermediate (MPC)</td>
                    <td>Narayana Junior College, Kadapa</td>
                    <td>Board of Intermediate Education, Andhra Pradesh</td>
                    <td>2020</td>
                    <td>89%</td>
                </tr>
                <tr>
                    <td>Secondary School</td>
                    <td>Vidya Mandir English Medium High School, Kadapa</td>
                    <td>Central Board of Secondary Education</td>
                    <td>2018</td>
                    <td>70%</td>
                </tr>
            </table>
        </section>

        <!-- Skills Section -->
        <section id="skills">
            <h1>My Skills</h1>
            <ul style="display: inline-block; text-align: left;">
                <li>Python Basics</li>
                <li>HTML and CSS Basics</li>
                <li>JavaScript Basics</li>
                <li>Software Testing</li>
                <li>Amazon Web Services</li>
            </ul>
        </section>

        <!-- Projects Section -->
        <section id="projects">
            <h1>My Projects</h1>
            <table>
                <tr>
                    <th>Projects</th>
                    <th>Description</th>
                </tr>
                <tr>
                    <td>Portfolio Website</td>
                    <td>I have built a Portfolio Website using HTML, CSS & JavaScript.</td>
                </tr>
                <tr>
                    <td>Python Simple Calculator</td>
                    <td>I have built a simple calculator using Python.</td>
                </tr>
            </table>
        </section>

    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>

</body>
</html>
