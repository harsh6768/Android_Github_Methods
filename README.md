# Steps to perform Different method in android studio

### 1. Push Android Projects into the github
     
![Push into github](https://github.com/octivia/Android_Github_Methods/blob/master/images/Screenshot%20(392)_LI.jpg)

### 2. Push Android Projects into the existing github repository
      1. Go to Root folder
      2. git init
      3. git add .
      4. Create .gitignore txt file in root folder. Place these content in file.
         *.iml
         .gradle
         /local.properties
         /.idea/workspace.xml
         /.idea/libraries
         .idea
         .DS_Store
         /build
         /captures
         .externalNativeBuild
      5. git remote add origin https://github.com/username/project.git
      6. git commit - m "Initial Commit"
      7. git push origin
      
### 3. Commit into github after updating the Android Project
### 4. Clone Android Projects from github
