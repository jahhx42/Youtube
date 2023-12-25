Preview
## Table of Contents
- [Description](#description)
- [Installation](#installation)
  - [Suitable Browsers](#suitable-browsers)
  - [Installation Methods](#installation-methods)
- [Running the project](#running-the-project)
- [Outline of the code](#outline-of-the-code)
  - [HTML Organization](#html-organization)
  - [CSS Organization](#css-organization)
- [Future Aspirations](#future-aspirations)
- [Final Notes](#final-notes)
  
## Description
This project is a copy of [Simon Biao's](https://github.com/SuperSimpleDev) YouTube project. My GitHub repository will clone the code and provide comments and explanations to the code. The purpose of this project is to showcase the struggles of a beginner coder, as well as offering an in-depth analysis of the code.This project is a copy of Simon Biao https://github.com/SuperSimpleDev's youtube project. My github will clone the code and give comments and explanations to the code. This project is meant to show the struggles of a beginner coder as well as providing an in- depth analysis of the code.

 ### Suitable Browsers: 
 In order to install this project, you must first have a suitable project and a browser. Supported browsers for this project include Brave, Edge, chrome - other suitable browsers can be found here: https://blog.hubspot.com/blog/tabid/6307/bid/5847/a-marketer-s-guide-to-html5.aspx#which-browsers-support-html5

## Installation Methods:
 
These are the installation of vs code for different OS:

_Windows_:

<details>
  <summary>Click to Expand</summary>
  
  1. Download the installer (.exe file) from the official VS Code website. 
  2. Run the installer executable. 
  3. Follow the on-screen instructions to complete the installation.
</details>
   
_MacOS_:
<details> 
<summary> Click to Expand</summary>
  
1. Download the .dmg file from the official VS Code website.
2. Open the downloaded .dmg file.
3. Drag the Visual Studio Code icon to the "Applications" folder.
4. Launch VS Code from the Applications folder.
</details>


_Linux: Ubuntu/Debian-based systems_:
<details>
  <summary> Click to Expand</summary>
  
1. Open a terminal.
2. Download the .deb package from the official VS Code website.
3. Install the package using the package manager. For example: 
  If you use bash
  <pre style = "background-color = white; color: black;">
```bash
# Navigate to the directory where you downloaded the .deb package
cd /path/to/downloaded/package

# Install the package
sudo dpkg -i filename.deb

# Resolve dependencies (if any)
sudo apt-get install -f
  </pre>
</details>

_Red Hat/Fedora Based Systems_:

<details>
<summary>Click to Expand</summary>

1. Open a terminal.
2. Download the .rpm package from the official VS Code website.
3. Install the package using the package manager. For example: .
<pre style="background-color: white; color: black;">
bash
Download the .rpm package from the official VS Code website.
</pre>

</details>

## Running the project

Running the project is pretty simple, but a few things need to be kept in mind. If you have a default browser, the browser might not support HTML5 and other websites, so you need to make sure that no matter what,you are working with a suitable browser. In order to run the code on a website, you can either open the file in a browser and refresh it every time a change is made in Visual Studio or you can use the standardDochtml structure which looks like

![DocType html structure](https://github.com/jahhx42/Youtube/assets/151959456/b9a40c2c-8913-417c-bc2b-918ed56eefef)



Both examples will render as formatted HTML code with syntax highlighting in Markdown viewers that support code blocks.


## Outline of the Code

Welcome to the YouTube Clone project! This repository contains the codebase for a simplified YouTube-like webpage. Below, you'll find information on the organization of the HTML and CSS elements.

### HTML Organization:
<details>
  <summary>Click to Expand</summary>
  
1. project Structure_: - There are 3 types of contributions that make up this project. The code includes a code written in html, code written in css, and external objects such as icons and images
   used for the website.
   
2. _Head Tag_: -The `<head>` section includes metadata and external resources. External fonts and stylesheets are linked for styling purposes.
Icons and images are linked to their respective paths.

3. _Header (Navbar) Section_: -The header section (`<!-- <div class="header"> -->`) is a key component containing the navigation bar. It is divided into left, middle, and right sections, each housing specific elements such as the logo, search bar, and user-related icons.
 
4. _Sidebar Section_:The `sidebar` nav class=<"sidebar"> provides navigation links to different sections of the platform.
Each link is represented by a `<div>` element containing an icon and a label.

5. _Video Grid Section_:The video grid `<div class="video-grid">` is the main content area displaying video previews.
Multiple video previews <div class="video-preview"> are dynamically generated, each containing a thumbnail, video duration, and information about the video.

6. other: External Scripts:
External JavaScript files may be linked for dynamic functionality, though none are present in the provided code.

</details>

### CSS Organization:
<details>
  <summary>Click to Expand</summary>

1. Selectors: -Selectors are patterns used to target HTML elements for styling. They allow you to define rules that apply styles to specific elements, classes, or IDs on your webpage.
2. Classes and IDs: -Classes (.) and *IDs* (#) are identifiers used to apply styles to specific elements. *Classes* are reusable and can be applied to multiple elements, while *IDs* are unique to a single element.
3. Pseudo-classes `(:hover)`: -Pseudo-classes* are used to style elements in specific states or conditions. The `:hover` *pseudo-class*, for example, is applied when a user hovers over an element, allowing for interactive styling effects.
4. Box Model: -The box model is a fundamental concept that defines how elements are structured on a webpage. It includes properties like `margin`, `border`, `padding`, and `content width`, influencing the layout and spacing of elements.
5. Flexbox: -`Flexbox` is a layout model designed to simplify the arrangement of elements in a flexible and responsive way. It provides a powerful mechanism for creating dynamic layouts, especially useful for items in a row or column.
6. Developer Tools (DevTools)
*Developer Tools*, often available in web browsers, provide a set of features for inspecting and debugging web pages. In the context of CSS, *DevTools* allow developers to inspect and modify styles in real-time, aiding in the development and troubleshooting process. You can evaluate the box model in browsers or in your code by right clicking and pressing inspect.  
</details>



### Future Aspirations
I plan on working on a project based on my experience with this one.This upcoming project will upload and process the comments, likes, video metadata, etc. from youtube’s api and keep track of the person’s comments(filter for bad comments/cus words), it will feature data storage- MongoDB, and an analytics machine– probably a socialblade APi that keeps track of the likes, dislikes, and comments/ viewer growth over time.

### Final notes

This project is meant to be a collaborative experience. As I learn and grow as a coder, I want those around me to grow as a coder. I want to grow to eventually give everyone on my platform a chance to gain open source experience and valuable work experience that will help them land their next programming job. This can happen if we collaboarate. I become a better coder by learning from all of you and improve my practice and habits to make sure I provide you with a valuable experience.
