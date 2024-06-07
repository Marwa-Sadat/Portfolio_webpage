Personal Portfolio 🚀

## Project Description 📝

> 🌟 Welcome to Marwa Sadat's Portfolio! 🌟

Welcome to my personal portfolio! 🌟 I'm Marwa Sadat, a passionate web developer with expertise in creating dynamic and responsive web applications. 💻 With a strong background in computer science and a love for the latest web technologies, I strive to deliver high-quality solutions. Let's explore my projects and skills! 

Featuring:

- *Home:* Explore my story and passion for web development.
- *About:* Learn more about my dedication and journey in the field.
- *Projects:* Dive into my portfolio, featuring projects like Tribute Pages, Technical Documentation, and Landing Pages.
- *Contact:* Interested in collaborating or need assistance with a project? Reach out, and let's make it happen!

---

Crafted with simplicity and practicality, this portfolio serves as a testament to my dedication and skills in web development. Happy exploring! 🚀

html
<!-- Welcome to Marwa Sadat's Portfolio! -->
<!DOCTYPE html>
  <html lang="en">
  <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marwa Sadat's Personal Portfolio</title>
  <link rel="stylesheet" href="styles.css">
  </head>
  <body>
  <header id="navbar">
    <div class="container">
        <img id="header-img" src="https://cdn.pixabay.com/photo/2022/01/30/13/33/github-6980894_1280.png" alt="Logo">
    </div>
  </header><section id="welcome-section">
    <div class="container">
        <h1>Welcome to My Portfolio</h1>
        <p>I am [MARWAS_SADAT], a Web Developer and Graphic Designer</p>
    </div>
  </section>
  <section id="projects">
    <div class="container">
        <h2>Projects</h2>
        <div class="project-tile">
            <h3>Project 1</h3>
            <p>Odin Project: An educational platform that utilizes HTML, CSS, Git, GitHub, and Command Line, empowering learners to master web development through structured courses and practical projects.</p>
            <a href="https://github.com/Marwa-Sadat/odin_project/pulls" target="_blank">View Project</a>
        </div>
        <div class="project-tile">
        </div>
    </section>
    <section id="contact">
        <h2>Contact Me</h2>
  </section>
  <footer>
    <div class="container">
      <p>M.S."thank you for visiting my portfolio. © 2024 All rights reserved."</p>
    </div>
  </footer>


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
  scroll-behavior: smooth;
}

.header {
  position: fixed;
  top: 0;
  left: 0;
  background-color: black;
  display: flex;
  justify-content: space-between;
  width: 100%;
  padding: 0 10%;
  align-items: center;
  z-index: 100;
}

.logo img {
  width: 200px;
  height: 80px;
  opacity: 0;
  animation: SlideR 1s ease forwards, updown 3s ease-in-out infinite;
  animation-delay: 0, 4s;
}

.home-content h1 {
  font-size: 56px;
  line-height: 130%;
  background-image: linear-gradient(
    -225deg,
    #ee5ff3 0%,
    #28f4f8 29%,
    #f2a456 67%,
    #ed5504 100%
  );
  background-size: 200% auto;
  color: #fff;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 3s linear infinite;
  display: inline-block;
  opacity: 0;
  animation: SlideR 1s ease forwards;
  animation-delay: 1s;
}


## Demo 📸

![Project Gif](https://github.com/Marwa-Sadat/Portfolio_webpage/assets/168111110/eeb17287-15d7-487a-b0e9-3ad1fac362cb)

## Technologies Used 🛠

- [HTML]
- [CSS]

## Usage 🎯

To use this project, follow these steps:

1. *Installation:*
   If you haven't already, follow the installation instructions mentioned in the [Installation](#installation-) section to clone the repository.

2. *Navigate to project directory:*
   bash
   cd Technical-Documentation-page
   
3. *Open the HTML file:*
   Open the index.html file in your preferred web browser. You can do this by double-clicking the file or using a command-line tool like open (for macOS) or start (for Windows).

4. *Explore the documentation:*
   Once the HTML file is opened, you'll have access to the technical documentation page. Navigate through different sections using the sidebar navigation or scroll through the content to learn about various topics.

5. *Modify as needed:*
   If you'd like to customize the documentation page or add your own content, feel free to edit the HTML and CSS files in your text editor of choice.

6. *Share and contribute:*
   If you find this project helpful, consider sharing it with others. You can also contribute to the project by submitting bug reports, feature requests, or pull requests to improve it for everyone.

## Author 👩‍💻

- LinkedIn: [Marwa Sadat](www.linkedin.com/in/MarwaSadat-aa362030b)
- Email: (marwasadat735@gmail.com)

## Contributing 🤝

Thank you for considering contributing to this project! Contributions from the community help improve the project for everyone.

### How to Contribute

If you'd like to contribute to this project, follow these steps:

1.  *Fork the repository:*
    Fork the repository to your own GitHub account.

2.  *Clone the repository:*
    Clone the repository to your local machine.

    bash
    git clone https://github.com/Marwa-Sadat/Portfolio_webpage.git
    

3.  *Create a new branch:*
    Create a new branch with a descriptive name to work on your contribution.

    bash
    git checkout -b feature/new-feature

    

4.  *Make your changes:*
    Make your changes to the project in your local environment. Ensure that your changes are in line with the project's coding conventions and style guidelines.

5.  *Commit your changes:*
    Once you've made your changes, commit them to your branch with clear and descriptive commit messages.

    bash
    git commit -a m 'Add new feature'

    

6.  *Push your changes:*
    Push your changes to your forked repository on GitHub.

    bash
    git push origin feature/new-feature

    

7.  *Submit a pull request:*
    Go to the original repository on GitHub and submit a pull request with your changes.