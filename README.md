# TibetanQA
## What is TibetanQA?
Tibetan Machine Reading Comprehension Dataset (TibetanQA) is a Tibetan reading comprehension datset, which contains 20,000 question answer pairs and 1,513 articles.

## TibetanQA
__Multi-domain resources:__ The articles are from the Tibetan Encyclopedia website and cover 12 topics, including nature, culture, education and so on.

__High quality:__ A complete and strict workflow is adopted to passage collection, question construction and answer verification to ensure the high quality of the data.

We invited the native Tibetan students to construct data sets using a program dedicated to collect question and answer pairs. We trained them first. Only the students whose accuracy rate reaches more than 90% participated in the construction of data sets. We encouraged them to construct various forms of questions. In addition, we invited another group to verify the answers.We discarded incomplete and grammatically incorrect question and answer pairs, and finally verified 20000 question and answer pairs. We divided the problem into four categories: word matching, synonym replacement, multi sentence reasoning and fuzzy problem. These four kinds of problems require the reasoning ability of the machine to be improved in turn.

## Leaderboard

|      Rank      |                  Model                   | EM  | F1  |
|:--------------:|:----------------------------------------:|:-:|:-:|
|                |            Human Performance             | 86.831  | 89.452  |
| 1 (Nov 12,2021) | [Ti-Reader (Minzu University of China)](https://aclanthology.org/2021.ccl-1.21/) | 67.9  | 77.4  |

## Data Detail

![type_ques](https://github.com/user-attachments/assets/dda61f27-92d0-438b-8e25-c61a1aaa0b80)![type_answer](https://github.com/user-attachments/assets/fc6e52d4-eef3-4b41-b9da-b6a6affe9cf8)

## Data Demo

རྒྱལ་ཡོངས་སུ་མིང་གྲགས་ཆེ་བའི་བྱིས་སྒྲུང་རྩོམ་པ་པོ་ཡེ་ཤེས་སྒྲོལ་མ་ལགས་ནི་སྤྱི་ལོ1925ལོར་མདོ་སྨད་ཀན་སུའུ་ཞིང་ཆེན་ཀན་ལྷོའི་ཅོ་ནེ་རྫོང་མཁར་ཆེན་ཤང་གི་ནུབ་གཟིག་སྡེ་བ་ནས་སྐྱེས་ཤིང་།ཆུང་དུས་ནས་བཟུང་།མོ་ལ་རིག་པ་ལྷན་སྐྱེས་སུ་མངའ་བ་དང་། ཆུང་དུས་སུ་སློབ་གྲྭ་འགྲིམས་ཏེ་སློབ་གྲྭ་ཆེན་མོ་ནས་སློབ་མཐར་ཕྱིན་རྗེས།རྒྱལ་ཁབ་ཕྱི་ནང་གི་རྩོམ་རིག་རིག་གཞུང་ལ་སྦྱངས་པ་གང་ལེགས་གནང་སྟེ།ཞོར་དུ་བརྩམས་ཆོས་སྣ་མང་སྤེལ་བའི་འགོ་བརྩམས་ཤིང་། མཐར་འདིའི་ཕྱོགས་ཀྱི་གྲུབ་འབྲས་གཡུར་དུ་ཟ་བ་ཐོབ་པ་དང་། སྤྱི་ལོ1983ལོར།ཀྲུང་གོའི་རྩོམ་པ་པོའི་མཐུན་ཚོགས་སུ་ཞུགས་པ་མ་ཟད།ཆེད་ལས་རྩོམ་པ་པོའི་འགན་གཅིག་ལྕོགས་སུ་བཞེས།

Q:ཡེ་ཤེས་སྒྲོལ་མ་ལགས་ནི་བྱ་བ་གང་སྒྲུབ་མཁན་ཞིག་ཡིན།

A:རྒྱལ་ཡོངས་སུ་མིང་གྲགས་ཆེ་བའི་བྱིས་སྒྲུང་རྩོམ་པ་པོ་ཡེ་ཤེས་སྒྲོལ་མ་ལགས་

Q:ཡེ་ཤེས་སྒྲོལ་མ་ཀྲུང་གོའི་རྩོམ་པ་པོའི་མཐུན་ཚོགས་སུ་ཞུགས་དུས་སྤྱི་ལོ་ག་ཚོད་ཡིན།

A:སྤྱི་ལོ1983ལོར།ཀྲུང་གོའི་རྩོམ་པ་པོའི་མཐུན་ཚོགས་སུ་ཞུགས་པ་མ་ཟད།

## Citation

Link: https://aclanthology.org/2021.ccl-1.20/

Cite (ACL): Yuan Sun, Sisi Liu, Chaofan Chen, Zhengcuo Dan, and Xiaobing Zhao. 2021. 面向机器阅读理解的高质量藏语数据集构建(Construction of High-quality Tibetan Dataset for Machine Reading Comprehension). In Proceedings of the 20th Chinese National Conference on Computational Linguistics, pages 208–218, Huhhot, China. Chinese Information Processing Society of China.

Cite (Informal): 面向机器阅读理解的高质量藏语数据集构建(Construction of High-quality Tibetan Dataset for Machine Reading Comprehension) (Sun et al., CCL 2021)

BibTeX:
```
@inproceedings{sun-etal-2021-mian,
    title = "面向机器阅读理解的高质量藏语数据集构建(Construction of High-quality {T}ibetan Dataset for Machine Reading Comprehension)",
    author = "Sun, Yuan  and
      Liu, Sisi  and
      Chen, Chaofan  and
      Dan, Zhengcuo  and
      Zhao, Xiaobing",
    editor = "Li, Sheng  and
      Sun, Maosong  and
      Liu, Yang  and
      Wu, Hua  and
      Liu, Kang  and
      Che, Wanxiang  and
      He, Shizhu  and
      Rao, Gaoqi",
    booktitle = "Proceedings of the 20th Chinese National Conference on Computational Linguistics",
    month = aug,
    year = "2021",
    address = "Huhhot, China",
    publisher = "Chinese Information Processing Society of China",
    url = "https://aclanthology.org/2021.ccl-1.20",
    pages = "208--218",
    abstract = "机器阅读理解是通过算法让机器根据给定的上下文回答问题,从而测试机器理解自然语言的程度。其中,数据集的构建是机器阅读理解的主要任务。目前,相关算法模型在大多数流行的英语数据集上都取得了显著的成绩,甚至超过了人类的表现。但对于低资源语言,由于缺乏相应的数据集,机器阅读理解研究还处于起步阶段。本文以藏语为例,人工构建了藏语机器阅读理解数据集(TibetanQA),其中包含20000个问题答案对和1513篇文章。本数据集的文章均来自云藏网,涵盖了自然、文化和教育等12个领域的知识,问题形式多样且具有一定的难度。另外,该数据集在文章收集、问题构建、答案验证、回答多样性和推理能力等方面,均采用严格的流程以确保数据的质量,同时采用基于语言特征消融输入的验证方法说明了数据集的质量。最后,本文初步探索了三种经典的英语阅读理解模型在TibetanQA数据集上的表现,其结果难以媲美人类,这表明在藏语机器阅读理解任务上还需要更进一步的探索。",
    language = "Chinese",
}
```
