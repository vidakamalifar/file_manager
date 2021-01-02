<h1>Malwarebytes Test</h1>
<h3>Android File Manager App</h3> 

With respect to the given task from Malwarebytes company, the following “read me” file is written to explain the main and detailed parts of the “File Manager” application. - Vida Kamalifar

 
 
<h3>Application Features:</h3> 
File explorer:  showing all files on your device.
Sort files: by Name, date, and type (ACS & DCS).
File details: by clicking on each file you can see a dialog that shows the detail of it with the image(if have one).
Search: search on the file list, see the result by highlighting text and you can save the result list. 
Save the search result: by clicking on the “Download list” you will download the search result in a .txt format. If you won’t give access to the application “scope storage” access, then the button won’t work and it will be disabled (in gray color).
Mockito Test: Mockito Test for sort function in the Presenter file. There is also another test for calculating the file size.
 
 
<h3>How to see the source code:</h3> 
<ul>
<li>Pull the code from the Github repository - Master branch (Link).</li>
<li>Open Android Studio and select 'Open an existing Android Studio Project'</li>
<li>Navigate to the repository.</li>
<li>Run the application.</li>
 </ul>
 
<h3>Android Version Targeting:</h3> 
<ul>
<li>compileSdkVersion 30</li>
<li>buildToolsVersion 30.0.2</li>
<li>minSdkVersion 24</li>
<li>targetSdkVersion 30</li>
 </ul>
 
<h3>Technologies:</h3> 
<ul>
<li>MVP</li>
<li>Java 8</li>
<li>Lambda Expressions</li>
<li>Scope Storage (Android 10 and 11 supported)</li>
<li>Butterknife</li>
<li>Easyprefs</li>
<li>Mockito Test</li>
<li>Constraintlayout</li>
</ul>
 
<h3>res/*</h3> 
The malwarebytes_logo.png document here is utilized as the picture to show in one of the perspectives in activity_splash.xml.
<ul>
<li>res/values/colors.xml</li>
<li>res/values/strings.xml</li>
<li>res/values/styles.xml</li>
<li>res/values/dimens.xml</li>
 </ul>
These XML records depict extra assets remembered for the application.
