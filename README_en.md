<div align="center">
  <img src="./web/荀子logonew.png" width="400"/>
</div>

# XunziALLM

With the rapid development of science and technology, artificial intelligence has penetrated into various fields. In response to the call for the activation and utilization of ancient books, to promote the in-depth integration of large language models and ancient book processing, and for the purpose of researching the intelligence of ancient books, the research group of the National Social Science Fund major project of Nanjing Agricultural University "Research on the Construction and Application of Cross-Language Knowledge Base of Ancient Chinese Classics" together with Zhonghua Book Company Gulian (Beijing) Media Tech Company, we launched a series of large-scale language models in the field of ancient books processing: Xunzi large language model of ancient books. Xunzi was not only a great simple materialist thinker in my country's pre-Qin period, but also a master of prose. He is also a pioneer and founder in the elaboration of linguistic theory. The Xunzi series is specially designed for intelligent processing of ancient books. The launch of this series of models will promote new developments in the research and protection of ancient books, and improve the efficiency and quality of the inheritance of Chinese traditional culture.

The Xunzi series model open source includes two parts: the base model [**XunziALLM**](https://modelscope.cn/models/Xunzillm4cc/Xunzi-Qwen), as a key focus of this open source model, this project has launched a fully open model for the field of ancient books. At the same time, to facilitate non artificial intelligence professionals to better understand this open source model, we have used some data to construct a dialogue model [**XunziChat**](https://modelscope.cn/models/Xunzillm4cc/Xunzi-Qwen-Chat). The calling method of the model is consistent with Alibaba Cloud's Qwen series of large models.

## Highlights of Xunzi Series models:

* Intelligent indexing of ancient books, the Xunzi model has powerful ancient book document indexing capabilities and can perform high-quality subject indexing of the content in ancient books, helping researchers quickly understand the topic of the article.

![index](./examples/index.png)
* Ancient book information extraction, the Xunzi model can automatically extract key information from ancient books, such as people, events, locations, etc., which greatly saves researchers time in sorting out information.

![ner](./examples/ner.png)
* Poetry generation: Xunzi model also has the ability to generate poetry, which can automatically generate ancient poems that comply with grammatical rules and rhyme requirements based on given themes or keywords, providing creative inspiration for poetry lovers.

![poetry](./examples/poetry.png)
* High-quality translation of ancient books: For those ancient books that are difficult to understand, the Xunzi model can provide high-quality translation services and help researchers better understand the meaning of the original text.

![translation](./examples/translation.png)
* Reading comprehension: the Xunzi model can analyze and interpret the given ancient Chinese text and realize automatic reading of ancient text.

![reading_comprehension](./examples/reading_comprehension.png)
* Lexical analysis: Xunzi model can complete automatic word segmentation and part-of-speech tagging of ancient text, which can effectively improve the research efficiency of linguistic workers.

![pos](./examples/pos.png)
* Automatic punctuation: Xunzi's large model can quickly complete sentence segmentation and punctuation of ancient text, improving the reading experience of ancient text for researchers and amateurs.

![punctuation](./examples/punctuation.png)

Since we also released the base model, users can also use personal training corpus to fine-tune the Xunzi base model according to their own needs, so that it can achieve better processing performance in downstream processing tasks of ancient books.

## Acknowledgements：
* Associate professor Shen Si,Nanjing University of Science and Technology，Provide technical support for large model training
* Doctor Zhu Danhao, Jiangsu Police Institute, Provide model parameter tuning
* Professor Li Bin, Nanjing Normal University, Provide knowledge support in the field of ancient literature
* Associate researcher Ma Xueliang, National Library of China，Provide knowledge related to classical philology

## Statement:

The Xunzi series of large language models have shown good performance in processing information in ancient Chinese texts. They can not only accurately analyze the complexity of ancient texts, but also further explore the rich connotations of traditional Chinese culture. However, we also clearly recognize that there are still many areas for improvement and optimization in this model. Therefore, we warmly welcome and encourage users to provide valuable feedback and suggestions on our model, and in future work, we will launch a new version of the large language model with better performance.

The large number of parameters in large language models also brings more randomness. Although we have tried our best to ensure data compliance when selecting training data, there may still be some unavoidable problems due to the complexity of data and models. Therefore, we will not be held responsible for any issues arising from the use of this open source model, including but not limited to data security issues, public opinion risks, or any risks and issues arising from the model being misled, abused, disseminated, or improperly utilized.

In addition, according to the ["Interim Measures for the Management of Generative Artificial Intelligence Services"](http://www.cac.gov.cn/2023-07/13/c_1690898327029107.htm) jointly issued by the National Cyberspace Administration and seven other departments. When training and using this model, as well as other generative models, please work together in accordance with relevant laws and regulations to build a harmonious, healthy, and sustainable generative artificial intelligence community.

If you have any questions during the use of the model, please feel free to contact us (zhaozhixiao@stu.njau.edu.cn).
