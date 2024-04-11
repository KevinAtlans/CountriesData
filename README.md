# 世界国家名称及国旗数据

#### [countries_list.json](countries_list.json "世界国家数据列表") 文件
国家数据列表 [country_data, ...]

#### [countries_abb2.json](countries_abb2.json "世界国家数据集合") 文件
以2位国家缩写为key的国家数据集合 {country_abb2 : country_data,  ...}

**country_data 国家数据**
```
{
	cn : 		国家中文名称,
	en : 		国家英文名称,
	full: 		国家英文全称,
	abb2: 		国家英文2位简称（大写）,
	abb3:		国家英文3位 简称（ 大写）,
	code:		国家code数字（字符串）
}

example:
{
	"cn"	:	"中国",
	"en"	:	"China",
	"full"	:	"the People's Republic of China",
	"abb2"	:	"CN",
	"abb3"	:	"CHN",
	"code"	:	"156"
}

```
**countries_list_new 国家数据**
```
{
	"code": "国家code数字（字符串）",
	"cn": "国家中文名",
	"en": "国家英文名",
	"cnFull": "国家中文全称",
	"enFull": "国家英文全称",
	"png": "国旗图片名 在 countries_flags 中查找",
	"teleCode": "国家 区号",
	"moneyCode": "国家货币代码",
	"moneySign": "国家货币符号",
	"moneyUnit": "国家货币名"
}

example:
{
	"code": "204",
	"cn": "贝宁",
	"en": "Benin",
	"cnFull": "贝宁共和国",
	"enFull": "the Republic of Benin",
	"png": "BJ",
	"teleCode": "229",
	"moneyCode": "XOF",
	"moneySign": "Fr",
	"moneyUnit": "法郎"
}
```

#### [countries_flags](countries_flags "国旗图片文件夹") 国旗图片文件夹
以国家英文2位简称为图片名的国旗图片，包含全部主流国家，缺少几个小众国家的国旗图片。
图片绝大部分宽640px
