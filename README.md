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
/* 1. Style the body */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 0;
    text-align: center;
}

/* 2. Style headers using a class */
.header {
    font-size: 24px;
    color: #007BFF;
    margin-bottom: 20px;
}

/* 3. Style paragraphs using an ID */
#intro-text {
    font-size: 18px;
    line-height: 1.6;
    margin: 20px auto;
    width: 80%;
}

/* 4. Style an image */
img {
    width: 300px;
    border: 5px solid #007BFF;
    border-radius: 10px;
    margin: 10px;
    padding: 5px;
    background-color: #fff;
}

/* 5. Button styling */
.button {
    background-color: #28a745;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

.button:hover {
    background-color: #218838;
}
