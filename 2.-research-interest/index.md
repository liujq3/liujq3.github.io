# RESEARCH INTEREST


<!--more-->
<br>

<div style="text-align: center;">
 <span style="font-size: 22px;">
<strong>Electronic Skins and Deep Learning Models for Supporting Observational Learning in Humanoid Robots</strong>
</span>
</div>
<br>

## Introduction
<div style="text-align: justify;">

With the rapid advancement of deep learning (DL) methods, robots assisted by flexible electronic skins (E-skins) can achieve precise monitoring of physiological signals and stable grasping of objects relying on tactile sensing showing broad application prospects in smart healthcare, smart industrial production and other fields. 
<strong>
However, most current studies still train related DL models using the _direct learning paradigm_ based on their own interaction trial-and-error.
Few adopt the _observational learning paradigm_ (OLP) based on tactile signals during human work.
</strong>
The former has problems such as low efficiency, high cost, and potential damage to itself or the environment, which limits its application in complex and high-precision tasks. 
The latter can collect high-quality tactile datasets when humans perform tasks, simulate the tactile perception perspective in human work, and enable the model to master task execution methods by "observing human work logic". 
This paradigm is similar to _"observational learning"_ pointed out in _social learning_ theory. 
It is expected to improve model training efficiency, reduce training costs, and promote the intelligent process of robots assisted by E-skins.
<br>
<br>

<strong>
However, this research direction is affected by the limitations of current E-skins technology and DL model development, facing many challenges.
</strong>
Although a large number of powerful E-skins have been reported in the past decade, they still have obvious deficiencies in conformality, scalability, and multimodal perception capabilities. 
At the same time, the development ideas and technical paths of DL models for tactile perception are also limited by the difficulty of obtaining high-quality and large-scale tactile datasets, resulting in a slow progress.
<br>
<br>

<strong>I am interested in the research direction of "integration of E-skins and DL" and hope to solve the problem of cross-domain knowledge transfer of tactile intelligence from humans to machines.</strong>
I plan to explore and develop E-skins suitable for both humans and humanoid robots, integrate learning algorithms, and construct an OLP based on tactile signals during human work with the help of DL methods such as transfer learning, so as to provide ideas for promoting the intelligent application of E-skins in the robot field.
</div>
<br>

## Method
<div style="text-align: justify;">

To effectively realize the cross-domain knowledge transfer of tactile intelligence from humans to machines and construct an OLP based on tactile signals during human work, it is necessary to first design special E-skins suitable for the observational learning scenarios of humanoid robots and build an integrated DL model for tactile perception-knowledge transfer that supports this paradigm.
</div>

### E-skins research
<div style="text-align: justify;">

<strong>As a carrier of tactile perception, E-skins need to have the characteristics of high conformality, easy scalability, and multimodal perception.</strong>
* <strong>High conformality: </strong>Achieving cross-domain knowledge transfer of tactile intelligence from humans to machines requires E-skins to be applicable to both human and machine surfaces, which puts forward high requirements for the conformality of E-skins. At the same time, high conformality helps E-skins obtain tactile information on complex curved surfaces more comprehensively and improve the accuracy and resolution of signals. However, most E - skins reported so far are prepared by traditional methods such as planar arrays and monolithic integration, which limits the improvement of conformality and hinders the application of E-skins.
* <strong>Easy scalability: </strong>Good scalability can reduce customization costs and improve application development efficiency. However, most current E-skins rely on fixed-size integrated designs or use single structures that are difficult to splice, making it difficult to flexibly adjust the size of the sensing area according to needs, which hinders the update and iteration process of intelligent applications of E-skins.
* <strong>Multimodal perception: </strong>Building E-skins that can perceive multiple modalities is of far-reaching significance in simulating more realistic and natural human tactile perception and improving system robustness. However, most E-skins reported at present only have the sensing modality of pressure perception, which greatly limits the application potential of E-skins in the robot field.
</div>

<div style="text-align: justify;">

> <strong>In my undergraduate graduation project, I initially explored the design and production of E-skins.</strong>
> <br>Through modular design and structural innovation, I developed four types of E-skins: 
> traditional monolithic type, back-expanded type, bandage type, and wristwatch type. Their conformality, scalability, and multimodal perception capabilities show a gradually increasing trend. 
> At the same time, I accumulated proficiently mastered skills such as virtual simulation modeling and 3D printing.
</div>
<div style="text-align: center;">

![](/posts/R_1_en.png)

| | Traditional monolithic | Back-expanded | Bandage type  |Wristwatch type|
|:---:|:--:|:----:|:---------:|:---:|
|Conformality|  × |  ×   |     ×     |√|
|Scalability|  × |  ×   |     √     |√|
|Multimodal perception cability|  × |  √   |     √     |√|

</div>


### DL models research
<div style="text-align: justify;">

In Albert Bandura's "Social Learning" theory, it is pointed out that _"observational learning"_ (learning by observing the behavior of demonstrators) is a core behavior acquisition path different from _"direct learning"_ (learning by the results of responses), and it is the key for humans to master complex behaviors. 
Its advantage lies in reducing tria-and-error costs and improving learning efficiency. Currently, this theory has been widely applied in AI model training: 
In the language field, large language models represented by the GPT series achieve semantic generalization by observing human language samples; 
In the painting field, models such as Imagine Art complete creation by learning human paintings, and all have achieved remarkable results.
<strong>
Applying observational learning to the training of tactile intelligent models and constructing an OLP based on tactile signals during human work is expected to have a variety of positive impacts on intelligent robots assisted by flexible E-skins:
</strong>
* <strong>Improve the scale and quality of datasets.</strong> Collecting data during human operations can avoid complex motion simulation of robots, and large-scale data can be obtained more simply, at low cost and efficiently. At the same time, human operations are more flexible and accurate, so the obtained data is more accurate and has more significant features.
* <strong>Enhance the flexibility and information security of model training.</strong> This training mode supports flexible training and deployment of small models, which can effectively reduce the risk of data leakage.
* <strong>Improve the generalization ability of the model.</strong> It is beneficial for machines to extract abstract knowledge such as task execution patterns and strategies, and then realize creative learning and application.
<br>
<br>

<strong>With the rapid development of machine learning and neural networks, various mature models continue to emerge, laying a good research foundation for constructing an OLP based on tactile signals during human work.</strong>
Specifically, existing paradigms and open-source models, such as transfer learning and Transformer models, can be utilized. Then, based on the dataset of tactile signals during human work, deep learning engineering frameworks (such as PyTorch and TensorFlow) are used to fine-tune the models in a targeted manner, so that the models can accurately learn behavior patterns and features related to touch, thereby realizing the training and optimization of tactile intelligent models based on the OLP.
</div>

<div style="text-align: justify;">

> <strong>In my undergraduate graduation project, I initially explored the construction method of deep learning engineering frameworks and proficiently mastered the use of TensorFlow preprocessing library.</strong> 
> <br>To build an intelligent E-skin application for pulse diagnosis, I simulated the pulse taking process and collected 5 types of pressure signals: pulse signal (PS), noise signal (NS), constant force signal (CF), random force signal (RF), and transient force signal (TF), with a total of 209 frames of data. A one dimensional convolutional neural network was built with the help of the TensorFlow preprocessing library to achieve accurate classification of the signals, and the accuracy rate reached 93%.
</div>
<div style="text-align: center;">

![](/posts/M_1_1_en.png)
</div>
<br>

