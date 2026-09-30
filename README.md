# Student-Attendence-Form
Attendence form during Collage seminar and events
<!DOCTYPE html>
<html>
<head>
    <title>Student Attendance Application</title>
</head>
<body>

    <h2>Student Attendance Application</h2>

    <form>
        <label>Student Name:</label><br>
        <input type="text" name="student_name" placeholder="Enter your name" required>
        <br><br>

        <label>Enrollment Number:</label><br>
        <input type="text" name="enrollment" placeholder="Enter enrollment number" required>
        <br><br>

        <label>Email:</label><br>
        <input type="email" name="email" placeholder="Enter email" required>
        <br><br>

        <label>Branch:</label><br>
        <select name="branch" required>
            <option value="">Select Branch</option>
            <option value="CSE">Computer Science Engineering</option>
            <option value="IT">Information Technology</option>
            <option value="ECE">Electronics & Communication</option>
            <option value="ME">Mechanical Engineering</option>
            <option value="CE">Civil Engineering</option>
        </select>
        <br><br>

        <label>College:</label><br>
        <input type="text" name="college" placeholder="Enter college name" required>
        <br><br>

        <input type="submit" value="Submit">

    </form>

</body>
</html>
