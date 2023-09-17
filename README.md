<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Front-End Developer</title>
    <style>
        /* Reset some default styles */
        body, h1, h2, p {
            margin: 0;
            padding: 0;
            /* color: aquamarine; */
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }

        header {
            background-color: #c7cf5b;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        h1 {
            font-size: 36px;
            margin-bottom: 10px;
            color: rgb(173, 120, 51);
        }

        h2 {
            font-size: 24px;
            margin-bottom: 20px;
        }

        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 20px;
        }

        .projects {
            display: flex;
            flex-wrap: wrap;
        }

        .project {
            width: calc(33.33% - 20px);
            margin: 10px;
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        /* Style for the stars */
 .stars {
    font-size: 20px; /* Adjust the font size as needed */
    margin-left: 5px; /* Add some spacing between the language name and stars */
    color: rgb(71, 224, 25);
}

/* Style for the experience section */
#experience {
    margin-top: 20px;
    color:chocolate;
    /* text-shadow: #333; */
}

/* Style for the experience item */
.experience-item {
    margin-bottom: 20px;
}

/* Style for the job title */
.experience-item h3 {
    font-size: 18px;
    color: #300b86;
    margin-bottom: 10px;
}

/* Style for the date range */
.experience-item h3::after {
    content: "";
    display: inline-block;
    width: 10px;
    height: 10px;
    background-color: #333;
    border-radius: 50%;
    margin-left: 10px;
    margin-right: 5px;
    position: relative;
    top: -2px;
}

/* Style for the list items */
.experience-item ul {
    list-style-type: disc;
    margin-left: 20px;
    padding-left: 0;
}

/* Style for the list items */
.experience-item ul li {
    font-size: 16px;
    color: #666;
    margin-bottom: 5px;
}

/* Style for the list item bullet points */
.experience-item ul li::before {
    content: "\2022"; /* Bullet point character */
    color: #00a600; /* Green color for bullet points */
    font-weight: bold;
    display: inline-block;
    width: 1em;
    margin-left: -1em;
}

/* Style for the education section */
#education {
    margin-top: 20px;
    color: chocolate;
}

/* Style for the education items */
.education-item {
    margin-bottom: 20px;
}

/* Style for the degree/diploma titles */
.education-item h3 {
    font-size: 18px;
    color: #333;
    margin-bottom: 10px;
}

/* Style for the school/university names */
.education-item p strong:first-child {
    font-weight: bold;
    color: #333;
}

/* Style for the location and year details */
.education-item p {
    font-size: 16px;
    color: #666;
    margin-bottom: 5px;
}

/* Style for the location and year details */
.education-item p strong:not(:first-child) {
    font-weight: normal;
    color: #666;
}
/* Style for the education section */
#education {
    margin-top: 20px;
}

/* Style for the education items */
.education-item {
    margin-bottom: 20px;
}

/* Style for the degree/diploma titles */
.education-item h3 {
    font-size: 18px;
    color: #333;
    margin-bottom: 10px;
}

/* Style for the school/university names */
.education-item p strong:first-child {
    font-weight: bold;
    color: #333;
}

/* Style for the location and year details */
.education-item p {
    font-size: 16px;
    color: #666;
    margin-bottom: 5px;
}

/* Style for the location and year details */
.education-item p strong:not(:first-child) {
    font-weight: normal;
    color: #666;
}





    </style>
</head>
<body>
    <header>
        <img src="C:\Users\harsh\OneDrive\Pictures\darshan immage.jpeg" alt="Your Name's Profile Picture" width="150" height="150">
        <h1>Darshan H Y</h1>
        <h2>Front-End Developer</h2>
        <h3>Contact No:7338541530</h3>
    </header>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
                <p>
                    Hi, I'm Darshan H Y, a passionate front-end developer with 1 years of experience in crafting interactive and user-friendly web experiences. My journey in web development started with a curiosity to create beautiful and functional websites that leave a lasting impression.
                </p>
                
                <ul>
                    <li>HTML5, CSS3, and JavaScript for building the foundation of web projects.</li>
                    <li>Responsive web design to ensure an optimal experience on all devices and screen sizes.</li>
                    <li>Optimizing website performance and loading speed for an exceptional user experience.</li>
                </ul>
                
                <p>
                    I am constantly learning and adapting to stay current with the latest web development trends and technologies. My passion for coding and problem-solving drives me to create innovative solutions that not only meet but exceed client expectations.
                </p>
                
                <p>
                    When I'm not coding, you can find me exploring new web design concepts, collaborating with creative teams, or enjoying a cup of coffee while brainstorming my next project.
                </p>
        </section><br>

        <body>
            <h1>Project List</h1>
            
            <!-- Link to Project 1 Page -->
            <a href="project1.html">Project 1: Automated PO Sharing</a> <br><br>
            
            <!-- Link to Project 2 Page -->
            <a href="project2.html">Project 2: Another Project</a>
        </body> 
        <!-- <section id="projects">
            <h2>Projects</h2>
            <div class="projects">
                <div class="project">
                    <h3>Automated Purchase Order Sharing from Google Sheet </h3>
                    <p>The goal of this project is to create a web application that automates the process of sharing purchase orders (POs) stored in a Google Sheet with relevant stakeholders. This automation will streamline the PO approval and distribution process, making it more efficient and error-free.</p>
                </div>
                <div class="project">
                    <h3>Project 2</h3>
                    <p>Description of project 2.</p>
                </div>
                <div class="project">
                    <h3>Project 3</h3>
                    <p>Description of project 3.</p>
                </div>
            </div>
        </section><br> -->

        <section id="education">
            <h2>Education</h2>
            
            <div class="education-item">
                <h3>Bachelor of Computer Application</h3>
                <p><strong>University:</strong> ST Joseph University</p>
                <p><strong>Location:</strong> 36, Langford Rd, Langford Gardens, Bengaluru 560027, Karnataka</p>
                <p><strong>Year of Graduation:</strong> 2023</p>
            </div>
            
            <div class="education-item">
                <h3>Class 12</h3>
                <p><strong>School Name:</strong> Al Falah Pre-University</p>
                <p><strong>Location:</strong> Mgadi, Ramanagara 562120, Karnataka</p>
                <p><strong>Year of Graduation:</strong> 2020</p>
            </div>
        </section><br>

        
        

        <section id="Skils">
            <section id="languages">
                <h2>Programming Languages</h2>
                <ul>
                    <li>
                        <span class="language">HTML</span>
                        <span class="stars">★★★☆☆</span>
                    </li>
                    <li>
                        <span class="language">JavaScript</span>
                        <span class="stars">★★★☆☆</span>
                    </li>
                    <li>
                        <span class="language">CSS</span>
                        <span class="stars">★★★☆☆</span>
                    </li>
                    <li>
                        <span class="language">Java</span>
                        <span class="stars">★★★☆☆</span>
                    </li>
                    <li>
                        <span class="language">Python</span>
                        <span class="stars">★★★☆☆</span>
                    </li>
                </ul>
            </section>
            
        </section>

        
        <section id="experience">
            <h2>Experience</h2>
            
            <div class="experience-item">
                <h3>Stellapps (Jan 2018 - June 2019)</h3>
                <ul>
                    <li>Devised strategic approaches to establish profitable logistics operations, enhance service quality, and drive supply chain efficiency, resulting in increased profit margins.</li>
                    <li>Orchestrated seamless coordination of forwarding transportation activities with external contractors, ensuring timely and efficient delivery of goods.</li>
                    <li>Implemented effective inventory management practices to maintain optimal inventory levels while minimizing costs.</li>
                </ul>
            </div>
            
            <div class="experience-item">
                <h3>NinjaCart (June 2019 - Sep 2021)</h3>
                <ul>
                    <li>Spearheaded the planning and design of system improvements to effectively address evolving demands.</li>
                    <li>Conducted user training and provided comprehensive support to resolve hardware and software issues across diverse areas.</li>
                    <li>Installed enhancements and fine-tuned parameters to optimize system functionality and performance.</li>
                    <li>Developed clear and concise diagrams to illustrate logical operational steps, ensuring smooth workflow processes.</li>
                    <li>Effectively communicated and conveyed business requirements to team members, facilitating a thorough understanding and successful implementation of functional demands.</li>
                </ul>
            </div>
            
            <div class="experience-item">
                <h3>Meesho (Sep 2021 - Current)</h3>
                <ul>
                    <li>Developed comprehensive project plans, effectively communicated deadlines, and consistently met or exceeded project milestones.</li>
                    <li>Successfully achieved a remarkable reduction in Days of Inventory on Hand (DOH) from 17.7 to 7.5 within a span of one month.</li>
                    <li>Proficient in utilizing advanced data analysis techniques, including pivot tables, charts, and macros, to gather and manipulate data for insightful decision-making.</li>
                    <li>Created dynamic sales visibility dashboards, providing real-time insights and enabling data-driven strategic decision-making.</li>
                    <li>Implemented an automated script to seamlessly extract data from external sources and populate it into Google Sheets, significantly reducing manual effort and improving data accuracy.</li>
                    <li>Proactively automated various manual processes, streamlining operations and enhancing productivity by leveraging scripting and automation tools.</li>
                </ul>
            </div>
        </section><br>
        
        <section id="contact">
            <h2>Contact Me</h2>
            <p>You can reach me at <a href="mailto:darshan.hy1722@gmail.com">darshan.hy1722@gmail.com</a></p>

        </section>
    </div>
</body>
</html>
