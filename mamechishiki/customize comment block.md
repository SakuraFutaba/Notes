1. input `Ctrl+Shift+P` and enter `snippets`
2. choose `Snippets: Configure User Snippets`
3. select the language to customize

There are some examples. I haven't tried them.

```json
{
  "Print to jsNoteTitle": {
    "prefix": "jsNoteTitle",
    "body": [
      "/*",
      " *@description:",
      " *@author: 123",
      " *@date: ${CURRENT_YEAR}-${CURRENT_MONTH}-${CURRENT_DATE} ${CURRENT_HOUR}:${CURRENT_MINUTE}:${CURRENT_SECOND}",
      " *@version: V1.0.5",
      "*/"
    ],
    "description": ""
  },
  "Print to jsfn": {
    "prefix": "jsfn",
    "body": [
      "/*",
      " *@functionName: ${TM_CURRENT_LINE}",
      " *@params1: ${1:参数1}",
      " *@params2: ${2:参数2}",
      " *@params3: ${3:参数3}",
      " *@params4: ${4:参数4}",
      " *@description:",
      " *@author: 123",
      " *@date: ${CURRENT_YEAR}-${CURRENT_MONTH}-${CURRENT_DATE} ${CURRENT_HOUR}:${CURRENT_MINUTE}:${CURRENT_SECOND}",
      " *@version: V1.0.5",
      "*/"
    ],
    "description": ""
  },
  "Print to jsModify": {
    "prefix": "jsModify",
    "body": [
      "/*",
      " *@description:",
      " *@modifyContent:",
      " *@author: 123",
      " *@date: ${CURRENT_YEAR}-${CURRENT_MONTH}-${CURRENT_DATE} ${CURRENT_HOUR}:${CURRENT_MINUTE}:${CURRENT_SECOND}",
      "*/"
    ],
    "description": ""
  },
  "Print to jsVariable": {
    "prefix": "jsVariable",
    "body": [
      "/*",
      " *@description:",
      " *@author: 123",
      " *@date: ${CURRENT_YEAR}-${CURRENT_MONTH}-${CURRENT_DATE} ${CURRENT_HOUR}:${CURRENT_MINUTE}:${CURRENT_SECOND}",
      " *@variable1: ${1:变量1}",
      " *@variable2: ${2:变量2}",
      " *@variable3: ${3:变量3}",
      " *@variable4: ${4:变量4}",
      " *@variable5: ${5:变量5}",
      "*/"
    ],
    "description": ""
  }
}

```

```html
"Print to html method": {
    "prefix": "csj",
    "body": [
        "<!-- ",
            "**@description",
			"-->"
    ],
}
```

```php
{
    "Print to functionComments": {
        "prefix": "/**",
        "body": [
            "/**",
            " * @name: ${1:函数名}",
            " * @desc: ${2:描述}",
            " * @author: 123",
            " * @date: $CURRENT_YEAR$CURRENT_MONTH$CURRENT_DATE",
            " * @param:	data	type	description",
            " * @return:	data	type	description",
            ""
        ],
        "description": "函数注释"
    }
}
```
