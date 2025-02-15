# Web Development Project  
[![Netlify Status](https://api.netlify.com/api/v1/badges/a17313e1-0d35-48d5-b659-54a709f97f06/deploy-status)](https://willowy-biscochitos-d1238e.netlify.app/)
<br>
Group Members:
Jasmine kaur  - Responsible for Overall website ,Design, Color scheme, and Theme.<br>
Gursimran Kaur - Table and content use<br>
Avneet Kaur - Images and links<br>
<br>
<h2>Project Overview</h2>
Portfolio Website Overview - Team Project
Design & Theme
Color Scheme: The website features a purple-themed design with various shades of purple for consistency and contrast.
Typography: Custom fonts and styles are defined in SASS for a cohesive look.
Responsive Layout: Utilizes Bootstrap's grid system and media queries for mobile compatibility.
Project Structure
Web Development Framework

<h2>About</h2>

This is a lightweight and customizable web development framework created by Jasmine Kaur, Avneet Kaur, and Gursimran Kaur. It provides a solid foundation for building responsive and modern web applications.

## Project Overview  
This project is a web-based application developed using HTML, CSS, JavaScript, and PHP. It includes dynamic content, interactive features, and a responsive design to ensure a smooth user experience.  

## Installation  
To set up the project locally:  
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-github-username/your-repository-name.git

Navigate to the project directory:
sh
cd your-repository-name

If using PHP, start a local server:
sh
php -S localhost:8000

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
Install Dependencies:

To include installation instructions for Sass in your GitHub repository's README file, you can use the following template:

```markdown
## Installation

To set up this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
   ```

2. **Install Dependencies**:
   - **Using npm**:
     ```bash
     npm install
     ```
   - **Using Yarn**:
     ```bash
     yarn install
     ```

3. **Install Sass**:
   - **Globally via npm**:
     ```bash
     npm install -g sass
     ```
   - **Locally via npm**:
     ```bash
     npm install sass --save-dev
     ```
   - **Using Homebrew (macOS)**:
     ```bash
     brew install sass/sass/sass
     ```
   - **Using Chocolatey (Windows)**:
     ```bash
     choco install sass
     ```

4. **Compile Sass to CSS**:
   ```bash
   sass source/stylesheets/index.scss build/stylesheets/index.css
   ```

5. **Run the Application**:
   ```bash
   npm start
   ```

6. **Access the Application**:
   Open your browser and navigate to `http://localhost:3000` to view the application.
```

Replace placeholders like `your-username`, `your-repository-name`, and specific commands with details relevant to your project.

For more detailed information on installing Sass, refer to the [official Sass installation guide](https://sass-lang.com/install/).

Usage
Open the project in a browser to explore the web application.
Navigate through different pages to interact with the features.
If applicable, use the admin panel to manage content.
Customization
You can customize the project by modifying the following files:

HTML: Edit structure and content in .html or .php files.
CSS: Modify styles in style.css to change the appearance.
JavaScript: Enhance functionality in script.js.
Features
Responsive design for all devices
Interactive UI components
Dynamic content using JavaScript and PHP
Custom theme support

Example Usage
<section id="home" class="intro-section">
  <div class="container">
    <div class="row align-items-center text-white">
      <!-- START THE CONTENT FOR THE INTRO -->
      <div class="col-md-6 intros text-start">
        <h1 class="display-2">Welcome,</h1>
        <h2>Our Web Development Team</h2>
        <p class="display-2--description lh-base">
          We are a team of three passionate web developers dedicated to creating modern, user-friendly, and high-performing websites. With expertise in front-end and back-end development, we specialize in crafting responsive and dynamic web experiences tailored to our clients' needs.
        </p>
        <button type="button" class="rounded-pill btn-rounded">
          Get in Touch
          <span><i class="fas fa-arrow-right"></i></span>
        </button>
      </div>

      Component: Intro Section (Built with Bootstrap & Sass)
Bootstrap Usage
Grid System (row and col-md-6)

Bootstrap’s grid system (row and col-md-6) ensures a two-column layout, making the text and image sit side by side.
This structure makes the section responsive, automatically stacking on smaller screens.
Typography (display-2, lh-base)

Bootstrap’s typography classes (display-2 for large headings, lh-base for line height) ensure consistent styling across different screen sizes.
Button (btn-rounded)

A Bootstrap-based button is styled with a custom class (rounded-pill) to make it pill-shaped.
Positioning (position-absolute, top-50, start-50, translate-middle)

<h2>Sass Implementation</h2>
Bootstrap’s position utilities place the play button in the center of the video box.
// _variables.scss (Sass Variables for colors, fonts, etc.)
$primary-color: #ffffff;
$secondary-color: #f8f9fa;
$text-color: #333;
$btn-bg: #ff5722;
$btn-hover: #e64a19;

// _buttons.scss (Button Styling)
.btn-rounded {
  background-color: $btn-bg;
  color: $primary-color;
  padding: 10px 20px;
  border-radius: 50px;
  transition: all 0.3s ease-in-out;

  &:hover {
    background-color: $btn-hover;
  }
}

// _intro.scss (Styling for Intro Section)
.intro-section {
  background: linear-gradient(to bottom, #007bff, #6610f2);
  color: $primary-color;
  padding: 100px 0;

  .intros {
    h1, h2 {
      font-weight: bold;
    }

    p {
      font-size: 18px;
    }
  }

  .video-box {
    position: relative;
    
    img {
      width: 100%;
      border-radius: 10px;
    }

    i {
      font-size: 50px;
      color: $primary-color;
    }
  }
}

// main.scss (Importing all partials)
@import "variables";
@import "buttons";
@import "intro";


1. SASS File (styles.scss)
Variables: Defined color palette (different shades of purple) and font styles.
Mixins: Created reusable styles for buttons, shadows, transitions, and spacing.
Nested Selectors: Organized styling to keep code modular and maintainable.
2. Bootstrap Integration
Navigation Bar: Implemented using Bootstrap's responsive navbar, allowing seamless navigation.
Grid System: Portfolio projects displayed using Bootstrap's col- classes for proper alignment and layout.
Buttons & Forms: Enhanced with Bootstrap components and further customized with SASS.
Features Implemented
✅ Portfolio Section: Displays details about the web developers, including links to their profiles and projects. 
✅ Navigation: Smooth scrolling functionality to navigate between Projects, About, Contact, and other sections. 
✅ Interactive Elements: Added hover effects and animations using SASS mixins and Bootstrap utilities. 
✅ Mobile Responsiveness: Optimized using Bootstrap's breakpoints, ensuring a seamless experience on all devices.
This document provides an overview of our team portfolio project, detailing how SASS and Bootstrap were utilized to create a well-structured, responsive, and visually appealing website.


