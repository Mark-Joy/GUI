## Installation Information

This installation information is only tested on windows system using Visual Studio 2015 and QT 5.8.0.
Different versions should have the same result, but it is not guaranteed since I did not tested yet.

## Build Steps:
1. Download QT 5.8.0 source code from [here](https://download.qt.io/archive/qt/5.8/5.8.0/single/)
2. Build QT statically:  [here](http://stackoverflow.com/questions/14932315/how-to-compile-qt-5-under-windows-or-linux-32-or-64-bit-static-or-dynamic-on-v)
3. Download and install QT: [qt-opensource-windows-x86-msvc2015-5.8.0.exe](https://download.qt.io/archive/qt/5.8/5.8.0/)
4. Have Visual Studio 2015 installed on your system.
5. Run "Developer Command Promt for Visual Studio". In its console, provided that QT is install in "C:\Qt\Qt5.8.0-x86", type the following command:  
 set PATH=C:\Qt\Qt5.8.0-x86\Tools\QtCreator\bin;C:\Qt\Qt5.8.0-x86\5.8\msvc2015\bin;%PATH%
6. Go to project build folder using the following command:  
 cd \<Path to project folder\>  
 Example: cd C:\GUI\build-GUI-Qt_Static_x86_5_8_0-Release
7. Build project using the following command:  
 jom.exe

## Installation Steps:
Now you have GUI.dll and GUI.lib in "GUI\release" folder.
Copy GUI.dll to use in your specified environment.

## License
GUI is available under the GNU Lesser General Public License version 3.
See License\License.txt in for more info.

## Hash
f20a8e2131d014b532437bd193ec2a53c00acff69d0e60382eaebcca44daa3e7