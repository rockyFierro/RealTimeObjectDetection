# ASL Input Controls
Using translations made possible by the work of Nichola Renotte and Priyanjali Gupta; Uses handsigns detected by Tensorflow object detection and maps them to custom commands as an alternative to keyboards and videogame controllers.

Built on top of  priiyaanjaalii0611/ASL_to_English
Reads your hand signs and translates them to English words using Tensorflow object detection API<br>
The model is built using transfer learning from pretrained model ssd_mobilenet model<br>
The dataset is made manually by running the __*Image Collection python file*__ that collects images from your webcam for all the mentioned below signs in the American Sign Language :<br>
* Hello ✋
* I Love You 💙
* Thank you 😺
* Please 🥺
* Yes ✔️
* No ❎

The image annotations is done with the help of LabelImage file which you can use by simply git cloning the following:<br>
[Git link](https://github.com/tzutalin/labelImg)<br>

The model was made only with help of [Nicholas Renotte tutorial](https://youtu.be/pDXdlXlaCco)
and Priyanjali Gupta
