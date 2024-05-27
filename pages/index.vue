<template>
    <head>
        <title>echo-1</title>
        <style>
            body {
                background-color: #111;
                color: #fff;
                font-family: monospace;
            }
            
            #container {
                width: 800px;
                margin: 20px auto;
                text-align: left;
            }
            
            #header {
                margin-bottom: 50px;
            }
            
            #image-container {
                float: right;
                margin: 20px;
            }
            
            img {
                max-width: 300px;
            }
            
            #text-container {
                margin: 20px;
            }
            
            #footer {
                clear: both;
                margin-top: 100px;
                text-align: center;
            }
        </style>
    </head>
    <body>
        <div id="container">
            <div id="header">
                <h1>echo-1</h1>
            </div>
            <div id="image-container">
                <img src="image1.jpg" alt="Image 1">
                <br>
                <img src="image2.jpg" alt="Image 2">
            </div>
            <div id="text-container">
                <p>
                    <!-- Text 1 goes here -->
                </p>
                <p>
                    <!-- Text 2 goes here -->
                </p>
            </div>
            <div id="footer">
                <p>
                    <!-- Footer text goes here -->
                </p>
            </div>
        </div>
    </body>
</template>