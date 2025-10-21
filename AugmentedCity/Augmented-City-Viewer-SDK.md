# **AC VIEWER SDK TUTORIAL**


# **_How to build and get AC Viewer application_**

DOWNLOAD Augmented.City SDK (see [link](#bookmark=id.1fob9te)) and perform the following steps in order to get AC Viewer demo app.

[https://github.com/OpenArCloud/oscp-unity-client.git](https://github.com/OpenArCloud/oscp-unity-client.git)


# **<span style="text-decoration:underline;">PRELIMINARY STEP: install Unity with all dependencies</span>**



1. **Install Unity version 2019.2.11 or higher **(see [Fig.1](#bookmark=id.tyjcwt)) **and add Modules** (see [Fig.2](#bookmark=id.3dy6vkm)**). **

To install Unity, **get Unity Hub from the following link**:


    [https://unity3d.com/get-unity/download/archive](https://unity3d.com/get-unity/download/archive)

The Unity Hub is a standalone application that allowsalows easily to manage your Unity Projects and installations. In addition, you can manually manage the installation of multiple versions of the Editor and run two versions of Unity at the same time (see [Fig.3](#bookmark=id.1t3h5sf)). Note that to prevent local conflicts, you should only open a Project in one Editor instance at a time.


    

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")



    Fig.1: Example of the several installed versions of Unity. 

NOTE: you can add modules click the three dots to the right of the version label, then select **Add Modules**. (**NOTE:** If you didn’t install the Editor via the Hub, you will not see this option. To enable this option, [install the Editor via the Hub](https://docs.unity3d.com/2019.4/Documentation/Manual/GettingStartedInstallingHub.html).)



1. In the **Add Modules** dialog, locate the module to add and tick its checkbox.
2. When you have selected all the modules to add, select **Done**.

    

<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")



    Fig.2: Example of the adding Modules in Unity Hub.


    

<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")



    Fig.3: Example of the created projects using different versions of Unity. 


NOTE: You can click the drop-down arrow next to the Unity Version to select a different version of the Editor. If you try to open a Project with an older version of the Editor than the one it was created in, Unity warns you that downgrading the Project might result in data loss and asks you to confirm your selection.

You can visit the following link to see Unity documentation:

[https://docs.unity3d.com/Manual/UnityManual.html](https://docs.unity3d.com/Manual/UnityManual.html)


# **Download and build SDK Unity project**



1. **Open the existing Unity project included into the downloaded SDK**

    Select the proper Unity version (version 2019.2.11 or higher) and click on ADD project (see [Fig.4](#bookmark=id.17dp8vu)


    

<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")



    Fig.4: Opening the existing Unity project using Unity Hub

2. **Set project settings for Android/ios and ARcore** (see [Fig.5](#bookmark=id.26in1rg))

    SDK uses ARFoundation systems, so you have to install the following packages (**Window** -> **Package manager**):


    updated packages 


    ARFoundation 4.1.5


    ARCore XR Plugin 4.1.5


    ARKit XR Plugin 4.1.5


    

<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")



    

<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")



    Fig.5: Screenshot showing how to check the installed packages of AR Foundation system

3. **Build for Android/IOS**

    You can build _AugCityDemo _Scene on Android/IOS and get an application that localizes and shows placeholders on scanned buildings.


    To create a build for Android/iOS, go to Build Settings (menu: File > Build Settings). In the Platform list, select Android/iOS, then select the Switch Platform button (see [Fig.7](#bookmark=id.1ksv4uv)/[Fig.8](#bookmark=id.44sinio)). 


    Set project settings for Android and ARcore / iOS and ARKit setting at true “Allow 'unsafe' Code” (see [Fig. 9](#bookmark=id.2jxsxqh))


    _<span style="text-decoration:underline;">Android environment setup</span>_


    To build and run for Android (see [Fig.7](#bookmark=id.1ksv4uv)), you must install the Unity Android Build Support platform module. You also need to install the Android Software Development Kit (SDK) and the Native Development Kit (NDK) to build and run any code on your Android device. By default, Unity installs a Java Development Kit based on OpenJDK. 


    Use the Unity Hub to install Android Build Support and the required dependencies: Android SDK & NDK tools, and OpenJDK (see [Fig.2](#bookmark=id.3dy6vkm)).


    You can check the Android SDK & NDK Tools and OpenJDK installation going to **Preferences > External tools** (see [Fig. 6](#bookmark=id.35nkun2)). 


    

<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")



    Fig. 6: Check installed dependencies for Android platform: go to **Preferences > External tools **


    Below some useful links:

* Unity gradle support:

    [https://developers.google.com/ar/develop/unity/android-11-build#unity_20193_and_20194](https://developers.google.com/ar/develop/unity/android-11-build#unity_20193_and_20194)

* Download the Gradle version from the following link:

    [https://gradle.org/releases/](https://gradle.org/releases/)


    

<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.png "image_tooltip")



    Fig.7: Steps to build for Android.




<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image9.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image9.png "image_tooltip")


Fig.8: Steps to build for IOS.



<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image10.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image10.png "image_tooltip")


Fig. 9: Set project settings for iOS and ARKit:  Allow 'unsafe' Code - true



<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image11.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image11.png "image_tooltip")


10- Build

[https://drive.google.com/file/d/1EAmVb2JCxYRTUHvfURg_3uSPT25SY0R8/view?usp=sharing](https://drive.google.com/file/d/1EAmVb2JCxYRTUHvfURg_3uSPT25SY0R8/view?usp=sharing)
