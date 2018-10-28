<p align="center"> 
<b>
<font size="5"> Recognizing American Sign Language Manual Signs from RGB-D Videos  </font> 
</b>
</p>
<p align="center">
Longlong Jing, Elahe Vahdani, Yingli Tian, Fellow, IEEE, and Matt Huenerfaut
</p>



![alt text](./media/demo_img.jpeg "Title")

--

<p align="center"> 
<b>
<font size="5"> Abstract </font> 
</b>
</p>

In this paper, we propose a 3D Convolutional Neural Network (3DCNN) based multi-stream framework to recognize American Sign Language (ASL) manual signs (consisting of movements of the hands, as well as non-manual face movements in some cases) in real-time from RGB-D videos, by fusing multimodality features including hand gestures, facial expressions, and body poses from multi-channels (RGB, depth, motion, and skeleton joints.) To learn the overall temporal dynamics in a video, we generate a proxy video by selecting a subset of frames for each video which then be used to train the proposed 3DCNN model. We collect a new ASL dataset, ASL-100-RGBD, which contains 42 RGB-D videos, each of 100 ASL manual signs, including RGB channel, depth maps, skeleton joints, face features, and HDface. The dataset is fully annotated for each semantic region (i.e. the time duration of each word that the human signer performs). Our proposed method achieves 75.9 accuracy from only RGB channel and 80.3 from the fusion of multi-channels for recognizing 100 ASL words, which demonstrate the effectiveness of recognizing ASL signs from RGB-D videos.

--

<p align="center"> 
<b>
<font size="5"> Demo Video </font> 
</b>
</p>
<p align="center">
<video width="950" height="540" controls>
  <source src="Demo.mp4" type="video/mp4">
</video>
</p>


[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/QPMZ_sNWsRc/0.jpg)](http://www.youtube.com/watch?v=QPMZ_sNWsRc)
