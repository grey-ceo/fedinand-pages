# fedinand-pages
when opened it shows details on my cv

<!DOCTYPE html>
<html>
<head>
    <title>My Personal Website</title>

    <style>
        body {
            background-color: blue;
            color: white;
            font-family: Arial;
            margin: 0;
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: darkblue;
        }

        nav {
            text-align: center;
            background-color: navy;
            padding: 15px;
        }

        nav button {
            background-color: white;
            color: blue;
            border: none;
            padding: 12px;
            margin: 5px;
            cursor: pointer;
            font-weight: bold;
        }

        nav button:hover {
            background-color: lightblue;
        }

        .page {
            display: none;
            background-color: white;
            color: black;
            margin: 25px auto;
            padding: 25px;
            width: 85%;
            min-height: 350px;
        }

        #home {
            display: block;
        }

        img {
            border: 3px solid blue;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            border: 1px solid black;
            padding: 12px;
            text-align: left;
        }

        th {
            background-color: lightblue;
        }

        footer {
            text-align: center;
            padding: 15px;
        }
    </style>

    <script>
        function showPage(pageName) {

            var pages = document.getElementsByClassName("page");

            for (var i = 0; i < pages.length; i++) {
                pages[i].style.display = "none";
            }

            document.getElementById(pageName).style.display = "block";
        }
    </script>

</head>

<body>

<header>
    <h1>MY PERSONAL WEBSITE</h1>
</header>

<nav>
    <button onclick="showPage('home')">HOME</button>

    <button onclick="showPage('experience')">
        PERSONAL EXPERIENCE
    </button>

    <button onclick="showPage('contacts')">CONTACTS</button>

    <button onclick="showPage('hobbies')">HOBBIES</button>
</nav>


<!-- HOME PAGE -->

<section id="home" class="page">

    <center>
        <h2>HOME</h2>

        <img src="SAVE_20250825_075055 (1).jpg"
             alt="My Photo"
             width="180"
             height="180">

        <h2>ABOUT ME</h2>
    </center>

    <p><b>Name:</b> FEDINAND MAKOKHA</p>

    <p>
        <b>Course:</b>
        Bachelor of Information Technology
    </p>

    <p>
        <b>Background:</b>
        I am an Information Technology student
        interested in computers, programming,
        web development and information systems.
    </p>

    <p>
        I enjoy learning new technologies and
        developing computer solutions to solve
        real-world problems.
    </p>

    <h3>What I hope to do after my course</h3>

    <p>
        After completing my course, I hope to work
        in the Information Technology field, gain
        professional experience and develop useful
        software and information systems.
    </p>

</section>


<!-- PERSONAL EXPERIENCE PAGE -->

<section id="experience" class="page">

    <center>
        <h2>PERSONAL EXPERIENCE</h2>

        <h3>MY CURRICULUM VITAE</h3>
    </center>

    <table>

        <tr>
            <th>Date</th>
            <th>Institutions Attended</th>
            <th>Awards Given</th>
        </tr>

        <tr>
            <td>2021 - 2024</td>
            <td>Silungai Secondary School</td>
            <td>Certificate of Secondary Education</td>
        </tr>

        <tr>
            <td>2023 - Present</td>
            <td>Kisii University</td>
            <td>Information Technology Student</td>
        </tr>

        <tr>
            <td>2024</td>
            <td>Kisii University</td>
            <td>BACHELOR OF SCIENCE AND TECHNOLOGY</td>
        </tr>

    </table>

</section>


<!-- CONTACTS PAGE -->

<section id="contacts" class="page">

    <center>
        <h2>CONTACTS</h2>
    </center>

    <p><b>Name:</b> FEDINAND MAKOKHA</p>

    <p><b>Phone:</b> +254 746381160</p>

    <p><b>Email:</b> molockygrey267@gmail.com</p>

    <p><b>Location:</b> Kenya</p>

    <p>
        <a href="mailto:molockygrey267@gmail.com">
            Email me
        </a>
    </p>

</section>


<!-- HOBBIES PAGE -->

<section id="hobbies" class="page">

    <center>
        <h2>MY HOBBIES</h2>
    </center>

    <ul>
        <li>Playing handball</li>
        <li>Watching handball</li>
        <li>Listening to music</li>
        <li>Learning programming</li>
        <li>Designing websites</li>
        <li>Travelling</li>
    </ul>

</section>


<footer>
    <hr>
    <p>&copy; 2026 My Personal Website</p>
    <p>FEDINAND MAKOKHA</p>
</footer>

</body>
</html>
