# Site
Servis site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Builder</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Website Builder</h1>
        <form id="websiteForm">
            <label for="pageTitle">Enter Page Title:</label>
            <input type="text" id="pageTitle" name="pageTitle" required>
            
            <label for="pageContent">Enter Page Content:</label>
            <textarea id="pageContent" name="pageContent" rows="4" required></textarea>
            
            <button type="button" onclick="buildWebsite()">Build Website</button>
        </form>

        <div id="result"></div>
    </div>

    <script src="script.js"></script>
</body>
</html>
