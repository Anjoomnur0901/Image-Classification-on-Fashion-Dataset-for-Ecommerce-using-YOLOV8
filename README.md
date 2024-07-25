# Image-Classification-on-Custom-Dataset-using-YOLOV8
<h1>Steps:</h1>
<ul>
  <li>Create a data folder. Which should have two folder called Train and Test.<br>
  <li>Train has Test should have multiple folders. The folder names should be the name of the classes.These folder will have images of the corresponding classes</li>
  <li>Train using YOLOv8</li>
  <li>Save Your run results</li>
  <li>In your results.csv make sure training/loss,val/loss is going down and accuracy is going up.</li>
</ul>
<p>Tune your model for better accuracy</p>
<p>Models will be saved in the weights folder. After every epoch we update our weight value and creates a model. last.pt saves the model of the last epoch. best.pt saves the best model of our entire training process</p>
<p>predict</p>

## references
[Reference Youtube Video](https://www.youtube.com/playlist?list=PLv8Cp2NvcY8ClWpGlPJ9tmBmUhlA94Umy)
[Official Documentation of YOLOv8 Classification](https://docs.ultralytics.com/tasks/classify/).
[Fashion-MNIST official repository](https://github.com/zalandoresearch/fashion-mnist).
