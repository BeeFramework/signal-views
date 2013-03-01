signal-views
============

本库记录的是支持 BeeUISignal 的 UI 控件的元信息。

每个UI库一个子目录，以UI控件命名，如 “GCurlPageView”。目录下是一个 json 文件，用以描述这个支持 BeeUISignal  的 UI 控件的元信息。

#### json 文件格式如下：


```
{
	"name":"GCurlPageView",
	"version":"0.0.1",
	"summary":"one of the most simple example for scrolling page. ",
	"description":"one of the most simple example for scrolling page.",
	"homepage":"https://github.com/gelosie/GCurlPageView-BeeUISignal",
	"license":"MIT",
	"author":
	{
		"name":"gelosie",
		"email":"gelosie.wang@gmailc.om",
		"homepage":"http://zhenian.com/",
		"github":"https://github.com/gelosie/"
	},
	"source":
	{
		"sccs":"git",
		"url":"https://github.com/gelosie/GCurlPageView-BeeUISignal.git",
		"files":["GCurlPageView/src/*.{h,m}"],
		"arc":"yes",
		"tag":""
	},
	"originsource":
	{
		"sccs":"git",
		"url":"https://github.com/gelosie/GCurlPageView.git",
		"files":[],
		"arc":"yes",
		"tag":""
	},
	"demo":["https://github.com/gelosie/GCurlPageView-BeeUISignal.git"],
	"screenshots":["https://github.com/gelosie/GCurlPageView-BeeUISignal/blob/master/doc/screenshots/GCurlPageView.png?raw=true"],
	"videos":[]
}

```