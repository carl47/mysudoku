In Windows, I still use the Visual Basic IDE to provide the GUI. The functions are provided by compiling the C++ core to a managed assembly DLL.
In Linux, I use Glade to develop the GUI and associated code. The functions are added to the GUI code directly.
The image of the Sudoku uses an uncompressed bitmap file in Windows BMP file format. This can be displayed in Windows and Linux. It can also be directly worked on to produce the various images necessary for the program.
I still standby this method of generating cross-platform applications.
It is especially useful when we have:
Most of the operational code able to be abstracted to a block of C++.
Only a simple GUI is needed on the platform.
This does require individual compilation for each platform that it supports.
Another approach is to use code that can be directly run on any platform without special preparation. This could be software written in an interpreted language for which run-time packages are needed.
I have been learning Java so I decided to rewrite my Sudoku program and make it truly platform independent. Let's hope it will be “Write Once, Run Anywhere”, not “Write Once, Debug Everywhere”.
We can use Eclipse or the NetBeans IDE. Each has is own GUI toolkit. I do use Eclipse but I decided to use Java Foundation Classes (JFC) and Swing.
The code can be written and hacked with a text editor using javac to compile and java to run the application.


https://www.codeproject.com/Articles/304541/Sudoku-game-using-Java
