# Object-Extraction-from-Rock-Art-Images

There are numerous rock arts all around the world signifying ancient objects. These object have historical value associated with them. It is however, a challenge to extract these objects from uneven rock surfaces in image processing. The art drwan is either too light or too cuttered. <br>
<B>Libraries used are as follows:</B> <br>
scikit-image<br>
Pillow<br>
rembg<br>
<br>
<br>
<B>Main steps involve:</B><br>
1- Increse the intensity of the image. By doing this the objects in the rock art become prominent.<br>
2- Remove the background. Once the objects are prominent, they act as the foreground objects. Hence the background can esaily be removed.<br>
3- Apply Gaussian filter. Even though the background is removed, the image has noise left. This can be removed using the Gaussian filter. It further blurs the objects.<br>
4- Optional step is to apply the Watershed Algorithm. This is if one would want to experiment further with the extracted objects. <br>

You can experiment the code with the given image 800wm.jpg.
Main code: Object Extraction from Rock Art Images.ipnyb


