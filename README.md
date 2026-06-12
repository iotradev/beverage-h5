# 群享饮品 - H5网页版

群里同事娱乐点单小程序，无需备案、无需认证，发链接到群里就能用！

## 功能

- ☕ 两大品类：苑探一口（柠檬茶）、维探一大口（咖啡）
- 🎨 商品定制：杯型、糖度、冰量、加料
- 🛒 购物车：数量修改、删除、清空
- 📋 订单历史：查看历史订单
- 📊 今日汇总：查看所有人都点了什么
- 📢 晒单功能：复制订单发到群里

## 部署到 GitHub Pages

### 方法一：GitHub 网页操作

1. 登录 GitHub，创建新仓库，名称为 `beverage-h5`
2. 上传 `index.html` 文件
3. 仓库设置 → Pages → Source 选择 `main` 分支
4. 保存后会生成链接：`https://你的用户名.github.io/beverage-h5/`

### 方法二：命令行

```bash
cd beverage-h5
git init
git add index.html
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/你的用户名/beverage-h5.git
git push -u origin main
```

然后在 GitHub 仓库设置中开启 Pages。

## 使用

部署完成后，把链接发到群里：
```
https://你的用户名.github.io/beverage-h5/
```

群友点开就能点单，无需任何安装！
