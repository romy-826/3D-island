# rong 的小岛

一个可自由走动的微缩 3D 小岛作品集 Demo，使用原生 HTML、CSS、JavaScript 和 WebGL。

## 已脱敏的公开版本

- 日记标题不含真实姓名，四页日记内容全部清空，保留空白书页与翻页交互。
- 保留小岛昵称、六张 AI 角色立绘作品、房间与物品互动。
- 图片已移除文本、EXIF 等附加元数据，图像像素数据保持不变。
- 只包含运行网站需要的文件；不包含历史版本、旧截图、本机路径、局域网地址、启动脚本、账号凭据或 Sites 配置。

## 上传 GitHub

1. 解压文件包，新建一个 GitHub 仓库。
2. 把本目录里的文件与 assets 文件夹一起上传到仓库根目录。确保根目录直接能看到 index.html。
3. 不要只上传 ZIP 压缩包，也不要把本机其他旧版本一起上传。

## 用 GitHub Pages 发布

仓库中打开 Settings → Pages，将 Source 设置为 Deploy from a branch，选择 main 分支和 /(root) 目录，保存。等待部署完成后，使用 GitHub 显示的网址访问。

部署之后可从手机浏览器直接访问，无需电脑持续开机或连接同一个 Wi-Fi。移动端需要支持 WebGL 的浏览器。

[GitHub Pages 官方发布说明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## 本地查看

通过任意静态 HTTP 服务打开项目根目录。若电脑安装了 Python，可在此目录运行 python -m http.server 8000，然后访问 http://localhost:8000/ 。双击 HTML 可能触发浏览器对本地图片纹理的限制。

## 操作

- 电脑：WASD 移动；鼠标拖动或方向键转向。
- 手机：按住屏幕箭头移动，拖动画面转向。
- 点击房门切换房间，点击相框浏览作品；可左右切换、放大和拖动图片。
- 日记保留空白翻页；全部三件卧室物品探索后，仍可前往书房。

## 文件

- index.html：页面入口与空白日记。
- garden.js / rooms.js / floral.js：三维场景与花卉。
- house.js / walk.js：房间切换、相机与走动。
- bedroom.js：卧室探索与日记翻页。
- gallery.js / assets/：作品展示与图片。
- CSS 文件：页面、物品卡片、字体与画廊样式。

## 字体与作品

中文手写字体使用 Long Cang，许可证见 FONT-LICENSE.txt。作品图片保留在此项目中；本文件包不额外授予第三方图片使用许可。
