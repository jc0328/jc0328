<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>项目展示</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 50px;
        }

        main {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .project-card {
            width: 300px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin: 20px;
            overflow: hidden;
        }

        .project-card img {
            width: 100%;
            height: auto;
        }

        .project-card h2 {
            padding: 10px;
            margin: 0;
        }

        .project-card p {
            padding: 0 10px 10px;
            color: #666;
        }

        .project-card a {
            display: block;
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            text-decoration: none;
        }

        .project-card a:hover {
            background-color: #555;
        }
    </style>
</head>

<body>
    <header>
        <h1>我的项目</h1>
        <p>以下是我参与的一些项目</p>
    </header>
    <main>
        <div class="project-card">
            <img src="project1.jpg" alt="项目 1">
            <h2>项目 1</h2>
            <p>这是一个使用 HTML、CSS 和 JavaScript 构建的静态网站项目，具有响应式设计和交互效果。</p>
            <a href="https://github.com/yourusername/project1">查看项目</a>
        </div>
        <div class="project-card">
            <img src="project2.jpg" alt="项目 2">
            <h2>项目 2</h2>
            <p>这是一个基于 Node.js 和 Express 框架的后端项目，实现了用户认证和数据存储功能。</p>
            <a href="https://github.com/yourusername/project2">查看项目</a>
        </div>
    </main>
</body>

</html>
