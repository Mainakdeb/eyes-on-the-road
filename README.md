# eyes-on-the-road
[![Binder](https://camo.githubusercontent.com/bfeb5472ee3df9b7c63ea3b260dc0c679be90b97/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f72656e6465722d6e627669657765722d6f72616e67652e7376673f636f6c6f72423d66333736323626636f6c6f72413d346434643464)](https://nbviewer.jupyter.org/github/Mainakdeb/eyes-on-the-road/tree/master/)

Detect distracted drivers using a trained CNN.

### Some test images and their respective prediction labels (using ResNet-18) :

<img src="https://github.com/Mainakdeb/eyes-on-the-road/blob/master/images/resnet18_preds2.png" width="610">

### Passing real-life images through the trained model :
This is Mayukh, looks like he's texting.

<img src="https://github.com/Mainakdeb/eyes-on-the-road/blob/master/images/mayukh_text_r.png" width="400">


### Training Metrics :

<img src="https://github.com/Mainakdeb/eyes-on-the-road/blob/master/images/accuracy_plot_res18.png" width="610">
The accuracy reaches 93.9% after 5th epoch.

### To Do :
* Record a video, pass the video frames through the model.
* Pass images through the model in real-time.
