# Face-Anonymisation
My Submission for the AlgorithmX fellowship, Hosted by thealgorithmx.com . 
The Task was to anonymise/blur all faces except Thomas shelby's face in the given image. This task was evaluated on different criteria as mentioned in their website.

*A note on the Novelty and the implication of this work along with required references for the purpose of the **AlgorithmX** panel:*


1.   This project is implemented **completely online**, uses Google drive as the source for all the files that are required. Done on **Google colab.**

2.   The model I have built is **completely dynamic** in the sense that even the variables that store the representations, are created dynamically, meaning that this could be done for **any** such picture where everyone's face, except Thomas shelby's needs to be anonymised.

3.   The model here uses the **VGG-net** which works wihtout training by using **Siamese network based similarity calculation of images**. We have used two metrics here, namely the Euclidean distance and the Cosine similarity with a threshold of 0.4 and 120 respectively, above which the images are not similar.

4.   This hence, works as a **Image verification** problem, where you know one is Thomas shelby, and you try to match it with the other faces, and blur all, except Thomas' face.
 
5.   This devoids the model of GPU bottlenecking, or any such issues of wasting time. Making it fast!


---
Links and references:


*   My AlgorithmX drive [link](https://drive.google.com/drive/folders/1IK5gd-vh_D_Po9U0WmEG4KTwZVU2zOIm?usp=sharing)
*   Haar Cascade Classifier XML [file](https://drive.google.com/file/d/1kDa3wLEUPJhUpg16Wx4ULe-02ZVl3ty_/view)
*   My [Resume](https://drive.google.com/file/d/12VsiPM3pAfNSrhc-mfI0WD15O8NSMpSz/view?usp=sharing)
*   Siamese Network Features for Image Matching [paper](https://users.aalto.fi/~kannalj1/publications/icpr2016.pdf)

*   VGG Net architecture [Medium article](https://medium.com/analytics-vidhya/vggnet-architecture-explained-e5c7318aa5b6)

---
If you are using this work anywhere, do DM me/Use it with due credits under: © Manjunathan.R, B.E.ECE, SSN College of Engineering
