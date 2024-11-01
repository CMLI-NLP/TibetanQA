# TibetanQA
## What is TibetanQA?
Tibetan Machine Reading Comprehension Dataset (TibetanQA) is a Tibetan reading comprehension datset, which contains 20,000 question answer pairs and 1,513 articles.

## TibetanQA
__Multi-domain resources:__ The articles are from the Tibetan Encyclopedia website and cover 12 topics, including nature, culture, education and so on.

__High quality:__ A complete and strict workflow is adopted to passage collection, question construction and answer verification to ensure the high quality of the data.

We invited the native Tibetan students to construct data sets using a program dedicated to collect question and answer pairs. We trained them first. Only the students whose accuracy rate reaches more than 90% participated in the construction of data sets. We encouraged them to construct various forms of questions. In addition, we invited another group to verify the answers.We discarded incomplete and grammatically incorrect question and answer pairs, and finally verified 20000 question and answer pairs. We divided the problem into four categories: word matching, synonym replacement, multi sentence reasoning and fuzzy problem. These four kinds of problems require the reasoning ability of the machine to be improved in turn.
## Data Detail

![type_ques](https://github.com/user-attachments/assets/dda61f27-92d0-438b-8e25-c61a1aaa0b80)![type_answer](https://github.com/user-attachments/assets/fc6e52d4-eef3-4b41-b9da-b6a6affe9cf8)

## Name of the published paper
<large>**面向机器阅读理解的高质量藏语数据集构建(Construction of High-quality Tibetan Dataset for Machine Reading Comprehension)** </large> \
<large> **link:** https://aclanthology.org/2021.ccl-1.20/ \
**cite:** Yuan Sun, Sisi Liu, Chaofan Chen, Zhengcuo Dan, and Xiaobing Zhao. 2021. 面向机器阅读理解的高质量藏语数据集构建(Construction of High-quality Tibetan Dataset for Machine Reading Comprehension). In Proceedings of the 20th Chinese National Conference on Computational Linguistics, pages 208–218, Huhhot, China. Chinese Information Processing Society of China. </large>

## Data Demo
### The Question Answering Dataset

རྒྱལ་ཡོངས་སུ་མིང་གྲགས་ཆེ་བའི་བྱིས་སྒྲུང་རྩོམ་པ་པོ་ཡེ་ཤེས་སྒྲོལ་མ་ལགས་ནི་སྤྱི་ལོ1925ལོར་མདོ་སྨད་ཀན་སུའུ་ཞིང་ཆེན་ཀན་ལྷོའི་ཅོ་ནེ་རྫོང་མཁར་ཆེན་ཤང་གི་ནུབ་གཟིག་སྡེ་བ་ནས་སྐྱེས་ཤིང་།ཆུང་དུས་ནས་བཟུང་།མོ་ལ་རིག་པ་ལྷན་སྐྱེས་སུ་མངའ་བ་དང་། ཆུང་དུས་སུ་སློབ་གྲྭ་འགྲིམས་ཏེ་སློབ་གྲྭ་ཆེན་མོ་ནས་སློབ་མཐར་ཕྱིན་རྗེས།རྒྱལ་ཁབ་ཕྱི་ནང་གི་རྩོམ་རིག་རིག་གཞུང་ལ་སྦྱངས་པ་གང་ལེགས་གནང་སྟེ།ཞོར་དུ་བརྩམས་ཆོས་སྣ་མང་སྤེལ་བའི་འགོ་བརྩམས་ཤིང་། མཐར་འདིའི་ཕྱོགས་ཀྱི་གྲུབ་འབྲས་གཡུར་དུ་ཟ་བ་ཐོབ་པ་དང་། སྤྱི་ལོ1983ལོར།ཀྲུང་གོའི་རྩོམ་པ་པོའི་མཐུན་ཚོགས་སུ་ཞུགས་པ་མ་ཟད།ཆེད་ལས་རྩོམ་པ་པོའི་འགན་གཅིག་ལྕོགས་སུ་བཞེས།

Q:ཡེ་ཤེས་སྒྲོལ་མ་ལགས་ནི་བྱ་བ་གང་སྒྲུབ་མཁན་ཞིག་ཡིན།

A:རྒྱལ་ཡོངས་སུ་མིང་གྲགས་ཆེ་བའི་བྱིས་སྒྲུང་རྩོམ་པ་པོ་ཡེ་ཤེས་སྒྲོལ་མ་ལགས་

Q:ཡེ་ཤེས་སྒྲོལ་མ་ཀྲུང་གོའི་རྩོམ་པ་པོའི་མཐུན་ཚོགས་སུ་ཞུགས་དུས་སྤྱི་ལོ་ག་ཚོད་ཡིན།

A:སྤྱི་ལོ1983ལོར།ཀྲུང་གོའི་རྩོམ་པ་པོའི་མཐུན་ཚོགས་སུ་ཞུགས་པ་མ་ཟད།གུང་བླ་གྲོང་ཚོར་ཚོ་ཆུང2ཡོད་ལ།སྤྱི་ལོ2015ལོར་གྲོང་ཚོ་ཡོངས་ལ་དུད་ཚང80དང་མི334ཡོད།སའི་རྒྱ་ཁྱོན་ལ་མུའུ་ཁྲི8.42དང་།རྨོ་ཞིང་གི་རྒྱ་ཁྱོན་ལ་མུའུ་ཁྲི0.09རྨོ་སྐྱུར་ནགས་གསོའི་རྒྱ་ཁྱོན་ལ་མུའུ337.6རྩྭ་སའི་རྒྱ་ཁྱོན་ལ་མུའུ་ཁྲི2.18བཅས་ཡོད།སྤྱི་ལོ2015ལོའི་གྲོང་གསེབ་ཀྱི་དཔལ་འབྱོར་སྤྱིའི་ཡོང་འབབ་སྒོར་ཁྲི323ཡིན་ཞིང་།གྲོང་བ་མི་རེའི་ཆ་སྙོམས་ཡོང་འབབ་སྒོར9682ཡིན།

Q:སྤྱི་ལོ2015ལོར་གུང་བླ་གྲོང་ཚོ་ཡོངས་ལ་དུད་ཚང་ག་ཚོད་དང་མི་ག་ཚོད་ཡོད།

A:སྤྱི་ལོ2015ལོར་གྲོང་ཚོ་ཡོངས་ལ་དུད་ཚང80དང་མི334ཡོད།

Q:གུང་བླ་གྲོང་ཚོའི་སའི་རྒྱ་ཁྱོན་ལ་མུའུ་ཁྲི་ག་ཚོད་ཡོད།

A:སའི་རྒྱ་ཁྱོན་ལ་མུའུ་ཁྲི8.42

Q:གུང་བླ་གྲོང་ཚོའི་རྨོ་ཞིང་གི་རྒྱ་ཁྱོན་ལ་མུའུ་ཁྲི་ག་ཚོད་ཡོད།

A:རྨོ་ཞིང་གི་རྒྱ་ཁྱོན་ལ་མུའུ་ཁྲི0.09

Q:གུང་བླ་གྲོང་ཚོའི་རྩྭ་སའི་རྒྱ་ཁྱོན་ལ་མུའུ་ཁྲི་ག་ཚོད་ཡོད།

A:རྩྭ་སའི་རྒྱ་ཁྱོན་ལ་མུའུ་ཁྲི2.18

Q:གུང་བླ་གྲོང་ཚོར་སྤྱི་ལོ2015ལོའི་གྲོང་གསེབ་ཀྱི་དཔལ་འབྱོར་སྤྱིའི་ཡོང་འབབ་སྒོར་ཁྲི་ག་ཚོད་ཡིན།

A:སྤྱི་ལོ2015ལོའི་གྲོང་གསེབ་ཀྱི་དཔལ་འབྱོར་སྤྱིའི་ཡོང་འབབ་སྒོར་ཁྲི323ཡིན་མི་རྣམས་ཀྱིས་ཐོག་ཁང་སྟེང་དུ་བྱེ་མ་སྐྱེལ་བའི་ཁྲོད་དུ།བྱེ་མར་རྩོལ་བ་བཏོན་པའི་མཇུག་འབྲས་ནི་བྱེ་མའི་ལྗིད་ཤུགས་སྟོབས་ནུས་ཇེ་ཆེར་བཏང་བ་ཡིན།ང་ཚོར་དེ་མཁོ་བ་ཡིན་ཞིང་།དེ་འདྲའི་རྩོལ་བ་ལ་གོ་ཆོད་རྩོལ་བ་ཟེར།ཡིན་ནའང་དམིགས་ཡུལ་དེ་འགྲུབ་པའི་ཆེད་དུ།བྱེ་མ་སྐྱེལ་བའི་གོ་རིམ་ཁྲོད་ད་དུང་ཚད་ཕྱིའི་རྩོལ་བ་འགའ་མི་འདོན་ཐབས་མེད་རེད།བྱ་བ་སྒྲུབ་སྐབས།ཚད་ཕྱིའི་ཁུར་བོ་ལ་མི་འདོན་ཐབས་མེད་ཡིན་པའི་རྩོལ་བ་ལ་ཚད་ཕྱིའི་རྩོལ་བ་ཟེར།གོ་ཆོད་རྩོལ་བ་དང་ཚད་ཕྱིའི་རྩོལ་བའི་སྡོམ་ལ་སྤྱིའི་རྩོལ་བ་ཟེར།

Q:མི་རྣམས་ཀྱིས་ཐོག་ཁང་སྟེང་དུ་བྱེ་མ་སྐྱེལ་བའི་ཁྲོད་དུ།བྱེ་མར་རྩོལ་བ་བཏོན་པའི་མཇུག་འབྲས་ནི་ཅི་ཞིག་ཡིན།

A:མི་རྣམས་ཀྱིས་ཐོག་ཁང་སྟེང་དུ་བྱེ་མ་སྐྱེལ་བའི་ཁྲོད་དུ།བྱེ་མར་རྩོལ་བ་བཏོན་པའི་མཇུག་འབྲས་ནི་བྱེ་མའི་ལྗིད་ཤུགས་སྟོབས་ནུས་ཇེ་ཆེར་བཏང་བ་ཡིན།

Q:གང་འདྲ་ཞིག་ལ་གོ་ཆོད་རྩོལ་བ་ཞེས་ཟེར།

A:མི་རྣམས་ཀྱིས་ཐོག་ཁང་སྟེང་དུ་བྱེ་མ་སྐྱེལ་བའི་ཁྲོད་དུ།བྱེ་མར་རྩོལ་བ་བཏོན་པའི་མཇུག་འབྲས་ནི་བྱེ་མའི་ལྗིད་ཤུགས་སྟོབས་ནུས་ཇེ་ཆེར་བཏང་བ་ཡིན།ང་ཚོར་དེ་མཁོ་བ་ཡིན་ཞིང་།དེ་འདྲའི་རྩོལ་བ་ལ་གོ་ཆོད་རྩོལ་བ་ཟེར།

Q:མི་རྣམས་ཀྱིས་ཐོག་ཁང་སྟེང་དུ་བྱེ་མ་སྐྱེལ་བའི་ཁྲོད་དུ།ད་དུང་རྩོལ་བ་གང་འདོན་དགོས།

A:ཡིན་ནའང་དམིགས་ཡུལ་དེ་འགྲུབ་པའི་ཆེད་དུ།བྱེ་མ་སྐྱེལ་བའི་གོ་རིམ་ཁྲོད་ད་དུང་ཚད་ཕྱིའི་རྩོལ་བ་འགའ་མི་འདོན་ཐབས་མེད་རེད།

Q:ཅི་འདྲ་ཞིག་ལ་ཚད་ཕྱིའི་རྩོལ་བ་ཞེས་ཟེར།

A:བྱ་བ་སྒྲུབ་སྐབས།ཚད་ཕྱིའི་ཁུར་བོ་ལ་མི་འདོན་ཐབས་མེད་ཡིན་པའི་རྩོལ་བ་ལ་ཚད་ཕྱིའི་རྩོལ་བ་ཟེར།གློག་ལྡན་པའི་མ་རྡུལ་ལམ་མ་རྡུལ་ཆུན་པོ་ལ་གྱེས་རྡུལ་ཟེར།མ་རྡུལ་ལས་གློག་རྡུལ་ཤོར་ཏེ་ཕོ་གློག་ཁུར་ལྡན་པས།ཕོ་གྱེས་རྡུལ་ཆགས།ཕོ་གྱེས་རྡུལ་ལ་ལྡན་པའི་ཕོ་གློག་ཁུར་གྲངས་ནི་མ་རྡུལ་དེ་ལས་ཤོར་བའི་གློག་རྡུལ་གྲངས་དང་མཚུངས།དེ་ནི་གཞི་རྒྱུ་དེའི་ཕོ་འདྲེས་འགྱུར་བྲིན་ཡིན།མ་རྡུལ་ལ་གློག་རྡུལ་ཐོབ་པ་དང་མོ་གློག་ཁུར་ལྡན་པས།མོ་གྱེས་རྡུལ་ཆགས།མོ་གྱེས་རྡུལ་ལ་ལྡན་པའི་མོ་གློག་ཁུར་གྲངས་ནི་མ་རྡུལ་དེར་ཐོབ་པའི་གློག་རྡུལ་གྲངས་དང་མཚུངས།

Q:གང་འདྲ་ཞིག་ལ་གྱེས་རྡུལ་ཟེར།

A:གློག་ལྡན་པའི་མ་རྡུལ་ལམ་མ་རྡུལ་ཆུན་པོ་ལ་གྱེས་རྡུལ་ཟེར།

Q:ཕོ་གྱེས་རྡུལ་ཆགས་ཚུལ་ནི་གང་འདྲ་ཡིན།

A:མ་རྡུལ་ལས་གློག་རྡུལ་ཤོར་ཏེ་ཕོ་གློག་ཁུར་ལྡན་པས།ཕོ་གྱེས་རྡུལ་ཆགས།

Q:ཕོ་གྱེས་རྡུལ་ལ་ལྡན་པའི་ཕོ་གློག་ཁུར་གྲངས་ནི་ག་ཚོད་ཡིན།

A:ཕོ་གྱེས་རྡུལ་ལ་ལྡན་པའི་ཕོ་གློག་ཁུར་གྲངས་ནི་མ་རྡུལ་དེ་ལས་ཤོར་བའི་གློག་རྡུལ་གྲངས་དང་མཚུངས།

Q:མ་རྡུལ་སྟེང་གི་གློག་རྡུལ་ཐོབ་ཤོར་གྱི་རྣམ་པ་ནི་གང་འདྲ་ཡིན།

A:མ་རྡུལ་ལ་གློག་རྡུལ་ཐོབ་པགླིང་སྣེའི་འོད་ཟེར་ནི་རང་བྱུང་ཁམས་ཆེན་པོའི་གནམ་དཔྱད་ལྗོངས་རྣམ་ཁྱད་པར་བའི་རིགས་ཤིག་ཡིན་ལ།དེ་ལ་གཏན་འཇགས་ཀྱི་གྲུབ་ཚུལ་མེད་པ་དང་།ཁ་དོག་ཡང་མི་འདྲ་བ་སྣ་ཚོགས་ཡོད་དེ།ལྗང་གུ་དང་དཀར་པོ།སེར་པོ།སྔོན་པོ་བཅས་ཡིན་ཞིང་།དེའི་ནང་ནས་མང་ཆེ་བ་ནི་མདོག་སྔོན་པོ་ཡིན་པ་དང་།སྐབས་ལ་ལར་མིག་དབང་འཕྲོག་པར་བྱེད་པའི་དམར་སྨུག་གི་མདོག་ཀྱང་ཡོད།ཡང་གླིང་སྣེའི་འོད་ཟེར་ནི་གྲང་ངར་ཤིན་ཏུ་ཆེ་བའི་སྟོན་ཁ་དང་དགུན་དུས་ཀྱི་མཚན་མོ་ཁོ་ནར་འབྱུང་བ་ཞིག་ཡིན་ལ།འཕྲེད་ཐིག་མཐོན་པོའི་ས་ཁུལ་དུ་མ་གཏོགས་ལྗོངས་རྣམ་ཁྱད་པར་བ་དེ་མཐོང་བའི་གོ་སྐབས་དབེན།དེ་ཡང་གྲང་ངར་ཆེ་བའི་སྨག་ནག་གི་མཚན་མོའི་དུས་སུ་བྱང་སྣེའི་འོད་ཟེར་འབྱུང་བ་མང་བའི་རྐྱེན་གྱིས།དེ་ལ་བལྟ་བའི་དུས་ཚོད་ཆེས་བཟང་ཤོས་ནི་ལོ་རེའི་ཟླ11པ་ནས་ཕྱི་ལོའི་ཟླ2པའི་བར་གྱི་དགུང་མོའི་ཆུ་ཚོད10བ་ནས་ནམ་གུང་གི་ཆུ་ཚོད2པའི་བར་ཡིན་ལ།སྐབས་ལ་ལར་མཛེས་སྡུག་ལྡན་པའི་ལྗོངས་རྣམ་དེའི་རྒྱུན་ནི་ཆུ་ཚོད1རིང་ལ་བསྲིང་ཐུབ་པ་ཡིན་ཞིང་།དེ་ནི་དབྱིབས་དང་གྲུབ་ཚུལ་རྣམ་པ་སྣ་ཚོགས་ཡོད་པར་མ་ཟད།ཤིན་ཏུ་ནས་གསང་བ་ལྐོག་གྱུར་ཞིག་ཀྱང་ཡིན།

Q:གླིང་སྣེའི་འོད་ཟེར་ནི་ཅི་ཞིག་ཡིན།

A:གླིང་སྣེའི་འོད་ཟེར་ནི་རང་བྱུང་ཁམས་ཆེན་པོའི་གནམ་དཔྱད་ལྗོངས་རྣམ་ཁྱད་པར་བའི་རིགས་ཤིག་ཡིན་ལ།

Q:གླིང་སྣེའི་འོད་ཟེར་ལ་གཏན་འཇགས་ཀྱི་གྲུབ་ཚུལ་མེད་པ་དང་།ཁ་དོག་ཡང་མི་འདྲ་བ་སྣ་ཚོགས་ཡོད་དེ་དེ་དག་རེ་རེ་ནི་ཅི་ཞིག་ཡིན།

A:དེ་ལ་གཏན་འཇགས་ཀྱི་གྲུབ་ཚུལ་མེད་པ་དང་།ཁ་དོག་ཡང་མི་འདྲ་བ་སྣ་ཚོགས་ཡོད་དེ།ལྗང་གུ་དང་དཀར་པོ།སེར་པོ།སྔོན་པོ་བཅས་ཡིན་ཞིང་།

Q:གླིང་སྣེའི་འོད་ཟེར་ནི་དུས་ནམ་ཞིག་ལ་བྱུང་བ་ཡིན།

A:ཡང་གླིང་སྣེའི་འོད་ཟེར་ནི་གྲང་ངར་ཤིན་ཏུ་ཆེ་བའི་སྟོན་ཁ་དང་དགུན་དུས་ཀྱི་མཚན་མོ་ཁོ་ནར་འབྱུང་བ་ཞིག་ཡིན་ལ།འཕྲེད་ཐིག་མཐོན་པོའི་ས་ཁུལ་དུ་མ་གཏོགས་ལྗོངས་རྣམ་ཁྱད་པར་བ་དེ་མཐོང་བའི་གོ་སྐབས་དབེན།

Q:གླིང་སྣེའི་འོད་ཟེར་ནི་གྲང་ངར་ཤིན་ཏུ་ཆེ་བའི་སྟོན་ཁ་དང་དགུན་དུས་ཀྱི་མཚན་མོ་ཁོ་ནར་འབྱུང་བའི་རྒྱུ་མཚན་ནི་ཅི་ཞིག་ཡིན།

A:དེ་ཡང་གྲང་ངར་ཆེ་བའི་སྨག་ནག་གི་མཚན་མོའི་དུས་སུ་བྱང་སྣེའི་འོད་ཟེར་འབྱུང་བ་མང་བའི་རྐྱེན་གྱིས།འདིའི་གནས་རི་ནི་རྨ་བྱང་ཡུལ་ཚོ་སྲིད་གཞུང་གི་ལྷོ་ནུབ་་ཕྱོགས་སུ་སྤྱི་ལེ20ཙམ་གྱི་མཚམས་ན་ཡོད་པའི་རྨ་ལྕམ་ལྷ་མོ་ཞེས་པའི་རྫ་རི་དེ་ཡིན་ཞིང་།མཐོ་ཚད་ལ་མཚོ་ངོས་ལས་སྨི3000ཡས་མས་ཡོད།སའི་གོ་ལའི་བྱང་གི་འཕྲེད་ཚད34°43′གྱི་མཚམས་དང་། ཤར་གྱི་གཞུང་ཚད100°47′གྱི་མཚམས་ན་ཡོད། 

Q:རྨ་ལྕམ་ལྷ་མོ་ནི་ཡུལ་ཚོ་གང་ཞིག་ན་ཡོད།

A:འདིའི་གནས་རི་ནི་རྨ་བྱང་ཡུལ་ཚོ་སྲིད་གཞུང་

Q:རྨ་ལྕམ་ལྷ་མོ་ནི་རྨ་བྱང་ཡུལ་ཚོ་སྲིད་གཞུང་གི་ཕྱོགས་གང་ཞིག་ན་ཡོད།

A:རྨ་བྱང་ཡུལ་ཚོ་སྲིད་གཞུང་གི་ལྷོ་ནུབ་་ཕྱོགས་

Q:རྨ་ལྕམ་ལྷ་མོ་ནི་རྨ་བྱང་ཡུལ་ཚོའི་སྤྱི་ལེ་ཅི་ཙམ་གྱི་མཚམས་ན་ཡོད།

A:སྤྱི་ལེ20ཙམ་གྱི་མཚམས་ན་ཡོད་པ

Q:རྨ་ལྕམ་ལྷ་མོ་ཡི་མཐོ་ཚད་ལ་མཚོ་ངོས་ལས་སྨི་ཅི་ཙམ་ཡོད།

A:མཐོ་ཚད་ལ་མཚོ་ངོས་ལས་སྨི3000ཡས་མས་ཡོད།དུག་སྦྲང་རྩ་མེད་དུ་གཏང་བ་ནི་ཀླད་གཉན་ཁ་པ་སྔོན་འགོག་གི་གནད་འགག་ཡིན་ལ།ཕག་ནི་ཀླད་གཉན་ཁ་པའི་ནད་དུག་གི་རྟེན་གཞི་དང་འགོ་ཁྱབ་ཀྱི་ཁུངས་ཡིན།ཡང་ཀླད་གཉན་ཁ་པ་དར་ཁྱབ་ཆེ་བའི་དུས་ཚིགས་ལ་མ་བསླེབས་སྔོན་དུ་ཕག་ལ་འགོག་ཁབ་བརྒྱབ་ན་ཀླད་གཉན་ཁ་པའི་ནད་འབྱུང་བའི་གྲངས་ཚད་ཇེ་དམའ་རུ་འགྲོ་བར་ཕན།གཞན་མི་ལ་འགོག་ཁབ་བརྒྱབ་ན་ཀླད་གཉན་ཁ་པའི་ནད་དུག་ཕོག་པའི་འགོག་ཤུགས་མཐོ་རུ་གཏོང་ཐུབ་པ་དང་།ཀླད་གཉན་ཁ་པའི་སྔོན་འགོག་ལ་ཡང་ཕན་ནུས་ཅུང་ལེགས་པོ་ལྡན་ཞིང་།ཀླད་གཉན་ཁ་པར་བཅོས་ཐབས་ཁྱད་པར་བ་ཞིག་ཡོད་པ་མ་ཡིན།དེ་ཡང་སྔ་མོ་ནས་སྨན་ཁང་དུ་ཞག་སྡོད་བྱ་བ་དང་རྒྱ་ཕྱི་ལུགས་ཀྱི་གསོ་བ་རིག་པའི་གཞུང་ལུགས་ཟུང་འབྲེལ་སྒོས་ནད་བཅོས་བྱས་ན།ནད་སོས་པར་ཤིན་ཏུ་ཕན་པ་དང་ནད་བག་འབྱུང་བ་ཡང་ཉུང་ངུར་འགྲོ་བ་ཡིན།

Q:ཀླད་གཉན་ཁ་པ་སྔོན་འགོག་གི་གནད་འགག་ནི་གང་ཡིན།

A:དུག་སྦྲང་རྩ་མེད་དུ་གཏང་བ་ནི་ཀླད་གཉན་ཁ་པ་སྔོན་འགོག་གི་གནད་འགག་ཡིན་

Q:གང་ནི་ཀླད་གཉན་ཁ་པའི་ནད་དུག་གི་རྟེན་གཞི་དང་འགོ་ཁྱབ་ཀྱི་ཁུངས་ཡིན།

A:ཕག་ནི་ཀླད་གཉན་ཁ་པའི་ནད་དུག་གི་རྟེན་གཞི་དང་འགོ་ཁྱབ་ཀྱི་ཁུངས་ཡིན།

Q:གང་འདྲ་བྱས་ན་ཀླད་གཉན་ཁ་པའི་ནད་འབྱུང་བའི་གྲངས་ཚད་ཇེ་དམའ་རུ་འགྲོ་བར་ཕན།

A:ཀླད་གཉན་ཁ་པ་དར་ཁྱབ་ཆེ་བའི་དུས་ཚིགས་ལ་མ་བསླེབས་སྔོན་དུ་ཕག་ལ་འགོག་ཁབ་བརྒྱབ་ན་ཀླད་གཉན་ཁ་པའི་ནད་འབྱུང་བའི་གྲངས་ཚད་ཇེ་དམའ་རུ་འགྲོ་བར་ཕན།དགེ་འདུན་ཆོས་ཀྱི་དབང་ཕྱུག་ནི་ཀིརྟི་སྐུ་ཕྲེང་དྲུག་པ་ཡིན་ཞིང་། མདོ་སྨད་རེབ་གོང་གི་ཆུ་མ་ཞེས་པའི་ས་ཆར་ཀླུ་རྒྱལ་གྱི་ཁྱིམ་ཚང་དུ་ཡབ་ངག་དབང་རབ་བརྟན་དང་ཡུམ་སྙིང་མོ་ཐར་གཉིས་ཀྱི་སྲས་སུ་རབ་བྱུང་བཅུ་གསུམ་པའི་ཆུ་འབྲུག་སྤྱི་ལོ1773ལོར་འཁྲུངས། དགུང་ལོ་ལྔ་ལ་ཕེབས་པ་མེ་སྤྲེལ་ལོར་ངོས་འཛིན་དང་བརྟག་དཔྱད་བཟང་པོ་བྱུང་བར་བརྟེན་ཀིརྟི་སྐུ་ཕྲེང་ལྔ་པའི་ཡང་སྤྲུལ་དུ་ཐག་བཅད་དེ་གདན་སར་བཀོད། མཛོད་དགེ་རི་ཁྲོད་དབང་སོ་མཁས་གྲུབ་བསྟན་འཛིན་དང་ཨང་སྨོན་སྤྲུལ་སྐུ་དགེ་རྒན་དུ་བསྟེན་ནས་གསན་བསམ་མཛད། འཇམ་བཞད་བར་པ་འཇིགས་མེད་དབང་པོ་དགོངས་པ་རྫོགས་པའི་མཆོད་འབུལ་གྱི་ཚོགས་དབུའི་གྲས་སུ་ཕེབས། དགུང་ལོ་ཉེར་ལྔ་པ་རབ་བྱུང་བཅུ་གསུམ་པའི་མེ་འབྲུག་སྤྱི་ལོ1796ལོར་སྐུ་མྱ་ངན་ལས་འདས།

Q:དགེ་འདུན་ཆོས་ཀྱི་དབང་ཕྱུག་ནི་ཀིརྟི་སྐུ་ཕྲེང་དུ་པ་ཡིན།

A:སྐུ་ཕྲེང་དྲུག་པ་ཡིན་

Q:ཀིརྟི་སྐུ་ཕྲེང་དྲུག་པ་སུ་ཡིན།

A:དགེ་འདུན་ཆོས་ཀྱི་དབང་ཕྱུག་

Q:དགེ་འདུན་ཆོས་ཀྱི་དབང་ཕྱུག་ནི་ཡུལ་གང་ནས་འཁྲུངས་པ་ཡིན།

A:མདོ་སྨད་རེབ་གོང་གི་ཆུ་མ་ཞེས་པའི་ས་ཆར་

Q:དགེ་འདུན་ཆོས་ཀྱི་དབང་ཕྱུག་གི་ཡབ་ཡུམ་གཉིས་ཀྱི་མིང་ལ་ཅི་ཟེར།

A:ཡབ་ངག་དབང་རབ་བརྟན་དང་ཡུམ་སྙིང་མོ་ཐར་

Q:དགེ་འདུན་ཆོས་ཀྱི་དབང་ཕྱུག་ནི་རབ་བྱུང་དུ་པའི་སྐབས་སུ་འཁྲུངས།

A:རབ་བྱུང་བཅུ་གསུམ་པའི་ཆུ་འབྲུག་སྤྱི་ལོ1773ལོར་

Q:དགེ་འདུན་ཆོས་ཀྱི་དབང་ཕྱུག་འཁྲུངས་དུས་སྤྱི་ལོ་དུ་པ་ཡིན།

A:སྤྱི་ལོ1773ལོ

Q:དགེ་འདུན་ཆོས་ཀྱི་དབང་ཕྱུག་དགུང་ལོ་ལྔ་ལ་ཕེབས་པའི་སྐབས་གང་ལ་ཐག་བཅད།

A:ཀིརྟི་སྐུ་ཕྲེང་ལྔ་པའི་ཡང་སྤྲུལ་དུ་ཐག་བཅད

Q:དགེ་འདུན་ཆོས་ཀྱི་དབང་ཕྱུག་ཀིརྟི་སྐུ་ཕྲེང་ལྔ་པའི་ཡང་སྤྲུལ་དུ་ཐག་བཅད་དེ་གདན་སར་བཀོད་རྗེས་སུ་དགེ་རྒན་དུ་བསྟེན།

A:མཛོད་དགེ་རི་ཁྲོད་དབང་སོ་མཁས་གྲུབ་བསྟན་འཛིན་དང་ཨང་སྨོན་སྤྲུལ་སྐུ་

Q:དགེ་འདུན་ཆོས་ཀྱི་དབང་ཕྱུག་ནི་དགུང་ལོ་དུའི་དུས་སྐུ་མྱ་ངན་ལས་འདས།

A:དགུང་ལོ་ཉེར་ལྔ་པ་

Q:དགེ་འདུན་ཆོས་ཀྱི་དབང་ཕྱུག་ནི་སྤྱི་ལོ་ནམ་གྱི་དུས་སྐུ་མྱ་ངན་ལས་འདས།

A:སྤྱི་ལོ1796ལོརའབྱུང་བར་གྱུར་པའི་རེག་བྱ་ནི་ས་ཆུ་མེ་རླུང་བཞིའོ།།སྲ་ཞིང་འཐས་པ་སའི་མཚན་ཉིད།རླན་ཞིང་གཤེར་བ་ཆུའི་མཚན་ཉིད།ཚ་ཞིང་སྲེག་པ་མེའི་མཚན་ཉིད། ཡང་ཞིང་གཡོ་བ་རླུང་གི་མཚན་ཉིད་དོ།།འབྱུང་བ་བཞིའི་བྱེད་ལས་ནི།སས་འཛིན་པ་དང་།ཆུས་སྡུད་པ་དང་།མེས་སྨིན་པ།  རླུང་གིས་རྒྱས་པར་བྱེད་པའོ།། 

Q:འབྱུང་བར་གྱུར་པའི་རེག་བྱ་ལ་དུ་ཡོད།

A:བཞི

Q:འབྱུང་བར་གྱུར་པའི་རེག་བྱ་གང་དག་ཡོད།

A:ས་ཆུ་མེ་རླུང་བཞིའོ།།

Q:སའི་མཚན་ཉིད་ནི་ཅི་ཞིག་ཡིན།

A:སྲ་ཞིང་འཐས་པ་སའི་མཚན་ཉིད

Q:ཆུ་ལ་མཚན་ཉིད་བཞག་ན་ཇི་ལྟར་འཇོག་དགོས།

A:རླན་ཞིང་གཤེར་བ་ཆུའི་མཚན་ཉིད།

Q:ཚ་ཞིང་སྲེག་པ་ནི་འབྱུང་བར་གྱུར་པའི་རེག་བྱ་ལས་གང་གི་མཚན་ཉིད་ཡིན།

A:མེའི་མཚན་ཉིད

Q:འབྱུང་བ་བཞིའི་བྱེད་ལས་ནི་གང་དག་ཡིན།

A:སས་འཛིན་པ་དང་།ཆུས་སྡུད་པ་དང་།མེས་སྨིན་པ།  རླུང་གིས་རྒྱས་པར་བྱེད་པའོ།།

Q:འབྱུང་བ་བཞིའི་བྱེད་ལས་ནི།སས་འཛིན་པ་དང་།ཆུས་སྡུད་པ་དང་།རླུང་གིས་རྒྱས་པར་བྱེད་པ།ད་དུང་གང་ཡོད།

A:མེས་སྨིན་པ།སྤྱི་ལོ1920ལོར་ཅེ་ཁེ་སི་ཝ་ཁེ་རྒྱལ་ཁབ་ཀྱི་རྩོམ་པ་པོ་ཁ་ཕེ་ཁེ་ཡིས་ཚན་རྟོག་སྒྲུང་གཏམ་ཞིག་གི་ནང་དུ་མིང་ལRobotཟེར་བའི་འཕྲུལ་ཆས་མི་ཞིག་བསམ་བཀོད་བྱས་ཤིང་།ཁོས་ཟ་མ་ཟ་མི་དགོས་ལ་ངལ་དུབ་མེད་པར་ལས་ཀ་ལས་ཐུབ།དེ་ལས་འགྲོ་བ་མིའི་སེམས་སུ་ལོ་མང་པོར་བཅངས་པའི་རེ་འདུན་ཞིག་མངོན་ཡོད།

Q:སྤྱི་ལོ1920ལོར་ཅེ་ཁེ་སི་ཝ་ཁེ་རྒྱལ་ཁབ་ཀྱི་རྩོམ་པ་པོ་སུས་མིང་ལRobotཟེར་བའི་འཕྲུལ་ཆས་མི་ཞིག་བསམ་བཀོད་བྱས་ཡོད།

A:ཁ་ཕེ་ཁེ་

Q:སྤྱི་ལོ1920ལོར་ཁ་ཕེ་ཁེ་ཡིས་སྒྲུང་གཏམ་གང་འདྲ་ཞིག་གི་ནང་དུ་མིང་ལRobotཟེར་བའི་འཕྲུལ་ཆས་མི་ཞིག་བསམ་བཀོད་བྱས།

A:ཚན་རྟོག་སྒྲུང་གཏམ་ཞིག་གི་ནང་དུ

Q:ཁ་ཕེ་ཁེ་ནི་རྒྱལ་ཁབ་གང་གི་མི་ཡིན།

A:ཅེ་ཁེ་སི་ཝ་ཁེ་རྒྱལ་ཁབ

Q:Robotལ་ཁྱད་ཆོས་ཅི་ཡོད།

A:ས་ཟ་མ་ཟ་མི་དགོས་ལ་ངལ་དུབ་མེད་པར་ལས་ཀ་ལས་ཐུབ།



