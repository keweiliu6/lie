# lie
一个大家都在说谎的聊天室

我想写一个软件，可以即时的替换用户输入中的某些关键字，以达到说谎的目的。

现在想到的关键字类型：
1、地点    北京 <==> 上海
2、真假    地球是圆的 <==> 地球不是圆的
3、判断    我认为地球是圆的 <==> 我不认为地球是圆的
4、时间    早上9点 <==> 晚上6点

技术难点
1、分词，区分词素，可以准确的找出要替换掉的词或词组
2、即时性，如果每个标准都要匹配一次，会产生大量匹配，从而降低运行效率，如果不能即时聊天，聊天室就失去意义了。

