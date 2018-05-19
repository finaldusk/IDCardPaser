# IDCardPaser
Chinese IDCardPaser 中国居民身份证解析器

# 本项目大部分代码来自以下两个项目
 [cn/GB2260.js](https://github.com/cn/GB2260.js).
 [mc-zone/IDValidator](https://github.com/mc-zone/IDValidator).
 
 # 与[mc-zone/IDValidator](https://github.com/mc-zone/IDValidator) 的区别
 地区码使用 [cn/GB2260.js](https://github.com/cn/GB2260.js) 中提供的数据，地区名称不包含省市从而大大减少了GB2260.js占用的空间
 使用js内置函数对出生日期进行日期校验
 不包含伪造ID功能
 
 # 项目中GB2260.js与[cn/GB2260.js](https://github.com/cn/GB2260.js)的区别
 本项目中的GB2260.js基于 GB2260.js/lib/201607.json 修改除大陆地区的地区码外还包含hongkong和macao的地区码
