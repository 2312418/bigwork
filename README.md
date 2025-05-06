CurriculumHelper

这是一个金融知识的点读笔记本，可实现“哪里不会点哪里”。我作为金融专业的学生，记的笔记中有时候存在不会的专业名词或者有疑问的地方，就可以选中，然后本程序就可以帮忙进行补充和解答，补充在笔记的下方。这样就可以实现下次看笔记的时候不需要再次查找，且这次补充笔记也不需要自己誊写。

（运行时，请先运行qt程序(CurriculumHelper.Qt)，再运行python程序(gpt.py)，这样python作为tcp客户端才能连接到服务器端，然后就可以正常使用）

本项目受copilot启发，当我用latex记笔记时，copilot经常可以帮我写出想要的latex代码，提高了记笔记的效率。

他可以实现类似CoPilot的功能，当你记了一些笔记，但是有些不太了解、存在疑问、需要补充的内容，可以选中你想补充的部分，然后按下工具栏中的ChatGPT图标，随后智谱的ChatGLM就会被自动调用，把你选中的内容发送给大模型，并且将生成的回答补充在光标位置之后。这样可以省去自己去搜索、誊抄或者以后再次搜索的时间。

比如，你是一个经济系学生，正在记笔记，当你写到“供需曲线的定义”后，懒得抄书了，就可以选中这几个字，并且按下ChatGPT的图标。

<img width="912" alt="1" src="https://github.com/ironmt/CurriculumHelper-NKU24SpringCpp/assets/28005559/7cb410a7-8991-4a72-906b-e89d4be4597d">

然后等待一会，关于“供需曲线的定义”便会出现在笔记本上

<img width="912" alt="2" src="https://github.com/ironmt/CurriculumHelper-NKU24SpringCpp/assets/28005559/8784e5b8-c3bd-478d-81a3-66e620618651">
