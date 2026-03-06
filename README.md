# Vibo 跳转页面

这是一个简单的跳转页面,用于在微信中访问扣子平台的应用。

## 功能
- 3秒倒计时自动跳转
- 可点击按钮立即跳转
- 美观的过渡页面

## 部署到 Vercel

### 1. 安装 Vercel CLI
```bash
npm install -g vercel
```

### 2. 登录 Vercel
```bash
vercel login
```

### 3. 部署项目
```bash
cd ~/.openclaw/workspace-dev/vibo-redirect
vercel --prod
```

### 4. 配置自定义域名
在 Vercel 控制台中:
1. 进入项目设置
2. 点击 "Domains"
3. 添加域名: `vibo.qfzixun.cn`
4. 按照提示配置 DNS 记录

## DNS 配置

在你的域名管理后台(qfzixun.cn)添加 CNAME 记录:

```
类型: CNAME
主机记录: vibo
记录值: cname.vercel-dns.com
TTL: 600
```

## 目标地址
https://y3vhzd3sn5.coze.site
