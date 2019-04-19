# machine_learning_resource
神经网络模型的网络结构参数
从 https://github.com/fchollet/deep-learning-models/releases 下载
拷贝到C:\Users\XXX\.keras\models 使用

tensorflow模型下载：  
https://github.com/tensorflow/models/blob/master/research/slim/README.md

mobilenet v2模型：  
https://github.com/tensorflow/models/blob/master/research/slim/nets/mobilenet/README.md

mobilenet v1模型：  
https://github.com/tensorflow/models/blob/master/research/slim/nets/mobilenet_v1.md



# 数据集

## CV数据集
1. MS-Celeb-1M 数据集  
MS-Celeb-1M 是微软的一个非常大的人脸识别数据库，它是从名人榜上选择前100万的名人，然后通过搜索引擎采集每个名人大约100张人脸图片而形成的。  
[官方下载地址](https://www.microsoft.com/en-us/research/project/ms-celeb-1m-challenge-recognizing-one-million-celebrities-real-world/)    

2. Adience 数据集  
Adience 数据集包含26580张图片，总共含有2284类，涉及的年龄范围有8个区段（0～2、4～6、8～13、15～20、25～32、38～43、48～53、60～），并且这个数据集含有噪声、姿势、光照等变化，尽可能真实地反映现实世界  
[官方下载地址](http://www.openu.ac.il/home/hassner/Adience/data.html#agegender)  


## NLP数据集
1. VCTK-Corpus数据集(10G)
VCTK-Corpus数据集可用来训练声纹识别，ASR；数据集中包含说话人（ID、年龄、性别、国家、地区),录音wav文件，说话内容txt文件。  
[官方下载地址](http://homepages.inf.ed.ac.uk/jyamagis/release/VCTK-Corpus.tar.gz)

**[http://www.openslr.org/resources.php系列英语数据集 start]**
1. Yesno  
一个人用希伯来语记录是或否的60个录音; 每个录音长八个字。    
[官方下载地址](http://www.openslr.org/1/)  

2. Vystadial    
英语和捷克语数据，来自Vystadial项目        
[官方下载地址](http://www.openslr.org/6/)  

3. TED-LIUM（21G）  
来自TED讲座的英语语音识别训练语料库，由缅因州大学信息实验室（LIUM）创建  
[官方下载地址](http://www.openslr.org/7/)  

4. TED-LIUMv2  
TED-LIUM语料库发布2，来自TED讲座的英语语音识别训练语料库，由缅因州大学信息实验室（LIUM）创建（在这里镜像）  
[官方下载地址](http://www.openslr.org/19/)  

5. TED-LIUM Release 3  
TED-LIUM corpus release 3  
[官方下载地址](https://www.openslr.org/51/)     

6. LibriSpeech language models, vocabulary and G2P models  
语言建模资源，用于LibriSpeech ASR语料库        
[官方下载地址](http://www.openslr.org/11/) 

7. libriSpeech_ASR_corpus数据集  
该数据集是包含大约1000小时的英语语音的大型语料库。这些数据来自LibriVox项目的有声读物。它已被分割并正确对齐，如果你正在寻找一个起点，请查看已准备好的声学模型，这些模型在kaldi-asr.org和语言模型上进行了训练，适合评估。    
[官方下载地址](https://www.openslr.org/12)  

8. Mini LibriSpeech ASR corpus数据集   
用于回归测试的一个LibriSpeech ASR corpus子集  
[官方下载地址](http://www.openslr.org/31/)  

9. Free ST American English Corpus
由Surfingtech（www.surfing.ai）提供的免费美式英语语料库，包含来自10位发言者的话语，每位发言者约有350个话语  
[官方下载地址](http://www.openslr.org/45/)

10. THCHS-30(中文)  
THCHS-30是在安静的办公室环境下，通过单个碳粒麦克风录取的，总时长超过30个小时。大部分参与录音的人员是会说流利普通话的大学生。采样频率16kHz，采样大小16bits。  
THCHS-30的文本选取自大容量的新闻，目的是为了扩充863语音库。我们选取1000句来录音。  
[官方下载地址](http://www.openslr.org/18/)    

11. Aishell（中文）
普通话数据，由北京贝壳科技有限公司提供  
录音时长178小时；录音文本涉及智能家居、无人驾驶、工业生产等11个领域；录制过程在安静室内环境中；同时使用3种不同设备： 高保真麦克风（44.1kHz，16-bit），Android系统手机（16kHz，16-bit），iOS系统手机（16kHz，16-bit），高保真麦克风录制的音频降采样为16kHz，用于制作AISHELL-ASR0009-OS1；400名来自中国不同口音区域的发言人参与录制。经过专业语音校对人员转写标注，并通过严格质量检验，此数据库文本正确率在95%以上。分为训练集、开发集、测试集。  
[官方下载地址](http://www.openslr.org/33/)    

12. Free ST Chinese Mandarin Corpus（中文）  
由Surfingtech（www.surfing.ai）提供的免费中文普通话语料库，包含855位发言者的话语，102600个话语;   
[官方下载地址](http://www.openslr.org/38/)     

13. Primewords Chinese Corpus Set 1(中文)  
上海Primewords有限公司（www.primewords.cn）发布的中文普通话语料库，包含100小时的语音数据  
[官方下载地址](http://www.openslr.org/47/)  
  
**[http://www.openslr.org/resources.php系列英语数据集 end]**  

1. VoxForge  
该数据集是带口音的语音清洁数据集，对测试模型在不同重音或语调下的鲁棒性非常有用。
http://www.voxforge.org/    
[官方下载地址](https://voice.mozilla.org/zh-CN/datasets)    

2. TIMIT数据集  
TIMIT数据集是来自美国630个人每个人说十个给定的句子，每一个句子都有标记  
[百度云](https://pan.baidu.com/s/1Mv3dqsGWynidRq3cisY2dQ)(95k2)