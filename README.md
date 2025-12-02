# NewGit
New rep
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>University Admission Form</h1>
    <form action="">
        <fieldset style="border: 2px solid black;">
            <legend>Personal Information:</legend><br>
            <label for="name">Name:</label>
            <input type="text" id="uname" name="uname"><br>
            <label for="birthday">Date of Birth:</label>
            <input type="date" id="birthday" name="birthday"><br>
            <label for="gender">Gender:</label>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br>
            <label for="email">Email:</label>
            <input type="text" id="email" name="email"><br>
            <label for="contact">Contact Number:</label>
            <input type="number" id="contact" name="contact"><br>
            <label for="adress">Address:</label>
            <textarea  id="adress"  name="adress" rows="4" cols="50" placeholder="Enter your address" ></textarea>
    
        </fieldset>
        <br>
        <fieldset style="border: 2px solid black;">
            <legend>Academic Details</legend>
            <label for="high school">High School Name:</label>
            <input type="text" id="high school" name="high school"><br>
            <label for="year of graduation">Year of Graduation</label>
            <input type="number" id="high school" name="high school" min="3" max="4"><br>
            <label for="gpa">GPA:</label>
            <input type="number" id="gpa" name="gpa"><br>
            <label for="age">Intended Major:</label>
            <select id="age" name="age">
                <option value="Selected Major"></option>
                <option value="Selected Minor"></option>
            </select><br>
            <label for="transcript">Upload Transcript:</label>
            <input type="file" id="fileUpload" name="myFile" accept=".jpg,,.png" multiple required>
            <br>

        </fieldset><br>

        <fieldset style="border: 2px solid black;">
            <legend>Additional Information</legend>
            <label for="activities">Extracurricular Activities:</label>
            <textarea id="activities" name="activities" rows="3" cols="50" ></textarea><br>
            <label for="question">Do you need scholarship?</label>
            <input type="checkbox" id="yes" name="yes">
            <label for="yes">Yes</label>
             <input type="checkbox" id="no" name="no">
            <label for="no">No</label><br>
            <label for="text">Agree to Terms:</label>
            <input type="checkbox" id="text" name="text">
        </fieldset>
        <input type="submit" value="Submit Application">
    </form>
</body>
</html>
