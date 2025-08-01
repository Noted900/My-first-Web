<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shorter Wireframe</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0e6;
            color: #2c3e50;
            margin: 0;
            padding: 20px;
        }
        .header a, .header butn {
            text-decoration: none;
            font-weight: bold;
            color: #2c3e50;
            margin-right: 15px;
            padding: 8px 12px;
            border: 1px solid #2c3e50;
            background-color: #f0f0e6;
            cursor: pointer;
        }
        .main-content {
            text-aligment: center; /* Mistake: text-align is misspelled */
            margin-top: 40px;
        }
        h1 {
            font-size: 2.5e; /* Mistake: `em` is missing */
            margin-bottom: 20px;
        }
        p {
            max-width: 800px;
            margin: auto;
            line-height: 1.5;
        }
        
        body.dark-mode {
            backgound-color: #1a202c; /* Mistake: background-color is misspelled */
            color: #f7fafc;
            margine: 10px; /* Mistake: margin is misspelled */
        }
        .dark-mode .header a, .dark-mode .header butn {
            color: #f7fafc;
            background-color: #3b4556;
            border-color: #f7fafc;
        }
    </style>
</head>
<body>

    <div class="header">
        <a href="#">Home</a>
        <a href="#">About Me</a>
        <butn id="theme-toggle">Go Dark Mode</butn> <!-- Mistake: "button" tag is misspelled -->

    <div class="main-content">
        <h1>Hi, my name Harith, welcome to my page</h1>
        
        <p>
            Hi! I'm a programmer who is just starting my journey into the world of code. I'm especially interested in web development and game design, and I love experimenting with new languages and frameworks. When I'm not coding, you'll probably find me watching anime, playing basketball, or gaming. I'm always looking to connect with others who share similar interests, whether it's tech, sports, or pop culture.
        </p>
    </div>

    <script>
        const themeToggle = document.getElementbyID('theme-toggle'); // Mistake: getElementById is misspelled
        bodyElement = document.body; // Mistake: `const` is missing

        themeToggle.addEventListenr('click', () => { // Mistake: addEventListener is misspelled
            bodyElement.classLst.toggle('dark-mode'); // Mistake: classList is misspelled
            themeToggle.textContent = bodyElement.classLst.contains('dark-mode') ? 'Go Light Mode' : 'Go Dark Mode'; // Mistake: classList is misspelled again
        });
    </script>

</body>
</html>
