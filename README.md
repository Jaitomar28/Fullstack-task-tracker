<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fullstack Task Tracker</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 40px;
            background-color: #f4f4f4;
            color: #333;
        }
        h1, h2, h3 {
            color: #222;
        }
        code {
            background-color: #eaeaea;
            padding: 4px 8px;
            border-radius: 5px;
        }
        pre {
            background-color: #333;
            color: #fff;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .btn {
            display: inline-block;
            background: #28a745;
            color: #fff;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 5px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        th {
            background: #28a745;
            color: #fff;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>📌 Fullstack Task Tracker</h1>
    <p>A simple task tracking application built with <strong>Spring Boot</strong> (backend) and <strong>React.js</strong> (frontend).</p>

    <h2>🚀 Tech Stack</h2>
    <ul>
        <li><strong>Backend:</strong> Java, Spring Boot, Spring Data JPA, MySQL</li>
        <li><strong>Frontend:</strong> React.js, Axios, React Hooks</li>
        <li><strong>Database:</strong> MySQL</li>
    </ul>

    <h2>📂 Project Structure</h2>
    <pre>
Fullstack-task-tracker/
│── backend/  (Spring Boot API)
│── frontend/ (React UI)
    </pre>

    <h2>⚡ Features</h2>
    <ul>
        <li>✅ Add new tasks</li>
        <li>✅ View task list</li>
        <li>✅ Delete tasks</li>
        <li>✅ RESTful API with Spring Boot</li>
        <li>✅ Frontend built using React</li>
    </ul>

    <h2>🔥 Getting Started</h2>
    <h3>1️⃣ Clone the repository</h3>
    <pre><code>git clone https://github.com/Jaitomar28/Fullstack-task-tracker.git
cd Fullstack-task-tracker</code></pre>

    <h3>2️⃣ Run the Backend (Spring Boot)</h3>
    <pre><code>cd backend
mvn spring-boot:run</code></pre>

    <h3>3️⃣ Run the Frontend (React)</h3>
    <pre><code>cd frontend
npm install
npm start</code></pre>

    <h2>🔗 API Endpoints</h2>
    <table>
        <tr>
            <th>Method</th>
            <th>Endpoint</th>
            <th>Description</th>
        </tr>
        <tr>
            <td>GET</td>
            <td>/api/tasks</td>
            <td>Fetch all tasks</td>
        </tr>
        <tr>
            <td>POST</td>
            <td>/api/tasks</td>
            <td>Add a new task</td>
        </tr>
        <tr>
            <td>DELETE</td>
            <td>/api/tasks/{id}</td>
            <td>Delete a task</td>
        </tr>
    </table>

    <h2>🎯 Author</h2>
    <p><strong>Jai Tomar</strong></p>
    <p>🔗 <a href="https://www.linkedin.com/in/jaitomar28/" target="_blank" class="btn">LinkedIn</a></p>
    <p>📂 <a href="https://github.com/Jaitomar28" target="_blank" class="btn">GitHub</a></p>

    <h2>⭐ Contribute</h2>
    <p>Feel free to raise an issue or submit a pull request.</p>

    <h2>📜 License</h2>
    <p>This project is licensed under the <strong>MIT License</strong>.</p>
</div>

</body>
</html>
