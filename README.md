# Logger Test for Flutter Web

What I did:
Ok heres how I tested: 
1. Downloaded the new branch project.
2. Unzipped logger folder, openend in VSCode -> Get Packages. Missing packages errors went away.
3. Now I switched to example folder in VSCode. terminal input: cd "PathToExmapleFolder" 
4. Now I created necessary flutter web files. terminal input: flutter create .
5. Files were created in example folder with a new main.dart in "lib" folder. Now I overwrite this default main.dart that the flutter sdk created with the provided
   in the root of example folder to see some logs. :)
6. Now I got a missing logger reference error in the main.dart of example folder. To get rid of that, I added following 2 lines in pubspec.yaml of example project:
    logger:
    path: ../
	
	
7. No more errors after last step, so I run in terminal: flutter run -d chrome
8. Watch result ;)


![GitHub Logo](https://github.com/Cocotus/logger/blob/master/Debug_result.PNG)
