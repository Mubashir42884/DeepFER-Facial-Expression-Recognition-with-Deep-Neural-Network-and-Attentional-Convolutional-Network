----
# DeepFER: Facial Expression Recognition with Deep Neural Network and Attentional Convolutional Network

### Authors: Mubashir Mohsin, Shahriar Hossain Rafi, and Jishan Ferdows Navil.
### Supervisor: Dr. Debajyoti Karmaker, Associate Professor, Member [Research and Publication Steering Committee], Department of Computer Science, AIUB.
----
<b> Project Description: </b></br>
This is a Computer Vision project and paper based on Deep Neural Networks and Attentional Convolutional Networks to recognize various human facial expressions. This project includes FER2013, JAFFE, CK+, and FERG datasets. The project has been made using Python and its popular Deep Learning modules like TensorFlow, Keras, and PyTorch. Below you'll get a detailed description of the whole project and the results.
</br></br>

<span>
  <h2>Contents</h2>
  1. Abstract</br>
  2. Introduction</br>
  3. Methods & Materials</br>
  4. Results</br>
  5. Future Works</br>
  6. References</br>
</span>


<span>
  <h2>1. Abstract</h2>
This paper delves comprehensively into the domain of facial expression recognition, a subject of burgeoning interest in recent decades. The inherent difficulty stems from the substantial intraclass variety seen in the field of facial expressions. In traditional approaches, classifiers trained on extensive image or video datasets are frequently combined with manually produced features like SIFT, HOG, and LBP. While these techniques have shown impressive effectiveness when used on controlled picture datasets, their performance deteriorates when applied to more intricate data sets with more image variance and uncompleted facial information. The ascendancy of deep learning models has ushered in a paradigm shift by ushering in end-to-end frameworks for facial expression recognition. Despite their discernible strides in performance, a substantial scope for refinement remains unexplored. This study proposes a pioneering deep learning framework hinged on an attentional convolutional network. This innovative architecture attains the ability to selectively focus on pivotal facial components, eliciting a pronounced enhancement over preceding models across diverse datasets, encompassing FER-2013, CK+, FERG, and JAFFE. A visualization technique is also developed that, based on the predictions of the classifier, identifies crucial facial regions that are influential in the identification of various emotional states. Experimental data underwent an empirical examination, which affirmed that various emotions display distinct reactions to various facial regions. </br>
  <b>   Keywords: Deep learning, Computer Vision, Facial Expression Recognition, Spatial Transformation, Attention Mechanism, Neural Network, CNN</b>
</span>

<span>
  <h2>1. Introduction</h2>
Facial expressions are a significant point of human non-verbal communication, serving as a conduit for passing on assumptions, excitedly, and social signals. The capacity to precisely recognize facial expressions holds essential suggestions for a wide cluster of spaces, checking human-computer interaction, enthusiastic computing, brain ask approximately, and without a question law prerequisite [3]. Adjusted facial expression assertion frameworks energize the extraction of enthusiastic states from people, empowering a more noteworthy understanding of their energized reactions and supporting making compassionate AI frameworks. Facial expressions are enthusiastic, advancing shapes that show up over time. Capturing the worldly stream of facial expressions is basic for a comprehensive understanding of assumptions. In extension, not all facial zones contribute further to communicating a particular feeling. For occasion, the mouth locale can be more educator for recognizing elation, whereas the eyebrow and haven locales might play an essential parcel in recognizing stun. Convolutional Neural Systems (CNNs) have laid out unprecedented execution in picture classification assignments, persuading their application to facial expression assertion [4]. In this paper, we present a novel approach to facial expression confirmation, the Attentional Convolutional Organize (ACN), which opens up the capabilities of CNNs by joining thought components to center on the striking divide of the stand-up. This study's objective is to: 
<span>
  </br></br> <b><i>[I] In advancement, we utilize the visualization strategy proposed in [5] to highlight the go-up against the image’s most striking areas. </br>[II] the parts of the picture which have the foremost grounded influence on the classifier’s result.</i></b> </br></br>
</span>
Interior the taking after parts, we detail the arrangement, arranging strategy, and the test comes around of the proposed ACN. We examine its execution on benchmark datasets and compare it to existing CNN-based models. Also, we dive into the interpretability of ACN's thought maps and see their recommendations.
</span>
