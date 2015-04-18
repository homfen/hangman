#Hangman
Hangman game javascript version

##游戏介绍：

Hangman直译为“上吊的人”，是一个猜单词的双人游戏。由一个玩家想出一个单词或短语，另一个玩家猜该单词或短语中的每一个字母。第一个人抽走单词或短语，只留下相应数量的空白与下划线。

##算法介绍：

1.根据要猜的词的长度，从字典中取出所有符合长度的单词

2.统计取出的单词中字幕的出现频率并排序

3.按字幕频率猜测，如果没猜中则用下一个字母猜测；如果猜中，则从1中的单词中选出单词中筛选出猜中位置为猜中单词的单词，重复2、3

4.如果所有字母都猜中或达到单个单词错误上限，则猜下一个单词

5.如果所有的单词都猜完，游戏结束
