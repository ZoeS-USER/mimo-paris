# Mimo在巴黎散步的天

和小猫 Mimo 探索十二个巴黎生活与旅行场景，通过角色对话、法语发音、单词和短语拼写学习日常表达。

入口： https://zoes-user.github.io/mimo-paris/

地图可拖动、缩放，点击地点开始学习。每站六轮对话，拼写正确后左滑继续、右滑回看；完成后可生成带场景二维码的自拍卡。支持收藏、易错词练习和发音。

这是无需构建的静态网站。学习进度保存在各自浏览器中，暂不跨设备同步。网站使用本地图片、音频和预生成二维码，无需微信 AppID 或云函数。

## GitHub Pages

仓库 Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save。

保持 `.nojekyll` 与 `index.html` 在根目录，完整保留 `miniprogram/` 和 `codes/` 目录。场景链接通过 `?scene=cafe` 等查询参数打开，兼容 GitHub Pages 项目子路径。

对话与插画为教学内容。词卡包含用户学习资料的简短来源标注；不包含原始 PDF、个人文件或访问密钥。正式教学使用前建议由法语教师审校。
