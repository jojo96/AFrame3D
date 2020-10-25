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

You can find the whole tutorial at: https://medium.com/p/552c257685dd
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

Thank you :)
