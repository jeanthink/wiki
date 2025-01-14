Plantuml
===
#FOSS 

Related:
- [[mermaidjs]] 类似工具
- [[bpmn]]

## 项目相关

1. 在 [Does a grammar exist for the language? - PlantUML Q&A](https://forum.plantuml.net/157/does-a-grammar-exist-for-the-language) 里的回答中，说明了 PlantUML 不存在 BNF 定义，一切通过正则表达式完成
2. 早期主要的图表，都可以在 @startuml 和 @enduml 之间完成，没有像 mermaidjs 那样使用不同的起始标识符。但实际上你并没法在一个文件里混合不同的图表类型，猜测是将最早检测到的隐式图表标识设置为图表类型，之后再识别别的特有关键字，直接会报错。

## 一些工具

- [Real World PlantUML](https://real-world-plantuml.com/)

## 一些观点

> 表达需求，设计的方法太多了，强迫用 UML 形成一套标准，哲学上叫形而上学。可以说 UML 基本是上世纪瀑布模型下的产物，强调项目前期过渡的设计。现在互联网项目，需求改变太快了，按部就班根本就行不通。
> <cite>https://v2ex.com/t/590767#r_7743243</cite>

画架构/流程示意图的需求一直都在，但是不会只限于 UML 这套体系。一般的功能设计示意也许使用简单的流程图、时序图、ER 图就够了。更大的系统架构设计、更丰富剖面的展示等，还没有合适的通用正式定义，这时候更加自由的 draw.io 等工具也许更适合。

[深入分析JavaScript模块循环引用 - 文章 - ByteTech](https://tech.bytedance.net/articles/6989515049500934152)

[//begin]: # "Autogenerated link references for markdown compatibility"
[mermaidjs]: ../products/mermaidjs "Mermaid.js"
[bpmn]: bpmn "Business Process Model And Notation"
[//end]: # "Autogenerated link references"