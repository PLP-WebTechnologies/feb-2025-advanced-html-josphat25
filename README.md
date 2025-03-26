# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

# Create an index.html file.
# Add an ordered list with roman numerals
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ordered List with Roman Numerals</title>
</head>
<body>
    <h1>My Roman Numerals List</h1>
    <ol type="I">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
        <li>Fourth item</li>
    </ol>
</body>
</html>

- # Add an external image from pexels.com
   <h2>Here's a Beautiful Image from Pexels</h2>
    <img src="https://images.pexels.com/photos/34950/pexels-photo-34950.jpeg" alt="Nature Image from Pexels" width="600">

</body>
</html>

# Add a table of 5 contacts with; name, address, mobile and emails

    <h2>Contacts Table</h2>
    <table border="1" cellpadding="10">
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
                <td>123 Main St, Springfield</td>
                <td>(555) 123-4567</td>
                <td>johndoe@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak St, Rivertown</td>
                <td>(555) 234-5678</td>
                <td>janesmith@example.com</td>
            </tr>
            <tr>
                <td>Michael Johnson</td>
                <td>789 Pine St, Hilltop</td>
                <td>(555) 345-6789</td>
                <td>michaelj@example.com</td>
            </tr>
            <tr>
                <td>Emily Davis</td>
                <td>101 Maple St, Greenfield</td>
                <td>(555) 456-7890</td>
                <td>emilydavis@example.com</td>
            </tr>
            <tr>
                <td>Chris Lee</td>
                <td>202 Birch St, Lakeside</td>
                <td>(555) 567-8901</td>
                <td>chrislee@example.com</td>
            </tr>
        </tbody>
    </table>

</body>
</html>

- # Add a registration form
    <h2>Registration Form</h2>
    <form action="#" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
        <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email address" required>
        <br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter a secure password" required minlength="8">
        <br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>

        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="Male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="Female">
        <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="Other">
        <label for="other">Other</label>
        <br><br>

        <label for="membership">Membership Level:</label>
        <select id="membership" name="membership" required>
            <option value="basic">Basic</option>
            <option value="premium">Premium</option>
            <option value="vip">VIP</option>
        </select>
        <br><br>


        <label for="terms">
            <input type="checkbox" id="terms" name="terms" required> I agree to the <a href="#">terms and conditions</a>.
        </label>
        <br><br>

        <button type="submit">Register</button>
    </form>

</body>
</html>

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
