# Student-Attendence-Form
Attendence form during Collage seminar and events
<!DOCTYPE html>
<html>
<head>
    <title>Student Attendance Form</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0ebf8;
            margin: 0;
            padding: 30px;
        }

        .form-container {
            width: 600px;
            margin: auto;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.15);
            overflow: hidden;
        }

        .header {
            background-color: #673ab7;
            height: 10px;
        }

        .form-content {
            padding: 30px;
        }

        h1 {
            font-size: 28px;
            font-weight: normal;
            margin-bottom: 10px;
        }

        .description {
            color: #555;
            margin-bottom: 25px;
        }

        label {
            display: block;
            font-size: 16px;
            margin-bottom: 10px;
        }

        input, select {
            width: 100%;
            padding: 12px;
            border: none;
            border-bottom: 1px solid #777;
            box-sizing: border-box;
            font-size: 15px;
            margin-bottom: 25px;
            outline: none;
        }

        input:focus, select:focus {
            border-bottom: 2px solid #673ab7;
        }

        .submit-btn {
            background-color: #673ab7;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 5px;
            font-size: 15px;
            cursor: pointer;
        }

        .submit-btn:hover {
            background-color: #512da8;
        }
    </style>
</head>

<body>

    <div class="form-container">

        <div class="header"></div>

        <div class="form-content">

            <h1>Student Attendance Form</h1>

            <p class="description">
                Please fill in the details below to mark your attendance.
            </p>

            <form>

                <label>Student Name</label>
                <input type="text" placeholder="Your answer" required>

                <label>Enrollment Number</label>
                <input type="text" placeholder="Your answer" required>

                <label>Email</label>
                <input type="email" placeholder="Your email" required>

                <label>Branch</label>
                <select required>
                    <option value="">Choose</option>
                    <option>CSE</option>
                    <option>IT</option>
                    <option>ECE</option>
                    <option>Mechanical</option>
                    <option>Civil</option>
                </select>

                <label>College</label>
                <input type="text" placeholder="Your college name" required>

                <button type="submit" class="submit-btn">
                    Submit
                </button>

            </form>

        </div>
    </div>

</body>
</html>
    </form>

</body>
</html>
