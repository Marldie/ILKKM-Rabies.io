# ILKKM-Rabies.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Submission Example</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Fill Out the Form</h1>
        <form id="userForm">
            <label for="name">Name:</label>
            <input type="text" id="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" required>

            <label for="message">Message:</label>
            <textarea id="message" required></textarea>

            <button type="submit">Submit</button>
        </form>

        <div id="result" class="result"></div>
    </div>

    <script src="script.js"></script>
</body>
</html>
