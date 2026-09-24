# 🌐 GlobalTrade Pro - 中外贸易宣传网站

## 快速预览

直接用浏览器打开 `index.html` 即可预览网站效果。

---

## 🚀 免费部署指南（GitHub Pages）

### 第一步：注册 GitHub 账号
1. 访问 https://github.com
2. 点击 "Sign up" 注册账号（免费）

### 第二步：创建仓库
1. 登录后点击右上角 "+" → "New repository"
2. 仓库名填写：`你的用户名.github.io`（必须是这个格式）
   - 例如：`zhangsan.github.io`
3. 设为 **Public**（公开）
4. 点击 "Create repository"

### 第三步：上传网站文件
1. 进入仓库，点击 "uploading an existing file"
2. 把 `index.html` 文件拖进去
3. 点击 "Commit changes"

### 第四步：访问网站
等待 1-2 分钟，访问：`https://你的用户名.github.io`

✅ **全球可见！免费！无需服务器！**

---

## 🔗 绑定自定义域名（可选，约 ¥60/年）

### 购买域名
推荐在以下平台购买：
- **Cloudflare Registrar**（推荐，成本价无加价）：https://www.cloudflare.com/products/registrar/
- **Namecheap**：https://www.namecheap.com
- **阿里云万网**（国内访问好）：https://wanwang.aliyun.com

推荐域名格式：
- `yourbrand.com`
- `yourbrand-global.com`
- `yourbrand-trading.com`

### 配置域名
1. 在仓库根目录创建文件 `CNAME`
2. 文件内容只写你的域名，如：`www.yourbrand.com`
3. 在域名服务商处添加 DNS 记录：
   - **类型**：A
   - **名称**：@ 或 www
   - **值**：`185.199.108.153`、`185.199.109.153`、`185.199.110.153`、`185.199.111.153`
4. 等待 DNS 生效（5分钟~24小时）

---

## 🎨 自定义内容

### 替换占位内容
网站中的以下内容需要替换成你的真实信息：

| 内容 | 位置 | 说明 |
|------|------|------|
| 公司名 | Logo区域 | 替换 "GlobalTrade Pro" |
| 地址 | 联系我们 → 地址卡片 | 替换广州地址 |
| 邮箱 | 联系我们 → 邮箱卡片 | 替换 trade@globaltradepro.com |
| 电话 | 联系我们 → 电话/WhatsApp | 替换示例号码 |
| 产品 | 产品中心 | 替换为你的真实产品 |
| 案例 | 客户案例 | 替换为你的真实客户评价 |
| 统计数据 | 首页统计区 | 替换国家数、客户数等 |
| 图片 | 各处 emoji | 替换为真实产品/工厂图片 |

### 替换图片方法
将 emoji 图标替换为真实图片，例如：

```html
<!-- 替换前 -->
<div class="product-img">⚙️</div>

<!-- 替换后 -->
<div class="product-img">
  <img src="images/product-1.jpg" alt="Precision Components" style="width:100%; height:100%; object-fit:cover;">
</div>
```

---

## 📱 部署到其他平台

### Vercel（推荐，速度快）
1. 注册 https://vercel.com
2. 连接 GitHub 仓库
3. 自动部署，获得 `xxx.vercel.app` 域名

### Netlify
1. 注册 https://netlify.com
2. 拖拽上传 `index.html` 所在文件夹
3. 自动部署

---

## 📋 网站功能清单

- ✅ 中英双语一键切换
- ✅ 响应式设计（手机/平板/电脑）
- ✅ 滚动动画效果
- ✅ 询盘表单
- ✅ 导航栏滚动吸顶
- ✅ 回到顶部按钮
- ✅ SEO 友好
- ✅ 零依赖，纯 HTML/CSS/JS

---

## 后续可扩展

- 添加 Google Analytics 统计访问量
- 接入真实表单后端（Formspree / EmailJS）
- 添加 WhatsApp 在线客服按钮
- 多语言扩展（阿拉伯语、西班牙语等）
