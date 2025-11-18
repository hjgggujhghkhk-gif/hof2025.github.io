<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>名人堂展示</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'PingFang SC', sans-serif;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 20px;
    }
    
    .hall-container {
      background: rgba(255, 255, 255, 0.95);
      border-radius: 20px;
      padding: 40px;
      max-width: 600px;
      width: 100%;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
      text-align: center;
    }
    
    .hall-title {
      font-size: 2.5em;
      color: #2c3e50;
      margin-bottom: 20px;
      background: linear-gradient(45deg, #667eea, #764ba2);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    
    .hall-subtitle {
      font-size: 1.2em;
      color: #7f8c8d;
      margin-bottom: 30px;
    }
    
    .achievement-card {
      background: #f8f9fa;
      border-radius: 15px;
      padding: 30px;
      margin: 20px 0;
      border-left: 5px solid #667eea;
    }
    
    .achievement-title {
      font-size: 1.5em;
      color: #2c3e50;
      margin-bottom: 10px;
    }
    
    .achievement-desc {
      color: #7f8c8d;
      line-height: 1.6;
    }
    
    .cta-button {
      background: linear-gradient(45deg, #667eea, #764ba2);
      color: white;
      border: none;
      padding: 15px 40px;
      font-size: 1.1em;
      border-radius: 50px;
      cursor: pointer;
      transition: transform 0.3s ease;
      margin-top: 30px;
    }
    
    .cta-button:hover {
      transform: translateY(-2px);
    }
  </style>
</head>
<body>
  <div class="hall-container">
    <h1 class="hall-title">🏆 名人堂</h1>
    <p class="hall-subtitle">您的GitHub Pages项目已成功部署！</p >
    
    <div class="achievement-card">
      <h2 class="achievement-title">首次部署成功</h2>
      <p class="achievement-desc">
        恭喜您完成了第一个GitHub Pages项目的部署！
        这个页面将作为您的名人堂展示页面，记录您的技术成长历程。
      </p >
    </div>
    
    <button class="cta-button" onclick="window.open('https://github.com', '_blank')">
      查看我的GitHub
    </button>
  </div>
</body>
</html>
