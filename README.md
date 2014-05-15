TinyForm `V1.2.2`
========================
------------------------------------
### TinyForm简介
> TinyForm是一个JavaScript表单自动验证插件，不依赖其它任何第三方插件。    
—— [TinyRise官网](http://www.tinyrise.com)

#### 引入js与css文件
``` html
<script type="text/javascript" src="form.js"></script>
<link rel="stylesheet" href="style.css">
```
### 如何使用：
- input 标签必需是在Form表单中
- input 的标签 type 必需是 text,select textarea password 中的一种

### Form标签属性介绍：
- **needsValidate** : 表单是否进行验证，false不进行验证,否则进行验证。
- **callback** : 表单验证后的回调函数,callback(e),如果验证未能通过，则e为当前元素,通过则e为空。

### Input标签属性介绍：
- **empty** :说明此input输入允许为空
- **minlen** :说明此input允许输入最小长度 如:minlen=5
- **maxlen** :说明此input允许输入最大长度 如:minlen=32
- **min** :说明此input允许输入最大值 如:min=6
- **max** :说明此input允许输入最小值 如:max=20
- **disabled** :说明此input不进行验证
- **alt** :要提示的信息
- **pattern** :说明此input输入需要满足的规则:

> - required : 不能为空。
> - email : 邮箱地址验证。
> - ip : IP地址验证。
> - id : 身份证验证。
> - zip : 邮编验证。
> - phone : 电话验证。
> - mobi : 手机号码验证。
> - date : 日期格式验证(如:2014-05-10)。
> - datetime : 日期时间验证(如:2014-05-10 12:00:00)。
> - int : 数字验证。
> - float : 浮点数验证。
> - 正则表达式 : 自定义验证规则。

### 对外开放的函数
> - autoValidate.init 初始化对表单进行扫描绑定函数
> - autoValidate.validate(event) 初始化对表单进行扫描绑定函数
> - autoValidate.showMsg({error:error,id:textfield,msg:alt,empty:empty}) 显示验证信息


[pic]: (https://tfsimg.alipay.com/images/mobilecodec/T19QJdXjlXXXXXXXXX)

### 反馈与建议

- [论坛>>进入](http://www.tinyrise.com)

- 邮箱：<tinyrise@tinyrise.com>

---------
感谢阅读这份帮助文档，[访问官网](http://www.tinyrise.com)了解更多。
