# TextGrapher
Text Content Grapher based on keyinfo extraction by NLP method。输入一篇文档，将文档进行关键信息提取，进行结构化，并最终组织成图谱组织形式，形成对文章语义信息的图谱化展示。
# 项目介绍
如何用图谱和结构化的方式，即以简洁的方式对输入的文本内容进行最佳的语义表示是个难题。　本项目将对这一问题进行尝试，采用的方法为：输入一篇文档，将文档进行关键信息提取，并进行结构化，并最终组织成图谱组织形式，形成对文章语义信息的图谱化展示。　　
# 使用方式
    from text_grapher import *
    content = '你要分析的文本'
    handler = CrimeMining()
    handler.main(content)
结果保存在graph.html文件当中。　　

# 事件举例
１) 中兴事件　
![image](https://github.com/liuhuanyong/TextGrapher/blob/master/image/%E4%B8%AD%E5%85%B4%E4%BA%8B%E4%BB%B6.png)

2) 魏则西事件　
![image](https://github.com/liuhuanyong/TextGrapher/blob/master/image/%E9%AD%8F%E5%88%99%E8%A5%BF%E4%BA%8B%E4%BB%B6.png)

3) 雷洋事件　
![image](https://github.com/liuhuanyong/TextGrapher/blob/master/image/%E9%9B%B7%E6%B4%8B%E5%AB%96%E5%A8%BC%E4%BA%8B%E4%BB%B6.png)

4) 同学杀人事件　
![image](https://github.com/liuhuanyong/TextGrapher/blob/master/image/%E5%90%8C%E5%AD%A6%E6%9D%80%E4%BA%BA%E4%BA%8B%E4%BB%B6.png)

# 总结
１）如何用图谱和结构化的方式，即以简洁的方式对输入的文本内容进行最佳的语义表示是个难题。  
２）本项目采用了高频词，关键词，命名实体识别，主谓宾短语识别等抽取方式，并尝试将三类信息进行图谱组织表示，这种表示方式是一种尝试。  
３）命名实体识别以及关键信息抽取受限于NLP的性能，在算法和方式上还存在多处不足。
# Question?
 send mail to lhy_in_blcu@126.com  
 If any question about the project or me ,see https://liuhuanyong.github.io/
