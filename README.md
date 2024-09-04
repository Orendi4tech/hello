<!DOCTYPE html>
<html>

<head>
    <title>My Web Page</title>
</head>

<body>
    <h1>My First WebPage</h1>
    <br>
    <table cellspacing="20" colour="green">

        <tr>
            <th>Webpage Contents</th>
            <th>Information Table</th>
            <th>Contact Form</th>
        </tr>
    </table>
</body>

<body>
    <br>
    <img src="/Downloads/sun.jpeg" alt="A beautiful sunset" height="300" width="800">

    <a href="https://www.techyjaunt.com" target="-blank">
        <br>Visit TechyJaunt</a>

    <p>This is a simple paragraph describing thr content of the webpage. It explains the purpose of the page and
        <br>provides some basic information about what the users expect to find.
    </p>

    <style>
        body {
            font-family: Arial, sans-serif;
        }

        h1 {
            color: white;
            text-align: center;
        }

        h1 {
            background-color: green;
            padding: 20px;
        }

table {color:green}

      
    </style>


    <h3>Webpage Contents</h3>

    <ul>
        <li>Introduction</li>
        <li>Table information</li>
        <li>Contact form</li>

    </ul>
    <table border="1" color="black" cellpadding="20" cellspacing="0">
        <!--beginning of table head-->
        <thead>
            <tr>
                <th> Item</th>
                <th>Description</th>
                <th>Quantity </th>
            </tr>
        </thead>


        <tbody>
            <tr>
                <td>Pens</td>
                <td>Blue Ink Pens</td>
                <td>5</td>

            </tr>

            <tr>
                <td>John</td>
                <td>Permament Markers</td>
                <td>3</td>
            </tr>


            </tr>
            <td>Markers</td>
            <td>Spiral-bound Notebooks</td>
            <td>2</td>
            </tr>

        </tbody>

    </table>
    <br>
    <h4>Registration Form</h1>
        <form action="/submit-form" method="POST">
            <!-- Text Input -->
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <br></br>
            <!-- Email Input -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br></br>
            <!-- Password Input -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required><br>
            <br></br>
            <!-- Radio Buttons -->
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br>
            <br></br>
            <!-- Checkbox -->
            <label>Suscribe:</label>
            <input type="checkbox" id="subscribe" name="subscribe">
            <label for="subscribe">Yes, I want to Subscribe</label><br>
            <br></br>
            <!-- Number of Items -->
            <label for="Number of Items">Number of Items:</label>
            <input type="password" id="Number of Items" name="Number of Items" required><br>
            <br></br>
            <!-- Date -->
            <label for="date">date:</label>
            <input type="date" id="date" name="date" required><br>
            <br></br>
            <!-- Dropdown Select -->
            <label for="country">Country:</label>
            <select id="country" name="country">
                <option value="NIGERIA">NIGERIA</option>
                <option value="canada">Canada</option>
                <option value="uk">UK</option>
            </select><br>
            <br></br>

            <!-- Textarea -->
            <label for="comments">Comments:</label>
            <textarea id="comments" name="comments" rows="10" cols="50" placeholder="Enter your
comments"></textarea>

            <br></br>
            <!-- Submit Button -->
            <input type="submit" value="Submit">
        </form> 
    </body>

</html>
