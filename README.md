# Pytorch-Image-Caption
#### Trianed with NVIDIA GPU P100
#### Data
- COCO Dataset is used, check thier website for details [Link](http://cocodataset.org/#download)
- Training and Test dats look like this:
<img src="/image/test_img.png" width="350" height="250"/> 

#### Training
- Transfer Learning is used with Resnet150 for extracting image features(Convolutional Neural Network) and Recurrent Neural Network using LSTM is used.
<img src="/image/loaded_model.png" width="450"/> 
- We can see that model is actually learning!  :stuck_out_tongue_winking_eye:
<img src="/image/train0.png" width="450"/>
<img src="/image/train_end.png" width="450"/> 

#### Testing
- Prediction: Well.. it seems like my model perfers to use "on" :joy:
<img src="/image/pred1.png" width="450"/> 
<img src="/image/pred2.png" width="450"/> 
<img src="/image/pred3.png" width="450"/> 

#### Conclusion
Overall, with this project, I cannot underestimate the power of deep learning again.. 
