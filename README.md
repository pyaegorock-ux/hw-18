# hw-18
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Heading Assignment</title>
    <style>
        body {
            font-family: "Times New Roman", Times, serif;
            padding: 40px;
        }

        /* Heading 1: Black top bar and subtle Red reflection shadow */
        h1 {
            display: inline-block;
            border-top: 3px solid black;
            font-size: 44px;
            margin-bottom: 30px;
            /* Creates the red "ghosting" effect seen in your image */
            text-shadow: 2px 2px 2px rgba(255, 0, 0, 0.4);
        }

        /* Heading 2: Yellow outer border with a Black inner line */
        h2 {
            font-style: italic;
            font-weight: normal;
            font-size: 32px;
            padding: 4px 10px;
            /* The 'yellow' box effect */
            border: 3px solid #E6E600; 
            /* The 'black' inner line effect */
            outline: 1px solid black;
            outline-offset: -4px;
        }

        /* Heading 3: Right aligned, bold, and underlined */
        h3 {
            text-align: right;
            text-decoration: underline;
            font-size: 26px;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <h1>This is heading 1</h1>

    <h2>This is heading 2</h2>

    <h3>This is heading 3</h3>

</body>
</html>
