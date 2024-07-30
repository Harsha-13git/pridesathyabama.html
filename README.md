<!DOCTYPE html>
<html>
<head>
    <title>Sign up</title>
</head>
<body>
    <h1 style="color: crimson;">Sign up</h1>
    <form>
        <label for="firstName">First name:</label>
        <input type="text" id="firstName" name="firstName"><br><br>

        <label for="lastName">Last name:</label>
        <input type="text" id="lastName" name="lastName"><br><br>

        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="Male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="Female">
        <label for="female">Female</label><br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" placeholder="dd-mm-yyyy"><br><br>

        <label for="designation">Designation:</label>
        <input type="text" id="designation" name="designation"><br><br>

        <label for="department">Department:</label>
        <select id="department" name="department">
            <option value="select">Select Department</option>
            <!-- Add more options as needed -->
        </select><br><br>

        <label for="salary">Salary:</label>
        <input type="text" id="salary" name="salary"><br><br>

        <fieldset>
            <legend>Address</legend>
            <label for="country">Country:</label>
            <select id="country" name="country">
                <option value="country">Country</option>
                <!-- Add more options as needed -->
            </select><br><br>

            <label for="ftNo">Ft-no:</label>
            <input type="text" id="ftNo" name="ftNo"><br><br>

            <label for="area">Area:</label>
            <input type="text" id="area" name="area"><br><br>

            <label for="city">City:</label>
            <input type="text" id="city" name="city"><br><br>

            <label for="state">State:</label>
            <input type="text" id="state" name="state"><br><br>

            <label for="code">Code:</label>
            <input type="text" id="code" name="code"><br><br>
        </fieldset>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
