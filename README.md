# ionic hudson script
Ant script for hudson build script in ionic framework android application

# Adding hudson script
 Add new project and choose Execute Windows batch command paste the bellow code in command text box:
```
d:
cd D:\AndroidRepo\myapp
ant -buildfile antbuild.xml
```

# Ant Script File Changes
Open the ``` antbuild.xml ``` file and change location of the path and put this file into your ionic project.

Require to change the following variables in the ``` antbuild.xml ``` file
```
<property name="projname" value="Your Project Name here"/>
<property name="workspace" value="your project location example D:/AndroidRepo/myapp/"/>
<property name="apkname" value="your apk name example: myapp"/>
<property name="zipalignpath" value="zipalign.exe path example  D:\Android\build-tools\22.0.1\"/>
<property name="keystorepassword" value="12345678"/>
<property name="destpath" value="where the singened apk need to create include end with / example  D:/APK/"/>
<property name="repository" value="your repository"/>

```

Enjoy !!!

# Support and Help.

Your help and support are welcome..
