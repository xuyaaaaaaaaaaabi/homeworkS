# homeworkS

* 1.0v版本上传时忽略了git作业要求的要至少10次commit，所以在提交的时候就几乎已经写好了，后续会尽量多次提交，保证作业质量

* 1.1v版本将原本的控制台输出改成了按照文件位置输出

* 1.2v版本分离了统计字符数以及是否为单词的方法

* 1.3v版本将一些基本功能挪出，比如输入的位置信息，字符串中空白字符转换，回车符的判定，逐行读入数据时候的数据处理以及核心代码计算单词数量

* 1.4v版本修复了之前遗漏的排序bug，并且将map排序，print输出移出
  * bug来源于countF类当中的inLineFirst方法，平移函数的时候吧循环里面的s1[i]写成了s1[0]，导致后续函数的结果写死，产生bug
* 1.5v版本将文件读入写出分离

