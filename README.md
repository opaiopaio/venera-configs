# venera-configs

Configuration file repository for [Venera](https://github.com/venera-app/venera).

## Subscribe

Add the following URL to your Venera app's comic source repository settings:

```
https://cdn.jsdelivr.net/gh/opaiopaio/venera-configs@main/index.json
```

## Available Sources

| Source | Key | Version |
|--------|-----|---------|
| 拷贝漫画 | copy_manga | 1.4.1 |
| Komiic | Komiic | 1.0.4 |
| 包子漫画 | baozi | 1.1.6 |
| Picacg | picacg | 1.0.5 |
| nhentai | nhentai | 1.2.0 |
| 紳士漫畫 | wnacg | 1.0.4 |
| ehentai | ehentai | 1.2.0 |
| 禁漫天堂 | jm | 1.4.0 |
| MangaDex | manga_dex | 1.1.1 |
| 爱看漫 | ikmmh | 1.0.5 |
| 少年ジャンプ＋ | shonen_jump_plus | 1.1.1 |
| hitomi.la | hitomi | 1.1.2 |
| comick | comick | 1.2.0 |
| 优酷漫画 | ykmh | 1.0.0 |
| 再漫画 | zaimanhua | 1.0.2 |
| 漫画柜 | ManHuaGui | 1.2.1 |
| 漫蛙吧 | manwaba | 1.0.2 |
| Lanraragi | lanraragi | 1.2.0 |
| Komga | komga | 1.0.0 |
| カドコミ | comic_walker | 1.0.0 |
| 漫画1234 | mh1234 | 1.0.0 |
| CCC追漫台 | ccc | 1.0.1 |
| GoDa漫画 | goda | 1.0.0 |
| 18漫画 | mh18 | 1.0.0 |
| 漫小肆 | mxs | 1.0.0 |
| 漫画人 | manhuaren | 1.0.0 |
| H-Comic | hcomic | 1.0.0 |
| jcomic.net | jcomic | 1.0.0 |
| 热辣漫画 | hot_manga | 1.0.0 |
| Kavita | kavita | 1.0.0 |
| 嗨皮漫画 | happy | 1.0.0 |

## Create a new configuration

1. Download `_template_.js`, `_venera_.js`, put them in the same directory
2. Rename `_template_.js` to `your_config_name.js`
3. Edit `your_config_name.js` to your needs. 
   - The `_template_.js` file contains comments to help you with that. 
   - The `_venera_.js` is used for code completion in your IDE.
4. Add your source to `index.json`
5. Push to your repository, jsDelivr CDN will update automatically