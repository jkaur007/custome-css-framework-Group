# Web Development Project  
[![Netlify Status](https://api.netlify.com/api/v1/badges/a17313e1-0d35-48d5-b659-54a709f97f06/deploy-status)](https://willowy-biscochitos-d1238e.netlify.app/)
<br>
<b>Group Members:</b><br>

<b>Jasmine kaur</b> - <i>Responsible for Overall website ,Design, Color scheme, and Theme, Github and all installation</i>.<br>
<b>Gursimran Kaur</b> - <i>Table and content use</i><br>
<b>Avneet Kaur</b> - <i>Images and links.</i><br>
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

This is a lightweight and customizable web development framework created by Jasmine Kaur, Avneet Kaur, and Gursimran Kaur. It provides a solid foundation for building responsive and modern web applications which is design by Scss.

## Project Overview  
This project is a web-based application developed using HTML, CSS, JavaScript, Sass and Bootstrap. It includes dynamic content, interactive features, and a responsive design to ensure a smooth user experience.  

## Installation  
To set up the project locally:  
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-github-username/your-repository-name.git

Navigate to the project directory:
sh
cd your-repository-name

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

To include Bootstrap in your project, you have several options:

**1. Using a Content Delivery Network (CDN):**

This method allows you to link directly to Bootstrap's CSS and JavaScript files hosted on a CDN, eliminating the need to download and host the files yourself.

- **Include Bootstrap CSS:**

  Add the following line within the `<head>` section of your HTML file:

  ```html
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
  ```

- **Include Bootstrap JavaScript:**

  Place the following lines just before the closing `</body>` tag:

  ```html
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js" integrity="sha384-oBqDVmMz4fnFO9gybP6a4mA4jQp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6p+Qp6a98W6 
Replace placeholders like `your-username`, `your-repository-name`, and specific commands with details relevant to your project.

For more detailed information on installing Sass, refer to the [official Sass installation guide](https://sass-lang.com/install/).


## Usage
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
````
<h2>Example Usage of how i made Intro section in my portfolio website:<h2>
<section id="home" class="intro-section">
  <div class="container">
    <div class="row align-items-center text-white">
      <!-- START THE CONTENT FOR THE INTRO -->
      <div class="col-md-6 intros text-start">
        <h1 class="display-2">Welcome,</h1>
        <h2>Our Web Development Team</h2>
        <p class="display-2--description lh-base">
          We are a team of three passionate web developers dedicated to creating modern, user-friendly, and high-performing websites. With expertise in front-end and back-end development.
        </p>
        <button type="button" class="rounded-pill btn-rounded">
          Get in Touch
          <span><i class="fas fa-arrow-right"></i></span>
        </button>
      </div>
````
     <h2>Component: Intro Section (Built with Bootstrap & Sass)<h2>
Bootstrap Usage
Grid System (row and col-md-6)

Bootstrap’s grid system (row and col-md-6) ensures a two-column layout, making the text and image sit side by side.
This structure makes the section responsive, automatically stacking on smaller screens.
Typography (display-2, lh-base)

Bootstrap’s typography classes (display-2 for large headings, lh-base for line height) ensure consistent styling across different screen sizes.
Button (btn-rounded)

A Bootstrap-based button is styled with a custom class (rounded-pill) to make it pill-shaped.
Positioning (position-absolute, top-50, start-50, translate-middle)


## Sass Implementation ##



Bootstrap’s position utilities place the play button in the center of the video box.
// _variables.scss (Sass Variables for colors, fonts, etc.)
```
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
````

## _intro.scss (Styling for Intro Section)
```
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
```


1. SASS File (styles.scss)
Variables: Defined color palette (different shades of purple) and font styles.
Mixins: Created reusable styles for buttons, shadows, transitions, and spacing.
Nested Selectors: Organized styling to keep code modular and maintainable.
2. Bootstrap Integration
Navigation Bar: Implemented using Bootstrap's responsive navbar, allowing seamless navigation.
Grid System: Portfolio projects displayed using Bootstrap's col- classes for proper alignment and layout.
Buttons & Forms: Enhanced with Bootstrap components and further customized with SASS.
Features Implemented<br>

<h2>Features of the website</h2>

✅ Portfolio Section: Displays details about the web developers, including links to their profiles and projects. <br>

✅ Navigation: Smooth scrolling functionality to navigate between Projects, About, Contact, and other sections.<br>

✅ Interactive Elements: Added hover effects and animations using SASS mixins and Bootstrap utilities. <br>

✅ Mobile Responsiveness: Optimized using Bootstrap's breakpoints, ensuring a seamless experience on all devices.
This document provides an overview of our team portfolio project, detailing how SASS and Bootstrap were utilized to create a well-structured, responsive, and visually appealing website.


