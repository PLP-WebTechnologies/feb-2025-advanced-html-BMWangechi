<DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1-0">
    <title>Ordered List Sample</title>
</head>
<body>
    <Ordered List with Roman Numerals>
    <ol type="i"   start="1">
        <li>Music</li>
        <li>Art</li>
        <li>Dance</li>
        <li>Painting</li>
    </ol>
    
    <!-- External Image from pexels.com -->
        <img src="https://images.pexels.com/photos/1234567/pexels-photo-1234567.jpeg"
alt="A Salad Photo">


    <!-- Table of Contacts -->
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
                    <td>Bancy Muthoni</td>
                    <td>Elmwood Hts</td>
                    <td>0745767624</td>
                    <td>muthoni@yahoo.com</td>
                </tr>
                <tr>
                    <td>Irene Ngush</td>
                    <td>Westlands</td>
                    <td>0727306133</td>
                    <td>ingush@gmail.com</td>
                </tr>
                <tr>
                    <td>Penina Masese</td>
                    <td>Ngong Rd</td>
                    <td>0798885576</td>
                    <td>pmass@gmail.com</td>
                </tr>
                <tr>
                    <td>Eric Wachira</td>
                    <td>Kilimani</td>
                    <td>0722176543</td>
                    <td>ewach@yahoo.com</td>
                </tr>
                <tr>
                    <td>Mark Murage</td>
                    <td>Kiambu Rd</td>
                    <td>0791588577</td>
                    <td>mmurage@yahoo.com</td>
                </tr>
            </tbody>
        </table>

        <!-- Registration Form -->
        <form action="/submit" method="post">
           <h2>Rgistration Form</h2>
           <!-- Name Field -->
            <label for="'name">Name</label>
            <input type="text" id="name" placeholder="Enter your name" required>
            <br>

            <!-- Email Field -->
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Enter your email" required>
            <br>

            <!-- Password Field -->
            <label for="password">Password</label>
            <input type="password" id="password" placeholder="Enter your password" required>
            <br>

            <!-- Date Field -->
            <label for="date" id="date">Date:</label>
            <input type="date" id="date" required>
            <br>

            <!-- Dropdown -->
            <label for="dropdown">Choose an option:</label>
            <select id="dropdown" name="dropdown" required>
                <option value="">Select...</option>
                <option value="option1">Option 1</option>
                <option value="option2">Option 2</option>
                <option value="option3">Option 3</option>
            </select>
            <br>
     
            <!-- Radio buttons -->
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female" required>
            <label for="female">Female</label>
            <br>
     
            <!-- Checkboxes -->
            <label>Interests:</label>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</input>
            <input type="checkbox" id="reading" name="interests" value="reading">
            <label for="reading">Reading</label>
            <br>
     
            <!-- Submit button -->
            <button type="submit">Register</button>
        </form>
</body>
</html>
