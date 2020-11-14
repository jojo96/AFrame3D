# AFrame3D
A method to convert an image to a 3D model in VR

A-Frame VR(3D model of a 2D Image)
A-frame is a really nice and easy to use web framework for creating VR and AR experiences. In this tutorial, we would use Python and A-frame to create a 3D model from a 2D image.
The input would be an image like this:

<img src="https://github.com/jojo96/AFrame3D/blob/main/1.png" width=99% height=600 alt="Normal"> 

Using this image, we will create a 3D model that can be viewed in webVR. The result:

<img src="https://github.com/jojo96/AFrame3D/blob/main/2.png" width=99% height=600 alt="Normal">

We can also animate this:

<img src="https://github.com/jojo96/AFrame3D/blob/main/3.gif" width=99% height=600 alt="Normal">

You can find the whole tutorial at: https://www.analyticsvidhya.com/blog/2020/10/virtual-reality-for-the-web-a-framecreating-3d-models-from-images/

The same method can be used to create pixel art in AFrame. An example:

<img src="https://github.com/jojo96/AFrame3D/blob/main/6.png" width=99% height=600 alt="Normal"> 

# AFrame Code

How to get the AFrame code?

The skeleton code is:
```
<html>
  <head>
    <script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
	<script src="https://unpkg.com/aframe-event-set-component@4.2.1/dist/aframe-event-set-component.min.js"></script> 
	<script src="https://unpkg.com/aframe-environment-component"></script>
	
  </head>
  <body>
 <a-scene>

    <a-camera><a-cursor></a-cursor></a-camera>
</a-scene>

</body>

</html>
```

Run any one of the files in the notebook folder and copy the text from the resulting text file. Paste the text after the opening a-scene tag.

Say, you want to make the "Pikachu 3D model". You can run the pikamodel.ipynb notebook and get the pik2.txt as output. Copy the text inside the pik2.txt and paste the text after <a-scene> tag. The complete example is in the A-Frame Examples folder.
	
# New Examples

You can now use 2 pokemon images and check out my notebook PikaCharDestroy.ipynb to create an interactive scene.

<img src="https://github.com/jojo96/AFrame3D/blob/main/PikaCharDestroy.gif" width=99% height=600 alt="Normal">

Thank you :)
