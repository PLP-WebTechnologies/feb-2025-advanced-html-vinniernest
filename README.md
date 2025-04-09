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
    <title>Advanced HTML5 Elements and Forms</title>
</head>
<body>
    <h2>Ordered List with Roman Numerals</h2>
    <ol type="I">
        <li>Introduction to HTML5</li>
        <li>Learning Multimedia Elements</li>
        <li>HTML5 Forms and Validation</li>
        <li>Responsive Design Principles</li>
        <li>Exploring Advanced Elements</li>
    </ol>
    <h2>External Image from Pexels</h2>
    <img src="https://images.pexels.com/photos/460672/pexels-photo-460672.jpeg" alt="Beautiful Landscape" width="500">
    <h2>Contacts</h2>
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
                <td>123 Elm Street</td>
                <td>123-456-7890</td>
                <td>john.doe@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak Avenue</td>
                <td>234-567-8901</td>
                <td>jane.smith@example.com</td>
            </tr>
            <tr>
                <td>David Johnson</td>
                <td>789 Pine Road</td>
                <td>345-678-9012</td>
                <td>david.johnson@example.com</td>
            </tr>
            <tr>
                <td>Emily Davis</td>
                <td>321 Maple Lane</td>
                <td>456-789-0123</td>
                <td>emily.davis@example.com</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>654 Cedar Blvd</td>
                <td>567-890-1234</td>
                <td>michael.brown@example.com</td>
            </tr>
        </tbody>
    </table>
    <h2>Registration Form</h2>
    <form action="/submit" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>
        <label for="country">Select Country:</label>
        <select id="country" name="country" required>
            <option value="USA">United States</option>
            <option value="UK">United Kingdom</option>
            <option value="Canada">Canada</option>
            <option value="Australia">Australia</option>
        </select><br><br>
        <label>Gender:</label><br>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label><br>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label><br><br>
        <label>Interests:</label><br>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label><br>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label><br>
        <input type="checkbox" id="travel" name="interests" value="travel">
        <label for="travel">Travel</label><br><br>
        <input type="submit" value="Register">
    </form>
</body>
</html>
