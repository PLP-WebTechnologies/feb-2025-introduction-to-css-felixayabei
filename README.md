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



#answers 
#index.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="style.css">
        <title>Styled Page</title>
    </head>
    
<body>
    <header>
        <h1 class="main-title">Welcome to My Styled Page</h1>
    </header>
    <section id="about">
        <h2>About Us</h2>
        <p>This is a sample paragraph to demonstrate styling.</p>
        <img src="https://images.pexels.com/photos/1234567/pexels-photo-1234567.jpeg" alt="Sample Image" class="styled-image">
    </section>
    <footer>
        <p class="footer-text">© 2025 My Website</p>
    </footer>
</body>
</html>

#style.css
body {
    font-family: 'Roboto', sans-serif; 
    background-color: #f0f4f8;
    color: #592828;
    margin: 0;
    padding: 0;
}

/* Style the main title */
.main-title {
    text-align: center;
    color: #2d3945;
    margin: 20px 0;
    font-size: 2.5em; 
}

/* Style the about section */
#about {
    padding: 30px;
    border: 1px solid #2980b9;
    margin: 20px auto;
    background-color: #ecf0f1;
    border-radius: 8px; 
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1); 
    max-width: 800px; 
}

/* Style the image */
.styled-image {
    width: 100%;
    max-width: 600px;
    border-radius: 10px;
    margin: 20px auto;
    display: block;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2); 
}

/* Style the footer text */
.footer-text {
    text-align: center;
    color: #121b1c;
    padding: 15px 0;
    font-size: 1em;
    border-top: 1px solid #4e5b63; 
    margin-top: 20px;
}
