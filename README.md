# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements</title>
</head>
<body>
    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List</h2>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
            <li>Fourth Item</li>
            <li>Fifth Item</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>External Image</h2>
        <img src="https://www.pexels.com/photo/example-image.jpg" alt="Pexels Sample Image" width="600">
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Contact List</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>John Doe</td>
                    <td>123 Main St</td>
                    <td>+254712345678</td>
                    <td>john@gmail.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Elm St</td>
                    <td>+254798765432</td>
                    <td>jane@gmail.com</td>
                </tr>
                <tr>
                    <td>Michael Brown</td>
                    <td>789 Pine St</td>
                    <td>+254701234567</td>
                    <td>michael@gmail.com</td>
                </tr>
                <tr>
                    <td>Sarah Johnson</td>
                    <td>159 Oak St</td>
                    <td>+254756789012</td>
                    <td>sarah@gmail.com</td>
                </tr>
                <tr>
                    <td>David Wilson</td>
                    <td>357 Maple St</td>
                    <td>+254743210987</td>
                    <td>david@gmail.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
            <br>

            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br>

            <label for="gender">Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required> Male
            <input type="radio" id="female" name="gender" value="female" required> Female
            <br>

            <label for="course">Select Course:</label>
            <select id="course" name="course" required>
                <option value="">--Choose a course--</option>
                <option value="cs">Computer Science</option>
                <option value="it">Information Technology</option>
                <option value="se">Software Engineering</option>
            </select>
            <br>

            <label>Interests:</label>
            <input type="checkbox" name="interests" value="coding"> Coding
            <input type="checkbox" name="interests" value="design"> Design
            <input type="checkbox" name="interests" value="gaming"> Gaming
            <br>

            <button type="submit">Register</button>
        </form>
    </section>
</body>
</html>

