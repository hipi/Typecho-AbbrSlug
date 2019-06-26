# AbbrSlug

> 是从`hexo` 转来的，因为 `hexo` 使用了 `hexo-abbrlink` 这个插件 ，为了 SEO 保持链接不变,所以特地稍微写了这个插件，希望能给到需要帮助的博主。

对标 `hexo-abbrlink` 插件  

以下参照了 `hexo-abbrlink` 的文档

## 设置:

```
alg -- 算法 (目前支持 crc16 和 crc32, 默认crc2)
rep -- 进制显示 (sulg 会显示10进制和16进制)
```

## 例子

> 生成的 slug 会像下面显示:

crc16 & hex
https://tmp.com/posts/66c8.html

crc16 & dec
https://tmp.com/posts/65535.html
crc32 & hex
https://tmp.com/posts/8ddf18fb.html

crc32 & dec
https://tmp.com/posts/1690090958.html

## 限制

`crc16` 算法最大支持 65535 个文章 （个人博客来说已经完全够了）

## 感谢

[NoahDragon](https://github.com/NoahDragon)
[Rozbo](https://github.com/Rozbo)
