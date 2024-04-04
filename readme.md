# CMake Templates
A simple template to be used for C and CPP projects. Can either be used for a repo with one project or multiple with minimal edits.

using add_subdirectory on a folder with this CMakeLists.txt automatically exposes the binary or include and libraries created. Look at example where a minimal executable and library are created with the template with minimal edits.

## Linux - Initialize project
```bash
cd ~/develop/
(export PROJECT_NAME="YourProjectName" && git clone git@github.com:Dequilla/CMakeTemplates.git $PROJECT_NAME && rm -rf "./$PROJECT_NAME/.git")
```

## Windows - Initialize project
```bat
chdir C:\develop\

set PROJECT_NAME=YourProjectName && git clone git@github.com:Dequilla/CMakeTemplates.git %PROJECT_NAME% && del /s /q ".\%PROJECT_NAME%\.git"
```
