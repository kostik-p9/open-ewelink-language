# open-ewelink-language
We created this project to support translation for eWelink

---
# IOS翻译注意事项

## 翻译文件：
	country-all.js : 国家码名称翻译
	locale-da.json : 丹麦翻译
	locale-en.json : 英文翻译
	locale-it.json : 意大利翻译
	locale-pl.json : 葡萄牙翻译
	locale-ru.json : 俄语翻译
	locale-zh.json : 简体中文翻译
	locale-zh_HK.json : 繁体中文（香港）翻译
	locale-zh_TW.json : 繁体中文 （台湾）翻译

## 翻译规则：
	国家码翻译：对国家名称的国际化，使用JSON格式来描述一个国家，如果需要新增国家，请新增一个JSON格式
	属性格式为：国家名称缩写+"_name"+":"+"具体国际化国家名称"，
	例如 :
	        {
            	zh_name: '中国',
            	en_name: 'China',
            	ru_name: 'Китай',
            	da_name: 'China',
            	prefix: '+86'
        	}

    其他部分翻译：对具体app文字的，
    属性格式为："App标识符（仅用于app本身唯一性描述与使用，本身无意义"+":"+“具体国际化翻译”；
    例如：
	    locale-zh.json :
		    {
	  			"ABOUTE_WELINK": "关于易微联",
		    }
		locale-en.json :
			{
				 "ABOUTE_WELINK": "About eWeLink",
			}
		local-zh_HT.js :
			{
				  "ABOUTE_WELINK": "關於易微联",
			}	

*注意：仅需对 ”具体国际化国家名称“与”具体国际化翻译“翻译，即 ":" 后面的内容翻译即可；*

---

---
# IOS Translation Notes

## Translation File:
  country-all.js :  country code translation
  locale-da.json :  Danish translation
  locale-en.json :  English translation
  locale-it.json :  Italian translation
  locale-pl.json :  Portuguese translation
  locale-ru.json :  Russian translation
  locale-zh.json :  Simplified Chinese translation
  locale-zh_HK.json : Traditional Chinese (HK) translation
  locale-zh_TW.json : Traditional Chinese (Taiwan) translation


## Translation rules：

	Country code translation: the name of a country or location should be described in JSON format. To add a new country or location, please add a country name in JSON format first.
	The attribute format should be: country name abbreviation + "_ name" + ":" + "specific internationalized country name"

	For example:
	          {
	              zh_name: '中国',
	              en_name: 'China',
	              ru_name: 'Китай',
	              da_name: 'China',
	              prefix: '+86'
	          }

	Other translation: for all other description and prompt words,
	The attribute format should be: "App identifier (only for the app itself to distinguish among different descriptions, it does not have any meaning)" + ":" + "specific international translation";
	For example:
	      locale-zh.json :
	        {
	          "ABOUTE_WELINK": "关于易微联",
	        }
	    locale-en.json :
	      {
	         "ABOUTE_WELINK": "About eWeLink",
	      }
	    local-zh_HT.js :
	      {
	          "ABOUTE_WELINK": "關於易微联",
	      }  

	* Note: it only needs to translate "specific internationalized country name" and "specific internationalized translation", which is the content behind the ":" *
---
android 翻译注意事项:
