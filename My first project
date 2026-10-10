
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PLP Day 5 Assignment</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 900px;
            margin: 30px auto;
            padding: 20px;
            line-height: 1.6;
            background: #f4f6f8;
            color: #222;
        }
        main {
            background: white;
            padding: 25px;
            border-radius: 10px;
        }
        h1, h2 { color: #174ea6; }
        pre {
            background: #1e293b;
            color: #f8fafc;
            padding: 15px;
            border-radius: 6px;
            overflow-x: auto;
        }
        code { font-family: Consolas, monospace; }
        button {
            padding: 10px 16px;
            background: #174ea6;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        @media print {
            body { background: white; margin: 0; }
            main { padding: 0; }
            button { display: none; }
        }
    </style>
</head>
<body>
<main>
    <button onclick="window.print()">Print / Save as PDF</button>

    <h1>PLP Software Engineering Essentials</h1>
    <h2>Day 5 Assignment</h2>

    <p><strong>Name:</strong> Diclot Selemani</p>
    <p><strong>Date:</strong> 10 October 2026</p>
    <p><strong>Course:</strong> Software Engineering Essentials</p>

    <hr>

    <h2>Part A: GitHub Repository Setup</h2>
    <p><strong>Repository:</strong> plp-day5-assignment</p>

    <p><strong>README.md</strong></p>
    <pre><code># PLP Day 5 Assignment

This project contains GitHub setup and API documentation
for the Software Engineering Essentials course.</code></pre>

    <p><strong>Git Commands</strong></p>
    <pre><code>git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main</code></pre>

    <h2>Part B: API Documentation</h2>
    <p><strong>Endpoint:</strong> POST /v1/projects/{projectId}/tasks</p>
    <p><strong>Description:</strong> Creates a new task in a project.</p>

    <h3>Headers</h3>
    <pre><code>Content-Type: application/json
Authorization: Bearer YOUR_ACCESS_TOKEN</code></pre>

    <h3>Request Body</h3>
    <pre><code>{
  "title": "Complete assignment",
  "description": "Submit the Day 5 assignment",
  "status": "pending",
  "dueDate": "2026-10-15"
}</code></pre>

    <h3>Successful Response — 201 Created</h3>
    <pre><code>{
  "id": "task_001",
  "projectId": "project_123",
  "title": "Complete assignment",
  "description": "Submit the Day 5 assignment",
  "status": "pending",
  "dueDate": "2026-10-15"
}</code></pre>

    <h3>HTTP Status Codes</h3>
    <ul>
        <li>201 Created — Task created successfully.</li>
        <li>400 Bad Request — Invalid request data.</li>
        <li>401 Unauthorized — Missing or invalid authentication.</li>
        <li>404 Not Found — Project does not exist.</li>
        <li>500 Internal Server Error — Server error.</li>
    </ul>

    <p><em>Note: This is a sample API specification.</em></p>

    <h2>Submission Checklist</h2>
    <ul>
        <li>Create the GitHub repository.</li>
        <li>Add README.md and api_documentation.md.</li>
        <li>Commit and push the files.</li>
        <li>Take screenshots of the repository and uploaded files.</li>
        <li>Submit the repository link and screenshots.</li>
    </ul>
</main>
</body>
</html>
