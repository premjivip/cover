# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:

```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            color: red;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(PHOTO.jpg);
            background-size: cover;
            position: relative;
        }

        .insight {
            color: white;
        }

        .booktitle {
            font-family: 'Algerian', cursive;
            font-size: 20px;
            text-align: center;
            color: rgb(112, 187, 216);
            position: relative;
            top: 80px;
        }

        .subtitle {
            font-family: Tahoma;
            font-size: large;
            text-align: center; /* Center the subtitle text */
            position: relative;
            top: 40px;
        }

        .author {
            font-family: 'Algerian', cursive;
            position: absolute;
            bottom: 10px;
            right: 10px;
            color: red;
            font-size: 25px;
        }

        .mypic {
            position: relative;
            top: 330px; 
            left: 295px;
            width: 150px;
            height: 150px;
            border-radius: 50%; 
            background-size: cover;
        }
    </style>
    <title>Book Cover Page</title>
</head>

<body>
    <div class="bookpage">
        <div class="insight">EXPERT INSIGHT</div>
        <div class="booktitle">
            <h1>THE JOHN WICK</h1>
        </div>
        <div class="author">
            PREMJI P 
        </div>
        <div class="mypic">
            <img src="photo.jpeg" width="100" height="100" alt="">
        </div>
    </div>
</body>
</html>

```
# OUTPUT
![Screenshot (22)](https://github.com/premjivip/cover/assets/143831886/96893338-959b-4c8e-a2c3-3a5cc46d779d)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
