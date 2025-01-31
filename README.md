<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>学生基本信息</title>
    <style>
        body {
            font-family: "宋体", "微软雅黑", sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        .info-section {
            margin: 20px 0;
            padding: 20px;
            background: #fff;
            border-bottom: 1px solid #e7e7e7;
        }
        .info-section h2 {
            color: #333;
            border-bottom: 2px solid #e7e7e7;
            padding-bottom: 10px;
        }
        .info-section p {
            margin: 10px 0;
        }
        .info-section strong {
            width: 100px;
            display: inline-block;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>学生基本信息表</h1>
        </div>
    </header>

    <div class="container">
        <section class="info-section">
            <h2>基本信息</h2>
            <p><strong>姓名：</strong> 张三</p>
            <p><strong>性别：</strong> 男</p>     
            <p><strong>学号：</strong> 20240001</p> 
            <p><strong>班级：</strong> 计算机科学与技术1班</p>
        </section>

        <section class="info-section">
            <h2>联系方式</h2>
            <p><strong>电话：</strong> 123-4567-8900</p>
            <p><strong>电子邮箱：</strong> zhangsan@example.com</p>
        </section>

        <section class="info-section">
            <h2>特长爱好</h2>
            <p><strong>特长：</strong> 编程、篮球</p>
            <p><strong>爱好：</strong> 阅读、旅游、音乐</p>
        </section>
    </div>

    <footer>
        <div class="container">
            <p>&copy; 2024 学生基本信息表</p>
        </div>
    </footer>
</body>
</html>
