🏔️ Mountain View Webpage

A simple and visually appealing Mountain View webpage created using HTML5 and CSS3. The project uses a background image to create a full-screen mountain scene with centered text overlay.

📌 Project Overview

This project demonstrates how to create a webpage with:

- Full-screen background image
- Background image covering the entire screen
- Transparent content overlay
- Centered heading and paragraph
- Custom font sizes
- Simple and clean UI design

🛠️ Technologies Used

- HTML5
- CSS3

📂 Project Structure

Mountain-View/
│
├── index.html
├── Capture.PNG
└── README.md

✨ Features

🏔️ Background Image

The webpage uses an image as the background:

body {
    background-image: url(Capture.PNG);
    background-size: cover;
}

The "background-size: cover" property ensures that the image covers the available screen area.

📝 Content Overlay

The heading and paragraph are placed inside a ".content" container:

<div class="content">
    <h1>Mountain</h1>
    <p>Beautiful mountain view</p>
</div>

The container has a transparent white background:

.content {
    background-color: rgba(255, 255, 255, .3);
}

This allows the background image to remain visible behind the content.

🎯 Centered Content

The content is centered horizontally using:

text-align: center;

It is positioned vertically using:

margin-top: 350px;

🎨 CSS Styling

Background

body {
    background-image: url(Capture.PNG);
    background-size: cover;
}

This creates the full-page mountain background.

Heading

h1 {
    font-size: 60px;
}

The main title is displayed with a large font size.

Paragraph

p {
    font-size: 30px;
}

The subtitle is made larger for better visibility.

Resetting Default Spacing

* {
    margin: 0;
    padding: 0;
}

This removes the default margin and padding applied by browsers.

🚀 How to Run

1. Create a project folder.

2. Add the following files:

index.html
Capture.PNG
README.md

3. Make sure "Capture.PNG" is located in the same folder as "index.html".

4. Open "index.html" in any modern web browser.

You can also use VS Code Live Server to run the project.

🖼️ Image Requirement

The HTML code expects an image named:

Capture.PNG

If you want to use another image, change:

background-image: url(Capture.PNG);

to:

background-image: url(your-image.jpg);

🔮 Future Improvements

The project could be enhanced by adding:

- Responsive design
- CSS animations
- A navigation bar
- A button such as "Explore More"
- Text shadow effects
- Gradient overlays
- Responsive typography
- Multiple mountain images
- Parallax scrolling effects

📱 Responsive Design

The current design uses a fixed "margin-top" value of "350px". For better responsiveness, the content could be centered using Flexbox:

body {
    min-height: 100vh;
    background-image: url(Capture.PNG);
    background-size: cover;
    background-position: center;

    display: flex;
    justify-content: center;
    align-items: center;
}

.content {
    text-align: center;
}

This approach allows the content to remain centered across different screen sizes.

👨‍💻 Author

BCA 1st Year Student
Dezyne Ecole College

📄 License

This project is created for educational and learning purposes. You are free to modify and improve the code for your own projects.# Background
