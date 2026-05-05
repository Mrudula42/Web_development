# 1 Create a simple HTML page displaying personal details using text formatting tags.
<!DOCTYPE html>
<html>
<head>
    <title>Personal Details</title>
</head>
<body>
    <h1><u>My Personal Details</u></h1>
    <p><b>Name:</b> Mrudula Kale</p>
    <p><strong>Age:</strong> 20</p>
    <p><i>Course:</i> Computer Engineering</p>
    <p><em>College:</em> Dhole patil College of Engineering</p>
    <p><b>Hobbies:</b></p>
    <p>
        <u>Reading</u>, 
        <i>Listening to Music</i>, 
        <strong>Coding</strong>
    </p>
    <p>
        <b>About Me:</b><br>
        I am a <strong>passionate</strong> student who loves 
        <i>learning new technologies</i> and 
        <u>building creative projects</u>.
    </p>
</body>
</html>


#2 Design a web page that includes an image, hyperlink, and a nested table.
<!DOCTYPE html>
<html>
<style>
table, th, td {
    border: 1px solid black;   border-collapse: collapse;}
h1{
color:hotpink;
}
</style>
<body>
<h1>Image</h1>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTK2fGfpcvALkrtrl8lAUZSFIx7Bfzt_FVeOQ&s" alt="DPES logo";></img>
<h1>Hyperlink</h1>
<a href="https://dpcoepune.edu.in/departments/computer-engineering/">Click here</a><br>
<h1>Nested Table</h1>
<table style= "width:40%">
        <tr>
            <th>Employees</th>
            <th>NetWorth</th>
        </tr>
        <tr>
            <td>
                <!-- Nested Table -->
                <table style="width:100%">
                    <tr>
                        <th>Name</th>
                        <th>Salary</th>
                    </tr>
                    <tr>
                        <td>Ramesh</td>
                        <td>5000</td>
                    </tr>
                    <tr>
                        <td>Shabbir</td>
                        <td>7000</td>
                    </tr>
                </table>
            </td>
            <td>12,000</td>
        </tr>
    </table>
</body>
</html>



#3 Create a form with fields: name, email, gender, date of birth, and submit button.
<!DOCTYPE html>
<html>
<style>
form{
    font-size:25px;
    color:green;
}
h1{
    color:red;
    font-size:35px;
}
</style>
</body>
<h1><u>Students details</u></h1>
<form action="">
Name: <input type="text" name="Name"><br><br>
Email: <input type="email" name="Email"><br><br>
Gender<br>
<input type="radio" name="Gender">Male<br>
<input type="radio" name="Gender">Female<br><br>
Date of birth: <input type="date" name="dob"><br><br>
<input type="submit" name="submit">
</form>
</body>
</html>



#4 Create Follwing output image using internal CSS  
<!DOCTYPE html>
<html>
<head>
    <title>My Schedule</title>

    <!-- Internal CSS -->
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }

        h1 {
            margin-top: 20px;
        }

        table {
            margin: 20px auto;
            border-collapse: collapse;
            width: 60%;
        }

        th, td {
            border: 1px solid #888;
            padding: 12px;
        }

        th {
            background-color: #e0e0e0;
            font-weight: bold;
        }

        tr:nth-child(even) {
            background-color: #f5f5f5;
        }
    </style>
</head>
<body>
    <h1>My Schedule</h1>
    <table>
        <tr>
            <th>Day</th>
            <th>Task</th>
            <th>Time</th>
        </tr>
        <tr>
            <td>Monday</td>
            <td>Code Practice</td>
            <td>10:00 AM</td>
        </tr>
        <tr>
            <td>Wednesday</td>
            <td>Team Meeting</td>
            <td>2:00 PM</td>
        </tr>
        <tr>
            <td>Friday</td>
            <td><i>Project Review</i></td>
            <td>4:00 PM</td>
        </tr>
    </table>
</body>
</html>
