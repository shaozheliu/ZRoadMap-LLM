## （一）神奇咒语可以激发LLM的能力
### 1.利用RL的方法找到适合的prompt


## （二）In context learning 
### 1. 大语言模型真的读懂prompt的范例了么？
参考论文：[Larger language models do in-context learning differently](https://arxiv.org/abs/2303.03846)
方法：不断的给模型喂错误的范例，观察模型是否真的输出错误。利用的是InstructGPT。
结论：
- 随着给的范例中错误比例提高，模型输出错误的比例也会提高。
- 模型的参数量越大，受错误范例影响的比例越大。



## （三）CoT复杂任务拆解