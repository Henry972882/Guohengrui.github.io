# 郭恒瑞个人主页

这是一个可以直接上传到 GitHub 的静态个人主页项目。
当前版本已经把个人照片直接嵌入 `index.html`，上传时不依赖额外图片路径。

## 文件说明

- `index.html`：主页主文件
- `style.css`：页面样式文件
- `.nojekyll`：保证 GitHub Pages 以静态站点方式直接发布

## 本地预览

直接用浏览器打开 `index.html` 即可查看页面效果。

## 上传到 GitHub

1. 在 GitHub 新建一个仓库
2. 把 `index.html`、`style.css`、`README.md`、`.nojekyll` 上传到仓库根目录
3. 提交后即可在仓库中查看源码

## 发布为 GitHub Pages

1. 进入 GitHub 仓库页面
2. 点击 `Settings`
3. 打开 `Pages`
4. 在 `Build and deployment` 中选择：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - 文件夹选择 `/ (root)`
5. 保存后等待几分钟，GitHub 会生成你的个人主页链接

## 页面内容

主页当前包含以下信息：

- 姓名：郭恒瑞
- 专业：日语
- 职务：外院学术部部长
- 兴趣爱好：篮球、辩论、阅读、语言交流
- 性格特点：认真、开朗、负责、善沟通
- 项目经历：
  - 参与市级大创项目《AI时代下中国文化形象》
  - PRP 项目《数据可视化》负责人
- 辩论荣誉：
  - 第30届联合杯冠军
  - 瀛泰杯法律交流赛亚军

你也可以继续补充联系方式、技能证书、获奖经历和个人邮箱等内容。
