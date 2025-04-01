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
/* Style for body */
body {
    font-family: Arial, sans-serif; /* Different font */
    background-color: #f4f4f4; /* Light background color */
    margin: 0;
    padding: 20px;
}

/* Style for all headings */
h1, h2, h3 {
    color: #333; /* Dark color for headings */
}

/* Class selector for paragraph styling */
.text-highlight {
    color: #007BFF; /* Blue color for highlighted text */
    margin-bottom: 15px; /* Adds space below highlighted text */
}

/* ID selector for styling the image */
#featured-image {
    border: 5px solid #ccc; /* Light gray border */
    padding: 10px; /* Space inside the border */
    margin-top: 20px; /* Space above the image */
    width: 100%; /* Make image responsive */
    max-width: 600px; /* Maximum width */
}

/* Style for the container */
.container {
    background-color: white; /* White background for the container */
    padding: 20px; /* Space inside the container */
    border-radius: 8px; /* Rounded corners */
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Introduction to CSS</title>
    <link rel="stylesheet" href="style.css"> <!-- Link to external CSS file -->
</head>
<body>
    <div class="container">
        <h1>Welcome to CSS!</h1>
        <h2>Applying Styles</h2>
        <p class="text-highlight">This paragraph is styled using a class selector to highlight text in blue.</p>
        <p>CSS allows you to style your web pages, making them more attractive and readable.</p>
        
        <h3>Here is an example of an image:</h3>
        <img id="featured-image" src="https://via.placeholder.com/600" alt="Sample Image">
        
        <h3>More about CSS</h3>
        <p>Utilizing CSS effectively can improve the aesthetics and functionality of your website significantly.</p>
    </div>
</body>
</html>
