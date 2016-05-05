<article class="markdown-body entry-content" itemprop="text">
<h1><a id="Camera Capture in Android" class="anchor" href="#ACamera Capture in Android" aria-hidden="true"></a>Camera Capture in Android
</h1>
<p>Camera Capture Feature in Android : This project is an overview of the syntax to launch an existing camera application installed on phone.</p>

<p>
Android camera in our application : You will use MediaStore.ACTION_IMAGE_CAPTURE to launch an existing camera application installed on your phone. Its syntax is given below
</p>
<h5>
android.provider.MediaStore.ACTION_IMAGE_CAPTURE<br>Providing Permissions in Manifest.file
</h5>
<li>
<strong>Step 1 : </strong>Provide read , write and using camera permission in the manifest file.

</li>
<img src="http://armorappz.com/github/manifestcamera.png">

<li>
<strong>Step 2 : </strong>Then Create a activy_main.xml and add a imageview and button to call the camera. When the button is clicked, camera intent will be called and the image is captured.


</li>
<img src="http://armorappz.com/github/activity_mainxml.png">

<li>
<strong>Step 3 : </strong>Then write the mainActivity .class and start the activity for result class with the request code. Request code is the one which responds which activity has started the Request so that the data will be supplied to that activity. And then the onActivity result will get the image and set it in the ImageView. onActivity Result method must be called to obtain the image so that if the request code matches, the image will be displayed in the ImageView.



</li>
<img src="http://armorappz.com/github/main_activity.png">
