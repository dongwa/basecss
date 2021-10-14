# 文档
https://xiaomi.f.mioffice.cn/docs/dock4J13i3gHg7AfRAqTFlvVQW7#

# 编译
安装liveSassComplie插件
修改配置
``` json
	"liveSassCompile.settings.formats": [
		// 扩展
		{
			"format": "compressed", //可定制的出口CSS样式（expanded，compact，compressed，nested）
			"extensionName": ".min.css", //编译后缀名
			"savePath": null //编译保存的路径
		}
	],
	"liveSassCompile.settings.excludeList": [
		"**/node_modules/**",
		".vscode/**"
	],
```
使用`Live Sass: Compile Sass - Without Watch Mode`命令进行编译

# 部署
使用cdn.jsdelivr.net部署，只需要推送到github即可
