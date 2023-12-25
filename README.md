Preview
#Table of contents

Description This project is a copy of Simon Biao https://github.com/SuperSimpleDev's youtube project. My github will clone the code and give comments and explanations to the code. This project is meant to show the struggles of a beginner coder as well as providing an in- depth analysis of the code.

Suitable Browsers : In order to install this project, you must first have a suitable project and a browser. Supported browsers for this project include Brave, Edge, chrome - other suitable browsers can be found here: https://blog.hubspot.com/blog/tabid/6307/bid/5847/a-marketer-s-guide-to-html5.aspx#which-browsers-support-html5

Installation Methods These are the installation of vs code for different OS:

_Windows_: 1. Download the installer (.exe file) from the official VS Code website. 2. Run the installer executable. 3. Follow the on-screen instructions to complete the installation.
macOS:

Download the .dmg file from the official VS Code website.
Open the downloaded .dmg file.
Drag the Visual Studio Code icon to the "Applications" folder.
Launch VS Code from the Applications folder.
Linux: Ubuntu/Debian-based systems:

Open a terminal.
Download the .deb package from the official VS Code website.
Install the package using the package manager. For example: 4.
bash
sudo dpkg -i .deb
sudo apt-get install -f
Red hat Red Hat/Fedora-based systems:

Open a terminal. Download the .rpm package from the official VS Code website. Install the package using the package manager. For example: .

bash
Download the .rpm package from the official VS Code website.
Running the project

  
  

    Running the project is pretty simple, but a few things need to be kept in mind. If you have a default browser, the browser might not support HTML5 and other websites, so you need to make sure that no matter what,
    you are working with a suitable browser. In order to run the code on a website, you can either open the file in a browser and refresh it every time a change is made in Visual Studio or you can use the standard
    Dochtml structure which looks like
  



  
  
  <!DOCTYPE html>
  
  <html>
    
    <head>
      
      <title></title>
    </head>

    
    <body>
    </body>
  
  </html>

Outline of the Code

Welcome to the YouTube Clone project! This repository contains the codebase for a simplified YouTube-like webpage. Below, you'll find information on the organization of the HTML and CSS elements.

HTML Organization:
Click to Expand
1. _Document Structure_: - `index.html` is the main HTML file representing the structure of the YouTube clone. - The document starts with a `` declaration, followed by the `` root element.
Document Structure:

The <head> section includes metadata and external resources.
External fonts and stylesheets are linked for styling purposes.
Icons and images are linked to their respective paths.
Header (Navbar) Section:

The header section (<div class="header">) is a key component containing the navigation bar.
It is divided into left, middle, and right sections, each housing specific elements such as the logo, search bar, and user-related icons.
Sidebar Section:

The sidebar (<nav class="sidebar">) provides navigation links to different sections of the platform.
Each link is represented by a <div> element containing an icon and a label.
5._ Video Grid Section_:

The video grid (<div class="video-grid">) is the main content area displaying video previews.
Multiple video previews (<div class="video-preview">) are dynamically generated, each containing a thumbnail, video duration, and information about the video.
External Scripts:
External JavaScript files may be linked for dynamic functionality, though none are present in the provided code.
CSS Organization:
Click to Expand
Purpose of Each File or Section:
index.html:

Represents the main structure of the YouTube clone.
Organizes components such as the header, sidebar, and video grid.
CSS Files (general.css, header.css, sidebar.css, video.css):

Provide modular styling for different sections of the webpage.
Enhance maintainability by separating concerns and encapsulating styles.
Important Terms YouTube Clone Project

Welcome to the YouTube Clone project! This repository contains the codebase for a simplified YouTube-like webpage.

HTML Organization:

Click to Expand
Folder:

A digital container used for organizing files. In the project, folders structure HTML, CSS, and image files, facilitating a well-organized codebase for easy maintenance and collaboration.
HTML (Hypertext Markup Language):

The standard language for structuring web content. HTML in the project outlines the webpage's structure, defining sections like the header, sidebar, and video grid.
CSS (Cascading Style Sheets):

A style sheet language for enhancing visual presentation. CSS is applied in the project to style elements, providing a cohesive and visually appealing design for the YouTube clone.
Styling:

The process of applying visual attributes using CSS. Styling in the project includes setting colors, fonts, and layouts, contributing to a polished and user-friendly interface.
Stylesheet:

A file defining the visual presentation of a web document. Stylesheets in the project, written in CSS, ensure consistent styling across multiple pages, maintaining a uniform look and feel.
Purpose of Each File or Section:

- `index.html`: - Represents the main structure of the YouTube clone. - Organizes components such as the header, sidebar, and video grid.

- CSS Files (`general.css`, `header.css`, `sidebar.css`, `video.css`): - Provide modular styling for different sections of the webpage. - Enhance maintainability by separating concerns and encapsulating styles.

This organization helps users navigate the codebase by dividing the code into meaningful sections, making it easier to locate and modify specific elements or styles related to the header, sidebar, and video grid.

Future Aspirations

This website will upload and process the comments, likes, video metadata, etc. from youtube’s api and keep track of the person’s comments(filter for bad comments/cus words), it will feature data storage- MongoDB, and an analytics machine– probably a socialblade APi that keeps track of the likes, dislikes, and comments/ viewer growth over time

Final notes

This project is meant to be a collaborative experience. As I learn and grow as a coder, I want those around me to grow as a coder. I want to grow to eventually give everyone on my platform a chance to gain open source experience and valuable work experience that will help them land their next programming job. This can happen if we collaboarate. I become a better coder by learning from all of you and improve my practice and habits to make sure I provide you with a valuable experience
