# sichuanshenguanlixiton
🎯 核心痛点 痛点 1：遥感教学需要零安装的交互式演示环境 传统遥感课需要安装 ENVI / ArcGIS / QGIS 等专业软件，学生装一次就得半小时。这个项目让一切在浏览器里运行——所有算法都基于 Canvas API 纯前端实现，后端只是一个静态文件服务器 + 简单的登录注册。  代码体现：  后端 server.js 只做静态托管 + 登录注册（约 65 行） 所有遥感算法全部内嵌在 index.html 的一个 &lt;script> 标签里 痛点 2：NDVI 植被指数计算需要直观的「波段选择 → 伪彩色 → 统计」演示 学生常常不理解 NDVI = (NIR - Red) / (NIR + Red) 这个公式到底在做什么
