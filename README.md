### 1. 部署 Cloudflare Pages：
   - 在 Github 上先 Fork 本项目，并点上 Star !!!
   - 在 Cloudflare Pages 控制台中选择 `连接到 Git`后，选中 `Cf-Text-to-Image`项目后点击 `开始设置`。

### 2. 给 Pages绑定 自定义域：
   - 在 Pages控制台的 `自定义域`选项卡，下方点击 `设置自定义域`。
   - 填入你的自定义次级域名，注意不要使用你的根域名，例如：
     您分配到的域名是 `fuck.ass.com`，则添加自定义域填入 `ai.fuck.ass.com`即可；
   - 按照 Cloudflare 的要求将返回你的域名DNS服务商，添加 该自定义域 `ai`的 CNAME记录 `Cf-Text-to-Image.pages.dev` 后，点击 `激活域`即可。
### 4. 添加变量名称：
   1. 绑定**变量名称**为`AI`的**Workers AI**；
![QQ20250307-134135](https://github.com/user-attachments/assets/8e31f8a6-6ee1-4742-b933-d1dfbd39f23d)
![QQ20250307-134527](https://github.com/user-attachments/assets/0daf3593-9c42-41bf-b5eb-c80afd4ab130)
![QQ20250307-134419](https://github.com/user-attachments/assets/57fdc2c9-f998-4f70-a729-862a002898b6)
