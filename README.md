<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h1>Ordered List</h1>
    <ol type="I">
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
    </ol>

    <!-- External Image -->
    <h2>Image from Pexels</h2>
    <img src="https://www.pexels.com/photo/beautiful-scenery-12345678/" alt="Beautiful Scenery" width="400">

    <!-- Table of Contacts -->
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
                <td>123 Main Street</td>
                <td>+1234567890</td>
                <td>johndoe@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Elm Avenue</td>
                <td>+1234567891</td>
                <td>janesmith@example.com</td>
            </tr>
            <tr>
                <td>Mike Johnson</td>
                <td>789 Oak Lane</td>
                <td>+1234567892</td>
                <td>mikejohnson@example.com</td>
            </tr>
            <tr>
                <td>Anna Brown</td>
                <td>321 Pine Street</td>
                <td>+1234567893</td>
                <td>annabrown@example.com</td>
            </tr>
            <tr>
                <td>Chris Evans</td>
                <td>654 Maple Avenue</td>
                <td>+1234567894</td>
                <td>chrisevans@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="/submit" method="post">
        <!-- Name -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>
        <br><br>

        <!-- Email -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>

        <!-- Password -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required>
        <br><br>

        <!-- Date -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>

        <!-- Dropdown -->
        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value="">Select</option>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>
        <br><br>

        <!-- Radio Buttons -->
        <p>Subscription Plan:</p>
        <input type="radio" id="basic" name="plan" value="basic" required>
        <label for="basic">Basic</label>
        <input type="radio" id="premium" name="plan" value="premium" required>
        <label for="premium">Premium</label>
        <br><br>

        <!-- Checkboxes -->
        <p>Preferred Features:</p>
        <input type="checkbox" id="feature1" name="features" value="feature1">
        <label for="feature1">Feature 1</label>
        <input type="checkbox" id="feature2" name="features" value="feature2">
        <label for="feature2">Feature 2</label>
        <input type="checkbox" id="feature3" name="features" value="feature3">
        <label for="feature3">Feature 3</label>
        <br><br>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>
</body>
</html>
