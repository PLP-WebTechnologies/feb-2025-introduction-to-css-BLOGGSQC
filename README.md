# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Introduction to CSS</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking the external CSS file -->
</head>
<body>
    <header id="main-header">
        <h1>Welcome to My Web Page</h1>
    </header>

    <section class="content-section">
        <h2>About This Page</h2>
        <p>This page demonstrates the use of CSS for styling HTML elements.</p>
        <img src="https://images.pexels.com/photos/1234567/pexels-photo-1234567.jpeg" alt="Sample Image" class="styled-image">
    </section>

    <footer class="footer">
        <p>&copy; 2025 My Web Page</p>
    </footer>
</body>
</html>

CSS File:

/* Basic reset for margins and paddings */
body {
    margin: 0;
    padding: 0;
    font-family: 'Arial', sans-serif; /* Default font */
}

/* Styling for the main header */
#main-header {
    background-color: #4CAF50; /* Green background */
    color: white; /* White text */
    padding: 20px; /* Padding around the header */
    text-align: center; /* Centered text */
}

/* Styling for content section */
.content-section {
    margin: 20px; /* Margin around the content section */
    padding: 15px; /* Padding inside the content section */
    border: 1px solid #ccc; /* Light gray border */
    border-radius: 5px; /* Rounded corners */
    background-color: #f9f9f9; /* Light background color */
}

/* Styling for the image */
.styled-image {
    width: 100%; /* Responsive image */
    max-width: 600px; /* Maximum width */
    border: 2px solid #4CAF50; /* Green border around the image */
    border-radius: 5px; /* Rounded corners for the image */
    margin-top: 15px; /* Margin above the image */
}

/* Styling for the footer */
.footer {
    text-align: center; /* Centered text */
    padding: 10px; /* Padding inside the footer */
    background-color: #333; /* Dark background */
    color: white; /* White text */
    position: relative; /* Positioning */
    bottom: 0; /* Align to bottom */
    width: 100%; /* Full width */
}

