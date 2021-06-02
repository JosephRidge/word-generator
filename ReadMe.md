#Intro To flutter :

* Flutter is basically a widget driven platform
* Uses Native ARM Binary architecture hence making it fast.
* DART is the main language
* enables dev of cross-platfomr applications( IOS / Android)

# SetUp (Bias towards Linux n Android Studio :

1.  install the sdk from : https://flutter.dev/docs/get-started/install/linux#install-flutter-manually
2.  Extract the zip file to your desired directory
e.g. cd && mkdir development
     cd development
     tar xf ~/Downloads/flutter_linux_2.2.1-stable.tar.xz

3. once extracted, on terminal:
change current directory to where you have extracted flutter,
type *pwd* and press enter. now copy the output . In my case my output was */home/ridge/development/flutter/bin/flutter
*

4. Let's add it to pur path :
 On terminal run *vim ~/.bashrc* , this will open the bash script on terminal  once it has opened u will scroll till
the bottom by using the downward arrow button, at the bottom youb will add a line similar to mine(line 139) but in your case it will differ
 depending on the path of your flutter sdk :
![bashrc](https://user-images.githubusercontent.com/42699812/120552423-c3cfc500-c3e6-11eb-9d04-d34d0bab217f.png)
ONce done type ':wq!' this will save and close the edit.
PS: when placing th eexport make  sure not to use ' = ' but use ' : ' eg . use this export PATH="$PATH:`pwd`/flutter/bin"
in place of export PATH="$PATH=`pwd`/flutter/bin".
PS: pwd == Present Working Directory

5. Verify Installation :
Restart terminal, by closing and opening it again, then run 'flutter doctor',
 if it is successful it will print out an about flutter section if not it will throw an error

6. ON Android now add the Flutter and Dart plugind through File -> Settings -> Plugins -> Search and install

7. Create an App : on terminal  : mkdir FlutterApp && cd FlutterApp && flutter create your_preffred_appname

# # ------------------------------------------------------------------------------------------------------------









