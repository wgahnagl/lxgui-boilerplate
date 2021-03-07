# What is lxgui? 
lxgui is a platform independent C++ gui library for making applications with a familiar xml/lua API. The main project can be found [![here!](https://github.com/cschreib/lxgui)](https://github.com/cschreib/lxgui) 

# What is this? 
this is a boilerplate project to help you get started with lxgui quickly! Simply fork the project, install the dependencies, and run 

```
git submodule update --init --recursive
mkdir build 
cd build 
cmake .. 
make 

```

and you should have the test file built in the main directory. 
execute it with ./example-ui and try out all of lxgui's features! From there you can follow the instructions on [![the main project's readme!](https://github.com/cschreib/lxgui/blob/master/README.md)](https://github.com/cschreib/lxgui/blob/master/README.md) to build your own UI!

# Install Dependencies 
```
git clone https://github.com/unnamed-mmo/lxgui
sudo dnf install -y freetype-devel SFML-devel lua-bit32 mesa-libGLU-devel lua-devel
cd lxgui
git submodule update --init
```                                                                       
## install GLEW                                                                                                    
download tar of the [![latest release](https://github.com/nigels-com/glew/releases/)](https://github.com/nigels-com/glew/releases/)                                                                                 
```
sudo dnf -y install libXmu-devel libXi-devel libGL-devel dos2unix git wget gcc
```
unzip, enter the dir and 
```
sudo make install 
```

go back to the lxgui dir
```
mkdir build
cd build 
cmake ..
make 
