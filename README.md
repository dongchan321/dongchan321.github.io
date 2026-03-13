<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的展示页</title>
    <style>
        body { font-family: '微软雅黑', sans-serif; margin: 0; padding: 0; background: #f9f9f9; color: #333; }
        .container { max-width: 800px; margin: 50px auto; padding: 20px; background: white; box-shadow: 0 0 10px rgba(0,0,0,0.1); border-radius: 8px; }
        h1 { color: #2c3e50; text-align: center; }
        p { line-height: 1.6; }
        .download-btn { display: inline-block; background: #3498db; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; margin: 10px 0; }
        .download-btn:hover { background: #2980b9; }
        form { margin-top: 30px; }
        input, textarea { width: 100%; padding: 10px; margin: 8px 0; border: 1px solid #ddd; border-radius: 4px; box-sizing: border-box; }
        button { background: #2ecc71; color: white; padding: 12px 20px; border: none; border-radius: 4px; cursor: pointer; }
        button:hover { background: #27ae60; }
    </style>
</head>
<body>
    <div class="container">
        <h1>欢迎来到我的展示页</h1>
        <p>这里是公司/个人介绍等。</p>
        
        <!-- 文件下载区 -->
        <h2>📁 资料下载</h2>
        <p>点击下方按钮下载示例文件：</p>
        <a href="sample.pdf" class="download-btn" download>下载示例PDF</a>
        
        <!-- 联系表单区 -->
        <h2>📞 联系我们</h2>
        <form action="https://formspree.io/f/你的表单ID" method="POST">
            <input type="text" name="姓名" placeholder="您的姓名" required>
            <input type="email" name="邮箱" placeholder="您的邮箱" required>
            <textarea name="留言" rows="4" placeholder="留言内容"></textarea>
            <button type="submit">提交</button>
        </form>
    </div>
</body>
</html>
