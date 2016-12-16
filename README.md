# 字符串
str组件用于处理和字符相关的功能

[TOC]

####创建实例对象
```
$obj = new \houdunwang\str\Str();
```

####汉字转拼音
```
echo $obj->pinyin('后盾');
```

####PHP代码压缩/去空白注释
```
$obj->stripWhitespace(file_get_contents('hdphp/hdphp.php'));
```

####全角转半角
```
echo $obj->toSemiangle('，“');
```

####去除标点符号
```
echo $obj->removePunctuation('北京后盾网，免费开源框架。');
```

####utf8转gbk
```
$obj->utf8ToGbk("后盾网人人做后盾");
```

####gbk转utf8
```
$obj->gbkToUtf8("后盾网人人做后盾");
```
