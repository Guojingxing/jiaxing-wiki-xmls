# jiaxing-wiki-xmls
MediaWiki平台的jiaxingwiki数据库的xml转储文件

**包括两个部分：** fandom和miraheze
## 使用方法
1. 通过创建的wiki的`Special:Import`页面可以导入`xml`文件，跨wiki前缀随便填，如`jiaxing_`。
2. 如果文件很大，就把文件拆分成很多个小文件一个一个上传（fandom不用，miraheze需要）。
3. 如果很长时间（60天）不编辑miraheze了，记得一定要在`Special:Export`导出xml放在这里保存。
