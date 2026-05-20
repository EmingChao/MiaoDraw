# MiaoDraw

AI 图像生成工作坊，基于 OpenAI 兼容 API 的纯静态 Web 应用。

#### 喵喵生图购买店铺: https://pay.ldxp.cn/shop/dingdangmao
#### 喵喵生图CDK兑换: https://img.matsca.com/redeem/

## 功能特性

- **多模型支持** — GPT Image 1/2、DALL-E 2/3
- **图像生成** — 支持多种尺寸（256×256 ~ 1792×1024）、质量调节、风格选择
- **图像编辑** — 粘贴/上传原图，通过提示词进行 AI 编辑
- **队列管理** — 批量添加提示词，自动排队生成
- **历史记录** — 本地 IndexedDB 存储，支持预览、下载、复制 URL
- **积分配额** — 支持 img.matsca.com 的配额实时查询与自动刷新
- **连接测试** — 一键验证 API 连通性

## 使用方式

直接打开 `MiaoDraw.html` 即可使用，无需安装任何依赖。

1. 点击右上角 **设置** 按钮
2. 填写 **API Base URL** 和 **API Key**
3. 输入提示词，点击 **生成图像**

### 积分配额

当 API 地址配置是喵绘API时，状态栏会自动显示剩余配额。支持手动点击刷新，生图/编辑完成后自动更新。

## 技术栈

- 纯 HTML + CSS + JavaScript，无框架依赖
- localStorage 存储设置，IndexedDB 存储历史
- OpenAI 兼容 API

## License

MIT
