# 宁波鑫驰众模具有限公司官网

## 项目说明
这是宁波鑫驰众模具有限公司的官方网站源代码，采用工业诗学设计风格，蓝白配色方案。

## 技术栈
- React 19
- Tailwind CSS 4
- Vite 7
- TypeScript

## 部署方式

### 方式一：直接部署静态文件
本文件夹包含已构建好的静态文件，可以直接部署到任何静态服务器：

1. 将整个文件夹上传到服务器
2. 配置Web服务器（Nginx/Apache）指向此目录
3. 确保配置单页应用路由重定向到 index.html

### 方式二：本地预览
直接用浏览器打开 `index.html` 文件即可预览（部分功能可能需要HTTP服务器）

推荐使用简单HTTP服务器：
```bash
# Python 3
python -m http.server 8000

# Node.js (需要先安装 http-server)
npx http-server -p 8000
```

然后访问 http://localhost:8000

## Nginx 配置示例
```nginx
server {
    listen 80;
    server_name your-domain.com;
    root /path/to/xinchizhong-website;
    index index.html;

    location / {
        try_files $uri $uri/ /index.html;
    }
}
```

## 联系方式
- 公司地址：中国 · 浙江省 · 宁波市 · 象山县
- 电话：+86 574 8888 8888
- 邮箱：info@xinchizhong.com

## 版权信息
© 2026 宁波鑫驰众模具有限公司. All rights reserved.
