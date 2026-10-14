# FORM · 身体养成手账

免费的个人 PWA 健身计划工具。包括按日训练清单、打卡、重量记录、12周进度、身体指标趋势、调整训练日、JSON 备份、ICS 日历提醒。

## 部署到 GitHub Pages（免费）

1. 在 GitHub 创建一个**公开**仓库，例如 `form-fitness`。
2. 上传本文件夹内的 `index.html`、`manifest.webmanifest`、`sw.js` 和 `icon.svg` 到仓库根目录。
3. 打开仓库 **Settings → Pages → Build and deployment**，Source 选 **Deploy from a branch**，Branch 选 `main`，目录选 `/ (root)`，保存。
4. 等待部署完成，打开 GitHub Pages 提供的 HTTPS 地址。
5. iPhone 用 Safari 打开网站，选择分享 → **添加到主屏幕**。

注意：直接打开本地 HTML 可以体验大部分界面，但离线缓存和主屏幕安装需要 HTTPS 网站环境。

## 通知

第一版不包含后台推送。打开 App 的「设置 → 导出12周日历」，将 `.ics` 导入手机日历并开启通知。日历事件默认在 11:00 开始，提前 30 分钟提醒；可在日历内修改。重复导入可能出现重复事件。

## 数据隐私

训练数据只保存在当前浏览器 localStorage 中，不上传云端。清除网站数据或换设备会丢失记录；请定期在设置中导出 JSON 备份。不同浏览器/主屏幕安装模式的数据可能不会共享。

## 训练提示

前3周先做1—2组，逐步进阶；医生已表示可正常运动，但若出现胸痛、濒晕、明显不适，应立即停止运动并寻求医疗评估。游泳在教练指导下进行。
