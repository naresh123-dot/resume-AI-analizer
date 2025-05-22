# resume-AI-analizer
<!DOCTYPE html>
<html>
<head>
    <title>Resume Analyzer</title>
</head>
<body>
    <h1>Upload Your Resume</h1>
    <form method="post" action="/upload" enctype="multipart/form-data">
        <input type="file" name="resumeFile" accept=".pdf,.docx" required />
        <button type="submit">Analyze</button>
    </form>
</body>
</html>
