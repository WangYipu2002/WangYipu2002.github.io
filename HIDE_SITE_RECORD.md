# 网站隐藏/恢复操作记录

> 记录时间：2026-06-18
> 操作目的：隐藏 WangYipu2002.github.io 网站，防止搜索引擎收录

---

## 📋 修改内容

### 1. 新增 `robots.txt` — 禁止搜索引擎爬虫

**文件路径：** `robots.txt`

**内容：**
```text
User-agent: *
Disallow: /
```

**作用：** 告诉所有搜索引擎不要索引网站内容

---

### 2. 修改 `_includes/head.html` — 添加 noindex 元标签

**文件路径：** `_includes/head.html`

**添加内容：**
```html
<meta name="robots" content="noindex, nofollow, noarchive">
```

**作用：** 阻止搜索引擎索引当前页面

---

### 3. 新增 `login.html` — 密码保护页面模板（可选）

**文件路径：** `login.html`

**作用：** 可作为网站入口，添加密码访问控制

---

## 🔙 恢复方法（取消隐藏）

如果你想让网站重新被搜索引擎收录，按以下步骤操作：

### 步骤 1：删除 `robots.txt`

```bash
rm robots.txt
```

### 步骤 2：恢复 `_includes/head.html`

删除或注释掉以下代码：
```html
<meta name="robots" content="noindex, nofollow, noarchive">
```

### 步骤 3：提交更改

```bash
git add .
git commit -m "chore: remove robots.txt and noindex to re-enable search indexing"
git push origin main
```

### 步骤 4（可选）：请求搜索引擎重新收录

- **Google**：在 [Search Console](https://search.google.com/search-console) 中提交网址索引请求
- **百度**：在 [搜索资源平台](https://ziyuan.baidu.com) 中提交收录请求

---

## 📌 Git 提交记录

| 项目 | 值 |
|:---|:---|
| Commit Hash | `8d671c6` |
| 提交信息 | `chore: add robots.txt and noindex to hide site from search engines` |
| 修改文件数 | 3 个文件 |
| 新增行数 | 82 行 |

---

## ⚠️ 注意事项

1. **搜索引擎生效时间**：通常需要几天到几周不等
2. **已索引内容**：搜索引擎会逐步移除，不会立即消失
3. **GitHub Pages 限制**：此仓库为 fork 仓库，无法改为私有
4. **直接访问**：以上操作无法阻止通过直接 URL 访问网站，如需完全隐藏需考虑其他托管方案
