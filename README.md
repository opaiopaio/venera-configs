# venera-configs

Configuration file repository for [Venera](https://github.com/venera-app/venera).

## Subscribe

Add the following URL to your Venera app's comic source repository settings:

```
https://cdn.jsdelivr.net/gh/opaiopaio/venera-configs@main/index.json
```

## 维护说明

本仓库 fork 自 [venera-app/venera-configs](https://github.com/venera-app/venera-configs)。维护思路：

- **除 nhentai 外，其余源一律跟随上游。** 漫画站点改版频繁，自己维护跟不上；这些源直接同步上游最新文件，不做本地改动，只把更新地址指向本仓库，让 CDN 走自己的仓库。
- **nhentai 单独维护。** 上游仍使用已废弃的 Cookie 认证，本仓库改用 v2 API Key 登录（带获取 API Key 引导），并修复了收藏、语言标签、正文加载等问题。
- **本次（2026-10-06）从上游同步的源**：拷贝漫画、Picacg、紳士漫畫、GoDa漫画、MangaDex、爱看漫、カドコミ，以及新增的 MYCOMIC。
- **未收录**：上游新增的「拷贝漫画（多账号）」与「拷贝漫画」使用同一个 `key`，实测会互相覆盖，故不收录；如需使用，请先在文件内改成独立的 `key`。
- **代码风格**：全仓库使用 Prettier 默认配置统一格式化，方便与上游比对差异。

## Create a new configuration

1. Download `_template_.js`, `_venera_.js`, put them in the same directory
2. Rename `_template_.js` to `your_config_name.js`
3. Edit `your_config_name.js` to your needs.
   - The `_template_.js` file contains comments to help you with that.
   - The `_venera_.js` is used for code completion in your IDE.
4. Add your source to `index.json`
5. Push to your repository, jsDelivr CDN will update automatically
