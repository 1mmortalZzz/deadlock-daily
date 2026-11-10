# 🔥 r/DeadlockTheGame 每日热点

> 自动抓取 Reddit r/DeadlockTheGame 热帖，生成可视化报告。

**网站：** https://1mmortalZzz.github.io/deadlock-daily

## 功能

- 🏆 每日冠军卡片
- 🔥 Top 25 热门帖排行
- 💬 讨论最热帖
- ⚔️ 英雄热度分析
- 📊 类型分布图
- 🔤 热词云
- 🌙 深色/浅色模式切换
- 🔍 upvotes / 评论数筛选
- 📁 历史归档

## 自动更新

- **每日 10:00 AM 北京时间** 自动抓取并部署
- 由 QClaw Agent 驱动

## PogPog UGC 搬运量

单独页面，统计每天从 Reddit r/DeadlockTheGame 搬运到 PogPog 的帖子数量。放在子目录里，避免被每日热点报告覆盖根目录的 `index.html`。

- **页面：** https://1mmortalzzz.github.io/deadlock-daily/ugc/
- **怎么更新：** 每次跑完后只改 `ugc/data.json`。页面从该文件读取每日搬运量、累计和帖子标题，不必改 `ugc/index.html`。
- 日期按 **Asia/Shanghai（GMT+8）** 统计。不要把账号邮箱写进这个 JSON。

## 报告格式

每份报告包含：
- 100 篇 Hot 帖完整数据
- upvotes、评论数、作者、发布时间
- 中文内容概括
- 里程碑检测（首次破 5000/2000/1000/500/100 赞）
