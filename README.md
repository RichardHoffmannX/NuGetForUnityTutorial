# NuGetForUnityTutorial

How do I install NuGetForUnity?
Install via OpenUPM
The package is available on the openupm registry. So you can install it via openupm-cli or manually using a scoped registry see documentation at openupm.
openupm add com.github-glitchenzo.nugetforunity
Install as GIT dependency via Package Manager
Unity 2019.3 or newer
Open Package Manager window (Window | Package Manager)
Click + button on the upper-left of a window, and select "Add package from git URL..."
Enter the following URL and click Add button
https://github.com/GlitchEnzo/NuGetForUnity.git?path=/src/NuGetForUnity
NOTE: To install a concrete version you can specify the version by prepending #v{version} e.g. #v2.0.0. For more see Unity UPM Documentation.

Unity 2019.2 or earlier
Close Unity Editor

Open Packages/manifest.json by any Text editor

Insert the following line after "dependencies": {, and save the file.

"com.glitchenzo.nugetforunity": "https://github.com/GlitchEnzo/NuGetForUnity.git?path=/src/NuGetForUnity",
Reopen Unity project in Unity Editor

Install via .unitypackage file
Install the provided Unity package into your Unity project. Located here. 

https://github.com/GlitchEnzo/NuGetForUnity/releases

Download the *.unitypackage file. Right-click on it in File Explorer and choose "Open in Unity."

How do I use NuGetForUnity?
To launch, select NuGet → Manage NuGet Packages
