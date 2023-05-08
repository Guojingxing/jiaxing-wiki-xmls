# jiaxing-wiki-xmls
MediaWiki平台的jiaxingwiki数据库的xml转储文件

**包括两个部分：** fandom和miraheze
## 使用方法
1. 通过创建的wiki的`Special:Import`页面可以导入`xml`文件，跨wiki前缀随便填，如`jiaxing_`。
2. 如果文件很大，就把文件拆分成很多个小文件一个一个上传（fandom不用，miraheze需要）。
3. 如果很长时间（60天）不编辑miraheze了，记得一定要在`Special:Export`导出xml放在这里保存。

## 具体步骤
你可以使用GitHub来保存你在Miraheze上编辑的Wiki的XML转储文件。GitHub可以用作版本控制系统，帮助你跟踪文件的变更。以下是将XML转储文件保存到GitHub的方法：
1. 首先，在Miraheze的Wiki中导出你想要保存的内容。前往“特殊页面”（Special Pages），然后选择“导出页面”（Export pages）。按照说明导出XML文件。
2. 创建一个新的GitHub仓库。如果你没有GitHub帐户，你需要先注册一个。
3. 将XML转储文件上传到新创建的GitHub仓库。这可以通过Git命令行工具或GitHub网站上的文件上传功能来完成。
现在，你的Miraheze Wiki的XML转储文件已保存在GitHub上。你可以随时下载该文件，并将其导入到其他MediaWiki实例中。
